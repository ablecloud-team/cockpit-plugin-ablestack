---
id: Alert
section: components
cssPrefix: pf-c-alert
---## Examples

### Types

```html
<div class="pf-c-alert" aria-label="Default alert">
  <div class="pf-c-alert__icon">
    <i class="fas fa-fw fa-bell" aria-hidden="true"></i>
  </div>
  <p class="pf-c-alert__title">
    <strong>
      <span class="pf-screen-reader">Default alert:</span>Default alert title</strong>
  </p>
</div>
<br />
<div class="pf-c-alert pf-m-info" aria-label="Information alert">
  <div class="pf-c-alert__icon">
    <i class="fas fa-fw fa-info-circle" aria-hidden="true"></i>
  </div>
  <p class="pf-c-alert__title">
    <strong>
      <span class="pf-screen-reader">Info alert:</span>Info alert title</strong>
  </p>
</div>
<br />
<div class="pf-c-alert pf-m-success" aria-label="Success alert">
  <div class="pf-c-alert__icon">
    <i class="fas fa-fw fa-check-circle" aria-hidden="true"></i>
  </div>
  <p class="pf-c-alert__title">
    <strong>
      <span class="pf-screen-reader">Success alert:</span>Success alert title</strong>
  </p>
</div>
<br />
<div class="pf-c-alert pf-m-warning" aria-label="Warning alert">
  <div class="pf-c-alert__icon">
    <i class="fas fa-fw fa-exclamation-triangle" aria-hidden="true"></i>
  </div>
  <p class="pf-c-alert__title">
    <strong>
      <span class="pf-screen-reader">Warning alert:</span>Warning alert title</strong>
  </p>
</div>
<br />
<div class="pf-c-alert pf-m-danger" aria-label="Danger alert">
  <div class="pf-c-alert__icon">
    <i class="fas fa-fw fa-exclamation-circle" aria-hidden="true"></i>
  </div>
  <p class="pf-c-alert__title">
    <strong>
      <span class="pf-screen-reader">Danger alert:</span>Danger alert title</strong>
  </p>
</div>
```

### Variations

```html
<div class="pf-c-alert pf-m-success" aria-label="Success alert">
  <div class="pf-c-alert__icon">
    <i class="fas fa-fw fa-check-circle" aria-hidden="true"></i>
  </div>
  <p class="pf-c-alert__title">
    <strong>
      <span class="pf-screen-reader">Success alert:</span>Success alert title</strong>
  </p>
  <div class="pf-c-alert__action">
    <button class="pf-c-button pf-m-plain" type="button" aria-label="Close success alert: Success alert title">
      <i class="fas fa-times" aria-hidden="true"></i>
    </button>
  </div>
  <div class="pf-c-alert__description">
    <p>Success alert description. This should tell the user more information about the alert.</p>
  </div>
  <div class="pf-c-alert__action-group">
    <button class="pf-c-button pf-m-link pf-m-inline" type="button">View details</button>
    <button class="pf-c-button pf-m-link pf-m-inline" type="button">Ignore</button>
  </div>
</div>
<br />
<div class="pf-c-alert pf-m-success" aria-label="Success alert">
  <div class="pf-c-alert__icon">
    <i class="fas fa-fw fa-check-circle" aria-hidden="true"></i>
  </div>
  <p class="pf-c-alert__title">
    <strong>
      <span class="pf-screen-reader">Success alert:</span>Success alert title</strong>
  </p>
  <div class="pf-c-alert__action">
    <button class="pf-c-button pf-m-plain" type="button" aria-label="Close success alert: Success alert title">
      <i class="fas fa-times" aria-hidden="true"></i>
    </button>
  </div>
  <div class="pf-c-alert__description">
    <p>Success alert description. This should tell the user more information about the alert.
      <a href="#">This is a link.</a>
    </p>
  </div>
</div>
<br />
<div class="pf-c-alert pf-m-success" aria-label="Success alert">
  <div class="pf-c-alert__icon">
    <i class="fas fa-fw fa-check-circle" aria-hidden="true"></i>
  </div>
  <p class="pf-c-alert__title">
    <strong>
      <span class="pf-screen-reader">Success alert:</span>Success alert title</strong>
  </p>
  <div class="pf-c-alert__action">
    <button class="pf-c-button pf-m-plain" type="button" aria-label="Close success alert: Success alert title">
      <i class="fas fa-times" aria-hidden="true"></i>
    </button>
  </div>
  <div class="pf-c-alert__action-group">
    <button class="pf-c-button pf-m-link pf-m-inline" type="button">View details</button>
    <button class="pf-c-button pf-m-link pf-m-inline" type="button">Ignore</button>
  </div>
</div>
<br />
<div class="pf-c-alert pf-m-success" aria-label="Success alert">
  <div class="pf-c-alert__icon">
    <i class="fas fa-fw fa-check-circle" aria-hidden="true"></i>
  </div>
  <p class="pf-c-alert__title">
    <strong>
      <span class="pf-screen-reader">Success alert:</span>Success alert title</strong>
  </p>
  <div class="pf-c-alert__action">
    <button class="pf-c-button pf-m-plain" type="button" aria-label="Close success alert: Success alert title">
      <i class="fas fa-times" aria-hidden="true"></i>
    </button>
  </div>
</div>
<br />
<div class="pf-c-alert pf-m-success" aria-label="Success alert">
  <div class="pf-c-alert__icon">
    <i class="fas fa-fw fa-check-circle" aria-hidden="true"></i>
  </div>
  <p class="pf-c-alert__title">
    <strong>
      <span class="pf-screen-reader">Success alert:</span>Success alert title</strong>
  </p>
</div>
<br />
<div class="pf-c-alert pf-m-success" aria-label="Success alert with title truncation">
  <div class="pf-c-alert__icon">
    <i class="fas fa-fw fa-check-circle" aria-hidden="true"></i>
  </div>
  <p class="pf-c-alert__title pf-m-truncate">
    <strong>
      <span class="pf-screen-reader">Success alert:</span>Lorem ipsum dolor sit amet, consectetur adipiscing elit. Curabitur pellentesque neque cursus enim fringilla tincidunt. Proin lobortis aliquam dictum. Nam vel ullamcorper nulla, nec blandit dolor. Vivamus pellentesque neque justo, nec accumsan nulla rhoncus id. Suspendisse mollis, tortor quis faucibus volutpat, sem leo fringilla turpis, ac lacinia augue metus in nulla. Cras vestibulum lacinia orci. Pellentesque sodales consequat interdum. Sed porttitor tincidunt metus nec iaculis. Pellentesque non commodo justo. Morbi feugiat rhoncus neque, vitae facilisis diam aliquam nec. Sed dapibus vitae quam at tristique. Nunc vel commodo mi. Mauris et rhoncus leo.</strong>
  </p>
  <div class="pf-c-alert__description">
    <p>This example uses ".pf-m-truncate" to limit the title to a single line and truncate any overflow text with ellipses.</p>
  </div>
</div>
<br />
<div class="pf-c-alert pf-m-success" aria-label="Success alert with title truncation at 2 lines">
  <div class="pf-c-alert__icon">
    <i class="fas fa-fw fa-check-circle" aria-hidden="true"></i>
  </div>
  <p class="pf-c-alert__title pf-m-truncate" style="--pf-c-alert__title--max-lines: 2">
    <strong>
      <span class="pf-screen-reader">Success alert:</span>Lorem ipsum dolor sit amet, consectetur adipiscing elit. Curabitur pellentesque neque cursus enim fringilla tincidunt. Proin lobortis aliquam dictum. Nam vel ullamcorper nulla, nec blandit dolor. Vivamus pellentesque neque justo, nec accumsan nulla rhoncus id. Suspendisse mollis, tortor quis faucibus volutpat, sem leo fringilla turpis, ac lacinia augue metus in nulla. Cras vestibulum lacinia orci. Pellentesque sodales consequat interdum. Sed porttitor tincidunt metus nec iaculis. Pellentesque non commodo justo. Morbi feugiat rhoncus neque, vitae facilisis diam aliquam nec. Sed dapibus vitae quam at tristique. Nunc vel commodo mi. Mauris et rhoncus leo.</strong>
  </p>
  <div class="pf-c-alert__description">
    <p>This example uses ".pf-m-truncate" and sets "--pf-c-alert__title--max-lines: 2" to limit title to two lines and truncate any overflow text with ellipses.</p>
  </div>
</div>
```

### Inline types

```html
<div class="pf-c-alert pf-m-inline" aria-label="Inline default alert">
  <div class="pf-c-alert__icon">
    <i class="fas fa-fw fa-bell" aria-hidden="true"></i>
  </div>
  <p class="pf-c-alert__title">
    <strong>
      <span class="pf-screen-reader">Default inline alert:</span>Default inline alert title</strong>
  </p>
</div>
<br />
<div class="pf-c-alert pf-m-info pf-m-inline" aria-label="Inline information alert">
  <div class="pf-c-alert__icon">
    <i class="fas fa-fw fa-info-circle" aria-hidden="true"></i>
  </div>
  <p class="pf-c-alert__title">
    <strong>
      <span class="pf-screen-reader">Info alert:</span>Info inline alert title</strong>
  </p>
</div>
<br />
<div class="pf-c-alert pf-m-success pf-m-inline" aria-label="Inline success alert">
  <div class="pf-c-alert__icon">
    <i class="fas fa-fw fa-check-circle" aria-hidden="true"></i>
  </div>
  <p class="pf-c-alert__title">
    <strong>
      <span class="pf-screen-reader">Success alert:</span>Success inline alert title</strong>
  </p>
</div>
<br />
<div class="pf-c-alert pf-m-warning pf-m-inline" aria-label="Inline warning alert">
  <div class="pf-c-alert__icon">
    <i class="fas fa-fw fa-exclamation-triangle" aria-hidden="true"></i>
  </div>
  <p class="pf-c-alert__title">
    <strong>
      <span class="pf-screen-reader">Warning alert:</span>Warning inline alert title</strong>
  </p>
</div>
<br />
<div class="pf-c-alert pf-m-danger pf-m-inline" aria-label="Inline danger alert">
  <div class="pf-c-alert__icon">
    <i class="fas fa-fw fa-exclamation-circle" aria-hidden="true"></i>
  </div>
  <p class="pf-c-alert__title">
    <strong>
      <span class="pf-screen-reader">Danger alert:</span>Danger inline alert title</strong>
  </p>
</div>
```

### Inline variations

```html
<div class="pf-c-alert pf-m-success pf-m-inline" aria-label="Success alert">
  <div class="pf-c-alert__icon">
    <i class="fas fa-fw fa-check-circle" aria-hidden="true"></i>
  </div>
  <p class="pf-c-alert__title">
    <strong>
      <span class="pf-screen-reader">Success alert:</span>Success alert title</strong>
  </p>
  <div class="pf-c-alert__action">
    <button class="pf-c-button pf-m-plain" type="button" aria-label="Close success alert: Success alert title">
      <i class="fas fa-times" aria-hidden="true"></i>
    </button>
  </div>
  <div class="pf-c-alert__description">
    <p>Success alert description. This should tell the user more information about the alert.</p>
  </div>
  <div class="pf-c-alert__action-group">
    <button class="pf-c-button pf-m-link pf-m-inline" type="button">View details</button>
    <button class="pf-c-button pf-m-link pf-m-inline" type="button">Ignore</button>
  </div>
</div>
<br />
<div class="pf-c-alert pf-m-success pf-m-inline" aria-label="Success alert">
  <div class="pf-c-alert__icon">
    <i class="fas fa-fw fa-check-circle" aria-hidden="true"></i>
  </div>
  <p class="pf-c-alert__title">
    <strong>
      <span class="pf-screen-reader">Success alert:</span>Success alert title</strong>
  </p>
  <div class="pf-c-alert__action">
    <button class="pf-c-button pf-m-plain" type="button" aria-label="Close success alert: Success alert title">
      <i class="fas fa-times" aria-hidden="true"></i>
    </button>
  </div>
  <div class="pf-c-alert__description">
    <p>Success alert description. This should tell the user more information about the alert.
      <a href="#">This is a link.</a>
    </p>
  </div>
</div>
<br />
<div class="pf-c-alert pf-m-success pf-m-inline" aria-label="Success alert">
  <div class="pf-c-alert__icon">
    <i class="fas fa-fw fa-check-circle" aria-hidden="true"></i>
  </div>
  <p class="pf-c-alert__title">
    <strong>
      <span class="pf-screen-reader">Success alert:</span>Success alert title</strong>
  </p>
  <div class="pf-c-alert__action">
    <button class="pf-c-button pf-m-plain" type="button" aria-label="Close success alert: Success alert title">
      <i class="fas fa-times" aria-hidden="true"></i>
    </button>
  </div>
  <div class="pf-c-alert__action-group">
    <button class="pf-c-button pf-m-link pf-m-inline" type="button">View details</button>
    <button class="pf-c-button pf-m-link pf-m-inline" type="button">Ignore</button>
  </div>
</div>
<br />
<div class="pf-c-alert pf-m-success pf-m-inline" aria-label="Success alert">
  <div class="pf-c-alert__icon">
    <i class="fas fa-fw fa-check-circle" aria-hidden="true"></i>
  </div>
  <p class="pf-c-alert__title">
    <strong>
      <span class="pf-screen-reader">Success alert:</span>Success alert title</strong>
  </p>
</div>
```

### Custom icon

```html
<div class="pf-c-alert pf-m-success" aria-label="Success alert">
  <div class="pf-c-alert__icon">
    <i class="fas fa-fw fa-cog" aria-hidden="true"></i>
  </div>
  <p class="pf-c-alert__title">
    <strong>
      <span class="pf-screen-reader">Success alert:</span>Success alert title</strong>
  </p>
</div>
<br />
<div class="pf-c-alert pf-m-success pf-m-inline" aria-label="Success alert">
  <div class="pf-c-alert__icon">
    <i class="fas fa-fw fa-cog" aria-hidden="true"></i>
  </div>
  <p class="pf-c-alert__title">
    <strong>
      <span class="pf-screen-reader">Success alert:</span>Success alert title</strong>
  </p>
</div>
```

## Documentation

### Overview

Add a modifier class to the default alert to change the color: `.pf-m-success`, `.pf-m-danger`, `.pf-m-warning`, or `.pf-m-info`.

### Accessibility

| Attribute                                               | Applied to                | Outcome                                                                                                                                 |
| ------------------------------------------------------- | ------------------------- | --------------------------------------------------------------------------------------------------------------------------------------- |
| `aria-label="Default alert"`                            | `.pf-c-alert`             | Indicates the default alert.                                                                                                            |
| `aria-label="Success alert"`                            | `.pf-c-alert`             | Indicates the success alert.                                                                                                            |
| `aria-label="Danger alert"`                             | `.pf-c-alert`             | Indicates the danger alert.                                                                                                             |
| `aria-label="Warning alert"`                            | `.pf-c-alert`             | Indicates the warning alert.                                                                                                            |
| `aria-label="Information alert"`                        | `.pf-c-alert`             | Indicates the information alert.                                                                                                        |
| `aria-label="Close success alert: Success alert title"` | `.pf-c-button.pf-m-plain` | Indicates the close button. Please provide descriptive text to ensure assistive technologies clearly state which alert is being closed. |
| `aria-hidden="true"`                                    | `.pf-c-alert__icon <i>`   | Hides icon for assistive technologies. ** Required **                                                                                   |

| Class               | Applied to                  | Outcome                                                                                                                       |
| ------------------- | --------------------------- | ----------------------------------------------------------------------------------------------------------------------------- |
| `.pf-screen-reader` | `.pf-c-alert__title <span>` | Content that is visually hidden but accessible to assistive technologies. This should state the type of alert.  ** Required** |

### Usage

| Class                       | Applied to           | Outcome                                                                                                                                                                                                                         |
| --------------------------- | -------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| `.pf-c-alert`               | `<div>`              | Applies default alert styling. Always use with a modifier class. ** Required**                                                                                                                                                  |
| `.pf-c-alert__icon`         | `<div>`              | Defines the alert icon. ** Required **                                                                                                                                                                                          |
| `.pf-c-alert__title`        | `<p>, <h1-h6>`       | Defines the alert title. ** Required **                                                                                                                                                                                         |
| `.pf-c-alert__description`  | `<div>`              | Defines the alert description area.                                                                                                                                                                                             |
| `.pf-c-alert__action`       | `<div>`              | Defines the action button wrapper. Should contain `.pf-c-button.pf-m-plain` for close action or `.pf-c-button.pf-m-link` for link text. It should only include one action.                                                      |
| `.pf-c-alert__action-group` | `<div>`              | Defines the action button group. Should contain `.pf-c-button.pf-m-link.pf-m-inline` for inline link text. **Note: ** only inline link buttons are supported in the alert action group.                                         |
| `.pf-m-success`             | `.pf-c-alert`        | Applies success styling.                                                                                                                                                                                                        |
| `.pf-m-danger`              | `.pf-c-alert`        | Applies danger styling.                                                                                                                                                                                                         |
| `.pf-m-warning`             | `.pf-c-alert`        | Applies warning styling.                                                                                                                                                                                                        |
| `.pf-m-info`                | `.pf-c-alert`        | Applies info styling.                                                                                                                                                                                                           |
| `.pf-m-inline`              | `.pf-c-alert`        | Applies inline styling.                                                                                                                                                                                                         |
| `.pf-m-truncate`            | `.pf-c-alert__title` | Modifies the title to display a single line and truncate any overflow text with ellipses. **Note:** you can specify the max number of lines to show by setting the `--pf-c-alert__title--max-lines` (the default value is `1`). |
