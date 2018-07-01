Install the [CSS and Javascript Injection](https://chrome.google.com/webstore/detail/css-and-javascript-inject/ckddknfdmcemedlmmebildepcmneakaa/related?hl=en) Ghrome Extention and then use the folloing CSS code.

```css
body.ember-application {
  direction: rtl;
  text-align: right;
}

.gh-nav-list svg {
  margin-right: 0;
  margin-left: 15px;
}

.koenig-plus-menu-button {
  margin: -2px -66px 0 0;
}

.gh-publishmenu-dropdown {
  right: auto;
}

.settings-menu-container {
  text-align: left;
  direction: ltr;
}

.gh-publishmenu-dropdown {
  direction: ltr;
}

.ember-power-select-trigger {
  padding: 0 30px 0 8px;
}

.dropdown-menu {
  right: 0;
}

.dropdown-menu svg {
  margin-right: 0;
  margin-left: 10px;
}

.gh-notification-content {
  text-align: left;
}

.koenig-cardmenu {
  left: auto;
}
```