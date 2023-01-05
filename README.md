# Marketing_BI_system_ETL

This is an ETL pipeline to extract data from Facebook Graph API. You can also modify it and apply it to other platforms. Just make sure to read API doc of the platform first.

## 1 - Extract and Transform
- Read Facebook API doc: https://developers.facebook.com/docs/graph-api/
- Use API Explorer to find your needed endpoint: https://developers.facebook.com/tools/explorer/
- Use Request library to extract data, loop through every page and parse into JSON
- Transform data and do feature engineering

## 2 - Load
- Create Credential and connect to Google sheet throught Sheet API
- Load dataframe to Sheet, using Gspread library. Use Incremental load and Full load approaches

After that, you can use a visualization tool and connect to sheet.
