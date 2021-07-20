# overlay-sample

## Run

```go
go run main.go hello.go
// hello
```

```go
go run main.go good_bye.go
// good bye
```

```go
go run -overlay replace.json main.go good_bye.go
// hello
```
