domain-widget
=============

Widget for selling GoDaddy reseller domain

If you have your own storefront pages for the GoDaddy reseller product, this form allows you to search for domains.

Simply change the `prog_id` and the `action` location on the form and you are ready to rock!

## Example

To see a live example, visit http://resellers.github.io/domain-widget/

## Getting Started

1. Embed the example from `index.html` into your page
2. Change the form's action to point to your reseller storefront (www.secureserver.net or yourcustomdomain.com - the Custom Domain feature can be enabled here: https://reseller.secureserver.net/Settings/CustomDomainSettings.aspx or https://reseller.godaddy.com/Settings/CustomDomainSettings.aspx))
```html
<form action="http://www.secureserver.net/domains/search.aspx?checkAvail=1&amp;prog_id=domainspricedright" method="post">
```
3. Change your 'prog_id' - (found on https://reseller.secureserver.net/Settings/default.aspx or https://reseller.godaddy.com/Settings/default.aspx  )
```html
<form action="http://www.secureserver.net/domains/search.aspx?checkAvail=1&amp;prog_id=domainspricedright" method="post">
```
4. Add the appropriate domain extensions you'd like to offer
