# Watson IoT's Carbon Theme Mixin

The Carbon design system uses [themeing](https://next.carbondesignsystem.com/guidelines/themes/#themes-are-used-to-customize-component-styles-to-fit-the-specific-aesthetic-of-a-brand-or-product) for customization of CSS properties. The wiot-theme partial creates the mixin that will override the default theme applied to the Carbon component library.

## Usage

First install the wiot-theme package from NPM.

```
Yarn add wiot-theme
```

Once installed import the mixin partial sass file and include the mixin before importing any carbon files.

```
@import 'wiot-theme/scss/wiot-theme';
@include WatsonIotTheme();
```
