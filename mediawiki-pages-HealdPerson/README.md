# HEALD Person

Provides a collection of wiki pages for easy inclusion of Person fields and semantics in Mediawiki projects (HEALD wiki).

# Requirements

* MediaWiki 1.30+
* SemanticMediaWiki
* PageForms
* PagePort or PageExchange
* mediawiki-pages-ExternalLink
* mediawiki-pages-Dates
* mediawiki-pages-AllowedValues

# Setup

## via PagePort 

* download the repository
* run `php extensions/PagePort/maintenance/importPages.php --source ~/mediawiki-pages-HealdPerson`

## via PageExchange

* Add the following line to your LocalSettings.php `$wgPageExchangePackageFiles[] = 'https://raw.githubusercontent.com/NationalGalleryOfArt/heald-packages/main/mediawiki-pages-HealdPerson/page-exchange.json';`
* Navigate to `Special:Packages` and install the package
