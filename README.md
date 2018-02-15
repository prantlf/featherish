## featherish

[![npm](https://img.shields.io/npm/v/featherish.svg?style=flat-square)]()
[![license](https://img.shields.io/npm/l/featherish.svg?style=flat-square)]()
[![stars](https://img.shields.io/github/stars/michaelbazos/featherish.svg?style=flat-square)]()
[![deps status](https://david-dm.org/michaelbazos/featherish/status.svg?style=flat-square)](https://david-dm.org/michaelbazos/featherish)

### Description

Web components vectorial icons for modern web applications. Design of the icons by [Cole Bemis](https://github.com/colebemis/).

### Demo
<h4>
  <a href="https://stackblitz.com/edit/featherish?file=index.html">
    >> See live demo <<
  </a>
</h4>

### Usage

_1. Install the package_

```sh
npm install featherish
```

_2. Import icons you need_

```js
import 'featherish/icons/github';
import 'featherish/icons/gitlab';
import 'featherish/icons/heart';
import 'featherish/icons/moon';
```

_3. Use_

```html
<i-github></i-github>
<i-gitlab></i-gitlab>
<i-heart></i-heart>
<i-moon></i-moon>
```

Note that you might need to add a polyfill. For that, npm install `@webcomponents/custom-elements` and import the polyfill before importing the icons.

```js
import '@webcomponents/custom-elements/src/native-shim';
```


### Styling icons

Icons can be customised with any CSS property that you can apply on a SVG element.

```html
<i-heart class="big fill-red"></i-heart>
```

```css
.big {
  height: 50px;
  width: 50px;
}

.fill-red {
  fill: red;
}
```

### Available icons

Refer to the table below for the list of all available icons.

|     | Component tag name |
| --- | ------------------ |
| ![activity](https://cdn.rawgit.com/feathericons/feather/v4.5.0/icons/activity.svg) | `<i-activity>` |
| ![airplay](https://cdn.rawgit.com/feathericons/feather/v4.5.0/icons/airplay.svg) | `<i-airplay>` |
| ![alert-circle](https://cdn.rawgit.com/feathericons/feather/v4.5.0/icons/alert-circle.svg) | `<i-alert-circle>` |
| ![alert-octagon](https://cdn.rawgit.com/feathericons/feather/v4.5.0/icons/alert-octagon.svg) | `<i-alert-octagon>` |
| ![alert-triangle](https://cdn.rawgit.com/feathericons/feather/v4.5.0/icons/alert-triangle.svg) | `<i-alert-triangle>` |
| ![align-center](https://cdn.rawgit.com/feathericons/feather/v4.5.0/icons/align-center.svg) | `<i-align-center>` |
| ![align-justify](https://cdn.rawgit.com/feathericons/feather/v4.5.0/icons/align-justify.svg) | `<i-align-justify>` |
| ![align-left](https://cdn.rawgit.com/feathericons/feather/v4.5.0/icons/align-left.svg) | `<i-align-left>` |
| ![align-right](https://cdn.rawgit.com/feathericons/feather/v4.5.0/icons/align-right.svg) | `<i-align-right>` |
| ![anchor](https://cdn.rawgit.com/feathericons/feather/v4.5.0/icons/anchor.svg) | `<i-anchor>` |
| ![aperture](https://cdn.rawgit.com/feathericons/feather/v4.5.0/icons/aperture.svg) | `<i-aperture>` |
| ![arrow-down-circle](https://cdn.rawgit.com/feathericons/feather/v4.5.0/icons/arrow-down-circle.svg) | `<i-arrow-down-circle>` |
| ![arrow-down-left](https://cdn.rawgit.com/feathericons/feather/v4.5.0/icons/arrow-down-left.svg) | `<i-arrow-down-left>` |
| ![arrow-down-right](https://cdn.rawgit.com/feathericons/feather/v4.5.0/icons/arrow-down-right.svg) | `<i-arrow-down-right>` |
| ![arrow-down](https://cdn.rawgit.com/feathericons/feather/v4.5.0/icons/arrow-down.svg) | `<i-arrow-down>` |
| ![arrow-left-circle](https://cdn.rawgit.com/feathericons/feather/v4.5.0/icons/arrow-left-circle.svg) | `<i-arrow-left-circle>` |
| ![arrow-left](https://cdn.rawgit.com/feathericons/feather/v4.5.0/icons/arrow-left.svg) | `<i-arrow-left>` |
| ![arrow-right-circle](https://cdn.rawgit.com/feathericons/feather/v4.5.0/icons/arrow-right-circle.svg) | `<i-arrow-right-circle>` |
| ![arrow-right](https://cdn.rawgit.com/feathericons/feather/v4.5.0/icons/arrow-right.svg) | `<i-arrow-right>` |
| ![arrow-up-circle](https://cdn.rawgit.com/feathericons/feather/v4.5.0/icons/arrow-up-circle.svg) | `<i-arrow-up-circle>` |
| ![arrow-up-left](https://cdn.rawgit.com/feathericons/feather/v4.5.0/icons/arrow-up-left.svg) | `<i-arrow-up-left>` |
| ![arrow-up-right](https://cdn.rawgit.com/feathericons/feather/v4.5.0/icons/arrow-up-right.svg) | `<i-arrow-up-right>` |
| ![arrow-up](https://cdn.rawgit.com/feathericons/feather/v4.5.0/icons/arrow-up.svg) | `<i-arrow-up>` |
| ![at-sign](https://cdn.rawgit.com/feathericons/feather/v4.5.0/icons/at-sign.svg) | `<i-at-sign>` |
| ![award](https://cdn.rawgit.com/feathericons/feather/v4.5.0/icons/award.svg) | `<i-award>` |
| ![bar-chart-2](https://cdn.rawgit.com/feathericons/feather/v4.5.0/icons/bar-chart-2.svg) | `<i-bar-chart-2>` |
| ![bar-chart](https://cdn.rawgit.com/feathericons/feather/v4.5.0/icons/bar-chart.svg) | `<i-bar-chart>` |
| ![battery-charging](https://cdn.rawgit.com/feathericons/feather/v4.5.0/icons/battery-charging.svg) | `<i-battery-charging>` |
| ![battery](https://cdn.rawgit.com/feathericons/feather/v4.5.0/icons/battery.svg) | `<i-battery>` |
| ![bell-off](https://cdn.rawgit.com/feathericons/feather/v4.5.0/icons/bell-off.svg) | `<i-bell-off>` |
| ![bell](https://cdn.rawgit.com/feathericons/feather/v4.5.0/icons/bell.svg) | `<i-bell>` |
| ![bluetooth](https://cdn.rawgit.com/feathericons/feather/v4.5.0/icons/bluetooth.svg) | `<i-bluetooth>` |
| ![bold](https://cdn.rawgit.com/feathericons/feather/v4.5.0/icons/bold.svg) | `<i-bold>` |
| ![book-open](https://cdn.rawgit.com/feathericons/feather/v4.5.0/icons/book-open.svg) | `<i-book-open>` |
| ![book](https://cdn.rawgit.com/feathericons/feather/v4.5.0/icons/book.svg) | `<i-book>` |
| ![bookmark](https://cdn.rawgit.com/feathericons/feather/v4.5.0/icons/bookmark.svg) | `<i-bookmark>` |
| ![box](https://cdn.rawgit.com/feathericons/feather/v4.5.0/icons/box.svg) | `<i-box>` |
| ![briefcase](https://cdn.rawgit.com/feathericons/feather/v4.5.0/icons/briefcase.svg) | `<i-briefcase>` |
| ![calendar](https://cdn.rawgit.com/feathericons/feather/v4.5.0/icons/calendar.svg) | `<i-calendar>` |
| ![camera-off](https://cdn.rawgit.com/feathericons/feather/v4.5.0/icons/camera-off.svg) | `<i-camera-off>` |
| ![camera](https://cdn.rawgit.com/feathericons/feather/v4.5.0/icons/camera.svg) | `<i-camera>` |
| ![cast](https://cdn.rawgit.com/feathericons/feather/v4.5.0/icons/cast.svg) | `<i-cast>` |
| ![check-circle](https://cdn.rawgit.com/feathericons/feather/v4.5.0/icons/check-circle.svg) | `<i-check-circle>` |
| ![check-square](https://cdn.rawgit.com/feathericons/feather/v4.5.0/icons/check-square.svg) | `<i-check-square>` |
| ![check](https://cdn.rawgit.com/feathericons/feather/v4.5.0/icons/check.svg) | `<i-check>` |
| ![chevron-down](https://cdn.rawgit.com/feathericons/feather/v4.5.0/icons/chevron-down.svg) | `<i-chevron-down>` |
| ![chevron-left](https://cdn.rawgit.com/feathericons/feather/v4.5.0/icons/chevron-left.svg) | `<i-chevron-left>` |
| ![chevron-right](https://cdn.rawgit.com/feathericons/feather/v4.5.0/icons/chevron-right.svg) | `<i-chevron-right>` |
| ![chevron-up](https://cdn.rawgit.com/feathericons/feather/v4.5.0/icons/chevron-up.svg) | `<i-chevron-up>` |
| ![chevrons-down](https://cdn.rawgit.com/feathericons/feather/v4.5.0/icons/chevrons-down.svg) | `<i-chevrons-down>` |
| ![chevrons-left](https://cdn.rawgit.com/feathericons/feather/v4.5.0/icons/chevrons-left.svg) | `<i-chevrons-left>` |
| ![chevrons-right](https://cdn.rawgit.com/feathericons/feather/v4.5.0/icons/chevrons-right.svg) | `<i-chevrons-right>` |
| ![chevrons-up](https://cdn.rawgit.com/feathericons/feather/v4.5.0/icons/chevrons-up.svg) | `<i-chevrons-up>` |
| ![chrome](https://cdn.rawgit.com/feathericons/feather/v4.5.0/icons/chrome.svg) | `<i-chrome>` |
| ![circle](https://cdn.rawgit.com/feathericons/feather/v4.5.0/icons/circle.svg) | `<i-circle>` |
| ![clipboard](https://cdn.rawgit.com/feathericons/feather/v4.5.0/icons/clipboard.svg) | `<i-clipboard>` |
| ![clock](https://cdn.rawgit.com/feathericons/feather/v4.5.0/icons/clock.svg) | `<i-clock>` |
| ![cloud-drizzle](https://cdn.rawgit.com/feathericons/feather/v4.5.0/icons/cloud-drizzle.svg) | `<i-cloud-drizzle>` |
| ![cloud-lightning](https://cdn.rawgit.com/feathericons/feather/v4.5.0/icons/cloud-lightning.svg) | `<i-cloud-lightning>` |
| ![cloud-off](https://cdn.rawgit.com/feathericons/feather/v4.5.0/icons/cloud-off.svg) | `<i-cloud-off>` |
| ![cloud-rain](https://cdn.rawgit.com/feathericons/feather/v4.5.0/icons/cloud-rain.svg) | `<i-cloud-rain>` |
| ![cloud-snow](https://cdn.rawgit.com/feathericons/feather/v4.5.0/icons/cloud-snow.svg) | `<i-cloud-snow>` |
| ![cloud](https://cdn.rawgit.com/feathericons/feather/v4.5.0/icons/cloud.svg) | `<i-cloud>` |
| ![code](https://cdn.rawgit.com/feathericons/feather/v4.5.0/icons/code.svg) | `<i-code>` |
| ![codepen](https://cdn.rawgit.com/feathericons/feather/v4.5.0/icons/codepen.svg) | `<i-codepen>` |
| ![command](https://cdn.rawgit.com/feathericons/feather/v4.5.0/icons/command.svg) | `<i-command>` |
| ![compass](https://cdn.rawgit.com/feathericons/feather/v4.5.0/icons/compass.svg) | `<i-compass>` |
| ![copy](https://cdn.rawgit.com/feathericons/feather/v4.5.0/icons/copy.svg) | `<i-copy>` |
| ![corner-down-left](https://cdn.rawgit.com/feathericons/feather/v4.5.0/icons/corner-down-left.svg) | `<i-corner-down-left>` |
| ![corner-down-right](https://cdn.rawgit.com/feathericons/feather/v4.5.0/icons/corner-down-right.svg) | `<i-corner-down-right>` |
| ![corner-left-down](https://cdn.rawgit.com/feathericons/feather/v4.5.0/icons/corner-left-down.svg) | `<i-corner-left-down>` |
| ![corner-left-up](https://cdn.rawgit.com/feathericons/feather/v4.5.0/icons/corner-left-up.svg) | `<i-corner-left-up>` |
| ![corner-right-down](https://cdn.rawgit.com/feathericons/feather/v4.5.0/icons/corner-right-down.svg) | `<i-corner-right-down>` |
| ![corner-right-up](https://cdn.rawgit.com/feathericons/feather/v4.5.0/icons/corner-right-up.svg) | `<i-corner-right-up>` |
| ![corner-up-left](https://cdn.rawgit.com/feathericons/feather/v4.5.0/icons/corner-up-left.svg) | `<i-corner-up-left>` |
| ![corner-up-right](https://cdn.rawgit.com/feathericons/feather/v4.5.0/icons/corner-up-right.svg) | `<i-corner-up-right>` |
| ![cpu](https://cdn.rawgit.com/feathericons/feather/v4.5.0/icons/cpu.svg) | `<i-cpu>` |
| ![credit-card](https://cdn.rawgit.com/feathericons/feather/v4.5.0/icons/credit-card.svg) | `<i-credit-card>` |
| ![crop](https://cdn.rawgit.com/feathericons/feather/v4.5.0/icons/crop.svg) | `<i-crop>` |
| ![crosshair](https://cdn.rawgit.com/feathericons/feather/v4.5.0/icons/crosshair.svg) | `<i-crosshair>` |
| ![database](https://cdn.rawgit.com/feathericons/feather/v4.5.0/icons/database.svg) | `<i-database>` |
| ![delete](https://cdn.rawgit.com/feathericons/feather/v4.5.0/icons/delete.svg) | `<i-delete>` |
| ![disc](https://cdn.rawgit.com/feathericons/feather/v4.5.0/icons/disc.svg) | `<i-disc>` |
| ![dollar-sign](https://cdn.rawgit.com/feathericons/feather/v4.5.0/icons/dollar-sign.svg) | `<i-dollar-sign>` |
| ![download-cloud](https://cdn.rawgit.com/feathericons/feather/v4.5.0/icons/download-cloud.svg) | `<i-download-cloud>` |
| ![download](https://cdn.rawgit.com/feathericons/feather/v4.5.0/icons/download.svg) | `<i-download>` |
| ![droplet](https://cdn.rawgit.com/feathericons/feather/v4.5.0/icons/droplet.svg) | `<i-droplet>` |
| ![edit-2](https://cdn.rawgit.com/feathericons/feather/v4.5.0/icons/edit-2.svg) | `<i-edit-2>` |
| ![edit-3](https://cdn.rawgit.com/feathericons/feather/v4.5.0/icons/edit-3.svg) | `<i-edit-3>` |
| ![edit](https://cdn.rawgit.com/feathericons/feather/v4.5.0/icons/edit.svg) | `<i-edit>` |
| ![external-link](https://cdn.rawgit.com/feathericons/feather/v4.5.0/icons/external-link.svg) | `<i-external-link>` |
| ![eye-off](https://cdn.rawgit.com/feathericons/feather/v4.5.0/icons/eye-off.svg) | `<i-eye-off>` |
| ![eye](https://cdn.rawgit.com/feathericons/feather/v4.5.0/icons/eye.svg) | `<i-eye>` |
| ![facebook](https://cdn.rawgit.com/feathericons/feather/v4.5.0/icons/facebook.svg) | `<i-facebook>` |
| ![fast-forward](https://cdn.rawgit.com/feathericons/feather/v4.5.0/icons/fast-forward.svg) | `<i-fast-forward>` |
| ![feather](https://cdn.rawgit.com/feathericons/feather/v4.5.0/icons/feather.svg) | `<i-feather>` |
| ![file-minus](https://cdn.rawgit.com/feathericons/feather/v4.5.0/icons/file-minus.svg) | `<i-file-minus>` |
| ![file-plus](https://cdn.rawgit.com/feathericons/feather/v4.5.0/icons/file-plus.svg) | `<i-file-plus>` |
| ![file-text](https://cdn.rawgit.com/feathericons/feather/v4.5.0/icons/file-text.svg) | `<i-file-text>` |
| ![file](https://cdn.rawgit.com/feathericons/feather/v4.5.0/icons/file.svg) | `<i-file>` |
| ![film](https://cdn.rawgit.com/feathericons/feather/v4.5.0/icons/film.svg) | `<i-film>` |
| ![filter](https://cdn.rawgit.com/feathericons/feather/v4.5.0/icons/filter.svg) | `<i-filter>` |
| ![flag](https://cdn.rawgit.com/feathericons/feather/v4.5.0/icons/flag.svg) | `<i-flag>` |
| ![folder-minus](https://cdn.rawgit.com/feathericons/feather/v4.5.0/icons/folder-minus.svg) | `<i-folder-minus>` |
| ![folder-plus](https://cdn.rawgit.com/feathericons/feather/v4.5.0/icons/folder-plus.svg) | `<i-folder-plus>` |
| ![folder](https://cdn.rawgit.com/feathericons/feather/v4.5.0/icons/folder.svg) | `<i-folder>` |
| ![git-branch](https://cdn.rawgit.com/feathericons/feather/v4.5.0/icons/git-branch.svg) | `<i-git-branch>` |
| ![git-commit](https://cdn.rawgit.com/feathericons/feather/v4.5.0/icons/git-commit.svg) | `<i-git-commit>` |
| ![git-merge](https://cdn.rawgit.com/feathericons/feather/v4.5.0/icons/git-merge.svg) | `<i-git-merge>` |
| ![git-pull-request](https://cdn.rawgit.com/feathericons/feather/v4.5.0/icons/git-pull-request.svg) | `<i-git-pull-request>` |
| ![github](https://cdn.rawgit.com/feathericons/feather/v4.5.0/icons/github.svg) | `<i-github>` |
| ![gitlab](https://cdn.rawgit.com/feathericons/feather/v4.5.0/icons/gitlab.svg) | `<i-gitlab>` |
| ![globe](https://cdn.rawgit.com/feathericons/feather/v4.5.0/icons/globe.svg) | `<i-globe>` |
| ![grid](https://cdn.rawgit.com/feathericons/feather/v4.5.0/icons/grid.svg) | `<i-grid>` |
| ![hard-drive](https://cdn.rawgit.com/feathericons/feather/v4.5.0/icons/hard-drive.svg) | `<i-hard-drive>` |
| ![hash](https://cdn.rawgit.com/feathericons/feather/v4.5.0/icons/hash.svg) | `<i-hash>` |
| ![headphones](https://cdn.rawgit.com/feathericons/feather/v4.5.0/icons/headphones.svg) | `<i-headphones>` |
| ![heart](https://cdn.rawgit.com/feathericons/feather/v4.5.0/icons/heart.svg) | `<i-heart>` |
| ![help-circle](https://cdn.rawgit.com/feathericons/feather/v4.5.0/icons/help-circle.svg) | `<i-help-circle>` |
| ![home](https://cdn.rawgit.com/feathericons/feather/v4.5.0/icons/home.svg) | `<i-home>` |
| ![image](https://cdn.rawgit.com/feathericons/feather/v4.5.0/icons/image.svg) | `<i-image>` |
| ![inbox](https://cdn.rawgit.com/feathericons/feather/v4.5.0/icons/inbox.svg) | `<i-inbox>` |
| ![info](https://cdn.rawgit.com/feathericons/feather/v4.5.0/icons/info.svg) | `<i-info>` |
| ![instagram](https://cdn.rawgit.com/feathericons/feather/v4.5.0/icons/instagram.svg) | `<i-instagram>` |
| ![italic](https://cdn.rawgit.com/feathericons/feather/v4.5.0/icons/italic.svg) | `<i-italic>` |
| ![layers](https://cdn.rawgit.com/feathericons/feather/v4.5.0/icons/layers.svg) | `<i-layers>` |
| ![layout](https://cdn.rawgit.com/feathericons/feather/v4.5.0/icons/layout.svg) | `<i-layout>` |
| ![life-buoy](https://cdn.rawgit.com/feathericons/feather/v4.5.0/icons/life-buoy.svg) | `<i-life-buoy>` |
| ![link-2](https://cdn.rawgit.com/feathericons/feather/v4.5.0/icons/link-2.svg) | `<i-link-2>` |
| ![link](https://cdn.rawgit.com/feathericons/feather/v4.5.0/icons/link.svg) | `<i-link>` |
| ![linkedin](https://cdn.rawgit.com/feathericons/feather/v4.5.0/icons/linkedin.svg) | `<i-linkedin>` |
| ![list](https://cdn.rawgit.com/feathericons/feather/v4.5.0/icons/list.svg) | `<i-list>` |
| ![loader](https://cdn.rawgit.com/feathericons/feather/v4.5.0/icons/loader.svg) | `<i-loader>` |
| ![lock](https://cdn.rawgit.com/feathericons/feather/v4.5.0/icons/lock.svg) | `<i-lock>` |
| ![log-in](https://cdn.rawgit.com/feathericons/feather/v4.5.0/icons/log-in.svg) | `<i-log-in>` |
| ![log-out](https://cdn.rawgit.com/feathericons/feather/v4.5.0/icons/log-out.svg) | `<i-log-out>` |
| ![mail](https://cdn.rawgit.com/feathericons/feather/v4.5.0/icons/mail.svg) | `<i-mail>` |
| ![map-pin](https://cdn.rawgit.com/feathericons/feather/v4.5.0/icons/map-pin.svg) | `<i-map-pin>` |
| ![map](https://cdn.rawgit.com/feathericons/feather/v4.5.0/icons/map.svg) | `<i-map>` |
| ![maximize-2](https://cdn.rawgit.com/feathericons/feather/v4.5.0/icons/maximize-2.svg) | `<i-maximize-2>` |
| ![maximize](https://cdn.rawgit.com/feathericons/feather/v4.5.0/icons/maximize.svg) | `<i-maximize>` |
| ![menu](https://cdn.rawgit.com/feathericons/feather/v4.5.0/icons/menu.svg) | `<i-menu>` |
| ![message-circle](https://cdn.rawgit.com/feathericons/feather/v4.5.0/icons/message-circle.svg) | `<i-message-circle>` |
| ![message-square](https://cdn.rawgit.com/feathericons/feather/v4.5.0/icons/message-square.svg) | `<i-message-square>` |
| ![mic-off](https://cdn.rawgit.com/feathericons/feather/v4.5.0/icons/mic-off.svg) | `<i-mic-off>` |
| ![mic](https://cdn.rawgit.com/feathericons/feather/v4.5.0/icons/mic.svg) | `<i-mic>` |
| ![minimize-2](https://cdn.rawgit.com/feathericons/feather/v4.5.0/icons/minimize-2.svg) | `<i-minimize-2>` |
| ![minimize](https://cdn.rawgit.com/feathericons/feather/v4.5.0/icons/minimize.svg) | `<i-minimize>` |
| ![minus-circle](https://cdn.rawgit.com/feathericons/feather/v4.5.0/icons/minus-circle.svg) | `<i-minus-circle>` |
| ![minus-square](https://cdn.rawgit.com/feathericons/feather/v4.5.0/icons/minus-square.svg) | `<i-minus-square>` |
| ![minus](https://cdn.rawgit.com/feathericons/feather/v4.5.0/icons/minus.svg) | `<i-minus>` |
| ![monitor](https://cdn.rawgit.com/feathericons/feather/v4.5.0/icons/monitor.svg) | `<i-monitor>` |
| ![moon](https://cdn.rawgit.com/feathericons/feather/v4.5.0/icons/moon.svg) | `<i-moon>` |
| ![more-horizontal](https://cdn.rawgit.com/feathericons/feather/v4.5.0/icons/more-horizontal.svg) | `<i-more-horizontal>` |
| ![more-vertical](https://cdn.rawgit.com/feathericons/feather/v4.5.0/icons/more-vertical.svg) | `<i-more-vertical>` |
| ![move](https://cdn.rawgit.com/feathericons/feather/v4.5.0/icons/move.svg) | `<i-move>` |
| ![music](https://cdn.rawgit.com/feathericons/feather/v4.5.0/icons/music.svg) | `<i-music>` |
| ![navigation-2](https://cdn.rawgit.com/feathericons/feather/v4.5.0/icons/navigation-2.svg) | `<i-navigation-2>` |
| ![navigation](https://cdn.rawgit.com/feathericons/feather/v4.5.0/icons/navigation.svg) | `<i-navigation>` |
| ![octagon](https://cdn.rawgit.com/feathericons/feather/v4.5.0/icons/octagon.svg) | `<i-octagon>` |
| ![package](https://cdn.rawgit.com/feathericons/feather/v4.5.0/icons/package.svg) | `<i-package>` |
| ![paperclip](https://cdn.rawgit.com/feathericons/feather/v4.5.0/icons/paperclip.svg) | `<i-paperclip>` |
| ![pause-circle](https://cdn.rawgit.com/feathericons/feather/v4.5.0/icons/pause-circle.svg) | `<i-pause-circle>` |
| ![pause](https://cdn.rawgit.com/feathericons/feather/v4.5.0/icons/pause.svg) | `<i-pause>` |
| ![percent](https://cdn.rawgit.com/feathericons/feather/v4.5.0/icons/percent.svg) | `<i-percent>` |
| ![phone-call](https://cdn.rawgit.com/feathericons/feather/v4.5.0/icons/phone-call.svg) | `<i-phone-call>` |
| ![phone-forwarded](https://cdn.rawgit.com/feathericons/feather/v4.5.0/icons/phone-forwarded.svg) | `<i-phone-forwarded>` |
| ![phone-incoming](https://cdn.rawgit.com/feathericons/feather/v4.5.0/icons/phone-incoming.svg) | `<i-phone-incoming>` |
| ![phone-missed](https://cdn.rawgit.com/feathericons/feather/v4.5.0/icons/phone-missed.svg) | `<i-phone-missed>` |
| ![phone-off](https://cdn.rawgit.com/feathericons/feather/v4.5.0/icons/phone-off.svg) | `<i-phone-off>` |
| ![phone-outgoing](https://cdn.rawgit.com/feathericons/feather/v4.5.0/icons/phone-outgoing.svg) | `<i-phone-outgoing>` |
| ![phone](https://cdn.rawgit.com/feathericons/feather/v4.5.0/icons/phone.svg) | `<i-phone>` |
| ![pie-chart](https://cdn.rawgit.com/feathericons/feather/v4.5.0/icons/pie-chart.svg) | `<i-pie-chart>` |
| ![play-circle](https://cdn.rawgit.com/feathericons/feather/v4.5.0/icons/play-circle.svg) | `<i-play-circle>` |
| ![play](https://cdn.rawgit.com/feathericons/feather/v4.5.0/icons/play.svg) | `<i-play>` |
| ![plus-circle](https://cdn.rawgit.com/feathericons/feather/v4.5.0/icons/plus-circle.svg) | `<i-plus-circle>` |
| ![plus-square](https://cdn.rawgit.com/feathericons/feather/v4.5.0/icons/plus-square.svg) | `<i-plus-square>` |
| ![plus](https://cdn.rawgit.com/feathericons/feather/v4.5.0/icons/plus.svg) | `<i-plus>` |
| ![pocket](https://cdn.rawgit.com/feathericons/feather/v4.5.0/icons/pocket.svg) | `<i-pocket>` |
| ![power](https://cdn.rawgit.com/feathericons/feather/v4.5.0/icons/power.svg) | `<i-power>` |
| ![printer](https://cdn.rawgit.com/feathericons/feather/v4.5.0/icons/printer.svg) | `<i-printer>` |
| ![radio](https://cdn.rawgit.com/feathericons/feather/v4.5.0/icons/radio.svg) | `<i-radio>` |
| ![refresh-ccw](https://cdn.rawgit.com/feathericons/feather/v4.5.0/icons/refresh-ccw.svg) | `<i-refresh-ccw>` |
| ![refresh-cw](https://cdn.rawgit.com/feathericons/feather/v4.5.0/icons/refresh-cw.svg) | `<i-refresh-cw>` |
| ![repeat](https://cdn.rawgit.com/feathericons/feather/v4.5.0/icons/repeat.svg) | `<i-repeat>` |
| ![rewind](https://cdn.rawgit.com/feathericons/feather/v4.5.0/icons/rewind.svg) | `<i-rewind>` |
| ![rotate-ccw](https://cdn.rawgit.com/feathericons/feather/v4.5.0/icons/rotate-ccw.svg) | `<i-rotate-ccw>` |
| ![rotate-cw](https://cdn.rawgit.com/feathericons/feather/v4.5.0/icons/rotate-cw.svg) | `<i-rotate-cw>` |
| ![rss](https://cdn.rawgit.com/feathericons/feather/v4.5.0/icons/rss.svg) | `<i-rss>` |
| ![save](https://cdn.rawgit.com/feathericons/feather/v4.5.0/icons/save.svg) | `<i-save>` |
| ![scissors](https://cdn.rawgit.com/feathericons/feather/v4.5.0/icons/scissors.svg) | `<i-scissors>` |
| ![search](https://cdn.rawgit.com/feathericons/feather/v4.5.0/icons/search.svg) | `<i-search>` |
| ![send](https://cdn.rawgit.com/feathericons/feather/v4.5.0/icons/send.svg) | `<i-send>` |
| ![server](https://cdn.rawgit.com/feathericons/feather/v4.5.0/icons/server.svg) | `<i-server>` |
| ![settings](https://cdn.rawgit.com/feathericons/feather/v4.5.0/icons/settings.svg) | `<i-settings>` |
| ![share-2](https://cdn.rawgit.com/feathericons/feather/v4.5.0/icons/share-2.svg) | `<i-share-2>` |
| ![share](https://cdn.rawgit.com/feathericons/feather/v4.5.0/icons/share.svg) | `<i-share>` |
| ![shield-off](https://cdn.rawgit.com/feathericons/feather/v4.5.0/icons/shield-off.svg) | `<i-shield-off>` |
| ![shield](https://cdn.rawgit.com/feathericons/feather/v4.5.0/icons/shield.svg) | `<i-shield>` |
| ![shopping-bag](https://cdn.rawgit.com/feathericons/feather/v4.5.0/icons/shopping-bag.svg) | `<i-shopping-bag>` |
| ![shopping-cart](https://cdn.rawgit.com/feathericons/feather/v4.5.0/icons/shopping-cart.svg) | `<i-shopping-cart>` |
| ![shuffle](https://cdn.rawgit.com/feathericons/feather/v4.5.0/icons/shuffle.svg) | `<i-shuffle>` |
| ![sidebar](https://cdn.rawgit.com/feathericons/feather/v4.5.0/icons/sidebar.svg) | `<i-sidebar>` |
| ![skip-back](https://cdn.rawgit.com/feathericons/feather/v4.5.0/icons/skip-back.svg) | `<i-skip-back>` |
| ![skip-forward](https://cdn.rawgit.com/feathericons/feather/v4.5.0/icons/skip-forward.svg) | `<i-skip-forward>` |
| ![slack](https://cdn.rawgit.com/feathericons/feather/v4.5.0/icons/slack.svg) | `<i-slack>` |
| ![slash](https://cdn.rawgit.com/feathericons/feather/v4.5.0/icons/slash.svg) | `<i-slash>` |
| ![sliders](https://cdn.rawgit.com/feathericons/feather/v4.5.0/icons/sliders.svg) | `<i-sliders>` |
| ![smartphone](https://cdn.rawgit.com/feathericons/feather/v4.5.0/icons/smartphone.svg) | `<i-smartphone>` |
| ![speaker](https://cdn.rawgit.com/feathericons/feather/v4.5.0/icons/speaker.svg) | `<i-speaker>` |
| ![square](https://cdn.rawgit.com/feathericons/feather/v4.5.0/icons/square.svg) | `<i-square>` |
| ![star](https://cdn.rawgit.com/feathericons/feather/v4.5.0/icons/star.svg) | `<i-star>` |
| ![stop-circle](https://cdn.rawgit.com/feathericons/feather/v4.5.0/icons/stop-circle.svg) | `<i-stop-circle>` |
| ![sun](https://cdn.rawgit.com/feathericons/feather/v4.5.0/icons/sun.svg) | `<i-sun>` |
| ![sunrise](https://cdn.rawgit.com/feathericons/feather/v4.5.0/icons/sunrise.svg) | `<i-sunrise>` |
| ![sunset](https://cdn.rawgit.com/feathericons/feather/v4.5.0/icons/sunset.svg) | `<i-sunset>` |
| ![tablet](https://cdn.rawgit.com/feathericons/feather/v4.5.0/icons/tablet.svg) | `<i-tablet>` |
| ![tag](https://cdn.rawgit.com/feathericons/feather/v4.5.0/icons/tag.svg) | `<i-tag>` |
| ![target](https://cdn.rawgit.com/feathericons/feather/v4.5.0/icons/target.svg) | `<i-target>` |
| ![terminal](https://cdn.rawgit.com/feathericons/feather/v4.5.0/icons/terminal.svg) | `<i-terminal>` |
| ![thermometer](https://cdn.rawgit.com/feathericons/feather/v4.5.0/icons/thermometer.svg) | `<i-thermometer>` |
| ![thumbs-down](https://cdn.rawgit.com/feathericons/feather/v4.5.0/icons/thumbs-down.svg) | `<i-thumbs-down>` |
| ![thumbs-up](https://cdn.rawgit.com/feathericons/feather/v4.5.0/icons/thumbs-up.svg) | `<i-thumbs-up>` |
| ![toggle-left](https://cdn.rawgit.com/feathericons/feather/v4.5.0/icons/toggle-left.svg) | `<i-toggle-left>` |
| ![toggle-right](https://cdn.rawgit.com/feathericons/feather/v4.5.0/icons/toggle-right.svg) | `<i-toggle-right>` |
| ![trash-2](https://cdn.rawgit.com/feathericons/feather/v4.5.0/icons/trash-2.svg) | `<i-trash-2>` |
| ![trash](https://cdn.rawgit.com/feathericons/feather/v4.5.0/icons/trash.svg) | `<i-trash>` |
| ![trending-down](https://cdn.rawgit.com/feathericons/feather/v4.5.0/icons/trending-down.svg) | `<i-trending-down>` |
| ![trending-up](https://cdn.rawgit.com/feathericons/feather/v4.5.0/icons/trending-up.svg) | `<i-trending-up>` |
| ![triangle](https://cdn.rawgit.com/feathericons/feather/v4.5.0/icons/triangle.svg) | `<i-triangle>` |
| ![truck](https://cdn.rawgit.com/feathericons/feather/v4.5.0/icons/truck.svg) | `<i-truck>` |
| ![tv](https://cdn.rawgit.com/feathericons/feather/v4.5.0/icons/tv.svg) | `<i-tv>` |
| ![twitter](https://cdn.rawgit.com/feathericons/feather/v4.5.0/icons/twitter.svg) | `<i-twitter>` |
| ![type](https://cdn.rawgit.com/feathericons/feather/v4.5.0/icons/type.svg) | `<i-type>` |
| ![umbrella](https://cdn.rawgit.com/feathericons/feather/v4.5.0/icons/umbrella.svg) | `<i-umbrella>` |
| ![underline](https://cdn.rawgit.com/feathericons/feather/v4.5.0/icons/underline.svg) | `<i-underline>` |
| ![unlock](https://cdn.rawgit.com/feathericons/feather/v4.5.0/icons/unlock.svg) | `<i-unlock>` |
| ![upload-cloud](https://cdn.rawgit.com/feathericons/feather/v4.5.0/icons/upload-cloud.svg) | `<i-upload-cloud>` |
| ![upload](https://cdn.rawgit.com/feathericons/feather/v4.5.0/icons/upload.svg) | `<i-upload>` |
| ![user-check](https://cdn.rawgit.com/feathericons/feather/v4.5.0/icons/user-check.svg) | `<i-user-check>` |
| ![user-minus](https://cdn.rawgit.com/feathericons/feather/v4.5.0/icons/user-minus.svg) | `<i-user-minus>` |
| ![user-plus](https://cdn.rawgit.com/feathericons/feather/v4.5.0/icons/user-plus.svg) | `<i-user-plus>` |
| ![user-x](https://cdn.rawgit.com/feathericons/feather/v4.5.0/icons/user-x.svg) | `<i-user-x>` |
| ![user](https://cdn.rawgit.com/feathericons/feather/v4.5.0/icons/user.svg) | `<i-user>` |
| ![users](https://cdn.rawgit.com/feathericons/feather/v4.5.0/icons/users.svg) | `<i-users>` |
| ![video-off](https://cdn.rawgit.com/feathericons/feather/v4.5.0/icons/video-off.svg) | `<i-video-off>` |
| ![video](https://cdn.rawgit.com/feathericons/feather/v4.5.0/icons/video.svg) | `<i-video>` |
| ![voicemail](https://cdn.rawgit.com/feathericons/feather/v4.5.0/icons/voicemail.svg) | `<i-voicemail>` |
| ![volume-1](https://cdn.rawgit.com/feathericons/feather/v4.5.0/icons/volume-1.svg) | `<i-volume-1>` |
| ![volume-2](https://cdn.rawgit.com/feathericons/feather/v4.5.0/icons/volume-2.svg) | `<i-volume-2>` |
| ![volume-x](https://cdn.rawgit.com/feathericons/feather/v4.5.0/icons/volume-x.svg) | `<i-volume-x>` |
| ![volume](https://cdn.rawgit.com/feathericons/feather/v4.5.0/icons/volume.svg) | `<i-volume>` |
| ![watch](https://cdn.rawgit.com/feathericons/feather/v4.5.0/icons/watch.svg) | `<i-watch>` |
| ![wifi-off](https://cdn.rawgit.com/feathericons/feather/v4.5.0/icons/wifi-off.svg) | `<i-wifi-off>` |
| ![wifi](https://cdn.rawgit.com/feathericons/feather/v4.5.0/icons/wifi.svg) | `<i-wifi>` |
| ![wind](https://cdn.rawgit.com/feathericons/feather/v4.5.0/icons/wind.svg) | `<i-wind>` |
| ![x-circle](https://cdn.rawgit.com/feathericons/feather/v4.5.0/icons/x-circle.svg) | `<i-x-circle>` |
| ![x-square](https://cdn.rawgit.com/feathericons/feather/v4.5.0/icons/x-square.svg) | `<i-x-square>` |
| ![x](https://cdn.rawgit.com/feathericons/feather/v4.5.0/icons/x.svg) | `<i-x>` |
| ![zap-off](https://cdn.rawgit.com/feathericons/feather/v4.5.0/icons/zap-off.svg) | `<i-zap-off>` |
| ![zap](https://cdn.rawgit.com/feathericons/feather/v4.5.0/icons/zap.svg) | `<i-zap>` |
| ![zoom-in](https://cdn.rawgit.com/feathericons/feather/v4.5.0/icons/zoom-in.svg) | `<i-zoom-in>` |
| ![zoom-out](https://cdn.rawgit.com/feathericons/feather/v4.5.0/icons/zoom-out.svg) | `<i-zoom-out>` |


### FAQ

...

### License

MIT © [Michael Bazos](mailto:micabazos@gmail.com)
