# Building Accessible Web Apps with ArcGIS Maps SDK for JavaScript and Calcite Design System

Presented at the 2023 Esri Developer Summit by [Kelly Hutchins](https://github.com/kellyhutchins) and [Kitty Hurley](https://github.com/geospatialem) on Tuesday, March 7, 2023 in Palm Springs, California.

## JS Maps SDK Demos

- [Prefers reduced motion](demos/PrefersReducedMotion.html): Disable animation when `prefers-reduced-motion` is active.
- [Search focus](demos/SearchFocus.html): Handle focus switch between the search and the search results popup.
- [Focus popup on open](demos/PopupFocus.html): Use the `shouldFocus` option on `Popup.open`.
- [Map description](demos/MapDescription.html): Add a description to the map using `aria-describedby`.
- [High contrast basemap with BasemapToggle](demos/HighContrastBasemapToggle.html): Toggle between the light and dark high contrast basemaps using the BasemapToggle widget.
- [Map Navigation](demos/MapNavigation.html) Demonstrate one option for navigating map data via the keyboard. Also shows how to use [Aria Live Regions](https://developer.mozilla.org/en-US/docs/Web/Accessibility/ARIA/ARIA_Live_Regions) to update assistive technology about dynamic changes.

## Calcite Demos

- [Contrast (Enhanced) with Calcite](demos/CustomCalciteIconColor.html): Provide Web Content Accessibility Guidelines (WCAG) Level AAA enhanced contrast to your Calcite apps.
- [Dynamically add an external link icon to Calcite Links](demos/DynamicallyAddExternalIcon.html): Dynamically add context to assistive technologies and an accompanying Calcite Icon.
- [Reduced motion support with Calcite Loader](demos/ReducedMotionSupportCalciteLoader.html): Calcite disables animation when system animations are disabled.
- [High Contrast with Calcite Dropdown](demos/HighContrastWithCalciteDropdown.html): Calcite enables high contrast colors when enabled on the system.
- [Apply core concepts tutorial](demos/CalciteApplyCoreConcepts.html): Tutorial showcased with Color Oracle tool.
