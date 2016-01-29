
# uid

[![Build Status](https://travis-ci.org/zemirco/uid.svg)](https://travis-ci.org/zemirco/uid)
[![GoDoc](https://godoc.org/github.com/zemirco/uid?status.svg)](https://godoc.org/github.com/zemirco/uid)

Generate URL safe strings.

## Example

```go
package main

import "github.com/zemirco/uid"

func main() {
  id := uid.Gen(10)
  fmt.Println(id)
  // 9BZ1sApAX4
}
```

## Test

`go test`

## Benchmark

```bash
BenchmarkGen1   20000000  104 ns/op
BenchmarkGen5   20000000  110 ns/op
BenchmarkGen10  10000000  120 ns/op
BenchmarkGen20  10000000  155 ns/op
BenchmarkGen50   5000000  252 ns/op
```

## License

MIT
