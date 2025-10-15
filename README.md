# US Airline Sector Financial Analysis

This report provides a detailed comparative financial analysis of three distinct players in the U.S. airline industry: legacy carrier United Airlines (UAL), low-cost carrier JetBlue (JBLU), and regional operator SkyWest (SKW). Utilizing financial data from the beginning of 2020 through the end of fiscal year 2024, this study examines the post-pandemic recovery, financial health, profitability, and operational efficiency of each company. The strategic importance of this analysis lies in understanding the divergent recovery paths and competitive positioning that have emerged in a sector profoundly reshaped by recent global events.

## Data Sources

- Financial Modeling Prep (FMP) API: https://financialmodelingprep.com/developer/docs/

## Steps to render gh-pages

Follow https://quarto.org/docs/publishing/github-pages.html#publish-command

1.  Modify "\_quarto.yml"

``` yaml
project:
  type: website
  output-dir: docs
```

2.  Add `.nojekyll` file at the root of the repo

``` bash
touch .nojekyll
```

3.  Render your site and push it to GitHub

``` bash
quarto render
git push
```

4.  Update `.gitignore` to have following

``` bash
/.quarto/
/_site/
```

5.  Publish to gh-pages

``` bash
quarto publish gh-pages
```
