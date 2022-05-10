# confidentialledger

> see https://aka.ms/autorest

This is the AutoRest configuration file for confidentialledger.

## Getting Started

To build the SDKs for My API, simply install AutoRest via `npm` (`npm install -g autorest`) and then run:

> `autorest readme.md`

To see additional help and options, run:

> `autorest --help`

For other options on installation see [Installing AutoRest](https://aka.ms/autorest/install) on the AutoRest github page.

---

## Configuration

### Basic Information

These are the global settings for the confidentialledger.

```yaml
openapi-type: data-plane
vanilla: true
```

### Tag: package-0.1-preview-ledger

These settings apply only when `--tag=package-0.1-preview-ledger` is specified on the command line.

```yaml $(tag) == 'package-2022-04-20-preview-ledger'
input-file:
  - Microsoft.ConfidentialLedger/preview/2022-04-20-preview/confidentialledger.json
```

### Tag: package-0.1-preview-identity

These settings apply only when `--tag=package-0.1-preview-identity` is specified on the command line.

```yaml $(tag) == 'package-2022-04-20-preview-identity'
input-file:
  - Microsoft.ConfidentialLedger/preview/2022-04-20-preview/identityservice.json
```

---

# Code Generation

## Go

See configuration in [readme.go.md](./readme.go.md)

## Python

See configuration in [readme.python.md](./readme.python.md)

## Ruby

See configuration in [readme.ruby.md](./readme.ruby.md)

## TypeScript

See configuration in [readme.typescript.md](./readme.typescript.md)

## CSharp

See configuration in [readme.csharp.md](./readme.csharp.md)
