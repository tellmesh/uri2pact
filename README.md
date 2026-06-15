# uri2pact


## AI Cost Tracking

![PyPI](https://img.shields.io/badge/pypi-costs-blue) ![Version](https://img.shields.io/badge/version-0.1.1-blue) ![Python](https://img.shields.io/badge/python-3.9+-blue) ![License](https://img.shields.io/badge/license-Apache--2.0-green)
![AI Cost](https://img.shields.io/badge/AI%20Cost-$0.00-orange) ![Human Time](https://img.shields.io/badge/Human%20Time-1.0h-blue) ![Model](https://img.shields.io/badge/Model-openrouter%2Fqwen%2Fqwen3--coder--next-lightgrey)

- 🤖 **LLM usage:** $0.0001 (1 commits)
- 👤 **Human dev:** ~$100 (1.0h @ $100/h, 30min dedup)

Generated on 2026-06-15 using [openrouter/qwen/qwen3-coder-next](https://openrouter.ai/qwen/qwen3-coder-next)

---

Shared loader for `markpact://` registries embedded in README files.

Used by:

- `touri` — `markpact:capability` blocks → capability manifests
- `uri2flow` — `markpact:flow` blocks → compact URI flows

## Example

```bash
touri list markpact://examples/22_markpact_weather/README.md
uri2flow expand markpact://examples/22_markpact_weather/README.md#weather-local-health
```

See [`docs/MARKPACT_WITH_TOURI.md`](../../docs/MARKPACT_WITH_TOURI.md).


## License

Licensed under Apache-2.0.
