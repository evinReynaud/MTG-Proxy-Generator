# MTG-Proxy-Generator
Forked from [philo-jh/MTG-Proxy-Generator](https://github.com/philo-jh/MTG-Proxy-Generator)
## Try the Live App Below:
[MTG Proxy-Generator](https://evinReynaud.github.io/MTG-Proxy-Generator/)
## What's different in this fork?
 - New feature: custom images can be imported to be printed alongside official card images
 - New feature: A dedicated button has been added to print the proxies
 - Improvement: The -cd or -code flags are no longer needed to retrieve cards by code
 - Improvement: The requests to Scryfall's API are spread out to prevent a possible ban of users IP
 - Bug fix: The cards inputted as code (with or without the -cd option) are not altered when retrieving data from Scryfall
## How to Use:
Ever wondered how your deck would play if you just had those couple of cards? Now you can try them out before you buy with MTG Proxy-Generator! Create proxy versions of cards or even decks to playtest before purchasing. Just enter a list in MTGO format with one card name per line. You can then print them out 9 on a page and insert them over other cards in sleeves to playtest.
## Import Decks Using Easy MTGO Syntax
![edit screen](Screenshots/3.png)
## Create Proxy-Versions of Decks You'd Like to Test
![review screen](Screenshots/1.png)
## Choose Whatever Print Your Heart Desires!
![review screen](Screenshots/2.png)
## Technology Used:
This app was built with HTML, CSS, Javascript, jQuery, and Bootstrap. Thanks to the awesome ScryFall API for the database!
