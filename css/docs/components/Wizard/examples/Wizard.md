---
id: Wizard
section: components
cssPrefix: pf-c-wizard
wrapperTag: div
---import './Wizard.css'

## Examples

### Basic

```html isFullscreen
<div class="pf-c-wizard">
  <div class="pf-c-wizard__header">
    <button class="pf-c-button pf-m-plain pf-c-wizard__close" type="button" aria-label="Close">
      <i class="fas fa-times" aria-hidden="true"></i>
    </button>
    <h1 class="pf-c-title pf-m-3xl pf-c-wizard__title">Wizard title</h1>
    <p class="pf-c-wizard__description">Here is where the description goes</p>
  </div>
  <button aria-label="Wizard Header Toggle" class="pf-c-wizard__toggle" aria-expanded="false">
    <ol class="pf-c-wizard__toggle-list">
      <li class="pf-c-wizard__toggle-list-item">
        <span class="pf-c-wizard__toggle-num">2</span>Configuration
        <i class="fas fa-angle-right pf-c-wizard__toggle-separator" aria-hidden="true"></i>
      </li>
      <li class="pf-c-wizard__toggle-list-item">Substep B</li>
    </ol>
    <span class="pf-c-wizard__toggle-icon">
      <i class="fas fa-caret-down" aria-hidden="true"></i>
    </span>
  </button>
  <div class="pf-c-wizard__outer-wrap">
    <div class="pf-c-wizard__inner-wrap">
      <nav class="pf-c-wizard__nav" aria-label="Steps">
        <ol class="pf-c-wizard__nav-list">
          <li class="pf-c-wizard__nav-item">
            <button class="pf-c-wizard__nav-link">Information</button>
          </li>
          <li class="pf-c-wizard__nav-item">
            <button class="pf-c-wizard__nav-link pf-m-current">Configuration</button>
            <ol class="pf-c-wizard__nav-list">
              <li class="pf-c-wizard__nav-item">
                <button class="pf-c-wizard__nav-link">Substep A</button>
              </li>
              <li class="pf-c-wizard__nav-item">
                <button class="pf-c-wizard__nav-link pf-m-current" aria-current="page">Substep B</button>
              </li>
              <li class="pf-c-wizard__nav-item">
                <button class="pf-c-wizard__nav-link">Substep C</button>
              </li>
            </ol>
          </li>
          <li class="pf-c-wizard__nav-item">
            <button class="pf-c-wizard__nav-link">Additional</button>
          </li>
          <li class="pf-c-wizard__nav-item">
            <button class="pf-c-wizard__nav-link" disabled>Review</button>
          </li>
        </ol>
      </nav>
      <main class="pf-c-wizard__main">
        <div class="pf-c-wizard__main-body">
          <p>Wizard content goes here</p>
        </div>
      </main>
    </div>
    <footer class="pf-c-wizard__footer">
      <button class="pf-c-button pf-m-primary" type="submit">Next</button>
      <button class="pf-c-button pf-m-secondary" type="button">Back</button>
      <div class="pf-c-wizard__footer-cancel">
        <button class="pf-c-button pf-m-link" type="button">Cancel</button>
      </div>
    </footer>
  </div>
</div>
```

### Nav expanded (mobile)

```html isFullscreen
<div class="pf-c-wizard">
  <div class="pf-c-wizard__header">
    <button class="pf-c-button pf-m-plain pf-c-wizard__close" type="button" aria-label="Close">
      <i class="fas fa-times" aria-hidden="true"></i>
    </button>
    <h1 class="pf-c-title pf-m-3xl pf-c-wizard__title">Wizard title</h1>
    <p class="pf-c-wizard__description">Here is where the description goes</p>
  </div>
  <button aria-label="Wizard Header Toggle" class="pf-c-wizard__toggle pf-m-expanded" aria-expanded="true">
    <ol class="pf-c-wizard__toggle-list">
      <li class="pf-c-wizard__toggle-list-item">
        <span class="pf-c-wizard__toggle-num">2</span>Configuration
        <i class="fas fa-angle-right pf-c-wizard__toggle-separator" aria-hidden="true"></i>
      </li>
      <li class="pf-c-wizard__toggle-list-item">Substep B</li>
    </ol>
    <span class="pf-c-wizard__toggle-icon">
      <i class="fas fa-caret-down" aria-hidden="true"></i>
    </span>
  </button>
  <div class="pf-c-wizard__outer-wrap">
    <div class="pf-c-wizard__inner-wrap">
      <nav class="pf-c-wizard__nav pf-m-expanded" aria-label="Steps">
        <ol class="pf-c-wizard__nav-list">
          <li class="pf-c-wizard__nav-item">
            <button class="pf-c-wizard__nav-link">Information</button>
          </li>
          <li class="pf-c-wizard__nav-item">
            <button class="pf-c-wizard__nav-link pf-m-current">Configuration</button>
            <ol class="pf-c-wizard__nav-list">
              <li class="pf-c-wizard__nav-item">
                <button class="pf-c-wizard__nav-link">Substep A</button>
              </li>
              <li class="pf-c-wizard__nav-item">
                <button class="pf-c-wizard__nav-link pf-m-current" aria-current="page">Substep B</button>
              </li>
              <li class="pf-c-wizard__nav-item">
                <button class="pf-c-wizard__nav-link">Substep C</button>
              </li>
            </ol>
          </li>
          <li class="pf-c-wizard__nav-item">
            <button class="pf-c-wizard__nav-link">Additional</button>
          </li>
          <li class="pf-c-wizard__nav-item">
            <button class="pf-c-wizard__nav-link" disabled>Review</button>
          </li>
        </ol>
      </nav>
      <main class="pf-c-wizard__main">
        <div class="pf-c-wizard__main-body">
          <p>Wizard content goes here</p>
        </div>
      </main>
    </div>
    <footer class="pf-c-wizard__footer">
      <button class="pf-c-button pf-m-primary" type="submit">Next</button>
      <button class="pf-c-button pf-m-secondary" type="button">Back</button>
      <div class="pf-c-wizard__footer-cancel">
        <button class="pf-c-button pf-m-link" type="button">Cancel</button>
      </div>
    </footer>
  </div>
</div>
```

### Finished

```html isFullscreen
<div class="pf-c-wizard pf-m-finished">
  <div class="pf-c-wizard__header">
    <button class="pf-c-button pf-m-plain pf-c-wizard__close" type="button" aria-label="Close">
      <i class="fas fa-times" aria-hidden="true"></i>
    </button>
    <h1 class="pf-c-title pf-m-3xl pf-c-wizard__title">Wizard title</h1>
    <p class="pf-c-wizard__description">Here is where the description goes</p>
  </div>
  <button aria-label="Wizard Header Toggle" class="pf-c-wizard__toggle" aria-expanded="false">
    <ol class="pf-c-wizard__toggle-list">
      <li class="pf-c-wizard__toggle-list-item">
        <span class="pf-c-wizard__toggle-num">2</span>Configuration
        <i class="fas fa-angle-right pf-c-wizard__toggle-separator" aria-hidden="true"></i>
      </li>
      <li class="pf-c-wizard__toggle-list-item">Substep B</li>
    </ol>
    <span class="pf-c-wizard__toggle-icon">
      <i class="fas fa-caret-down" aria-hidden="true"></i>
    </span>
  </button>
  <div class="pf-c-wizard__outer-wrap">
    <div class="pf-c-wizard__inner-wrap">
      <nav class="pf-c-wizard__nav" aria-label="Steps">
        <ol class="pf-c-wizard__nav-list">
          <li class="pf-c-wizard__nav-item">
            <button class="pf-c-wizard__nav-link">Information</button>
          </li>
          <li class="pf-c-wizard__nav-item">
            <button class="pf-c-wizard__nav-link">Configuration</button>
            <ol class="pf-c-wizard__nav-list">
              <li class="pf-c-wizard__nav-item">
                <button class="pf-c-wizard__nav-link">Substep A</button>
              </li>
              <li class="pf-c-wizard__nav-item">
                <button class="pf-c-wizard__nav-link">Substep B</button>
              </li>
              <li class="pf-c-wizard__nav-item">
                <button class="pf-c-wizard__nav-link">Substep C</button>
              </li>
            </ol>
          </li>
          <li class="pf-c-wizard__nav-item">
            <button class="pf-c-wizard__nav-link">Additional</button>
          </li>
          <li class="pf-c-wizard__nav-item">
            <button class="pf-c-wizard__nav-link">Review</button>
          </li>
        </ol>
      </nav>
      <main class="pf-c-wizard__main">
        <div class="pf-c-wizard__main-body">
          <div class="pf-l-bullseye">
            <div class="pf-c-empty-state pf-m-lg">
              <div class="pf-c-empty-state__content">
                <i class="fas fa- fa-cogs pf-c-empty-state__icon" aria-hidden="true"></i>
                <h1 class="pf-c-title pf-m-lg">Configuration in progress</h1>
                <div class="pf-c-empty-state__body">
                  <div class="pf-c-progress pf-m-singleline" id="progress-singleline-example">
                    <div class="pf-c-progress__description" id="progress-singleline-example-description"></div>
                    <div class="pf-c-progress__status" aria-hidden="true">
                      <span class="pf-c-progress__measure">33%</span>
                    </div>
                    <div class="pf-c-progress__bar" role="progressbar" aria-valuemin="0" aria-valuemax="100" aria-valuenow="33" aria-describedby="progress-singleline-example-description">
                      <div class="pf-c-progress__indicator" style="width:33%;"></div>
                    </div>
                  </div>
                </div>
                <div class="pf-c-empty-state__body">Lorem ipsum dolor sit amet, consectetur adipiscing elit. Donec non pulvinar tortor. Maecenas sit amet pellentesque velit, eu eleifend mauris.</div>
                <div class="pf-c-empty-state__secondary">
                  <button class="pf-c-button pf-m-link" type="button">Cancel</button>
                </div>
              </div>
            </div>
          </div>
        </div>
      </main>
    </div>
    <footer class="pf-c-wizard__footer">
      <button class="pf-c-button pf-m-primary" type="submit">Next</button>
      <button class="pf-c-button pf-m-secondary" type="button">Back</button>
      <div class="pf-c-wizard__footer-cancel">
        <button class="pf-c-button pf-m-link" type="button">Cancel</button>
      </div>
    </footer>
  </div>
</div>
```

## Documentation

### Accessibility

| Attribute               | Applied to                                                  | Outcome                                                                                         |
| ----------------------- | ----------------------------------------------------------- | ----------------------------------------------------------------------------------------------- |
| `aria-expanded="true"`  | `.pf-c-wizard__toggle`                                      | Indicates that the steps menu is visible. **Required**                                          |
| `aria-expanded="false"` | `.pf-c-wizard__toggle`                                      | Indicates that the steps menu is hidden. **Required**                                           |
| `aria-label="close"`    | `.pf-c-wizard__toggle-icon`                                 | Gives the close button an accessible name. **Required**                                         |
| `aria-hidden="true"`    | `.pf-c-wizard__toggle-icon`, `.pf-c-wizard__toggle-divider` | Hides the icon from assistive technologies. **Required**                                        |
| `aria-label="Steps"`    | `.pf-c-wizard__nav`                                         | Gives the steps nav element an accessible name. **Required**                                    |
| `disabled`              | `button.pf-c-wizard__nav-link`                              | Indicates that the element is disabled. **Required when a nav item is disabled**                |
| `aria-disabled="true"`  | `a.pf-c-wizard__nav-link`                                   | Indicates that the element is disabled. **Required for disabled links with `.pf-m-disabled`**   |
| `aria-current="page"`   | `.pf-c-wizard__nav-link`                                    | Indicates the current page link. Can only occur once on page. **Required for the current link** |
| `tabindex="-1"`         | `a.pf-c-wizard__nav-link`                                   | Removes a link from keyboard focus. **Required for disabled links with `.pf-m-disabled`**       |

### Usage

| Class                            | Applied to                                  | Outcome                                                                                                                               |
| -------------------------------- | ------------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------- |
| `.pf-c-wizard`                   | `<div>`                                     | Initiates the wizard component. **Required**                                                                                          |
| `.pf-c-wizard__header`           | `<header>`                                  | Initiates the header. **Required** when the wizard is in a modal. Not recommended to use when the wizard is placed on a page.         |
| `.pf-c-wizard__close`            | `.pf-c-button.pf-m-plain`                   | Initiates the close button. **Required**                                                                                              |
| `.pf-c-wizard__title`            | `.pf-c-title.pf-m-3xl`                      | Initiates the title. **Required**                                                                                                     |
| `.pf-c-wizard__description`      | `<p>`                                       | Initiates the description.                                                                                                            |
| `.pf-c-wizard__toggle`           | `<button>`                                  | Initiates the mobile steps menu toggle button. **Required**                                                                           |
| `.pf-c-wizard__toggle-list`      | `<ol>`                                      | Initiates the toggle list. **Required**                                                                                               |
| `.pf-c-wizard__toggle-list-item` | `<li>`                                      | Initiates a toggle list item. **Required**                                                                                            |
| `.pf-c-wizard__toggle-num`       | `<span>`                                    | Initiates the step number. **Required**                                                                                               |
| `.pf-c-wizard__toggle-separator` | `<i>`                                       | Initiates the separator between steps.                                                                                                |
| `.pf-c-wizard__toggle-icon`      | `<span>`                                    | Initiates the toggle icon wrapper. **Required**                                                                                       |
| `.pf-c-wizard__outer-wrap`       | `<div>`                                     | Initiates the outer wrapper. **Required**                                                                                             |
| `.pf-c-wizard__inner-wrap`       | `<div>`                                     | Initiates the inner wrapper. **Required**                                                                                             |
| `.pf-c-wizard__nav`              | `<nav>`                                     | Initiates the steps nav. **Required**                                                                                                 |
| `.pf-c-wizard__nav-list`         | `<ol>`                                      | Initiates a list of steps. **Required**                                                                                               |
| `.pf-c-wizard__nav-item`         | `<li>`                                      | Initiates a step list item. **Required**                                                                                              |
| `.pf-c-wizard__nav-link`         | `<a>`                                       | Initiates a step link. **Required**                                                                                                   |
| `.pf-c-wizard__main`             | `<main>`, `<div>`                           | Initiates the main container. **Required** Note: use the `<main>` element when when there are no other `<main>` elements on the page. |
| `.pf-c-wizard__main-body`        | `<div>`                                     | Initiates the main container body section. **Required**                                                                               |
| `.pf-c-wizard__footer`           | `<footer>`                                  | Initiates the footer. **Required**                                                                                                    |
| `.pf-c-wizard__footer-cancel`    | `<div>`                                     | Initiates the cancel button. **Required**                                                                                             |
| `.pf-m-expanded`                 | `.pf-c-wizard__toggle`, `.pf-c-wizard__nav` | Modifies the mobile steps toggle and steps menu for the expanded state.                                                               |
| `.pf-m-finished`                 | `.pf-c-wizard`                              | Modifies the wizard for the finished state.                                                                                           |
| `.pf-m-current`                  | `.pf-c-wizard__nav-link`                    | Modifies a step link for the current state. **Required**                                                                              |
| `.pf-m-disabled`                 | `.pf-c-wizard__nav-link`                    | Modifies a step link for the disabled state.                                                                                          |
| `.pf-m-no-padding`               | `.pf-c-wizard__main-body`                   | Modifies the main container body to remove the padding.                                                                               |
