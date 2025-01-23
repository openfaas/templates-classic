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

### License

This project is part of the OpenFaaS project licensed under the MIT License.
