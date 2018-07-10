First, install the [CSS and Javascript Injection](https://chrome.google.com/webstore/detail/css-and-javascript-inject/ckddknfdmcemedlmmebildepcmneakaa/related?hl=en) Chrome extension. The purpose of this extension is to enable us to write custom CSS code for the Ghost admin.

Click on the extension icon and copy the following code and paste it into the CSS window.

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

![RTL for Ghost Blog Admin Extention](https://user-images.githubusercontent.com/626005/42505826-3b5513da-8440-11e8-8cff-d2723bc74e24.png)

The final result will be like:

![admin](https://user-images.githubusercontent.com/626005/42133363-0f537862-7d29-11e8-8334-3543b2cbf810.png)

---

Blog Post: [RTL for Ghost Blog Admin](https://aspirethemes.com/blog/ghost-rtl).