dev:
	go run cmd/router/main.go

test:
	go test -race ./...

build:
	CGO_ENABLED=0 GOOS=linux go build -trimpath -a -o router cmd/router/main.go