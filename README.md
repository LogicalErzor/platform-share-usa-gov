*This README is auto-generated. Do not edit manually — changes will be overwritten.*

# Platform Share on USA.gov

Monthly desktop and mobile platform usage based on [DAP (Digital Analytics Program)](https://digital.gov/guides/dap/) OS visit data.

See [`analysis/os_filter.json`](analysis/os_filter.json) for which desktop platforms are included and excluded.

**Data range:** 2018-01 to 2026-10

## Desktop platforms

![Desktop platform share over time](assets/desktop-platforms.png)

### Latest month (2026-10)

| Platform | Share |
| --- | ---: |
| WINDOWS | 71.2% |
| MAC | 19.5% |
| LINUX | 7.0% |
| CHROME OS | 2.3% |
| BSD | 0.0% |

## Mobile platforms

![Mobile platform share over time](assets/mobile-platforms.png)

### Latest month (2026-10)

| Platform | Share |
| --- | ---: |
| IOS | 68.5% |
| ANDROID | 31.5% |

## Regenerate locally

```bash
pip install -r requirements.txt
python analysis/generate_readme.py
```
