# Use the official Golang image as the base image
FROM golang:latest

# Set the working directory inside the container
WORKDIR /app

# Copy the source code into the container
COPY hello.go .

# Install any dependencies
RUN go mod init example/hello
RUN go mod tidy

# Build the Go application
RUN go build -o hello

# Set the command to run when the container starts
CMD ["./hello"]
