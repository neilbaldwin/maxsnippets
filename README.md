# maxsnippets
VSCode Snippets for Cycling 74's Max visual programming language

Some Snippets for VSCode that provide a basic (and 'fake') code completion for Javascript in Max.

### Installation

As the APIs are Javascript-based, the Snippets need to either replace any existing Javascript Snippets you have created/installed or you could also edit your existing Javascript Snippet file then copy-and-paste the contents of the .snippet file here in the 'maxsnippets' folder.

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
