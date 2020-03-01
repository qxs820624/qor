# Gomerchant

Gomerchant is an abstracted payment interface for Golang, it provides unified API for different payment gateways.

## Usage

```go
import "github.com/qor/gomerchant/gateways/stripe"

func main() {
  Stripe := stripe.New(&stripe.Config{
    Key: config.Key,
  })
}
```

[![GoDoc](https://godoc.org/github.com/golang/gddo?status.svg)](http://godoc.org/github.com/qor/gomerchant)
