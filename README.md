*This README is auto-generated. Do not edit manually — changes will be overwritten.*

# Platform Share on USA.gov

Monthly desktop and mobile platform usage based on [DAP (Digital Analytics Program)](https://digital.gov/guides/dap/) OS visit data.

See [`analysis/os_filter.json`](analysis/os_filter.json) for which desktop platforms are included and excluded.

**Data range:** 2018-01 to 2026-09

## Desktop platforms

![Desktop platform share over time](assets/desktop-platforms.png)

### Latest month (2026-09)

| Platform | Share |
| --- | ---: |
| WINDOWS | 72.7% |
| MAC | 18.8% |
| LINUX | 6.4% |
| CHROME OS | 2.1% |
| BSD | 0.0% |

## Mobile platforms

![Mobile platform share over time](assets/mobile-platforms.png)

### Latest month (2026-09)

| Platform | Share |
| --- | ---: |
| IOS | 68.3% |
| ANDROID | 31.7% |

## Regenerate locally

```bash
pip install -r requirements.txt
python analysis/generate_readme.py
```
