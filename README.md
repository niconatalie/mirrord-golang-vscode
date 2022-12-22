### Steps to reproduce
1. Install dlv https://github.com/go-delve/delve/tree/master/Documentation/installation
1. Compile the binary `go build main.go`
1. Run dlv in headless mode `dlv exec ./main --headless --listen=127.0.0.1:50034`
1. Run debugger, you should be able to debug normally
1. Stop debugger, and launch it again with mirrord enabled
