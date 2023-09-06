# Google Analytics

Our Google Tracking ID is: G-RL4MZ0MHZ4

You can see the activity here:

[Google Dashboard](https://analytics.google.com/analytics/web/?authuser=0#/p396897933/reports/intelligenthome)

## How We Enabled Google Analytics

mkdocs material supports Google Analysis.  We only need to add four lines
to our mkdocs.yml configuration file.

```yml
extra:
  analytics:
    provider: google
    property: G-RL4MZ0MHZ4
```

See our mkdocs.yml on GitHub here:

[mkdocs.yml file in GitHub](https://github.com/CoderDojoTC/ai-racing-league/blob/master/mkdocs.yml)

The following line is placed into each HTML web page in the site branch:
```html
<script async="" src="https://www.googletagmanager.com/gtag/js?id=G-RL4MZ0MHZ4"></script>
```