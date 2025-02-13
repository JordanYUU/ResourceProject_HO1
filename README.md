# ResourceProject_HO1
Resource project handoff with Angela on behalf of Matt. This project looks at past due orders and asks if we have suppliers that has stock on hand which United can get our hands on. After collecting bids, we check for overlap, and we take the lower price out of them. The price is typically reasonable. It's based on quantity rate. L5s like Matt and Angela can approve anything up to ~$5000. After getting the data we need we then ask suppliers to cancel certain orders.


### Context
This project has been iterated on multiple times in the past.

We're trying to take out POs with exceptions, former resourced pos, filter out buyer codes that are 2, 4, 5, and 6, and those are are unavailable to be resourced. Basically some cleanup to figure out what can we actually resource.


### Project Proccess (General Tasks)
Yellow/pink columns 
VLookup
check if quote is active or expired
Concat the po number
look for alt vendor rep name (who has the po should we resource it)
Add new rep list.
Check if po vendor is the same as alt
Take out part # and resource hold
Filter out any N/A alt vendor names
Check active quotes for all suppliers to determine which to reach out to
When reaching out, we're basically asking for estimated dates 
After getting raw bids, delete whatever they don't have in stock
After getting responses, make any special notes (e.g. "Only ships in quantities of 50")
Awards are givin if only one supplier placed a bid. If there's more than 1 supplier, the lower bidder is awarded
Matt typically gives suppliers 2-3 days to reply to emails; it's rare that suppliers fail to respond.
POs to resource tab is what we're building to send out to the team. 

After all of that, the POs to resource, Summary, and Values tabs gets duplicated to a new workbook to then be sent out to reps for actioning. We can pick which suppliers to reach out to each round.

### Other notes
His active? checks if the date is before the date, and if so it shows as expired.
The same is true for the exception? column

Matt does a lot of the work manually but is open to us automating things as we see fit. 

Once a month is Matt's go-to timeline for this project.

### Keywords
Supplier - 
Quote - 
JWUU - 
M&E - 
