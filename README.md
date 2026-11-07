# Market Run prices

Daily price lists of Rami Levy, Osher Ad and Yochananof branches in the Haifa
area, taken from the chains' public price-transparency files and published to
GitHub Pages for the Market Run shopping-list app.

- `scripts/fetch_prices.py` downloads and trims the lists.
- `.github/workflows/prices.yml` runs it twice a day and deploys `site/`.
