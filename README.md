# prettytest

`prettytest` is an extremely simple Golang program (~80 LOC) to have pretty, colored output for Go tests.
It takes the exact arguments of `go test`, as it's just a wrapper that calls your local `go` binary.

`prettytest ./... -v` is equivalent to `go test ./... -v`.

## Installation

```sh
go install github.com/happybydefault/prettytest@latest
```

## Output

### Success

![Output of a test that succeeded](assets/success.png "Output of a test that succeeded")

### Fail

![Output of a test that failed](assets/fail.png "Output of a test that failed")
