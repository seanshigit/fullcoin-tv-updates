# Third-party source and licenses

Fullcoin TV is distributed under GPL-3.0-or-later with its corresponding source. It uses SagerNet sing-box libbox 1.14.4, also GPL-3.0-or-later. The complete pinned core source, its LICENSE and dependency declarations are in core/. Official source: https://github.com/SagerNet/sing-box/tree/v1.14.4 . The Android platform integration was informed by the official SagerNet/sing-box-for-android integration at f87c2ebdb7e34754be751bb5e58926db2fed8f8c (GPL-3.0-or-later).

The native binding generator is SagerNet/gomobile v0.1.13: https://github.com/SagerNet/gomobile/tree/v0.1.13 . Its source and license are included with the dependency sources. Android framework classes are provided by the operating system. JUnit and org.json are test-only dependencies and are not packaged in the application.

third_party/modules.txt records the Go modules used by the native library. Copies of their source and original license/notice files are preserved beneath third_party/sources/. Individual dependencies retain their own licenses. The Mozilla root certificate data is copied unchanged from the pinned sing-box source; its original certificate source and update code remain in core/common/certificate/ and core/cmd/internal/update_certificates/.

The Go standard library and compiler are supplied by the Go toolchain (Go 1.26.5, https://go.dev/dl/); their BSD-style license is included in third_party/go-LICENSE. Rebuilding may fetch public build dependencies from their official repositories or configured package mirrors; proxy secrets and signing keys are private inputs and are excluded from this archive.
