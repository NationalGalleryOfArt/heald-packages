# HEALD Place package
Contains the Place data structure for the HEALD wiki

# Requirements

* MediaWiki 1.30+
* PageForms
* PageExchange
* SemanticMediawiki
* mediawiki-pages-HeldImages
* mediawiki-pages-ExternalLink
* mediawiki-pages-Dates
* mediawiki-pages-Geolocation
* mediawiki-pages-HealdPerson
* Chameleon 3

# Setup

* Add the following line to your LocalSettings.php `$wgPageExchangePackageFiles[] = 'https://raw.githubusercontent.com/NationalGalleryOfArt/heald-packages/main/mediawiki-pages-HealdPlaces/page-exchange.json';`
* Navigate to `Special:Packages` and install the package

