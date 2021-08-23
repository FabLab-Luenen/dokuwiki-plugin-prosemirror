![Visual Editor logo (graphic design is my passion)](https://i.imgur.com/T2Z4gKp.png)

# Visual Editor for DokuWiki

Polished-up version of [cosmocode/dokuwiki-plugin-prosemirror](https://github.com/cosmocode/dokuwiki-plugin-prosemirror). 

The main aim of this fork is to make the editing experience as seamless as possible. This mostly means getting rid of small annoyances. I probably won't do any serious work on the actual core, since that is already quite solid. Thanks to Cosmocode for doing the hard part!

![Visual Editor demonstration. Entering edit mode, scrolling down, changing a bit of formatting, saving](https://i.imgur.com/BggrlRZ.gif)

## Good to know

In case your theme has a fixed header, you can configure the toolbar to stick below it while scrolling with the following CSS in userstyle.css:

```
/* Make menubar stick below header */
.editBox .prosemirror_wrapper .menubar {
	top: 5em; /* Height of your header */
}
```

