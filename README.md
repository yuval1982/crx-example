# crx-example
take this basic manifest's code and play with it:

{
  "manifest_version": 2,
  "name": "your extension’s name",
  "description": "This extension does bla bla bla",
  "version": "1.0",
  "icons": {"128": "icon.png"},
  "browser_action": {
    "default_icon": "icon.png",
    "default_popup": "popup.html"
  },
  "permissions": [  ] // no need at the moment, this ext knows nothing
}

now create your icon.png with Paint or get it from the web. make it 128px sqaure.

create an html file with a simple 'hello world' or something.

all these files should be in the same folder.

go to chrome://extensions
check the 'developer mode' checkbox
press 'load unpacked extentions' and choose the folder.

that's it. PUSH THE BUTTON!!!
