product_catalog2
================

First version of product catalog posted.  

Current fixes needed...
- BUG - local storage length doesn't account for deleted products  (need to sync local storage and collection IDs)
- BUG - Uncaught TypeError: Object #<Object> has no method 'setElement'  - not sure where this is coming from
- properly breakout index.html into templates, models, views, collections
- log success/failure when adding/updating models

Future fixes...
- form validation
- templatize the markup (mustache?)
- SASS'ify CSS
- refactor load/removal of forms (instead of display: none)
- user views - 'product admin' vs 'customer' for orders
- Hook up router and Restfull server
- update to current versions of backbone/underscore lib files (fix issues)
