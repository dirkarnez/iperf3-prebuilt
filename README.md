iperf3-prebuilt
===============
Prebuilt of [esnet/iperf: iperf3: A TCP, UDP, and SCTP network bandwidth measurement tool](https://github.com/esnet/iperf)

### Notes
- `--enable-static-bin` must be enabled in CI/CD otherwise `mic.exe` and `mis.exe` will fail to find dependencies
- `libtool: warning: undefined symbols not allowed in x86_64-pc-cygwin shared libraries;` just because `libtool` force-check OpenSSL installation and not allow link later
