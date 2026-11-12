<p align="center">
  <a href="https://fingerly.io">
    <picture>
      <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/fingerly-io/.github/main/assets/logo-dark.svg">
      <img src="https://raw.githubusercontent.com/fingerly-io/.github/main/assets/logo-light.svg" alt="Fingerly" height="44">
    </picture>
  </a>
</p>

<p align="center"><b>A clearer picture of every session.</b><br>Device fingerprinting and fraud detection for signups, logins and payments.</p>

<p align="center">
  <a href="https://fingerly.io">Website</a> &middot;
  <a href="https://docs.fingerly.io">Documentation</a> &middot;
  <a href="https://docs.fingerly.io/reference/overview">API reference</a> &middot;
  <a href="mailto:support@fingerly.io">Support</a>
</p>

<p align="center"><img src="https://raw.githubusercontent.com/fingerly-io/.github/main/assets/hero.webp" alt="Fingerly shields an application from bots, fake accounts and fraud, and recognises returning devices" width="100%"></p>

## What is Fingerly

Fingerly is a device fingerprinting API with web, iOS and Android SDKs. It recognises returning devices and detects bots, VPNs, Tor, device farms and tampering, so you can stop fraud and abuse in signups, logins and payments without adding friction for real customers. You add an SDK to your app, and your backend reads the result and decides what to do.

Start with the [quick start](https://docs.fingerly.io/docs/quick-start), or pick your platform below.

## SDKs

Every SDK is documented at [docs.fingerly.io/docs/sdks](https://docs.fingerly.io/docs/sdks).

### Web

The web SDKs live in the [`sdks`](https://github.com/fingerly-io/sdks) repository.

| Package | For | Version | Docs |
| --- | --- | --- | --- |
| [`@fingerly/web-js`](https://www.npmjs.com/package/@fingerly/web-js) | Browser JavaScript | ![npm](https://img.shields.io/npm/v/@fingerly/web-js?style=flat-square&label=npm) | [Guide](https://docs.fingerly.io/docs/sdks/javascript) |
| [`@fingerly/react`](https://www.npmjs.com/package/@fingerly/react) | React | ![npm](https://img.shields.io/npm/v/@fingerly/react?style=flat-square&label=npm) | [Guide](https://docs.fingerly.io/docs/sdks/react) |
| [`@fingerly/next`](https://www.npmjs.com/package/@fingerly/next) | Next.js | ![npm](https://img.shields.io/npm/v/@fingerly/next?style=flat-square&label=npm) | [Guide](https://docs.fingerly.io/docs/sdks/nextjs) |
| [`@fingerly/vue`](https://www.npmjs.com/package/@fingerly/vue) | Vue | ![npm](https://img.shields.io/npm/v/@fingerly/vue?style=flat-square&label=npm) | [Guide](https://docs.fingerly.io/docs/sdks/vue) |
| [`@fingerly/nuxt`](https://www.npmjs.com/package/@fingerly/nuxt) | Nuxt | ![npm](https://img.shields.io/npm/v/@fingerly/nuxt?style=flat-square&label=npm) | [Guide](https://docs.fingerly.io/docs/sdks/nuxt) |
| [`@fingerly/svelte`](https://www.npmjs.com/package/@fingerly/svelte) | Svelte | ![npm](https://img.shields.io/npm/v/@fingerly/svelte?style=flat-square&label=npm) | [Guide](https://docs.fingerly.io/docs/sdks/svelte) |
| [`@fingerly/angular`](https://www.npmjs.com/package/@fingerly/angular) | Angular | ![npm](https://img.shields.io/npm/v/@fingerly/angular?style=flat-square&label=npm) | [Guide](https://docs.fingerly.io/docs/sdks/angular) |
| [`@fingerly/core`](https://www.npmjs.com/package/@fingerly/core) | Framework-agnostic core shared by the web SDKs | ![npm](https://img.shields.io/npm/v/@fingerly/core?style=flat-square&label=npm) | [Guide](https://docs.fingerly.io/docs/sdks/javascript) |
| [`@fingerly/types`](https://www.npmjs.com/package/@fingerly/types) | Shared TypeScript contracts ([`sdk-types`](https://github.com/fingerly-io/sdk-types)) | ![npm](https://img.shields.io/npm/v/@fingerly/types?style=flat-square&label=npm) | [Guide](https://docs.fingerly.io/docs/sdks) |

### Mobile

| Repository | For | Install | Version | Docs |
| --- | --- | --- | --- | --- |
| [`sdk-ios`](https://github.com/fingerly-io/sdk-ios) | iOS and tvOS | Swift Package, `https://github.com/fingerly-io/sdk-ios` | ![release](https://img.shields.io/github/v/tag/fingerly-io/sdk-ios?style=flat-square&label=release) | [Guide](https://docs.fingerly.io/docs/sdks/ios) |
| [`sdk-android`](https://github.com/fingerly-io/sdk-android) | Android | `io.fingerly:fingerly` from [`maven.fingerly.io`](https://maven.fingerly.io) | ![release](https://img.shields.io/github/v/tag/fingerly-io/sdk-android?style=flat-square&label=release) | [Guide](https://docs.fingerly.io/docs/sdks/android) |
| [`sdk-react-native`](https://github.com/fingerly-io/sdk-react-native) | React Native | [`@fingerly/react-native`](https://www.npmjs.com/package/@fingerly/react-native) | ![npm](https://img.shields.io/npm/v/@fingerly/react-native?style=flat-square&label=npm) | [Guide](https://docs.fingerly.io/docs/sdks/react-native) |
| [`sdk-flutter`](https://github.com/fingerly-io/sdk-flutter) | Flutter | [`fingerly_flutter`](https://pub.dev/packages/fingerly_flutter) | ![pub](https://img.shields.io/pub/v/fingerly_flutter?style=flat-square&label=pub.dev) | [Guide](https://docs.fingerly.io/docs/sdks/flutter) |
| [`sdk-lynx`](https://github.com/fingerly-io/sdk-lynx) | Lynx | [`@fingerly/lynx`](https://www.npmjs.com/package/@fingerly/lynx) | ![npm](https://img.shields.io/npm/v/@fingerly/lynx?style=flat-square&label=npm) | [Guide](https://docs.fingerly.io/docs/sdks/lynx) |

### Server

Read events, verify webhooks and serve a same-origin proxy from your backend.

| Repository | For | Package | Version | Docs |
| --- | --- | --- | --- | --- |
| [`sdk-node`](https://github.com/fingerly-io/sdk-node) | Node.js | [`@fingerly/node`](https://www.npmjs.com/package/@fingerly/node) | ![npm](https://img.shields.io/npm/v/@fingerly/node?style=flat-square&label=npm) | [Guide](https://docs.fingerly.io/docs/sdks/node) |
| [`sdk-python`](https://github.com/fingerly-io/sdk-python) | Python | [`fingerly`](https://pypi.org/project/fingerly/) | ![PyPI](https://img.shields.io/pypi/v/fingerly?style=flat-square&label=PyPI) | [Guide](https://docs.fingerly.io/docs/sdks/python) |
| [`fingerly-go`](https://github.com/fingerly-io/fingerly-go) | Go | [`github.com/fingerly-io/fingerly-go`](https://pkg.go.dev/github.com/fingerly-io/fingerly-go) | ![release](https://img.shields.io/github/v/tag/fingerly-io/fingerly-go?style=flat-square&label=release) | [Guide](https://docs.fingerly.io/docs/sdks/go) |
| [`sdk-java`](https://github.com/fingerly-io/sdk-java) | Java and the JVM | [`io.fingerly:fingerly-server`](https://central.sonatype.com/artifact/io.fingerly/fingerly-server) | ![Maven Central](https://img.shields.io/maven-central/v/io.fingerly/fingerly-server?style=flat-square&label=Maven%20Central) | [Guide](https://docs.fingerly.io/docs/sdks/java) |
| [`sdk-dotnet`](https://github.com/fingerly-io/sdk-dotnet) | .NET and ASP.NET Core | [`Fingerly.Server`](https://www.nuget.org/packages/Fingerly.Server), [`Fingerly.Server.AspNetCore`](https://www.nuget.org/packages/Fingerly.Server.AspNetCore) | ![NuGet](https://img.shields.io/nuget/v/Fingerly.Server?style=flat-square&label=NuGet) | [Guide](https://docs.fingerly.io/docs/sdks/dotnet) |
| [`sdk-php`](https://github.com/fingerly-io/sdk-php) | PHP | [`fingerly/fingerly-php`](https://packagist.org/packages/fingerly/fingerly-php) | ![Packagist](https://img.shields.io/packagist/v/fingerly/fingerly-php?style=flat-square&label=Packagist) | [Guide](https://docs.fingerly.io/docs/sdks/php) |
| [`sdk-ruby`](https://github.com/fingerly-io/sdk-ruby) | Ruby | [`fingerly`](https://rubygems.org/gems/fingerly) | ![Gem](https://img.shields.io/gem/v/fingerly?style=flat-square&label=RubyGems) | [Guide](https://docs.fingerly.io/docs/sdks/ruby) |
| [`sdk-rust`](https://github.com/fingerly-io/sdk-rust) | Rust | [`fingerly`](https://crates.io/crates/fingerly) | ![crates.io](https://img.shields.io/crates/v/fingerly?style=flat-square&label=crates.io) | [Guide](https://docs.fingerly.io/docs/sdks/rust) |

### Proxy

A first-party proxy serves the SDK from your own domain. See [Proxy integrations](https://docs.fingerly.io/docs/proxy-integrations).

| Repository | For | Version | Docs |
| --- | --- | --- | --- |
| [`cloudflare-worker-proxy`](https://github.com/fingerly-io/cloudflare-worker-proxy) | Cloudflare Workers | ![release](https://img.shields.io/github/v/tag/fingerly-io/cloudflare-worker-proxy?style=flat-square&label=release) | [Guide](https://docs.fingerly.io/docs/sdks/cloudflare-worker) |
| [`sdks`](https://github.com/fingerly-io/sdks/tree/main/proxies/templates) | Templates for Vercel, Netlify, AWS CloudFront, Google Cloud Run, nginx, Caddy, Traefik and containers | | [Guide](https://docs.fingerly.io/docs/proxy-integrations) |

## Resources

- Website: [fingerly.io](https://fingerly.io)
- Documentation: [docs.fingerly.io](https://docs.fingerly.io)
- API reference: [docs.fingerly.io/reference/overview](https://docs.fingerly.io/reference/overview)
- Support: [support@fingerly.io](mailto:support@fingerly.io)
- Security reports: [security@fingerly.io](mailto:security@fingerly.io), see the [security policy](https://github.com/fingerly-io/.github/blob/main/SECURITY.md)

## Licences

The open-source SDKs and proxies are released under the [Apache License 2.0](https://www.apache.org/licenses/LICENSE-2.0). The native iOS and Android SDKs are distributed as compiled binaries under the Fingerly SDK License; their repositories hold the installation instructions and the licence text, not source code.

Fingerly is a product of Badele LLC.
