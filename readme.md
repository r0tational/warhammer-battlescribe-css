This CSS adds a Kill Team flavour for Battlescribe's standard HTML output, and is designed to be more practical for reference printouts during games.

It looks like this when printed (with Minion/Gunplay fonts)

![](https://github.com/r0tational/killteam-battlescribe/blob/master/print-page.png)

To be clear, I'm neither a designer nor a web developer, so I'm making no claims for how good it is! And I'm not promising to offer any support. But please feel free to use at your discretion and, of course, adapt/amend to your heart's content!

Here's what to do:

1. Grab the replacement CSS [from here](https://github.com/r0tational/killteam-battlescribe/blob/master/killteam-battlescribe.css)
2. Use Battlescribe to generate an HTML file and open in a text editor
3. Copy the full text of my CSS
4. Paste it into the HTML file, replacing everything between and including the `<style>` and `</style>` tags
5. Save the HTML and view/print it in a web browser. Chrome recommended (haven't tested Firefox, Safari won't print columns). Ensure the Background Graphics option is checked in the print dialog.

It displays in two ways. On your screen it should appear as a single column and be fairly clear to reference on a tablet during a game. Print it out, however, and it switches to a two-column view with smaller text.

Some quick notes (see above about making no claims):

- If you have them installed, the CSS will use Minion Pro and Gunplay fonts for the full, authentic, Kill Team experience. Minion is a premium font, but Gunplay is free to download via [http://typodermicfonts.com/gunplay/](http://typodermicfonts.com/gunplay/). Otherwise, it'll default to a Gunplay-like font from Google Fonts and Times, which I've found sufficiently compact and Kill Team-y.
- There are page break rules to prevent entries from splitting over columns and pages. I optimised it for keeping specialists, leaders/commanders/fire teams on single pages, but I haven't tested it extensively. The first page will be almost empty, and models with long lists of rules might break over pages and generally look terrible, but I've done what I can to make it practical.
- At the moment, the new Elites Kill Team creed rule description appears right at the end of the document. It would be way better if it displayed at the top! But because it's hardcoded into Battlescribe's HTML output, I can't (or don't know how to) move it with pure CSS.
Anyway, hope it's useful! And please feel free to share any improvements with the community!
