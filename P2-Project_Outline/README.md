# Project Outlines
This is a high-level outline of my project. It may change over time as my mentor provides feedback and direction to help sharpen ideas.

## Assignment Description
[Project Outline Assignment](https://education.launchcode.org/liftoff/assignments/project-outline/)

### Overview

####BatchSnapper: a mobile or web app for wholesale, consignement &/or retail of small batches
                    of one of a kind items by local artists and artisans

    *User #1 : the maker, artist or artisan
    *User #2 : the retail shop manager or buyer that wants to purchase at wholesale
                or consign User #1's items
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

4. Workflow management tracker
    *check off list to-dos of receiving inventory, dated & marking which staff completed
        1. delivery accepted
        2. box unpacked
        3. invoice & packing slip received, esp. digital file of invoice to expedite intake
        4. contents match invoice
        5. buyer approves actual retail prices, if different from vendors' MSRP staff enter into BachSnapper app
        6. if using a separate POS system, csv is exported to be imported into POS system
        7. approved invoice sent to Finance/Bookkeeping to be paid
        8. Finance/Bookkeeping confirm check #, amount & date sent
        9. Finance/Bookkeeping confirm date check cashed


5. Curated selections to appear to shoppers in app, on website, or on alternate sales channels
    * select which goods may appear where (may not want 100% of everything in stock to appear, for example out of season or leading up to official release dates)
    * shoppers have ability to create registries or wish-lists
    * visual history of purchase history
    * ability to tag purchase with meaningful description to remind self later "gift for (name)"

6. Payment processing. Third party?0


### Technologies
*React or React Native stack

&/Or

*Java with [Google's AppEngine](https://cloud.google.com/appengine/)
*[Firebase](https://firebase.google.com/)
*[Google's  Vision API](https://cloud.google.com/vision/?hl=en_US&_ga=2.248130688.-64059599.15359364)

### What I'll Have to Learn
*React or React Native
*how to set up & use Google's AppEngine & APIS
*may use machine learning model training
