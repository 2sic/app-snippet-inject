<image src="app-icon.png" align="right" width="200px">

# Snippet Inject 3 App for .net CMSs

> This is a [2sxc](https://2sxc.org) App for [DNN ☢️](https://www.dnnsoftware.com/) and [Oqtane 💧](https://www.oqtane.org/)

An app to quickly inject any js / css / html to your page

| Aspect              | Status | Comments or Version
| ------------------- | :----: | -------------------
| 2sxc                | ✅    | requires 2sxc v17.07.00
| Dnn                 | ✅    | For v9.6.1+
| Oqtane              | ✅    | Requires v05.00+
| No jQuery           | ✅    | 
| Live Demo           | ➖    |
| Install Checklist   | ✅    | See [Installation](https://azing.org/2sxc/r/fT9O-8LH) on [azing.org](https://azing.org/2sxc)
| Source & License    | ✅    | included, ISC/MIT
| App Catalog         | ✅    | See [app catalog](https://2sxc.org/en/apps/app/snippet-inject-v3-hybrid-for-dnn-and-oqtane)
| Screenshots         | ✅    | See [app catalog](https://2sxc.org/en/apps/app/snippet-inject-v3-hybrid-for-dnn-and-oqtane)
| Best Practices      | ✅    | Uses v13.10 conventions
| Bootstrap 3         | ❌    | Last supported in v03.21.00
| Bootstrap 4         | ❌    | Last supported in v03.21.00
| Bootstrap 5         | ✅    | no optimizations needed

## Customize the App

There are no app settings and only one app resource you can change.

If you want to customize the CSS, you will usually follow the ["Create Custom Styles in a Standard 2sxc App" checklist](https://azing.org/2sxc/r/gg_aB9FD).
But note that you usually don't want to do this, as added snippets should just be as-is

## History

* v03.21.01 2026-10
  * Removed Bootstrap 3 and Bootstrap 4 support; the app is now Bootstrap 5 only
  * For Bootstrap 3 or Bootstrap 4, use v03.21.00

* v.03.00 2021-10
  * Upgrade to v12.05 conventions
  * Switched all injects to use Razor
  * Reduced views to a single file
* v03.01 2022-05
  * Activated Lightspeed
* v03.02 2022-06
  * Replaced all base classes with their 2sxc 14 equivalend 
* v03.03 2023-05
  * Removed _ from Filenames
  * Replace Edit.Toolbar with `@Kit.Toolbar.Default`
* v03.04.00 2023-07
  * 2sxc 16.02 coding conventions
  * everything typed
* v03.17.00 2023-07
  * strong Typed
  * Auto Generated Class
* v03.17.01 2024-0
  * Update app.sln and app.csproj