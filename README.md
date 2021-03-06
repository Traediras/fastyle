# fastyle
Chrome and Firefox extension to restyle and enhance FurAffinity.net

### Wait No Longer!
If you cry yourself to sleep at night wondering if FA is *ever*
going to update their UI, cry no more! Your prayers have been
answered!

The **FAStyle** Extension restyles and enhances FurAffinity.net
with [Bootstrap](http://getbootstrap.com/) and [jQuery](http://jquery.com/)
so you can stay furry without being trapped in the Internet of the 90s.

### Highlight Features

* **Infinite Scroll** for *all* galleries (front page, browsing, searching, personal galleries, scraps, favorites, and new submissions)
* **Asynchronous Actions** -- when you click "Watch" or post a comment, it happens right then and there, no page reload!
* A cleaner, sleeker, and more visual experience with an emphasis on content.
* Much more!

### Firefox Setup
A precompiled `.xpi` file is included in this repo for easy support with
Firefox! This is all you have to do:

1. **Clone** or **[Download](https://github.com/CopperBadger/fastyle/archive/master.zip)** this repo.
2. In Firefox, press <kbd>Ctrl</kbd>+<kbd>O</kbd> / <kbd>Cmd</kbd>+<kbd>O</kbd> and select `fastyle-moz.xpi`
3. Follow the prompts to install the Add-On.
4. That's it! [Go to FA](http://www.furaffinity.net/) and enjoy!

### Chrome Setup
Setup for FAStyle from source is super easy:

1. **Clone** or **[Download](https://github.com/CopperBadger/fastyle/archive/master.zip)** this repo.
2. In Chrome, go to **chrome://extensions** (or just open your extensions page through the browser's settings menu).
3. Enable **Developer Mode** and select **Load Unpacked Extension**.
4. Select the *directory* containing the cloned / downloaded repo.
5. The extension should appear in your list of extensions. Enable it and [browse FA](http://www.furaffinity.net/)!

Google's introductory documentation on writing extensions is just
about all you'll have to know (aside from jQuery and Bootstrap, of
course) if you want to play around with the code, and can be found
here:

* <https://developer.chrome.com/extensions/getstarted>
* <https://developer.chrome.com/extensions/content_scripts>

### Using Other Themes (including Dark Themes)

Switching themes isn't yet supported in the Firefox Add-On, but it's
on it's way!

Since FAStyle is bulit on Bootstrap, it is compatible with all 16 of the
[wonderful and free bootswatch themes](http://bootswatch.com/), most of
which have been included in this repository in the `lib/css` directory.
Eventually, you will be able to change the theme of the extension through
a toolbar dropdown, but you can always change it manually.

Changing the theme isn't hard! Just do this:

1. Open **manifest.json**
2. Change `lib/css/united/bootstrap.min.css` (should be around line 17) to `lib/css/(theme)/bootstrap.min.css`, where (theme) is the name of the theme you want to use
3. Reload **chrome://extensions** by pressing the "Reload" link or using <kbd>Ctrl</kbd>+<kbd>R</kbd> / <kbd>Cmd</kbd>+<kbd>R</kbd>.
4. Reload FA to see the new theme!

Specifically **cyborg**, **darkly**, **slate**, and **superhero** are all
darker themes. (Superhero looks a lot like FA's original style, if you're
partial to the blue theming)

### Alpha Disclaimer and Warranty
FAStyle is still in development! There are still a good number of
To-Dos to take care of before the extension can be considered ready
for public use, but that doesn't mean it'll take very long. If you
choose to check out FAStyle (*and you really should!*), be prepared
for a few rough edges or otherwise untouched areas of the site.

This extension comes with no guarantee. Because it depends on the
structure of FA's markup, the extension will have to be updated
if said markup ever changes.

If you're a web developer and would like to help make / keep the
extention future-proof, please don't hesitate to ask about pitching
in! Just send me an email at [thecopperbadger@gmail.com](mailto:thecopperbadger@gmail.com).
