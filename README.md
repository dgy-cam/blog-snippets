# DGY Blog Snippets

## Shadowbox

### Example 1 - [Shadow] - [Buttons]
```html
<div class="callout">
    <div class="callout_inner">
        <a title="" href="" target="_blank" rel="noopener noreferrer">
            [button_text]
            <i class="icon-cart"></i>
        </a>
        <a title="" href="" target="_blank" rel="noopener noreferrer">
            [button_text]
            <i class="icon-cart"></i>
        </a>
    </div>
</div>
```
### Example 2 - [No Shadow] - [Form Embed]
```html
<div class="callout noshadow">
    <div class="callout_inner">
        <div class="build-form" data-list="H4fSnY" data-segment-name="KAL"></div>
    </div>
</div>
```
<table>
    <tr>
        <th>Variable</th>
        <th>Note</th>
    </tr>
    <tr>
        <td>H4fSnY</td>
        <td>The List ID for "Darn Yarn Newsletter"</td>
    </tr>
    <tr>
        <td>KAL</td>
        <td>The Klaviyo Property used to identify users who signed up using this particular form. This allows segmentation within Klaviyo. This can change as needed.</td>
    </tr>
</table>


## Product Promos (Use only if trained)
### Single Layout
```html
<div class="build-product" data-products="[['mystery-yarn-grab-bag',31220922482801,2]]" data-title="BOGO" data-layout="single"></div>
```
### Multi Product "Bundle" Layout
```html
<div class="build-product" data-title="Perfect Yarn Lovers Bundle" data-button="Add this bundle to cart" data-products="[['mystery-yarn-grab-bag',31220922482801,2],['peek-a-boo-lace-weight-silk-yarn',29417795354737,2],['5-pack-amigurumi-kits',4001905541233,1]]" data-layout="bundle"></div>
```
