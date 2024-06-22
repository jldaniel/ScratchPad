# Go Learning

Ad-hoc go learning

## Running the script

Install dependencies

```bash
go mod tidy
```

Run the script

```bash
go run .
```

Compile and run

```bash
go build -o hello
```

Run the exec

```bash
./hello
```

## Running with docker

Build the image

```bash
docker build -t hello-go .
```

Run the image

```bash
docker run --rm hello-go
```

