# UI Suite Base Recipe

A Drupal Recipe that provides a **complete starter setup for UI Suite
(component-based design)**.
This recipe installs and configures the core UI Suite ecosystem, allowing
developers to quickly adopt a **patterns-first, component-driven workflow**
based on UI Patterns, UI Skins, UI Icons, and UI Examples.

The goal of this recipe is to offer a **ready-to-use component design
foundation**, ideal for projects that want a modern front-end architecture with
reusable components, pattern libraries, and enhanced editorial tooling.

---

## 🚀 Features

- Installs all major **UI Patterns 2.x** ecosystem modules
- Enables **UI Skins** and **UI Icons** for enhanced presentation and theming
- Provides **UI Examples** for immediate learning and reference
- Prepares the site for a **component-based workflow** out of the box
- Ideal for **design systems**, **pattern libraries**, and **component-driven 
theming**

---

## 📦 Included Contrib Dependencies

This recipe requires the following contributed modules:

```json
{
  "drupal/ui_patterns": "^2.0",
  "drupal/ui_examples": "^1.0",
  "drupal/ui_skins": "^1.1@alpha",
  "drupal/ui_styles": "^1.19",
  "drupal/ui_icons": "^1.1@beta",
  "drupal/display_builder": "^1.0@alpha"
}
```

## 🔧 Modules Installed by This Recipe

The recipe installs all key building blocks necessary for a full UI Suite setup:

### 🧩 UI Patterns Core & Extensions
* `ui_patterns`
* `ui_patterns_blocks`
* `ui_patterns_field_formatters`
* `ui_patterns_layouts`
* `ui_patterns_library`
* `ui_patterns_views`
* `ui_patterns_field`
* `ui_patterns_ui`

### UI Styles & UI Skins
* `ui_styles`
* `ui_styles_block`
* `ui_styles_ckeditor5`
* `ui_styles_entity_status`
* `ui_styles_layout_builder`
* `ui_styles_ui_patterns`
* `ui_styles_library`
* `ui_styles_page`
* `ui_styles_views`
* `ui_skins`

### 🖼 UI Icons (Full Suite)
* `ui_icons`
* `ui_icons_field`
* `ui_icons_ckeditor5`
* `ui_icons_menu`
* `ui_icons_library`
* `ui_icons_picker`
* `ui_icons_text`
* `ui_icons_patterns`
* `ui_icons_media`
* `ui_icons_font`

### 📚 UI Examples
* `ui_examples`
* `ui_examples_defaults`

### Display builder
* `display_builder`
* `display_builder_entity_view`
* `display_builder_page_layout`
* `display_builder_views`
* `display_builder_ui`

## 📘 What This Recipe Provides

By installing this recipe you get:

**✔ Ready-to-use component system**

Patterns, fields, layouts, blocks, and views integration.

**✔ Enhanced editorial UX**

Settings UI, field groups, icon pickers, and pattern-driven content editing.

**✔ A design-system-friendly architecture**

Skins, styles, icon libraries, and reusable components.

**✔ Example patterns & templates**

UI Examples module provides reference implementations.

## 🛠 Installation
Install the recipe in your Drupal project using ddev (web as docroot):

    # Install the recipe dependencies using composer.
    ddev composer require bkhouy/ui-suite-base
    # Apply the recipe.
    ddev exec -d /var/www/html/web php core/scripts/drupal recipe ../recipes/ui-suite-base

## 📄 License

This recipe follows the licensing terms of the included Drupal modules.

## 📬 Maintainers

* [Brahim KHOUY](https://www.drupal.org/u/bkhouy)
