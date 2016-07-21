### Gathering App Data from the Google Play Store

In order to gather data from the Goole app store a script was programmed that could extract lists of apps from a specific url. The following urls were scanned:

* Top Paid Medical Apps : 
https://play.google.com/store/apps/category/MEDICAL/collection/topselling_paid

* Top Free Medical Apps : 
https://play.google.com/store/apps/category/MEDICAL/collection/topselling_free

For each app listed the script would extract the url of the app's detail page, where further imformation would be gathered and stored in a database.

The data set is similar to that of the itunes rss feed. The fields are limited to name, description, developer, image, and pricing. Based on the description text the apps were manually assigned to one or more categories. 