domain-widget
=============

Widget for selling GoDaddy reseller domain

If you have your own storefront pages for the GoDaddy reseller product, this form allows you to search for domains.

Simply change the `prog_id` and `url` in the form and you are ready to rock!

## Example

To see a live example, visit http://resellers.github.io/domain-widget/

## Getting Started

1. Embed the example from `index.html` into your page
2. Add the appropriate domain extensions you'd like to offer
3. Change your 'prog_id' - (found on https://www.resellercontrolcenter.com/Settings/default.aspx)
```html
<form action="http://www.secureserver.net/domains/search.aspx?checkAvail=1&amp;prog_id=domainspricedright" method="post"><!-- enter your prog_id and domain -->
```
4. Change all hard coded links to point to your reseller storefront (www.secureserver.net or yourcustomdomain.com)
```html
<form action="http://www.secureserver.net/domains/search.aspx?checkAvail=1&amp;prog_id=domainspricedright" method="post"><!-- enter your prog_id and domain -->
```
