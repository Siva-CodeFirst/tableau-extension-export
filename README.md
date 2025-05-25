# Export Data Tableau Extension

## Introduction
No matter how much you try to convince them, there will always be some users who want to reduce your beautiful Tableau charts to a table of numbers in Excel. So if they're going to do it anyway, you may as well give them a simple, controlled way, generating one Excel workbook and not a bunch of CSVs.

With the Export Data extension for Tableau Server you can place a simple button onto your dashboard, choose which sheets & columns are exported, and with one click your users can download a clean & tidy Excel workbook.

## Security/Privacy
At The Information Lab mission is to enable as many people as possible to use Tableau. Collecting private data or even metadata would be a pretty big blocker to this and so we just don't do it. Whether you use the standard hosted extension or the local installation no data is sent from the extension to any of our servers or hosting systems.

### In that case why isn't the extension sandboxed?
Good question! We'd love to allow the Export Data extension to be sandboxed, it would be able to enable so many more users including those on Tableau Public. In fact we were one of the very early advocates for the sandboxing of extensions. 

Sadly when it came to the implementation of a sandboxed extension the downloading of a file by an extension was considered to be a vector for attack and so was blocked. By definition of its primary function of allowing you to download your dashboard's summary data in an Excel file the Export Data extension can never be sandboxed. Please send any sad face emojis 😔 to Tableau.