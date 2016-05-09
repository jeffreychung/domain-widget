domain-widget
=============

Widget for selling GoDaddy reseller domain

If you have your own storefront pages for the GoDaddy reseller product, this form allows you to search for domains.

Simply change the `prog_id` and the `action` location on the form and you are ready to rock!

## Example

To see a live example, visit http://resellers.github.io/domain-widget/

## Getting Started

1. Embed the example into your page
2.
```html
<!-- domain-widget being here -->
<form class="form-inline" action="https://www.secureserver.net/domains/search.aspx?checkAvail=1&amp;prog_id={YOUR_PROG_ID}" method="post">
  <div class="form-group domain-search">
    <input type="text" class="form-control" placeholder="Search for a new domain" name="domainToCheck" >
  </div>
  <button type="submit" class="btn btn-default"><span class="glyphicon glyphicon-search"></span> Search</button>
</form>
<!-- domain-widget end here -->
```
3. Change '{YOUR_PROG_ID}'  (replace the entire value included the `{}`)

### Note
If you are using bootstrap you will want to add the following css:
```css
.form-inline .domain-search input {
    width:540px;
}
```

