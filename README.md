# OpenFaaS Classic templates

These templates should be considered deprecated, and recommended templates from the documentation or Function Store should be used instead.

They are retained in this repository for backwards compatibility purposes.

See also: [Language support](https://docs.openfaas.com/languages/overview/).

## Usage

```bash
faas-cli template store pull https://github.com/openfaas/templates-classic
```

Or

```bash
export OPENFAAS_TEMPLATE_STORE_URL="https://github.com/openfaas/templates-classic"

faas-cli new --lang go \
    NAME
```

## Contents

In most cases, alternatives have already been provided and are listed int the Function Store, or the [Languages section of the OpenFaaS documentation](https://docs.openfaas.com/languages/overview/).

| Name | Language | Version | Linux base | Watchdog | Link
|:-----|:---------|:--------|:-----------|:---------|:----
| go | Go | 1.23 | Alpine Linux | classic | [Legacy Go template (deprecated)](https://github.com/openfaas/templates/tree/master/template/go)
| bun-express | Bun | 1.0 | Alpine Linux | of-watchdog | [NodeJS template](https://github.com/openfaas/templates/tree/master/template/bun-express)
| node | NodeJS | 20 | Alpine Linux | classic | [Legacy NodeJS template (deprecated)](https://github.com/openfaas/templates/tree/master/template/node)
| python3 | Python | 3 | Alpine Linux | classic | [Legacy Python 3 template](https://github.com/openfaas/templates/tree/master/template/python3)
| python3-debian | Python | 3 | Debian Linux | classic | [Legacy Python 3 Debian template](https://github.com/openfaas/templates/tree/master/template/python3-debian)
| python27 | Python | 2.7.18 | Alpine Linux | classic | [Python 2.7 template (deprecated)](https://github.com/openfaas/templates/tree/master/template/python27)
| ruby | Ruby | 3.3 | Alpine Linux | classic| [Ruby template](https://github.com/openfaas/templates/tree/master/template/ruby)
| csharp | C# | N/A | Debian GNU/Linux 9 | classic | [Legacy C# template (deprecated)](https://github.com/openfaas/templates/tree/master/template/csharp)


### License

This project is part of the OpenFaaS project licensed under the MIT License.
