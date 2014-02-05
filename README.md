product_catalog2
================

First version of product catalog posted.  

<< ASSUMPTIONS  >>

1 - local storage - keys are always stored in ascending order
2 - local storage - only ID: Product (stringified JSON are saved in the DB).  
          If we want to store other vars in local Storage, we'd just need to fix the addProduct function

<< REFERENCES  >>

api/overview - http://backbonejs.org/
model/collection/view overviews - http://backbonetutorials.com/
general questions - stackoverflow
router example - http://aaronhardy.com/javascript/javascript-architecture-backbone-js-routers/
design ideas - codepen.io
file structure - https://github.com/VIISON/BackboneSwitchView
jquery reference - http://api.jquery.com/
underscore reference - http://underscorejs.org/


<< BUGS/IMMEDIATE TASKS >>

- BUG - various errors in firefox..
  - Use of attributes' nodeValue attribute is deprecated. Use value instead. product_catalog
  - 21:04:30.088 ReferenceError: event is not defined
- properly breakout index.html into templates, models, views, collections


<< FUTURE IMPROVEMENTS  >>

- form validation
- templatize the markup (mustache?)
- SASS'ify CSS
- refactor load/removal of forms (instead of display: none)
- user views - 'product admin' vs 'customer' for orders
- Hook up router and Restfull server
- update to current versions of backbone/underscore lib files (fix issues)
