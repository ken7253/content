---
title: Firefox 131 for developers
slug: Mozilla/Firefox/Releases/131
page-type: firefox-release-notes
---

{{FirefoxSidebar}}

This article provides information about the changes in Firefox 131 that affect developers. Firefox 131 is the current [Beta version of Firefox](https://www.mozilla.org/en-US/firefox/channel/desktop/#beta) and ships on [October 1, 2024](https://whattrainisitnow.com/release/?version=131).

## Changes for web developers

### Developer Tools

### HTML

#### Removals

### CSS

#### Removals

### JavaScript

#### Removals

### SVG

#### Removals

### HTTP

- A {{httpheader("Set-Cookie")}} HTTP header with the attribute value of [`SameSite=None`](/en-US/docs/Web/HTTP/Headers/Set-Cookie#none) must now also include the [`Secure`](/en-US/docs/Web/HTTP/Headers/Set-Cookie#secure) attribute. This ensures that cookies set with `SameSite=None` are only ever sent over HTTPS channels. ([Firefox bug 1909673](https://bugzil.la/1909673)).

#### Removals

### Security

#### Removals

### APIs

- [Text fragments](/en-US/docs/Web/URI/Fragment/Text_fragments) are now supported, allowing users to link to and highlight specific portions of text in a web page. This feature uses a particular syntax in the [URL fragment](/en-US/docs/Web/URI/Fragment) that identifies the target based on patterns in the rendered text.
  Website developers can also use the existence of the {{domxref("Document.fragmentDirective")}} property (an instance of the {{domxref("FragmentDirective")}} interface) to feature check for text fragment support, and the {{CSSxRef("::target-text")}} pseudo element to select and style text that has been selected using a text fragment link. ([Firefox bug 1914877](https://bugzil.la/1914877))

#### DOM

#### Media, WebRTC, and Web Audio

#### Removals

### WebAssembly

#### Removals

### WebDriver conformance (WebDriver BiDi, Marionette)

#### General

#### WebDriver BiDi

#### Marionette

## Changes for add-on developers

### Removals

### Other

## Experimental web features

These features are newly shipped in Firefox 131 but are disabled by default. To experiment with them, search for the appropriate preference on the `about:config` page and set it to `true`. You can find more such features on the [Experimental features](/en-US/docs/Mozilla/Firefox/Experimental_features) page.

- **Regular expression (?ims-ims:...) modifiers:** `javascript.options.experimental.regexp_modifiers`

  The [(?ims-ims:...)](/en-US/docs/Web/JavaScript/Reference/Regular_expressions/Modifier) regular expression modifiers allow you to make changes to only take effect in a specific part of a regex pattern. ([Firefox bug 1899813](https://bugzil.la/1899813)).

## Older versions

{{Firefox_for_developers}}
