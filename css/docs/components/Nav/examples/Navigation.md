---
id: Navigation
section: components
cssPrefix: pf-c-nav
---import './Navigation.css'

## Examples

### Default

```html
<nav class="pf-c-nav" aria-label="Global">
  <ul class="pf-c-nav__list">
    <li class="pf-c-nav__item">
      <a href="#" class="pf-c-nav__link">Link 1</a>
    </li>
    <li class="pf-c-nav__item">
      <a href="#" class="pf-c-nav__link pf-m-current" aria-current="page">Current link</a>
    </li>
    <li class="pf-c-nav__item">
      <a href="#" class="pf-c-nav__link">Link 3</a>
    </li>
    <li class="pf-c-nav__item">
      <a href="#" class="pf-c-nav__link">Link 4</a>
    </li>
  </ul>
</nav>
```

### Grouped nav

```html
<nav class="pf-c-nav" aria-label="Global">
  <section class="pf-c-nav__section" aria-labelledby="grouped-title1">
    <h2 class="pf-c-nav__section-title" id="grouped-title1">Section title 1</h2>
    <ul class="pf-c-nav__list">
      <li class="pf-c-nav__item">
        <a href="#" class="pf-c-nav__link">Link 1</a>
      </li>
      <li class="pf-c-nav__item">
        <a href="#" class="pf-c-nav__link">Link 2</a>
      </li>
      <li class="pf-c-nav__item">
        <a href="#" class="pf-c-nav__link">Link 3</a>
      </li>
    </ul>
  </section>
  <section class="pf-c-nav__section" aria-labelledby="grouped-title2">
    <h2 class="pf-c-nav__section-title" id="grouped-title2">Section title 2</h2>
    <ul class="pf-c-nav__list">
      <li class="pf-c-nav__item">
        <a href="#" class="pf-c-nav__link">Link 1</a>
      </li>
      <li class="pf-c-nav__item">
        <a href="#" class="pf-c-nav__link pf-m-current" aria-current="page">Current link</a>
      </li>
      <li class="pf-c-nav__item">
        <a href="#" class="pf-c-nav__link">Link 3</a>
      </li>
    </ul>
  </section>
</nav>
```

### Expanded

```html
<nav class="pf-c-nav" aria-label="Global">
  <ul class="pf-c-nav__list">
    <li class="pf-c-nav__item pf-m-expandable pf-m-expanded pf-m-current">
      <button class="pf-c-nav__link" id="expandable-example1" aria-expanded="true">Link 1 (current and expanded example)
        <span class="pf-c-nav__toggle">
          <span class="pf-c-nav__toggle-icon">
            <i class="fas fa-angle-right" aria-hidden="true"></i>
          </span>
        </span>
      </button>
      <section class="pf-c-nav__subnav" aria-labelledby="expandable-example1">
        <ul class="pf-c-nav__list">
          <li class="pf-c-nav__item">
            <a href="#" class="pf-c-nav__link">Current link</a>
          </li>
          <li class="pf-c-divider" role="separator"></li>
          <li class="pf-c-nav__item">
            <a href="#" class="pf-c-nav__link">Subnav link 2</a>
          </li>
          <li class="pf-c-nav__item">
            <a href="#" class="pf-c-nav__link pf-m-current" aria-current="page">Subnav link 3</a>
          </li>
        </ul>
      </section>
    </li>
    <li class="pf-c-nav__item pf-m-expandable pf-m-expanded">
      <button class="pf-c-nav__link" id="expandable-example2" aria-expanded="true">Link 2 (expanded, but not current example)
        <span class="pf-c-nav__toggle">
          <span class="pf-c-nav__toggle-icon">
            <i class="fas fa-angle-right" aria-hidden="true"></i>
          </span>
        </span>
      </button>
      <section class="pf-c-nav__subnav" aria-labelledby="expandable-example2">
        <ul class="pf-c-nav__list">
          <li class="pf-c-nav__item">
            <a href="#" class="pf-c-nav__link">Subnav link 1</a>
          </li>
          <li class="pf-c-nav__item">
            <a href="#" class="pf-c-nav__link">Subnav link 2</a>
          </li>
        </ul>
      </section>
    </li>
    <li class="pf-c-nav__item pf-m-expandable">
      <button class="pf-c-nav__link" id="expandable-example3" aria-expanded="false">Link 3
        <span class="pf-c-nav__toggle">
          <span class="pf-c-nav__toggle-icon">
            <i class="fas fa-angle-right" aria-hidden="true"></i>
          </span>
        </span>
      </button>
      <section class="pf-c-nav__subnav" aria-labelledby="expandable-example3" hidden>
        <ul class="pf-c-nav__list">
          <li class="pf-c-nav__item">
            <a href="#" class="pf-c-nav__link">Subnav link 1</a>
          </li>
          <li class="pf-c-nav__item">
            <a href="#" class="pf-c-nav__link">Subnav link 2</a>
          </li>
        </ul>
      </section>
    </li>
  </ul>
</nav>
```

### Expanded with subnav titles

```html
<nav class="pf-c-nav" aria-label="Global">
  <ul class="pf-c-nav__list">
    <li class="pf-c-nav__item pf-m-expandable pf-m-expanded pf-m-current">
      <button class="pf-c-nav__link" aria-expanded="true">Link 1
        <span class="pf-c-nav__toggle">
          <span class="pf-c-nav__toggle-icon">
            <i class="fas fa-angle-right" aria-hidden="true"></i>
          </span>
        </span>
      </button>
      <section class="pf-c-nav__subnav" aria-labelledby="subnav-title1">
        <h2 class="pf-c-nav__subnav-title pf-screen-reader" id="subnav-title1">Current and expanded example sub-navigation</h2>
        <ul class="pf-c-nav__list">
          <li class="pf-c-nav__item">
            <a href="#" class="pf-c-nav__link">Current link</a>
          </li>
          <li class="pf-c-nav__item">
            <a href="#" class="pf-c-nav__link pf-m-current" aria-current="page">Subnav link 2</a>
          </li>
          <li class="pf-c-nav__item">
            <a href="#" class="pf-c-nav__link">Subnav link 3</a>
          </li>
        </ul>
      </section>
    </li>
    <li class="pf-c-nav__item pf-m-expandable pf-m-expanded">
      <button class="pf-c-nav__link" aria-expanded="true">Link 2
        <span class="pf-c-nav__toggle">
          <span class="pf-c-nav__toggle-icon">
            <i class="fas fa-angle-right" aria-hidden="true"></i>
          </span>
        </span>
      </button>
      <section class="pf-c-nav__subnav" aria-labelledby="subnav-title2">
        <h2 class="pf-c-nav__subnav-title pf-screen-reader" id="subnav-title2">Expanded, but not current example sub-navigation</h2>
        <ul class="pf-c-nav__list">
          <li class="pf-c-nav__item">
            <a href="#" class="pf-c-nav__link">Subnav link 1</a>
          </li>
          <li class="pf-c-nav__item">
            <a href="#" class="pf-c-nav__link">Subnav link 2</a>
          </li>
        </ul>
      </section>
    </li>
  </ul>
</nav>
```

### Mixed

```html
<nav class="pf-c-nav" aria-label="Global">
  <ul class="pf-c-nav__list">
    <li class="pf-c-nav__item">
      <a href="#" class="pf-c-nav__link">Link 1 (not expandable)</a>
    </li>
    <li class="pf-c-nav__item pf-m-expandable pf-m-expanded">
      <button class="pf-c-nav__link" id="nav-mixed-link2" aria-expanded="true">Link 2 (expanded, but not current example)
        <span class="pf-c-nav__toggle">
          <span class="pf-c-nav__toggle-icon">
            <i class="fas fa-angle-right" aria-hidden="true"></i>
          </span>
        </span>
      </button>
      <section class="pf-c-nav__subnav" aria-labelledby="nav-mixed-link2">
        <ul class="pf-c-nav__list">
          <li class="pf-c-nav__item">
            <a href="#" class="pf-c-nav__link">Subnav link 1</a>
          </li>
          <li class="pf-c-nav__item">
            <a href="#" class="pf-c-nav__link">Subnav link 2</a>
          </li>
        </ul>
      </section>
    </li>
    <li class="pf-c-nav__item pf-m-expandable pf-m-current">
      <button class="pf-c-nav__link" id="nav-mixed-link4" aria-expanded="false">Link 3 (current, but not expanded example)
        <span class="pf-c-nav__toggle">
          <span class="pf-c-nav__toggle-icon">
            <i class="fas fa-angle-right" aria-hidden="true"></i>
          </span>
        </span>
      </button>
      <section class="pf-c-nav__subnav" aria-labelledby="nav-mixed-link4" hidden>
        <ul class="pf-c-nav__list">
          <li class="pf-c-nav__item">
            <a href="#" class="pf-c-nav__link">Subnav link 1</a>
          </li>
          <li class="pf-c-nav__item">
            <a href="#" class="pf-c-nav__link pf-m-current" aria-current="page">Subnav link 2</a>
          </li>
          <li class="pf-c-nav__item">
            <a href="#" class="pf-c-nav__link">Subnav link 3</a>
          </li>
        </ul>
      </section>
    </li>
  </ul>
</nav>
```

### Horizontal

```html
<nav class="pf-c-nav pf-m-horizontal" aria-label="Global">
  <button class="pf-c-nav__scroll-button" disabled aria-label="Scroll left">
    <i class="fas fa-angle-left" aria-hidden="true"></i>
  </button>
  <ul class="pf-c-nav__list">
    <li class="pf-c-nav__item">
      <a href="#" class="pf-c-nav__link pf-m-current" aria-current="page">Item 1</a>
    </li>
    <li class="pf-c-nav__item">
      <a href="#" class="pf-c-nav__link">Item 2</a>
    </li>
    <li class="pf-c-nav__item">
      <a href="#" class="pf-c-nav__link">Item 3</a>
    </li>
  </ul>
  <button class="pf-c-nav__scroll-button" disabled aria-label="Scroll right">
    <i class="fas fa-angle-right" aria-hidden="true"></i>
  </button>
</nav>
```

### Horizontal overflow

```html
<nav class="pf-c-nav pf-m-horizontal pf-m-scrollable" aria-label="Global">
  <button class="pf-c-nav__scroll-button" disabled aria-label="Scroll left">
    <i class="fas fa-angle-left" aria-hidden="true"></i>
  </button>
  <ul class="pf-c-nav__list">
    <li class="pf-c-nav__item">
      <a href="#" class="pf-c-nav__link">Horizontal nav item 1</a>
    </li>
    <li class="pf-c-nav__item">
      <a href="#" class="pf-c-nav__link">Horizontal nav item 2</a>
    </li>
    <li class="pf-c-nav__item">
      <a href="#" class="pf-c-nav__link">Horizontal nav item 3</a>
    </li>
    <li class="pf-c-nav__item">
      <a href="#" class="pf-c-nav__link">Horizontal nav item 4</a>
    </li>
    <li class="pf-c-nav__item">
      <a href="#" class="pf-c-nav__link pf-m-current" aria-current="page">Horizontal nav item 5</a>
    </li>
  </ul>
  <button class="pf-c-nav__scroll-button" aria-label="Scroll right">
    <i class="fas fa-angle-right" aria-hidden="true"></i>
  </button>
</nav>
```

### Tertiary

```html
<nav class="pf-c-nav pf-m-tertiary" aria-label="Local">
  <button class="pf-c-nav__scroll-button" disabled aria-label="Scroll left">
    <i class="fas fa-angle-left" aria-hidden="true"></i>
  </button>
  <ul class="pf-c-nav__list">
    <li class="pf-c-nav__item">
      <a href="#" class="pf-c-nav__link pf-m-current" aria-current="page">Item 1</a>
    </li>
    <li class="pf-c-nav__item">
      <a href="#" class="pf-c-nav__link">Item 2</a>
    </li>
    <li class="pf-c-nav__item">
      <a href="#" class="pf-c-nav__link">Item 3</a>
    </li>
  </ul>
  <button class="pf-c-nav__scroll-button" disabled aria-label="Scroll right">
    <i class="fas fa-angle-right" aria-hidden="true"></i>
  </button>
</nav>
```

### Tertiary overflow

```html
<nav class="pf-c-nav pf-m-tertiary pf-m-scrollable" aria-label="Local">
  <button class="pf-c-nav__scroll-button" disabled aria-label="Scroll left">
    <i class="fas fa-angle-left" aria-hidden="true"></i>
  </button>
  <ul class="pf-c-nav__list">
    <li class="pf-c-nav__item">
      <a href="#" class="pf-c-nav__link pf-m-current" aria-current="page">Tertiary nav item 1</a>
    </li>
    <li class="pf-c-nav__item">
      <a href="#" class="pf-c-nav__link">Tertiary nav item 2</a>
    </li>
    <li class="pf-c-nav__item">
      <a href="#" class="pf-c-nav__link">Tertiary nav item 3</a>
    </li>
    <li class="pf-c-nav__item">
      <a href="#" class="pf-c-nav__link">Tertiary nav item 4</a>
    </li>
    <li class="pf-c-nav__item">
      <a href="#" class="pf-c-nav__link">Tertiary nav item 5</a>
    </li>
  </ul>
  <button class="pf-c-nav__scroll-button" aria-label="Scroll right">
    <i class="fas fa-angle-right" aria-hidden="true"></i>
  </button>
</nav>
```

### Default in light mode

```html
<nav class="pf-c-nav pf-m-light" aria-label="Global">
  <ul class="pf-c-nav__list">
    <li class="pf-c-nav__item">
      <a href="#" class="pf-c-nav__link">Current link</a>
    </li>
    <li class="pf-c-nav__item">
      <a href="#" class="pf-c-nav__link pf-m-current" aria-current="page">Link 2</a>
    </li>
    <li class="pf-c-nav__item">
      <a href="#" class="pf-c-nav__link">Link 3</a>
    </li>
    <li class="pf-c-nav__item">
      <a href="#" class="pf-c-nav__link">Link 4</a>
    </li>
  </ul>
</nav>
```

### Expanded in light mode

```html
<nav class="pf-c-nav pf-m-light" aria-label="Global">
  <ul class="pf-c-nav__list">
    <li class="pf-c-nav__item pf-m-expandable pf-m-expanded pf-m-current">
      <button class="pf-c-nav__link" id="expandable-example1" aria-expanded="true">Link 1 (current and expanded example)
        <span class="pf-c-nav__toggle">
          <span class="pf-c-nav__toggle-icon">
            <i class="fas fa-angle-right" aria-hidden="true"></i>
          </span>
        </span>
      </button>
      <section class="pf-c-nav__subnav" aria-labelledby="expandable-example1">
        <ul class="pf-c-nav__list">
          <li class="pf-c-nav__item">
            <a href="#" class="pf-c-nav__link">Current link</a>
          </li>
          <li class="pf-c-divider" role="separator"></li>
          <li class="pf-c-nav__item">
            <a href="#" class="pf-c-nav__link">Subnav link 2</a>
          </li>
          <li class="pf-c-nav__item">
            <a href="#" class="pf-c-nav__link pf-m-current" aria-current="page">Subnav link 3</a>
          </li>
        </ul>
      </section>
    </li>
    <li class="pf-c-nav__item pf-m-expandable pf-m-expanded">
      <button class="pf-c-nav__link" id="expandable-example2" aria-expanded="true">Link 2 (expanded, but not current example)
        <span class="pf-c-nav__toggle">
          <span class="pf-c-nav__toggle-icon">
            <i class="fas fa-angle-right" aria-hidden="true"></i>
          </span>
        </span>
      </button>
      <section class="pf-c-nav__subnav" aria-labelledby="expandable-example2">
        <ul class="pf-c-nav__list">
          <li class="pf-c-nav__item">
            <a href="#" class="pf-c-nav__link">Subnav link 1</a>
          </li>
          <li class="pf-c-nav__item">
            <a href="#" class="pf-c-nav__link">Subnav link 2</a>
          </li>
        </ul>
      </section>
    </li>
    <li class="pf-c-nav__item pf-m-expandable">
      <button class="pf-c-nav__link" id="expandable-example3" aria-expanded="false">Link 3
        <span class="pf-c-nav__toggle">
          <span class="pf-c-nav__toggle-icon">
            <i class="fas fa-angle-right" aria-hidden="true"></i>
          </span>
        </span>
      </button>
      <section class="pf-c-nav__subnav" aria-labelledby="expandable-example3" hidden>
        <ul class="pf-c-nav__list">
          <li class="pf-c-nav__item">
            <a href="#" class="pf-c-nav__link">Subnav link 1</a>
          </li>
          <li class="pf-c-nav__item">
            <a href="#" class="pf-c-nav__link">Subnav link 2</a>
          </li>
        </ul>
      </section>
    </li>
  </ul>
</nav>
```

## Documentation

### Overview

The navigation system relies on several different sub-components:

-   `.pf-c-nav__list` - default navigation list. It is the basis for both default and expandable, vertical navigation.

### Accessibility

| Attribute                                                | Applied to                 | Outcome                                                                                                                                   |
| -------------------------------------------------------- | -------------------------- | ----------------------------------------------------------------------------------------------------------------------------------------- |
| `aria-label="[landmark description]"`                    | `.pf-c-nav`                | Describes `<nav>` landmark.                                                                                                               |
| `aria-labelledby="[id value of link describing subnav]"` | `.pf-c-nav__subnav`        | Gives the subnav `<section>` landmark an accessible name by referring to the element that provides the subnav `<section>` landmark title. |
| `aria-expanded="false"`                                  | `.pf-c-nav__link`          | Indicates that subnav section is hidden.                                                                                                  |
| `aria-expanded="true"`                                   | `.pf-c-nav__link`          | Indicates that subnav section is visible.                                                                                                 |
| `hidden`                                                 | `.pf-c-nav__subnav`        | Indicates that the subnav section is hidden so that it isn't visible in the UI and isn't accessed by assistive technologies.              |
| `disabled`                                               | `.pf-c-nav__scroll-button` | Indicates that a scroll button is disabled, when at the first or last item of a list. **Required when disabled**                          |
| `aria-current="page"`                                    | `.pf-c-nav__link`          | Indicates the current page link. Can only occur once on page.                                                                             |

### Usage

| Class                      | Applied to                                     | Outcome                                                                                                                                                                      |
| -------------------------- | ---------------------------------------------- | ---------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| `.pf-c-nav`                | `<nav>`                                        | Initiates a primary nav element.                                                                                                                                             |
| `.pf-c-nav__subnav`        | `<section>`                                    | Initiates a subnav section.                                                                                                                                                  |
| `.pf-c-nav__list`          | `<ul>`                                         | Initiates nav list.                                                                                                                                                          |
| `.pf-c-nav__item`          | `<li>`                                         | Initiates nav list item.                                                                                                                                                     |
| `.pf-c-nav__link`          | `<a>`                                          | Initiates nav list link.                                                                                                                                                     |
| `.pf-c-nav__section`       | `<section>`                                    | Initiates a nav section element.                                                                                                                                             |
| `.pf-c-nav__section-title` | `<h1>`, `<h2>`, `<h3>`, `<h4>`, `<h5>`, `<h6>` | Initiates a nav section title.                                                                                                                                               |
| `.pf-c-nav__toggle`        | `<span>`                                       | Initiates the nav toggle wrapper.                                                                                                                                            |
| `.pf-c-nav__toggle-icon`   | `<span>`                                       | Initiates a nav toggle icon wrapper.                                                                                                                                         |
| `.pf-c-nav__scroll-button` | `<button>`                                     | Initiates a nav scroll button. **Required for horizontal navs**                                                                                                              |
| `.pf-m-horizontal`         | `.pf-c-nav`                                    | Modifies nav for the horizontal variation.                                                                                                                                   |
| `.pf-m-tertiary`           | `.pf-c-nav`                                    | Modifies nav for the tertiary variation.                                                                                                                                     |
| `.pf-m-light`              | `.pf-c-nav`                                    | Modifies nav for the light variation. **Note: only for use with vertical navs, and requires `.pf-m-light` on the page component's sidebar element (`.pf-c-page__sidebar`)**. |
| `.pf-m-scrollable`         | `.pf-c-nav`                                    | Modifies nav for the scrollable state.                                                                                                                                       |
| `.pf-m-expandable`         | `.pf-c-nav__item`                              | Modifies for the expandable state.                                                                                                                                           |
| `.pf-m-expanded`           | `.pf-c-nav__item`                              | Modifies for the expanded state.                                                                                                                                             |
| `.pf-m-current`            | `.pf-c-nav__link`                              | Modifies for the current state.                                                                                                                                              |
