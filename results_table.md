### IOS Medical Apps

Searching the Apple iTunes store is typically done manually via the iTunes Application. Apple does not provide an openly accesable API to access store data. Therefore, searching for and gathering data about IOS Applications is not easy. However, Apple does provide an rss feed that can be used to list Apps in speficific categories and ordered acording to how new, or how popular they are and if they are free or not. The rss feed is limited to 100 items per category. The data provided by the rss feed is minimal, not much more than title and a text description of the app. There are no sub-genres or tags than can be used to further differentiate the apps.

Using a python script data was gathered from the following rss feeds:
* Top 100 Free Medical Apps
* Top 100 Grossing Medical Apps
* Top 100 Paid Medical Apps
This combined results included data about 255 IOS apps. The title and description fields were imported into a database. Other information from the data such as price, right, or image link were ignored. Based on the description of the app one or more categories were manually assigned to the app in order to further differentiate them
