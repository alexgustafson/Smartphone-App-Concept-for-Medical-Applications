### Gathering App Data from the Google Play Store

In order to gather data from the Goole app store a script was programmed that could extract lists of apps from a specific url. The following urls were scanned:

* Top Paid Medical Apps : 
https://play.google.com/store/apps/category/MEDICAL/collection/topselling_paid

* Top Free Medical Apps : 
https://play.google.com/store/apps/category/MEDICAL/collection/topselling_free

For each app listed the script would extract the url of the app's detail page. From the detail page more imformation would be gathered and stored in a database. The data set is similar to that of the itunes rss feed. The title and description text were imported, other fields such as pricing and copyright were ignored. 

Data on 480 Medical Apps for Android was imported. However a significant percentage of the apps could not be classified because the description text was in a language other than English, German, or French. 