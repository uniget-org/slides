## Quickstart <i class="fa-duotone fa-rocket-launch"></i>

Install `uniget`

```bash
curl -sLf https://github.com/uniget-org/cli/releases/latest/download/uniget_Linux_$(uname -m).tar.gz \
| sudo tar -xzC /usr/local/bin uniget
uniget update
```

Discover tools

```bash
uniget list
uniget tags
uniget search docker
uniget describe docker
```

Install/update tools

```bash
uniget install gojq yq
uniget install --default --plan
```