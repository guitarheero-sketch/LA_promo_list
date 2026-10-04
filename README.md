# GS009 LA Promo Finder — October 2026

A simple staff webpage for Living Appliances at Grand Senheng Temerloh.

## Open on your computer

Extract the ZIP first, then open `index.html`. Keep `index.html`, `style.css`, `app.js` and `data.js` together in the same folder. No installation or build command is needed.

## Make it public with GitHub Pages

Use a separate repository so you do not replace your existing CLKA webpage.

1. Sign in to GitHub. Create a new **public** repository, for example `gs009-la-promos`.
2. Extract this ZIP on your computer.
3. In the repository, choose **Add file → Upload files**. For an empty repository, use the **uploading an existing file** link.
4. Upload the extracted files, especially `index.html`, `style.css`, `app.js` and `data.js`. Upload the files themselves, not the ZIP or the outside folder. `index.html` must appear directly in the repository's main file list.
5. Choose **Commit changes**.
6. Open **Settings → Pages**.
7. Under **Build and deployment**, choose **Deploy from a branch**.
8. Select branch **main**, folder **/(root)**, then **Save**.
9. When GitHub finishes publishing, open the website link shown on the Pages screen. It will usually look like `https://YOUR-USERNAME.github.io/gs009-la-promos/`.

You do not need a `.github` folder or a workflow file. Nothing has been uploaded to your GitHub account by this package.

GitHub instructions: https://docs.github.com/en/pages/getting-started-with-github-pages/configuring-a-publishing-source-for-your-github-pages-site

## Included

- 1,138 models, including 365 air conditioners and 87 water heaters.
- Search by model, brand, product line or feature.
- Aircond filters for HP, inverter type and mounting.
- Water heater filters for pump and shower type.
- Brand, category, unit-price budget and offer filters.
- Compare up to three models side by side.
- Copy model code, Google product search and copy customer summary.
- Separate member price, Instant Save, S-Coin reward and installation charges.
- 28 standard installation/cleaning codes and eight LG CareShip plan codes.
- Shortlist retained for the current browser session.

## Price and promotion rules

Source: `LA Product List of Oct'26.xlsx`. Prepared 4 October 2026.

- SC / X-stock prices and total cashback rates take priority. Other sheets supply fields not listed there.
- This LA workbook has no separate 3X sheet. Its TOTAL S-COIN value is used directly; it is not multiplied again.
- Blank gift cells mean no gift. Older gift names are not restored from other online offers.
- 100% S-Coin cashback is retained as a valid clearance offer. It is a later reward, not a zero checkout price.
- Cashback uses member/Block price before Instant Save. Installation fees are excluded from the displayed cashback base.
- RM65 standard-shower / RM80 rain-shower promo installation is added to the device price.
- GS009 is not on the workbook's BTB branch list. Standard branch service rates are used.
- Brand TNG is claimed separately by the customer from the brand. It is not deducted from the displayed payment.
- FR, Backend, internal costs, grades, sales history and unclear RW RATE fields are excluded.
- Unknown features remain “Not stated”. No live inventory or remaining-stock quantity is implied.

## Verified model corrections

Selected specifications and names were checked against official brand and Senheng pages. The relevant model details include product-reference links.

- LG S3-Q09JAYPP: 1.0HP according to LG; workbook says 1.5HP.
- LG AS65GDBY0: PuriCare Alpha Pet Single; LG AS10GDBY0: Double. The workbook reverses those names. Workbook prices are preserved with a visible check note.
- LG CareShip is a separate LG care service. Do not infer a free-visit schedule or extended warranty from the workbook's “service warranty 1” field.
- Source conflicts and suspicious specifications are shown in each model's staff checks.

## Update next month

This is a static October snapshot. It does not fetch new prices automatically.

When a new workbook is ready, have the data rebuilt and replace `data.js` with the updated version. Review month labels and promotion dates in `index.html` and `app.js` at the same time. Changing only the heading does not update prices.

After October 2026, the page displays a stale-data notice. Expired installation offers stop being used in installation totals; matching standard rates are used instead. Other October prices remain visible as historical reference. The dated LG campaign ends 1 November 2026. Undated gifts remain subject to stock and current confirmation.

## Validation

Automated checks passed for all 1,138 card/detail renders, SC price priority, cashback arithmetic, search, HP and budget filters, the three-model limit, installation totals, service codes, calculator and expired-offer fallback.

Browser visual testing could not be completed in the build environment because the browser download failed. Check the page on your phone after upload, particularly comparison-table horizontal scrolling.

## Files

- `index.html`: webpage structure
- `style.css`: responsive appearance
- `app.js`: search, filters, comparison and calculations
- `data.js`: sanitized product and service data
- `README.md`: these instructions

The site runs without a backend. No account login or analytics is built in. Google search, product-reference links and the optional Google Fonts stylesheet use external websites. This is a staff reference, not an official Senheng website.
