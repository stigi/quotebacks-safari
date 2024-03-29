# Quotebacks - Safari Extension

This repo wraps the [quoteback extension](https://github.com/Blogger-Peer-Review/quotebacks) (or rather a [fork](https://github.com/stigi/quotebacks/) of it) in a Safari Web extension.

## Status

> [!WARNING]  
> This project is still work in progress and might change before an official release

## Demo

![demo](screenshots/00-demo.gif)

Also check out the [screenshots](screenshots).

## Changes to the Chrome/Firefox extension

- [@5d085662](https://github.com/stigi/quotebacks@5d0856629fb60eefe0aa2f7562bb307b5bf7af24) - Fix for Safari not invoking callback when sending ping message
- [df98e298c](https://github.com/stigi/quotebacks@df98e298c1475d144cb4892d741b05f3ba284d8f) - Dynamically update shortcut shown in Options

## Todos

- Prepare and release:
  - Mention Safari with `alt+s` shortcut on https://quotebacks.net/welcome.html
  - Possibly remove references to Chrome and Firefox when running on Safari (might be necessary for AppStore 🤡)
  - Coordinate with original quoteback authors about release & merge Safari changes upstream
  - Sign and Submit to the AppStore