---json
{
  "title": "Payroll rollback",
  "date": "2021-12-20T05:29:21.826Z",
  "severity": "partial-outage",
  "affectedsystems": [
    "api",
    "dns",
    "site-delivery"
  ],
  "resolved": false,
  "modified": "2021-12-20T09:28:08.578Z"
}
---
Payroll rollback will run a background job that will trigger a db deadlock. Most of the background job will fail because of this.

<!--- language code: en -->
