# metaculusAIstuff

The Metaculus API does not easily allow searching by category, so i had to do the following.
 - Search for the category
 - Copy everything into a google sheet
 - Sort by string length so the questions would go to the top of the sheet
 - use the process [here](https://www.bettercloud.com/monitor/the-academy/extract-urls-or-link-text-from-a-google-sheets-cell/) to extract the link address
 - parse the address for the question IDs
 - feed the IDs into the API to get the data
