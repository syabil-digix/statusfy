---json
{
  "title": "Payroll full compensation migration",
  "date": "2021-12-20T06:26:56.833Z",
  "severity": "degraded-performance",
  "affectedsystems": [
    "site-delivery"
  ],
  "resolved": true,
  "modified": "2021-12-20T09:27:42.841Z"
}
---
The query used are n+1 which hogging the system resources during this process

<!--- language code: en -->
