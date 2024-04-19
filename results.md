Results:

I've confirmed that all winners and amounts were indeed the lowest values and correctly associated with the corresponding participant. This assumes a 1:1 match between participant order and price order in the combined field.
Automated Steps:

I would set up an alert through a BI platform to check if the recorded winner doesn't align with the lowest price on a bid, and then trigger an alert. I know how to do this using Looker, with scheduled delivery of reports.
Scaling Up:

Automation of the cleaning process is essential. Participants and their prices per contract should be stored in separate tables, also divided by SKU and date. This allows for validation. The current monolithic table isn't suitable for repeated report delivery. Breaking it up into smaller tables and joining them would be the ideal approach.