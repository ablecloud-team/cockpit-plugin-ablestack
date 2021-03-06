---
id: Tab content
section: components
cssPrefix: pf-c-tab-content
---## Examples

### Basic

```html
<section class="pf-c-tab-content" id="tab1-panel" role="tabpanel" tabindex="0">Panel 1</section>
<section class="pf-c-tab-content" id="tab2-panel" role="tabpanel" tabindex="0" hidden>Panel 2</section>
<section class="pf-c-tab-content" id="tab3-panel" role="tabpanel" tabindex="0" hidden>Panel 3</section>
<section class="pf-c-tab-content" id="tab4-panel" role="tabpanel" tabindex="0" hidden>Panel 4</section>
```

### Light 300 background

```html
<section class="pf-c-tab-content pf-m-light-300" id="light-300-tab1-panel" role="tabpanel" tabindex="0">Panel 1</section>
<section class="pf-c-tab-content pf-m-light-300" id="tab2-panel" role="tabpanel" tabindex="0" hidden>Panel 2</section>
<section class="pf-c-tab-content pf-m-light-300" id="tab3-panel" role="tabpanel" tabindex="0" hidden>Panel 3</section>
<section class="pf-c-tab-content pf-m-light-300" id="tab4-panel" role="tabpanel" tabindex="0" hidden>Panel 4</section>
```

## Documentation

### Overview

Tab content should be used with the [tabs component](/documentation/core/components/tabs).

### Accessibility

| Attribute                             | Applied to          | Outcome                                                                                                                                        |
| ------------------------------------- | ------------------- | ---------------------------------------------------------------------------------------------------------------------------------------------- |
| `role="tabpanel"`                     | `.pf-c-tab-content` | Indicates that the element serves as a container for a set of tabs. **Required**                                                               |
| `aria-labelledby=[ID of tab element]` | `.pf-c-tab-content` | Provides an accessible name for the tab panel by referring to the tab element that controls it. **Required**                                   |
| `id=[ID of tab panel]`                | `.pf-c-tab-content` | Provides an ID for the tab panel, and should be used as the value of `aria-controls` on the tab element that controls the panel.  **Required** |
| `hidden`                              | `.pf-c-tab-content` | Indicates that the tab panel is not visible. **Required on all but the active tab panel**                                                      |
| `tabindex="0"`                        | `.pf-c-tab-content` | Puts the tab panel in the page tab sequence and facilitates movement to panel content for assistive technology users. **Required**             |

### Usage

| Class               | Applied to          | Outcome                                              |
| ------------------- | ------------------- | ---------------------------------------------------- |
| `.pf-c-tab-content` | `<section>`         | Initiates the tab content component. **Required**    |
| `.pf-m-light-300`   | `.pf-c-tab-content` | Modifies the tab content component background color. |
