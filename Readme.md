## 🥳 Boostrap v5 Sidebar Navigation

### [Live Preview Here 😯🚀](https://chandu4221.github.io/bootstrap-v5-sidebar-navigation/)

![Preview](./repoImages/preview.gif)

List of Plugins Used

- [SwiperEvents.js](https://github.com/john-doherty/swiped-events) - For detecting the TouchEvents on Mobile Devices

List of Tweaks Made for the Regular Bootstrap V5 Navbar

- `<body>` - added

  - `.pt-5` - to avoid overlapping issue of the contents when navbar is fixed on top.

- `nav` - added

  - `.bg-dark` - to change the navbar background color
  - `.fixed-top` - to make navbar fixed on top
  - `.main-navigation` - custom class used in script.js

- `a.navbar-brand` - added

  - `.order-2` - placing it next to the button on the mobile screens.
  - `.order-lg-1` - placing it first on the desktop devices and up.
  - `.mr-auto` - margin right auto on small screens.
  - `.mr-lg-3` - adds spacing between the brand and menu-links.
  - `.ml-3` - adds spacing between toggler button and brand on small screens.
  - `.ml-lg-0` - remove the margin left on desktop devices and up.

- `button.navbar-toggler`

  - `data-*` - removed default data-attributes.

- `overlay` - added overlay div

  - `.d-flex` - to display it as flex on small screens
  - `.d-lg-none` - to set display none on desktop devices and up.

- `.navbar-collapse`

  - `.collapse .navbar-collapse` - removed these classes.
  - `.order-lg-2` - to display it next to the brand on desktop devices and up
  - `.bg-dark` - background color class (should be same as the navbar background color).
  - `.d-lg-flex` - to display it as flex on desktop devices and up.
  - `.w-100` - set width 100%;
  - `.pb-3` - adds padding bottom on small screens
  - `.pb-lg-0` - remove padding bottom desktop devices and up
  - `.sidebar` - custom class to add extra css.

- `.navbar-nav`

  - `.mr-auto` - removed marign right auto on small devices.
  - `.mr-lg-auto` - added marginn right auto on desktop devices and up

- `.nav-link` - added

  - `.px-3` - increased horizontal padding on small devices
  - `.px-lg-2` - decreased padding to regular size.

---

Main Content

- `.container-fluid`

  - `mt-2` - to avoid overlapping with the navbar

---

Javascript Functionality

- `.main-navigation.active`
  - `clickEvent` - toggles `.active` class on `.main-navigation`.
  - `swiperRight` - adds `.active` class on `.main-navigation`
  - `swiperLeft` - removes `.active` class on `.main-navigation`

MADE WITH 💖 - BY CHANDRA SHEKHAR.
