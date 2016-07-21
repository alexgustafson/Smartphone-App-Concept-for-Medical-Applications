## Categorization

The term "Medical App" is very broad and neither the iTunes nor Goole app stores offer any kind of sub categorization. In order to get a better overview of what sort of Medical Apps are available it was necessary to manually browse the gathered data and assign categories to the apps.

A database management tool was created using the python based Django Web Framework. Django provides many tools that makes constructing and interacting with databases very easy. The built-in backend administration tool can be configured to browse, edit, and filter data. 

In order to quickly browse through and categorize over 700 apps. The Django backend admin was configured so that a apps could be categorized one after the other with a minimum of clicks or scrolling. The user was presented a list of uncategorized apps. The first one is clicked. The user is then presented with a page displaying the title and summary text of the app and a field from which a category can be selected. Once saved, that app is no longer presented on the list, the user can select the next app at the top of the list.



