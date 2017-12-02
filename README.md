Accessible Tabs
================

Keyboard / screen reader accessible tabs written in jQuery plug-in.


## Minimum Mark-up Required

To help facilitate the simplest integration with your CMS or code base, the required markup is as lean as possible, while maintaining a logical structure for instances where JavaScript may be disabled or unavailable.

The classes sans the 'js-' prefix can be renamed as you see fit, though the styling applied to them is also pretty minimal to allow for easier out of the box customization.

```html
<div class="tab-container"
     data-action="a11y-tabs"
     id="unique_id">

  <section class="tab-panel js-tabs__panel" data-tab-label="First Tab">
    <h2>Heading of Panel 1</h2>
    ...
  </section>
  <!--
    The above panel will have a tab generated with the
    text from the [data-tab-label] attribute
  -->

  <section class="tab-panel js-tabs__panel">
    <h#>Heading of Panel 2</h#>
    ...
  </section>
  <!--
    The above panel will have a tab generated with the
    text from the <h#>
  -->

  <section class="tab-panel js-tabs__panel">
    ...
  </section>
  <!--
    The above panel has neither a [data-tab-label] nor a
    <h#>, so the generated tab will have the text of "Tab 3"
    as this is the third panel.
  -->

</div> <!-- /.tab-container -->
```


### License & Such

This script was written by [Scott O'Hara](https://twitter.com/scottohara).

It has an [MIT](https://github.com/scottaohara/accessible-components/blob/master/LICENSE.md) license.

Do with it what you will :)
