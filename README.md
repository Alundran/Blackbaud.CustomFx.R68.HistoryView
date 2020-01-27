# Blackbaud.CustomFx.R68.HistoryView
Adds a button to the R68 Process history to view a snapshot report of data retained in the Gift Aid Online Submission XML. This is for Blackbaud CRM.

## What does this customisation do?

This customisation contains a report and spec that is based on the original R68 report spec for Blackbaud CRM. A new stored procedure is created which parses the XML that is submitted to HMRC as part of the Online Submission Process. Since the XML is stored when it's sent, we can parse this data into a report. The benefits of this is you will always be able to report on what data was sent as part of the Online Submission process where as currently the out of box reports are dynamic which restrict an organisations' ability to see point in time data.

### Installing

Download the Blackbaud.CustomFx.R68.HistoryView DLL and place it in the \bbappfx\vroot\bin folder of your Blackbaud CRM installation.

Navigate to Administration -> Features -> Catalog Browser in BBCRM and deploy the R68 History View Package. A new Action button will appear on the History tab of the R68 Process called 'View R68 Snapshot report'.

## Authors

* **Derek Marr**
