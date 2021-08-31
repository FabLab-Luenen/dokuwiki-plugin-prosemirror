# Visual Editor for DokuWiki

![Visual Editor logo (graphic design is my passion)](https://i.imgur.com/T2Z4gKp.png)

Polished-up version of [cosmocode/dokuwiki-plugin-prosemirror](https://github.com/cosmocode/dokuwiki-plugin-prosemirror), part of the [dokuwiki-preconfigured](https://github.com/fablab-luenen/dokuwiki-preconfigured/) project. 

The main aim of this fork is to make the editing experience as seamless as possible. This mostly means getting rid of small annoyances. I probably won't do any serious work on the actual core, since that is already quite solid. Thanks to Cosmocode for doing the hard part!

![Visual Editor demonstration. Entering edit mode, scrolling down, changing a bit of formatting, saving](https://i.imgur.com/BggrlRZ.gif)

## Installation

Extension Manager -> Manual install with URL `https://github.com/fablab-luenen/dokuwiki-visual-editor/zipball/release` (or manually extract it into `/lib/plugins/prosemirror`). 

## Good to know

In case your theme has a fixed header, you can configure the toolbar to stick below it while scrolling with the following CSS in userstyle.css:

```
/* Make menubar stick below header */
.editBox .prosemirror_wrapper .menubar {
	top: 5em; /* Height of your header */
}
```

