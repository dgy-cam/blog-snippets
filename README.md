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
        <div id="build-form" data-list="H4fSnY" data-segment-name="KAL"></div>
    </div>
</div>
```
Variable | Note
-- | --
H4fSnY | The List ID for "Darn Yarn Newsletter"
KAL | The Klaviyo Property used to identify users who signed up using this particular form. This allows segmentation within Klaviyo. This can change as needed.
