# Project Outline
This is a high-level outline of my project. It may change over time as my mentor provides feedback and direction to help sharpen ideas.

## Assignment Description
[Project Outline Assignment](https://education.launchcode.org/liftoff/assignments/project-outline/)

### Overview

####BatchSnapper: a mobile or web app for retail of small batches and one of a kind items by local artists and artisans

    *User #1 : the maker, artist or artisan
    *User #2 : the retail shop manager or buyer that wants to purchase User #1's items at wholesale or sell those items on consignment
    *User #3 : the retail staff handling shipping, receiving, stocking, sales floor
    *User #4 : the shoppers from the general public
    *User #5 : corporate or non-profit shopping accounts (holiday or patron gifts)

    User #1
        1. uses camera phone to snap a picture, apps uses Google Vision API tag with descriptions
        2. verifies & saves "vendorDescr"  the description tag(s) they prefer to tag the item have
        3. inputs wholesale & MSR prices
        4. can reuse descriptions, but would need to retake image if items less than 95% consistent

    Users #2
        1. select a list of favorite vendors
        2. view & select collections from favorite vendors' inventories
        3. plan schedule & route to visit vendors' studios for review & pickup

    Users #3
        1. verifies that items are as described on invoice
        2. verifies & saves "shopDescr"  description tag(s) that follow shop's conventions of categories & types
        3. input additional details "shopTitle"
        4. confirm actual retail price



### Features

1. Catalog Inventory Items
    *vendor saves snapshots and matches them to descriptions (price, Vision API tags)
    *shop staff take better quality images for use on website & other retail channels, these match to inventory descriptions as well

2. Invoicing
    *exported a file, eg. csv, that can be mapped or edited to import into any other POS to expedite inventory intake process

3. Maps GPS to optimize routes for picking up inventory direct from vendors' studios

4.

5. Payment processing
6.


### Technologies
*React or React Native stack

&/Or

*Java with [Google's AppEngine](https://cloud.google.com/appengine/)
*[Firebase](https://firebase.google.com/)
*[Google's  Vision API](https://cloud.google.com/vision/?hl=en_US&_ga=2.248130688.-64059599.15359364)

### What I'll Have to Learn
*React or React Native
*how to set up & use Google's AppEngine & APIS
*Machine learning model training
