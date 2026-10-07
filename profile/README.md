<br>
<p align="center">
  <a href="https://www.blendbyte.com">
    <picture>
      <source media="(prefers-color-scheme: dark)" srcset="https://www.blendbyte.com/logo_horizontal_light.png">
      <img src="https://www.blendbyte.com/logo_horizontal.png" alt="Blendbyte" width="420">
    </picture>
  </a>
</p>
<p align="center">
  Cloud infrastructure, web apps, and developer tools.
</p>
<p align="center">
  <a href="https://www.blendbyte.com">blendbyte.com</a> · <a href="mailto:hello@blendbyte.com">hello@blendbyte.com</a>
</p>
<br>

## What we do

We run web hosting and cloud infrastructure, build custom software for clients, and ship our own products: [Textual](https://www.textualapp.com), [Tindra](https://www.tindra.sh), [Stringhive](https://stringhive.com), and [ZNCHost](https://www.znchost.com). Everything runs on infrastructure we operate ourselves.

## What's on GitHub

Two kinds of repos live here.

**Stuff we ship in production.** Every public repo in this org is running somewhere in our stack. If it's here, we use it. If we don't use it, we don't publish it. No experiments, no graveyards.

**Projects we took over.** A lot of great software goes quiet when its maintainer moves on. Sometimes we fork it and keep it alive inside our org. Sometimes the original author is ready to pass the keys and we step in as the new home. Either way, the goal is the same: current platform and framework versions, real bug fixes, public releases.

## Highlights

### Apps and products

**[Textual](https://github.com/blendbyte/Textual)** &nbsp;·&nbsp; [textualapp.com](https://www.textualapp.com)

The native IRC client for macOS, around since 2010. Its original maintainer passed the project to us in 2026, and Textual 8 is in the works.

**[Tindra](https://github.com/blendbyte/tindra)** &nbsp;·&nbsp; [tindra.sh](https://www.tindra.sh)

Self-hosted error tracking, performance, uptime, and cron monitoring. Works with every Sentry SDK. One Go binary, one PostgreSQL database.

### Infrastructure tooling

**[nginx-modules](https://github.com/blendbyte/nginx-modules)** &nbsp;·&nbsp; [nginx-modules.com](https://www.nginx-modules.com)

Pre-built nginx dynamic modules as an APT repository for Debian and Ubuntu. brotli, zstd, ModSecurity, GeoIP2, and more. Just `apt install`.

**[CoyoteCert](https://github.com/blendbyte/coyotecert)** &nbsp;·&nbsp; [coyotecert.com](https://coyotecert.com)

ACME v2 client for PHP 8.3+. Works with Let's Encrypt, ZeroSSL, and any other RFC 8555 CA. Comes with a [Laravel integration](https://github.com/blendbyte/coyotecert-laravel).

**[openvox-intellij](https://github.com/blendbyte/openvox-intellij)**

OpenVox 8 and Puppet language support for PhpStorm and other IntelliJ Platform IDEs.

### Laravel ecosystem

**[laravel-paypal](https://github.com/blendbyte/laravel-paypal)**

PayPal REST API client for Laravel and standalone PHP. 1,200+ stars, 4.8M+ installs. Originally built by srmklive, now maintained by us.

**Filament plugins** &nbsp;·&nbsp; [Title With Slug](https://filamentphp.com/plugins/blendbyte-title-with-slug) &nbsp;·&nbsp; [Resource Lock](https://filamentphp.com/plugins/blendbyte-resource-lock)

A title and permalink input with live preview, and edit locking for multi-user panels. Both on Filament 5.

**Nova fields** &nbsp;·&nbsp; [nova-items-field](https://github.com/blendbyte/nova-items-field) &nbsp;·&nbsp; [nova-attach-many](https://github.com/blendbyte/nova-attach-many)

Kept working on Nova 5 after their original authors moved on.

**[livewire-honeypot](https://github.com/blendbyte/livewire-honeypot)**

Spam protection for Livewire 4 forms. No CAPTCHAs, no external requests.

## About sponsoring us

We get asked occasionally about GitHub Sponsors or similar. Short answer: please don't. This org *is* our sponsorship. The repos here are our commercial business giving back to the ecosystem we build on, and we'd rather keep it that way than add another funnel. The full list of what we publish lives on [our product page](https://www.blendbyte.com/products).

The best way to support the work is to become a customer. If you need managed hosting, cloud infrastructure, or a team to build something custom, say hi at [hello@blendbyte.com](mailto:hello@blendbyte.com). Every new customer is another reason these repos keep getting updates.

## Working with us

Issues and PRs get read. Good ones get merged fast. Drop a minimal repro in your bug reports and we'll take a look.

For commercial work, hosting, or anything that needs more than a pull request: [hello@blendbyte.com](mailto:hello@blendbyte.com).
