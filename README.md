# gethook-go — Go SDK

Go client for the [GetHook](https://gethook.io) Webhook Reliability Gateway API.

## Installation

```bash
go get github.com/gethook/gethook-go
```

## Usage

```go
package main

import (
    "context"
    "fmt"
    gethook "github.com/gethook/gethook-go"
)

func main() {
    cfg := gethook.NewConfiguration()
    cfg.AddDefaultHeader("Authorization", "Bearer hk_your_api_key")
    cfg.Servers = []gethook.ServerConfiguration{{URL: "https://api.gethook.io"}}

    client := gethook.NewAPIClient(cfg)
    sources, _, err := client.SourcesAPI.ListSources(context.Background()).Execute()
    if err != nil {
        panic(err)
    }
    fmt.Println(sources)
}
```

## Documentation

Full API reference: https://docs.gethook.io/api-reference.html

## Development

This SDK is auto-generated from the OpenAPI spec via `make sync` in the main [gethook](https://github.com/gethook/gethook) repo.
