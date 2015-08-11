# BootstrapThemer

**A Reactive Bootstrap Theme Editor for Meteor**

BootstrapThemer reactively compiles [Bootstrap 3](https://github.com/twbs/bootstrap) with user-defined custom variables and delivers the CSS to clients, who will have their stylesheets updated without refreshing their browser.

The [Bootstrap Magic](https://github.com/hitchcott/meteor-bootstrap-magic) package is implemented to allow easy editing of all of Bootstrap 3's LESS variables.

BootstrapThemer comes bundled with several [Bootswatch](https://github.com/thomaspark/bootswatch/) themes.

## Quickstart

If you already use a bootstrap 3 package, remove it.

Install using `meteor add tap:bootstrap-themer`

Include the editor template somewhere in your project `{{> BootstrapThemer}}`

## Features

* Theme Presets and Switching - Includes bootstswatch themes
* On-the-fly css updates to all clients without refreshing their browser
* Super-detailed tweaking without CSS knowledge using Bootsrap variables
* Free-type custom CSS overrides
* BootstrapMagic+ Theme Editor (with enhanced UI)

## Todo


```
- Custom Theme Creation and Saving + Routes
- Themes CRUD
- Ability to 'clone' with custom vars (new theme)
- FastRender integration
- IronRouter integration (route-based themes)
- Security for updating themes (use collection-hooks on server instead of methods, access control with regualr publish/subscribe)
- Font Uploads - TAPmedia integration
- FontAwesome Support
- Export bootswatch file
- i18n
```

## License

MIT 2014

## Credits / Packages Used

* Bootstrap
* Bootstrap Magic
* Bootswatch
* LESS Compiler
* Collection Hooks

Created by [Chris Hitchcott](http://github.com/hitchcott) for [TAPevents](http://tapevents.com).