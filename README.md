# eve-batch-apprise-contracts-faction
This tool fetches 30-day average contract prices from Adam4EVE using TypeIDs and appraises a list of EVE Online items. NOT FULLY COMPLETE!



Adam4EVE Contract Appraisal Tool
================================

This tool fetches 30-day average contract prices from Adam4EVE using TypeIDs
and appraises a list of EVE Online items. Outlier prices (±30% from median)
are filtered for cleaner valuation.

HOW TO USE
----------
1. Make sure you have Python 3 installed.
2. Open terminal / CMD in this folder and run:

    pip install requests

3. Put your Item list into [Janice https://janice.e-351.com ](https://janice.e-351.com), press submit and then the copy icon

4. CTRL+V into `Input.txt`

5. Run the script:

    python adam4eve_price_fetcher.py

6. Your result will be saved to:

    contract_appraisal_results.csv

NOTE: Items without contract price data or invalid TypeIDs will be skipped.

Fly dangerous o7
