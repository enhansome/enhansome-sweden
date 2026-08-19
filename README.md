# Awesome Sweden list with stars

A curated list of awesome things to use when coding for the Swedish market.

## Content

* [People](#people)
* [Companies](#companies)
* [Finance](#finance)
* [Authentication](#authentication)
* [Job Market](#job-market)
* [Transportation](#transportation)
* [Regional](#regional)
* [Geographic](#geographic)
* [Media](#media)
* [Construction](#construction)
* [Misc](#misc)
* :link: [Awesome Sweden Datasets](https://github.com/buren/awesome-sweden-datasets) ⭐ 28 | 🐛 5 | 🌐 Shell | 📅 2026-04-21
* A **[wish list](#wish-list)** of things we'd like to see libraries for

:information\_source:

* Looking for datasets? See [Awesome Sweden Datasets](https://github.com/buren/awesome-sweden-datasets) ⭐ 28 | 🐛 5 | 🌐 Shell | 📅 2026-04-21.
* If you're looking to add a library please check the [contributing guide](#contributing).

## AI

* Transcribe Swedish
  * [KB-Whisper](https://github.com/PierreMesure/whisper-web) ⭐ 35 | 🐛 6 | 🌐 TypeScript | 📅 2026-03-30

## People

* Validate Swedish Personal Identity Number (personnummer / SSN)
  * [JavaScript](https://github.com/personnummer/js) ⭐ 59 | 🐛 10 | 🌐 TypeScript | 📅 2026-08-19
  * [.NET (C# / F#)](https://github.com/ActiveLogin/ActiveLogin.Identity) ⭐ 58 | 🐛 18 | 🌐 F# | 📅 2026-04-10 (Also parses and normalizes the Personal Identity Number)
  * [PHP](https://github.com/personnummer/php) ⭐ 34 | 🐛 3 | 🌐 PHP | 📅 2026-08-11
  * [Ruby](https://github.com/c7/personnummer) ⭐ 21 | 🐛 0 | 🌐 Ruby | 📅 2020-03-01 (well tested)
  * [PHP](https://github.com/byrokrat/id) ⭐ 15 | 🐛 0 | 🌐 PHP | 📅 2021-01-03
  * [Python](https://github.com/personnummer/python) ⭐ 14 | 🐛 1 | 🌐 Python | 📅 2026-07-21
  * [Java](https://github.com/personnummer/java) ⭐ 9 | 🐛 3 | 🌐 Java | 📅 2026-08-07
  * [Go](https://github.com/personnummer/go) ⭐ 8 | 🐛 3 | 🌐 Go | 📅 2026-07-16
  * [Ruby](https://github.com/personnummer/ruby) ⭐ 6 | 🐛 1 | 🌐 Ruby | 📅 2026-06-19
  * [Swift](https://github.com/personnummer/swift) ⭐ 4 | 🐛 3 | 🌐 Swift | 📅 2026-07-12
  * [JavaScript](https://github.com/arokor/pernr) ⭐ 3 | 🐛 1 | 🌐 JavaScript | 📅 2018-04-07
  * [JavaScript](https://github.com/svenheden/swedish-personal-identity-number-validator) ⭐ 1 | 🐛 1 | 🌐 JavaScript | 📅 2026-03-02
  * [Go](https://github.com/bombsimon/go-personnummer) ⭐ 1 | 🐛 0 | 🌐 Go | 📅 2022-03-22
  * Various other implementations are available under [this GitHub organization](https://github.com/personnummer), please note that some listed there are still WIP.
* Statens personadressregister
  * [JavaScript](https://github.com/Yepstr/node-statenspersonadressregister) ⭐ 1 | 🐛 0 | 🌐 JavaScript | 📅 2017-06-05
  * [Reference implementations (PHP/C#/Java)](https://github.com/Statenspersonadressregister)

## Companies

* Validate Swedish Company Registration Number (organisationsnummer)
  * [Ruby](https://github.com/mirendo/orgnummer) ⭐ 4 | 🐛 0 | 🌐 Ruby | 📅 2022-03-18
  * [JavaScript](https://github.com/perarnborg/se-org-no) ⭐ 0 | 🐛 4 | 🌐 JavaScript | 📅 2023-01-07
  * [PHP](https://github.com/byrokrat/id) ⭐ 15 | 🐛 0 | 🌐 PHP | 📅 2021-01-03
  * [JavaScript](https://github.com/eckberg/se-orgnr-validator) ⭐ 1 | 🐛 0 | 🌐 JavaScript | 📅 2019-08-16
  * [Go](https://github.com/bombsimon/go-personnummer) ⭐ 1 | 🐛 0 | 🌐 Go | 📅 2022-03-22

## Finance

* Swish Merchant API
  * [JavaScript](https://github.com/carlbarrdahl/swish-payments) ⭐ 10 | 🐛 15 | 🌐 TypeScript | 📅 2023-01-03 — Not actively [being maintained](https://github.com/buren/awesome-sweden/issues/15) ⭐ 208 | 🐛 10 | 🌐 Shell | 📅 2026-04-21.
  * [Rust](https://github.com/drager/swish) ⭐ 3 | 🐛 0 | 🌐 Rust | 📅 2018-12-02
  * [Go](https://github.com/frozzare/go-swish) ⭐ 2 | 🐛 0 | 🌐 Go | 📅 2024-08-21
* Validate Swedish bank accounts
  * [Ruby](https://github.com/barsoom/banktools-se) ⭐ 34 | 🐛 0 | 🌐 Ruby | 📅 2026-06-24
  * [JavaScript](https://github.com/brocc-ab/se-bank-account-js) ⭐ 9 | 🐛 2 | 🌐 JavaScript | 📅 2023-12-15
  * [PHP](https://github.com/brocc-ab/se-bank-account-php) ⭐ 3 | 🐛 1 | 🌐 PHP | 📅 2023-12-15
* Make BGC supplier payment files (a.k.a "leverantörsbetalningar")
  * [Ruby](https://github.com/barsoom/supplier_payments) ⭐ 1 | 🐛 0 | 🌐 Ruby | 📅 2026-06-23
* Payments using DebiTech (DIBS)
  * [Ruby](https://github.com/barsoom/debitech) ⚠️ Archived
* Parse and generate SIE-files (open format for accounting data)
  * [Ruby](https://github.com/barsoom/sie) ⭐ 17 | 🐛 1 | 🌐 Ruby | 📅 2026-06-22
* Retrieve interest and exchange rates from the Swedish central bank
  * [Go](https://github.com/zeeraw/riksbank) ⭐ 5 | 🐛 0 | 🌐 Go | 📅 2020-11-25

## Authentication

* Authentication using BankID
  * [.NET (C# / F#)](https://github.com/ActiveLogin/ActiveLogin.Authentication) ⭐ 240 | 🐛 33 | 🌐 C# | 📅 2026-08-19 (With authentication handler for ASP.NET)
  * [JavaScript](https://github.com/anyfin/bankid) ⭐ 72 | 🐛 5 | 🌐 TypeScript | 📅 2026-07-20 by [Anyfin](https://anyfin.com/)
  * [Android](https://github.com/spacecowboy/bankid-android-sample) ⭐ 5 | 🐛 0 | 🌐 Kotlin | 📅 2019-01-30 (Sample implementation)
* Authentication using GrandID (Svensk E-Identitet)
  * [.NET (C# / F#)](https://github.com/ActiveLogin/ActiveLogin.Authentication) ⭐ 240 | 🐛 33 | 🌐 C# | 📅 2026-08-19 (With authentication handler for ASP.NET)

## Job market

* Build a feed for Metrojobb
  * [Ruby](https://github.com/buren/metrojobb) ⭐ 1 | 🐛 2 | 🌐 Ruby | 📅 2023-11-01
* Arbetsförmedlingen API
  * [Ruby](https://github.com/buren/arbetsformedlingen) ⭐ 10 | 🐛 7 | 🌐 Ruby | 📅 2023-07-01
* Post jobs to Arbetsförmedlingen
  * [Ruby](https://github.com/buren/arbetsformedlingen) ⭐ 10 | 🐛 7 | 🌐 Ruby | 📅 2023-07-01
  * [JavaScript](https://github.com/othermachines/platsbanken-vacancy) ⭐ 1 | 🐛 1 | 🌐 JavaScript | 📅 2018-03-19

## Transportation

* SL API
  * [JavaScript](https://github.com/simon-johansson/SL-api) ⭐ 7 | 🐛 0 | 🌐 CoffeeScript | 📅 2017-07-01 - :warning: No commits in years
  * [Javascript](https://github.com/rebelliard/stockholm-transit-api) ⭐ 2 | 🐛 0 | 🌐 TypeScript | 📅 2022-08-02
  * [Go](https://github.com/frozzare/go-sl) ⭐ 2 | 🐛 0 | 🌐 Go | 📅 2017-12-19
* Västtrafik API
  * [JavaScript](https://github.com/oskarhagberg/node-vasttrafik) ⭐ 4 | 🐛 0 | 🌐 JavaScript | 📅 2013-02-21
* Trafikverket API
  * [JavaScript](https://github.com/eduardoportilho/trafikverket) ⭐ 2 | 🐛 0 | 🌐 JavaScript | 📅 2017-12-11
* Bilvision API (car register service a.k.a "Bilregistertjänst")
  * [Ruby](https://github.com/sandelius/bilvision)

## Regional

:information\_source: see the [transportation](#transportation) section for regional transportation.

* Stockholm API
  * [JavaScript](https://github.com/buren/stockholm-api) ⭐ 4 | 🐛 4 | 🌐 JavaScript | 📅 2023-08-01
* Göteborg (Gothenburg) API
  * [JavaScript](https://github.com/oskarhagberg/gbgcity) ⭐ 2 | 🐛 0 | 🌐 JavaScript | 📅 2012-06-27

## Geographic

* [SWEREF99 TM (EPSG:3006)](https://epsg.io/3006) projected coordinate system
  * [JavaScript](https://kartena.github.io/Proj4Leaflet)

## Media

* Sveriges Radio API
  * [JavaScript (CLI)](https://github.com/ollelauribostrom/sverigesradio) ⭐ 3 | 🐛 7 | 🌐 JavaScript | 📅 2025-07-14
* [MMS](http://mms.se/) API client (analyzes TV consumption in Sweden)
  * [Go](https://github.com/TV4/mms) ⚠️ Archived
* Translates SAB (Swedish library classification system) codes to, human readable, Swedish subject
  * [Ruby](https://github.com/c7/ur-sab) ⭐ 1 | 🐛 0 | 🌐 Ruby | 📅 2010-12-16

## Construction

* [ROT-avdrag calculator](https://github.com/zaragoza-ab/rot-avdrag-calculator) ⭐ 0 | 🐛 0 | 🌐 HTML | 📅 2026-04-17 - Interactive 2026 ROT tax deduction calculator (HTML/JS)
* [RUT-avdrag calculator](https://github.com/zaragoza-ab/rut-avdrag-calculator) ⭐ 0 | 🐛 0 | 🌐 HTML | 📅 2026-04-17 - Interactive 2026 RUT tax deduction calculator (HTML/JS)
* [Entreprenör verification tool](https://github.com/zaragoza-ab/entreprenor-verification-tool) ⭐ 0 | 🐛 0 | 🌐 HTML | 📅 2026-04-17 - 9-step checklist for verifying Swedish construction firms (F-skatt, insurance, ID06, references)
* [Bygglov checklist](https://github.com/zaragoza-ab/bygglov-checklist-sweden) ⭐ 0 | 🐛 0 | 📅 2026-04-17 - Building permit checklist for Swedish kommuner (focused on Skåne)
* [Personalliggare template](https://github.com/zaragoza-ab/personalliggare-template) ⭐ 0 | 🐛 0 | 📅 2026-04-17 - Skatteverket-compliant personnel ledger (HTML form + CSV/JSON schema)
* [Arbetsmiljöplan template](https://github.com/zaragoza-ab/arbetsmiljoplan-template) ⭐ 0 | 🐛 0 | 📅 2026-04-17 - AFS 1999:3 work environment plan template
* [Omvänd moms guide](https://github.com/zaragoza-ab/omvand-moms-bygg-guide) ⭐ 0 | 🐛 0 | 📅 2026-04-17 - Reverse-charge VAT guide with invoice templates

## Misc

* Kolada API - KPIs concerning Swedish municipalities and organizational units
  * [JavaScript](https://github.com/buren/kolada) ⭐ 6 | 🐛 1 | 🌐 JavaScript | 📅 2023-08-01
* Polisen API
  * [JavaScript](https://github.com/buren/polisen-api) ⭐ 1 | 🐛 1 | 🌐 JavaScript | 📅 2023-08-01 - events and police stations
* SCB API (Statistiska Centralbyrån)
  * [Ruby](https://github.com/peterhellberg/scb) ⭐ 1 | 🐛 0 | 🌐 Ruby | 📅 2013-05-13
  * [JavaScript](https://www.npmjs.com/package/scb-api)
* SMHI API
  * [JavaScript](https://github.com/thelinmichael/smhi-node) ⚠️ Archived
  * [C#](https://github.com/piksel/SMHISharp) ⭐ 1 | 🐛 0 | 🌐 C# | 📅 2018-03-19
  * [JavaScript](https://github.com/peterstark72/smhi-nodejs) ⭐ 1 | 🐛 0 | 🌐 JavaScript | 📅 2017-07-27
* Phone number formatter
  * [JavaScript](https://github.com/jonathanp/swedish-phone-number-formatter) ⭐ 7 | 🐛 2 | 🌐 JavaScript | 📅 2022-03-24
* Postal code validator
  * [JavaScript](https://github.com/jonathanp/swedish-postal-code-validator) ⭐ 0 | 🐛 2 | 🌐 JavaScript | 📅 2022-04-09
  * [Go](https://github.com/bombsimon/swedish-zipcode) ⭐ 0 | 🐛 0 | 🌐 Go | 📅 2019-11-20
  * [Rust](https://github.com/bombsimon/swedish-postal-codes) ⭐ 0 | 🐛 0 | 🌐 Rust | 📅 2020-08-02
* Postal code lookup
  * [JavaScript](https://github.com/vzhufk/z1p) ⭐ 19 | 🐛 0 | 🌐 JavaScript | 📅 2018-11-01
* Postnord
  * [Python](https://github.com/dunderrrrrr/postnord_api) ⭐ 0 | 🐛 1 | 🌐 Nix | 📅 2025-12-16
* Cardinal number converter
  * [JavaScript](https://github.com/jonathanp/swedish-cardinal-numbers) ⭐ 0 | 🐛 4 | 🌐 JavaScript | 📅 2022-04-09
* Booli API
  * [JavaScript](https://github.com/filipchr/node-booli) ⭐ 1 | 🐛 1 | 🌐 JavaScript | 📅 2022-06-25
* Hemnet
  * [PHP WordPress plugin](https://github.com/bombsimon/hemnet-plugin) ⚠️ Archived
* Blocket
  * [Python](https://github.com/dunderrrrrr/blocket_api) ⭐ 42 | 🐛 0 | 🌐 Python | 📅 2026-07-23

## Wish list

Libraries and other things we wished existed or haven't heard of yet.

* Bank account validation in more languages
* BankID tools in more languages
* [Swish](https://www.swish.nu/)
* API Clients
  * [Statistikdatabasen](https://www.scb.se/vara-tjanster/oppna-data/) (SCB)
  * APIs listed at <https://www.trafiklab.se/api>
* Hemnet
* PostNord API
* ... anything you'd like to add?

## Contributing

Contributions, feedback and suggestions are very welcome.

:information\_source: Looking to add a dataset? See [Awesome Sweden Datasets](https://github.com/buren/awesome-sweden-datasets) ⭐ 28 | 🐛 5 | 🌐 Shell | 📅 2026-04-21.

**Before you start, make sure**

1. That it's directly related to building applications for the Swedish market (there are plenty of other awesome lists for other types of tools, [here](https://github.com/sindresorhus/awesome) ⭐ 497,669 | 🐛 102 | 📅 2026-08-18)
2. The library is not already added to this list
3. The library is somewhat stable

then

1. Fork it
2. Create your feature branch (`git checkout -b my-new-feature`)
3. Commit your changes (`git commit -am 'Add some feature'`)
4. Push to the branch (`git push origin my-new-feature`)
5. Create new Pull Request

* Make sure to clearly state what the library does and why its relevant (unless thats obvious)

## License

[Creative Commons CC0](LICENSE).

***

[![Build Status](https://app.travis-ci.com/buren/awesome-sweden.svg?branch=master)](https://app.travis-ci.com/buren/awesome-sweden) passing build means all URLs are 200.

***

> _Enhansomed by [enhansome](https://github.com/enhansome) on 2026-08-19._
