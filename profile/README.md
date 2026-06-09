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

We run web hosting and cloud infrastructure, build custom software for clients, and ship our own SaaS products. Everything runs on infrastructure we operate ourselves.

## What's on GitHub

Two kinds of repos live here.

**Stuff we ship in production.** Every public repo in this org is running somewhere in our stack. If it's here, we use it. If we don't use it, we don't publish it. No experiments, no graveyards.

**Packages we took over.** A lot of great packages go quiet when their maintainer moves on. Sometimes we fork them and keep them alive inside our org. Sometimes the original author is ready to pass the keys and we step in as the new home. Either way, the goal is the same: current framework versions, real bug fixes, public releases.

## Highlights

**[Tindra](https://github.com/blendbyte/tindra)**

Self-hosted error tracking and observability. It speaks the Sentry envelope protocol, so your existing SDKs can point at it after a one-line DSN change. No rewrites, no per-event bill, and your stack traces never leave your servers. Under the hood it's a single Go binary with PostgreSQL behind it and a Vue 3 frontend. We built it because we wanted our own observability running on our own hardware, and figured we probably weren't the only ones.

**[nginx-modules](https://nginx-modules.com)**

Pre-built nginx dynamic modules, served as a plain APT repository. brotli, zstd, ModSecurity, GeoIP2, headers-more, and a few others. Just `apt install`, load the module, and you're done. No compiling from source, and no chasing ABI mismatches either, since every module is built against the matching nginx version.

**[CoyoteCert](https://github.com/blendbyte/CoyoteCert)**

A modern ACME v2 client for PHP 8.3+. Works with Let's Encrypt, ZeroSSL, Google Trust Services, SSL.com, Buypass, and any other RFC 8555 CA. Fluent API, ECDSA by default, ARI-guided renewals, full EAB support, wildcard and multi-domain certs, and a swappable PSR-18 HTTP client. No CA affiliation, no telemetry, no lock-in.

**[laravel-paypal](https://github.com/blendbyte/laravel-paypal)**

PayPal REST API client for Laravel. 1,100+ stars, 337 forks. Originally built by srmklive, now maintained by us after a full handover. Modernized for PHP 8.3+ and Laravel 12/13, with standalone PHP support, PSR-18 HTTP clients, local webhook verification, and Fastlane.

**Filament plugins** &nbsp;·&nbsp; [Title With Slug](https://filamentphp.com/plugins/blendbyte-title-with-slug) &nbsp;·&nbsp; [Resource Lock](https://filamentphp.com/plugins/blendbyte-resource-lock)

Two plugins we maintain in the [official Filament directory](https://filamentphp.com/plugins), both already on Filament 5. **Title With Slug** gives you a WordPress-style title and permalink input with live preview and undo. **Resource Lock** prevents two editors from clobbering each other's work with real-time lock indicators and force-unlock support.

**[livewire-honeypot](https://github.com/blendbyte/livewire-honeypot)**

Spam protection for Livewire 4 forms. No CAPTCHAs, no external requests, no tracking pixels.

**Nova forks**

A stack of Laravel Nova packages kept working on current Laravel and PHP versions after their original authors moved on.

## About sponsoring us

We get asked occasionally about GitHub Sponsors or similar. Short answer: please don't. This org *is* our sponsorship. The repos here are our commercial business giving back to the ecosystem we build on, and we'd rather keep it that way than add another funnel. The full list of what we publish lives on [our product page](https://www.blendbyte.com/products).

The best way to support the work is to become a customer. If you need managed hosting, cloud infrastructure, or a team to build something custom, say hi at [hello@blendbyte.com](mailto:hello@blendbyte.com). Every new customer is another reason these repos keep getting updates.

## Working with us

Issues and PRs get read. Good ones get merged fast. Drop a minimal repro in your bug reports and we'll take a look.

For commercial work, hosting, or anything that needs more than a pull request: [hello@blendbyte.com](mailto:hello@blendbyte.com).
