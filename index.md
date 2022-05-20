## Open Market Content Management System is Comming Soon!
## E-Commerce with Big Ideas!

### Whats OMCMS?

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

When a user registers, all there content is in a folder thats encrypted with there GPG-Key thats created upon registration.

To backup OMCMS is as simple as backing up the database and the data folder that contains all the user and store contents thats it, to restore simply reinstall OMCMS and restore database and the backed up data folder!

With each new vendor they will have there own store with a mini store navigation that they can edit such as the store policy, stores GPG-Key, stores description, and also update the stores wallpaper/store photo.

## How does the payment method work?

We thoughtabout using escrow type of payment, but,
we thought that escrow could put a user at risk for using funds as they usually require depositing funds in a wallet, we dont!
As a vendor we ask for your recieving address as we feel its more safer for a typical user and hopefully would help each user feel more confortable.
Even i would speculate is a platform was legit or not when asking me to deposit funds to a website ive never seen.

All vendors are able to add there own payment methods, when posting a new listing vendors have the option to select what coin to accept or all.
While all users will have the ability to choose how to pay based on what the vendor accepts!

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
