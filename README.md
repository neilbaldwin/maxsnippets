# maxsnippets

Some Snippets for VSCode that provide a basic (and 'fake') code completion for Javascript in Max. Very much WIP!

### Installation

As the APIs are Javascript-based, the Snippets need to either replace any existing Javascript Snippets you have created/installed or alternatively you could edit your existing Javascript Snippet file then copy-and-paste the contents of the "javascript.json" file here in the 'maxsnippets' folder. Note: I obviously can't know if any of the Snippet IDs or Prefixes will conflict with any of your existing Snippets.

To edit/create a Snippet file for Javascript, in VSCode go to Preferences->Configure User Snippets and then select "javascript.json".

### Details

The API information and descriptions are taken from the very excellent Max resouce by Tim Schenk:

http://max-javascript-reference.tim-schenk.de/#gsc.tab=0

As of the initial release these are far, far from complete. I started this as a way to learn the JSUI and Mgraphics APIs so that's what I've initially concentrated on. I'll likely expand it, eventually and gradually, to encompoass the 'Max' API and 'Max For Live' API:

http://max-javascript-reference.tim-schenk.de/symbols/max.html

http://max-javascript-reference.tim-schenk.de/symbols/LiveApi.html

### Snippets as "code completion"?

It's a terrible fudge as I don't have the time or inclination to get involved in making proper code completion for Max (though if someone would they would be a total hero to many!). I basically made snippets with multiple Prefix triggers so that you can sort of type in a keyword such as 'line' and it will display all the commands to do with 'line' in the Mgraphics library (for example). The Snippet choices also contain basic descriptions from Tim Schenk's Max resource and also will fill out the structure of commands/function with placeholder names to give you a hint on how to use them.

### Contribution

Contributions, feedback and suggestions are VERY welcome!

### Warranty

None. Nope. Use at your own risk as I can't promise it won't break anything in the case that you have existing Snippet files in use. It also won't teach you how to code Max but it might help with remembering many of the API commands/functions!

