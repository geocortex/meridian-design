---
title: Design Language
---

import Icons from "../src/components/icons";

## Whitespace/Padding

Lorem ipsum dolor sit amet, consectetur adipiscing elit. Aliquam nec commodo elit. Curabitur dui nulla, vulputate id rutrum sed, maximus consequat eros. Nullam pharetra urna quis sapien tincidunt, et iaculis mauris ornare. Vestibulum convallis et felis at lobortis. Nulla bibendum vel quam quis accumsan.

---

## Buttons

We have various buttons options of differing importance and loudness.

### Default

Standard buttons with the last three being deactivated.
![buttons](/img/buttons/default.png "Default Buttons")

### Outlined Variant

Outlined buttons with the last three being deactivated.
![buttons](/img/buttons/outlined.png "Outlined Buttons")

### Text Variant

![buttons](/img/buttons/text.png "Text Buttons")

### Icon Button

![buttons](/img/buttons/icon.png "Icon Button") ![buttons](/img/buttons/icon-hover.png "Icon Button Hover State")

### Toggle Buttons

![buttons](/img/buttons/toggle.png "Toggle Buttons")

### Grouped Buttons

![buttons](/img/buttons/grouped-default.png "Grouped Buttons") ![buttons](/img/buttons/grouped-outlined.png "Outlined Grouped Buttons")

---
## Form Design
A properly designed form allows people to quickly enter values in a logical order and in a manner that makes sense to them. This requires fields to be flexible when interpreting the user's input.
### Labels
* Are easily interpreted
* Located on top of or to the left of most fields
  * Labels on the top is better for internationalization and long strings
* Usually appear to the right of check boxes and radio buttons
* Ensure there is not too much space between the label and it's associated field so that it is clear which field goes with the label

### Fields
* The length of text fields should suggest the amount of data that should be entered
* Ensure that there is not too much space between fields so that nothing gets accidentally overlooked.

### Links/Buttons
* Primary actions should be clear and obvious
* Secondary actions are for more discrete actions
* Multi-step and complex forms should have all other navigation removed
  * Back links should be included for easy corrections in multi-step forms
* Include a *Cancel* link to provide a safety net for users to escape the form

### Keyboard Use
* Do not force users to frequently switch between the keyboard and mouse
* Correct tab order is set up
* If possible, avoid drop-down lists where typing is quicker
  * Auto-complete or auto-suggest is very beneficial
### Be Helpful
* Be flexible when interpreting the values that users enter
  * Eg: when entering a phone number, accept both no-spaces and dashes
* Help users check the information they've entered before submitting
  * [WCAG 3.3.4](https://www.w3.org/TR/WCAG21/#error-prevention-legal-financial-data) requires error prevention for legal and financial data so that it is reversible, checked for errors, and confirmed.
* If possible, provide confirmation or error information where the user's attention is currently via immediate inline feedback
* If possible, try to avoid multiple columns for form layouts. This increases the likelihood that something in the right column will be missed.
  * Usability testing <sup>[\[1\]](https://baymard.com/blog/avoid-multi-column-forms) [\[2\]](https://cxl.com/research-study/form-field-usability/)</sup> has shown that multi-column forms do not perform as well as single column layouts.
* Remove any unnecessary distractions and links that competes with and takes the users attention away from the form they are filling out.

---

## Icons

### Where can I find the Icons?

Our master repository of icons, consists of over 600 pre-created icons ready for use in our icon package. Instructions on how to install packages can be found in our **<a href="https://developers.geocortex.com/docs/web/sdk-reference-third-party-libraries/#installing-packages" target="_blank">Developer Center</a>**. We store all our icons in this online repository, in several formats (png, svg, pdf). The .svg format icons are comprised of compound paths, black #000000), and an artboard of 24px by 24px. They have been stripped of all unnecessary meta info and optimized using the SVGo optimization script included in the repo.

### How do I use icons in my app?

Instructions for using either built in icons, or your own, can be found in the **<a href="https://developers.geocortex.com/docs/web/sdk-adding-icons/#next-steps" target="_blank">Developer Center</a>**.

### How do I create a custom icon?

When creating our icons, simplicity is key. Since we are working with a canvas of only 24px x 24px, every design provided must be concise and communicate the idea clearly, and easily. Fine details are less important than trying to ensure that shapes stay recognizable. Information regarding this process is available in our **<a href="https://developers.geocortex.com/docs/web/sdk-components-styling" target="_blank">Developer Center information</a>**.

#### Style

The visual language of our icons should be consistent, creating a harmonious appearance across all of our products:

-   All icons must be made using a single color (black), with negative space being transparent.
-   When employing linework, trying to maintain at least 2 pixels in width, with an equal amount of white space allows the designs to remain clear when viewed at 100%. This guideline is flexible however, depending on what elements are used.
-   Modifiers must be placed in the bottom right of the icon, with a border of 2px of empty space outlining it.
-   Simplistic, clear, and simple designs are preferable to complicated patterns.
-   The visual loudness of the icon should convey its importance, but not overpower other messages surrounding it, including the written identifier.

### Available Icons

<!--DOCUSAURUS_CODE_TABS-->
<!--JavaScript-->

<script>
  import icons from "../src/components/icons" import ReactDOM from "react-dom"
  ReactDom.render (icons, document.getElementById("IconsAttachPoint"));
</script>

<!--END_DOCUSAURUS_CODE_TABS-->

<Icons />

---

## Lists

Lorem ipsum dolor sit amet, consectetur adipiscing elit. Aliquam nec commodo elit. Curabitur dui nulla, vulputate id rutrum sed, maximus consequat eros. Nullam pharetra urna quis sapien tincidunt, et iaculis mauris ornare. Vestibulum convallis et felis at lobortis. Nulla bibendum vel quam quis accumsan.

### Simple List

![list](/img/list/simple.png "Simple List")

### Selected Item

![list](/img/list/selected-item.png "Selected Item List")

### Nested List

![list](/img/list/nested.png "Nested List")

### Menu List

![list](/img/list/menu.png "Menu List")

### List Controls

![list](/img/list/list-controls.png "List Controls")
![list](/img/list/list-controls-checkbox.png "List Controls (checkbox)")
![list](/img/list/list-controls-toggle.png "List Controls (toggle)")

### Pinned Subheader List

## ![list](/img/list/pinned-subheader.png "Pinned Subheader List")

## States

Lorem ipsum dolor sit amet, consectetur adipiscing elit. Aliquam nec commodo elit. Curabitur dui nulla, vulputate id rutrum sed, maximus consequat eros. Nullam pharetra urna quis sapien tincidunt, et iaculis mauris ornare. Vestibulum convallis et felis at lobortis. Nulla bibendum vel quam quis accumsan.

### Hover

Lorem ipsum dolor sit amet, consectetur adipiscing elit. Aliquam nec commodo elit. Curabitur dui nulla, vulputate id rutrum sed, maximus consequat eros. Nullam pharetra urna quis sapien tincidunt, et iaculis mauris ornare. Vestibulum convallis et felis at lobortis. Nulla bibendum vel quam quis accumsan.

### Focus

Lorem ipsum dolor sit amet, consectetur adipiscing elit. Aliquam nec commodo elit. Curabitur dui nulla, vulputate id rutrum sed, maximus consequat eros. Nullam pharetra urna quis sapien tincidunt, et iaculis mauris ornare. Vestibulum convallis et felis at lobortis. Nulla bibendum vel quam quis accumsan.

### Selected/Active

Lorem ipsum dolor sit amet, consectetur adipiscing elit. Aliquam nec commodo elit. Curabitur dui nulla, vulputate id rutrum sed, maximus consequat eros. Nullam pharetra urna quis sapien tincidunt, et iaculis mauris ornare. Vestibulum convallis et felis at lobortis. Nulla bibendum vel quam quis accumsan.

---

## Tabs

### Normal Tabs

![tabs](/img/tabs/normal.png "Normal Tabs")

### Scrollable Tabs

![tabs](/img/tabs/scrollable.png "Scrollable Tabs")

### Icon Tabs

![tabs](/img/tabs/icon.png "Icon Tabs")

### Indicator Color Tabs

![tabs](/img/tabs/indicator.png "Indicator Tabs")

### Tab Adornments

![tabs](/img/tabs/adornments.png "Adornments Tabs")

---

## Menus

Lorem ipsum dolor sit amet, consectetur adipiscing elit. Aliquam nec commodo elit. Curabitur dui nulla, vulputate id rutrum sed, maximus consequat eros. Nullam pharetra urna quis sapien tincidunt, et iaculis mauris ornare. Vestibulum convallis et felis at lobortis. Nulla bibendum vel quam quis accumsan.

![menus](/img/menus/menu.gif "Toggle Buttons")

---

## Dialogs

![dialog](/img/dialogs/dialog.png "Dialog")

## Panels & Panel Navigation

---
