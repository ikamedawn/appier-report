For more information about the API, see
the [Appier Cost API](https://docs.crossx.appier.com/docs/cost-api).

# Reporting API

## Get report

```python
from appier-report import Report

report = Report(access_token="your_access_token")
result = report.get_report(start_date='2023-05-27', end_date='2023-05-27')
print(result)
```
