---
ee_only: true
title: Live Search Quick Tour
tag: live-search
group: marketing
---

With a focus on speed, relevance, and ease of use, Live Search is a game changer for shoppers and merchants alike. Follow along for a quick tour of Live Search from the storefront.

### Search as you type

Live Search responds with suggested products and a thumbnail image of top search results in a popover as shoppers type queries into the [Search]({% link catalog/search-quick.md %}) box. Shoppers can go immediately to the [product detail]({% link quick-tour/product-page.md %}) page by clicking a suggested or featured product.  A _View all_ link in the footer of the popover displays the search results page.

The popover can return "search as you type" results for one character or more. To set the minimum number of characters required for a query, change the Catalog Search [Minimal Query Length](https://docs.magento.com/user-guide/catalog/search-configuration.html) configuration setting.

To customize the popover, refer to [Storefront Popover](https://devdocs.magento.com/live-search/storefront-popover.html) in the Live Search developer documentation.

![Example storefront - search as you type]({% link live-search/assets/storefront-search-as-you-type.png %}){: .zoom}
_Search as you type_

### Infinite scroll

When shoppers click _View all_ from the "search as you type" popover, additional products appear in the search results as they scroll down the page. There is no need to navigate through pages of static search results. The current query appears in the search box just above the results. Shoppers can simply change the current query to instantly update the results.

![Example storefront - view all]({% link live-search/assets/storefront-view-all.png %}){: .zoom}
_View all_

### Filtered search with facets

The Filters list in the left sidebar shows the available values derived from the current set of returned products. Filtered search uses multiple dimensions of attribute values, or [facets]({% link live-search/facets.md %}), as search criteria. The selection of filters is defined by the merchant and changes according to the products returned, with the most commonly-used facets pinned to the top of the list.

![Example storefront - price facets]({% link live-search/assets/storefront-filters.png %}){: .zoom}
_Filtered search_

### Synonyms

[Synonyms]({% link live-search/synonyms.md %}) expand the reach and sharpen the focus of queries by including words shoppers might use that differ from those in the catalog. You can fine tune the synonym dictionary to keep shoppers engaged and on the path to purchase.

### Merchandising rules

Merchandising [rules]({% link live-search/rules.md %}) shape the shopping experience with if-then statements that add logic and events to search. You can easily boost or bury products for a promotion, season, or other period of time.
