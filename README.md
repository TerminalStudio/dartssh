# DartSSH 2

[![pub package](https://img.shields.io/pub/v/dartssh.svg)](https://pub.dartlang.org/packages/dartssh) [![Build Status](https://travis-ci.org/GreenAppers/dartssh.svg?branch=master)](https://travis-ci.org/GreenAppers/dartssh) [![Coverage Status](https://coveralls.io/repos/github/GreenAppers/dartssh/badge.svg?branch=master)](https://coveralls.io/github/GreenAppers/dartssh?branch=master) [![documentation](https://img.shields.io/badge/Documentation-dartssh-blue.svg)](https://www.dartdocs.org/documentation/dartssh/latest/)

`dartssh2`  is a pure dart SSH implementation based on dartssh, with bug fixes, up-to-date dependencies and sound null safety.

`dartssh2` providing first-class tunnelling primitives.

## Feature support

| <!-- -->                   | <!-- -->                        |
|----------------------------|---------------------------------|
| **Keys**                   | Ed25519, ECDSA, RSA             |
| **KEX**                    | X25519DH, ECDH, DHGEX, DH       |
| **Cipher**                 | AES-CTR, AES-CBC                |
| **MAC**                    | MD5, SHA                        |
| **Compression**            | not yet supported               |
| **Forwarding**             | TCP/IP, Agent                   |
| **Tunneling drop-ins** for | Socket, WebSocket, package:http |

## Try

```sh
dart pub global activate dartssh2
```
Then use it as regular `ssh` command.

```sh
dartssh your-username@example.com
```

> If this doesn’t work, you might need to [set up your path](https://dart.dev/tools/pub/cmd/pub-global#running-a-script-from-your-path).

## Quick start - SSH client

<!-- CLIENT EXAMPLE BEGIN -->
<details >
<summary>
<sub><b>Click to see more:</b></sub>

```dart
import 'package:dartssh2/client.dart';
```
</summary>
<!-- <hr> -->
<h6>TODO</h6>

 ```html
TODO
```
</details>
<!-- CLIENT EXAMPLE END -->

## Quick start - SSH server

<!-- SERVER EXAMPLE BEGIN -->
<details >
<summary>
<sub><b>Click to see more:</b></sub>

```dart
import 'package:dartssh2/client.dart';
```
</summary>
<!-- <hr> -->
<h6>TODO</h6>

 ```html
TODO
```
</details>
<!-- SERVER EXAMPLE END -->


## Example

SSH client: [example/dartssh.dart](example/dartssh.dart)

SSH server: [example/dartsshs.dart](example/dartsshs.dart)

## References

- [`RFC 4251`](https://datatracker.ietf.org/doc/html/rfc4251) The Secure Shell (SSH) Protocol Architecture
- [`RFC 4252`](https://datatracker.ietf.org/doc/html/rfc4252) The Secure Shell (SSH) Authentication Protocol
- [`RFC 4253`](https://datatracker.ietf.org/doc/html/rfc4253) The Secure Shell (SSH) Transport Layer Protocol
- [`RFC 4254`](https://datatracker.ietf.org/doc/html/rfc4254) The Secure Shell (SSH) Connection Protocol

## Credits

https://github.com/GreenAppers/dartssh by GreenAppers

## License

dartssh is released under the terms of the MIT license. See [LICENSE](LICENSE).