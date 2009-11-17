# Reset stylesheet, for HTML5. #

By [Christopher Boone][1].

The [reset][2] stylesheet turns off most of the default presentational styles that browsers provide. Not everything, because some of them are unlikely to be replaced in any site's stylesheets, and some of them are useful. It also declares some basic styles -- `font-size` and `line-height`, for instance.

In addition, the stylesheet declares some basic display styles for [the new HTML5 elements][3], which browsers aren't fully up to speed on.

This stylesheet is based primarily on [Eric Meyer's reset.css][4] (version 1.0 | 20080212) and [YUI's CSS Reset][5] (version 3.0, build 1549), as well as on my own experience. The HTML5 styles are based on [the rendering suggestions contained in the November 13, 2009, draft standard][6], and [the CSS I extracted][7] from that lengthy document.


## Notes. ##

- Only [HTML5 elements][8] are dealt with here. [Deprecated elements][9] are not affected.
- I've added the `details` element to the list of those declared to be block level, since I think it must be, [per the description][9].
- Probably not all the CSS declared here is actually supported by browsers. (For example, [`display: ruby`][10].)

Feel free to use this in any way. And please let me know if I've made any mistakes, or if there any improvements I could make. Thanks.


## Bibliography. ##

Christopher Boone. [Announcement on the Hypsometry Blog.][11]

&mdash;&mdash;. [HTML5 default styles.][7]

Eric Meyer. [Reset.css.][4]

Web Hypertext Application Technology Working Group (WHATWG). [HTML5 Draft Standard, 13 November 2009, &sect;11 Rendering.][6]

Yahoo User Interface (YUI) Library Project. [CSS Reset.][5]


[1]: http://hypsometry.com
[2]: http://github.com/cboone/hypsometric-css/blob/master/reset/reset.css
[3]: http://www.w3.org/TR/html5-diff/#new-elements
[4]: http://meyerweb.com/eric/tools/css/reset
[5]: http://developer.yahoo.com/yui/3/cssreset/
[6]: http://www.whatwg.org/specs/web-apps/current-work/multipage/rendering.html
[7]: http://github.com/cboone/hypsometric-css/blob/master/html5/html5-defaults.css
[8]: http://www.whatwg.org/specs/web-apps/current-work/multipage/semantics.html#semantics
[9]: http://www.whatwg.org/specs/web-apps/current-work/multipage/interactive-elements.html#the-details-element
[10]: http://blog.whatwg.org/implementation-progress-on-the-html5-ruby-element
[11]: http://blog.hypsometry.com/articles/reset-stylesheets-and-html5/
