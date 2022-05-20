## Open Market Content Management System is Comming Soon!
## E-Commerce with Big Ideas!

### Whats OMCMS

We wanted to create a new CMS (Content Management System) that had similar features as Wordpress but more easy to maintain and use.
The more advanced it is the more difficult it is to maintain "usually", so we decided to create OMCMS, a platform thats mimlistic and efficent while offering the privacy and security features every E-Commerce Platform should have.

OMCMS (Open Market Content Management System) is a opensource self-hosted E-Commerce Platform, thats crypto and privacy focussed.
We aim to provide a easy to use platform for marketing where users are in control.

### What does OMCMS have to offer?

1. Vendor chooses what there willing to accept for crypto as a payment.
2. Each user has a generated GPG-Key Pair created upon creating an account.
3. All internal messages are encrypted by default.
4. Upon sending inqueries to vendor only one able to decrypt it is the vendor.
5. Blogging support only for admins at the moment.
6. Users can upload a seperate Public GPG-Key for securing there communications.
7. Backup and restore with ease with built in md5 hashing for integrity checks by default.
8. OMCMS Currently Only Supports MySQL.
9. Tagging and rep system for every user including vendors.
10. Only users who had purchased an item can leave a review, which helps prevent fake reviews.
11. Theres No Javascript as this project is privacy focussed while being Tor Browser friendly.
12. Plugins Repo.
13. Themes Repo.

## How does this work?

OMCMS works by using MySQL as a database.
Upon creating new listings, each string after TLD (.com,.net,.onion etc) is stored in the database not the actual url, like in WordPress!
Each posting of either a listing or blog update is a sepearate php file containing all the contents for that page.

When a user registers, all there content in in a folder thats encrypted with there GPG-Key thats created upon registration.

## Whats left for development?

1. Implement photo uploads.
2. Sanitise hidden metadata upon uploading photos/files for privacy reasons.
3. Add Plugins support.
4. Add Themes support.
5. 
6. Create Installer.

## What do we plan on adding?

We want to implement a 2FA feature that utilizes a Security Key

## What are some future features we would like to see?

With OMCMS we have the hopes in creating platform thats node based.
A marketplace thats self-hosted but also offers the ability to be a part of a global network of nodes with a mirrored DB for data integrigry and responsiveness.
If one node goes down that marketplace with still run as there other nodes that are a part of a mirrored database.

### Support or Contact

If this project interest you please reach out to us via email: omcms@tutanota.com,

Please use the following GPG-Key to secure your communications.
