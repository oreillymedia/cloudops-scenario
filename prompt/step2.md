
## Description

Please develop a simple web server written in Python or Go that pulls data from the [MBTA API](https://www.mbta.com/developers/v3-api). 

We recommend [registering](https://api-v3.mbta.com/register) (it's free and quick) to get an API Key which will allow up to 1000 requests per minute. Requests with no API keys are limited to 20 per minute.

## Specification

Create a form which allow a commuter to enter a beginning and ending location. The following information should be rendered (jinja2, GoTemplate) in HTML:
- Predict when the next train/bus arrives
    - How does this deviate from the normal schedule?
- Estimated commute time
- Are there any transfers?

Bonus:
- Are there are any alerts which affect our commute?