# sniff
A simple IP Address sniffer tool written in Rust

```shell
USAGE:
    sniff [OPTIONS] <IP_ADDRESS>

ARGS:
    <IP_ADDRESS>    An IPv4 or IPv6 valid IP address

OPTIONS:
    -h, --help                 Print help information
    -t, --timeout <TIMEOUT>    The connection timeout in millis [default: 3000]
    -T, --threads <THREADS>    The number of threads to use [default: 4]
    -V, --version              Print version information
```
