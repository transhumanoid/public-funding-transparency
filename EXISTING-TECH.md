# Existing Technology as Confession Engine

## Don't build new — make the existing one confess

QuickBooks files are already structured: chart of accounts, transaction dates, payee names, GST codes. Parse that against the bank feed and the ATO's BAS lodgements, and a discrepancy shows up as a diff, not a narrative. No human has to write a report. The paperwork they're already forced to keep becomes the evidence against them.

## The condition of funding

A condition of receiving funds: you need to upload your recent financials, your recent transaction summary, your transaction statements. Use the export QuickBooks files and stuff that you can use with your internet banking protocols. Use the existing technology.

## What the diff engine would check

- Chart of accounts vs bank feed reconciliation
- Payee names vs approved destination list (BSB/account binding)
- GST codes vs BAS lodgements
- Transaction dates vs funding release dates
- Any mismatch = flagged before funds move

Parked as an idea. Not going deeper for now. The creative side matters more than the implementation details.