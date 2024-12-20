# FreeOTP

[FreeOTP](https://freeotp.github.io/) is a two-factor authentication application for systems
utilizing one-time password protocols. Tokens can be added easily by scanning a QR code.

FreeOTP implements open standards:

* HOTP (HMAC-Based One-Time Password Algorithm) [RFC 4226](https://www.ietf.org/rfc/rfc4226.txt)
* TOTP (Time-Based One-Time Password Algorithm) [RFC 6238](https://www.ietf.org/rfc/rfc6238.txt)

This means that no proprietary server-side component is necessary: use any server-side component
that implements these standards.

## Download FreeOTP for iOS

* [App Store](https://apps.apple.com/app/freeotp-authenticator/id872559395)

## Contributing

Pull requests on GitHub are welcome under the Apache 2.0 license, see
[CONTRIBUTING](CONTRIBUTING.md) for more details.

### Install Build dependencies

You need to have [Carthage](https://github.com/Carthage/Carthage) installed for managing dependencies. In simple steps:

    brew install carthage
    carthage update --use-xcframeworks --platform iOS

## 軟體中文化
本專案為數位部開放原始碼軟體中文化專案項目之一，其中文化與專案應用可參考 Wiki。
