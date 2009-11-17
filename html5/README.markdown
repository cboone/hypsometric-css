# HTML5 default styles. #

By [Christopher Boone][1].

The [html5-defaults][3] stylesheet contains the basic CSS styles that [the latest -- November 13, 2009 -- draft standard of HTML5][4] recommend that browsers use. I compiled it from the examples in [&sect;11 Rendering of the draft standard][2].


## Notes. ##

- I've removed all references to [elements][5] and [attributes][6] that have been deprecated in HTML5.
- There are additional rendering instructions in the spec that cannot be represented in abstract CSS.
- Probably not all the CSS declared here is actually supported by browsers.
- I've left out all [the element bindings][7], since I believe [only Mozilla supports that functionality][8], and it currently
only supports it in a proprietary way.
- I've added the `details` element to the list of those declared to be block level, since I think it must be, [per the description][9].

Feel free to use this in any way. And please let me know if I've made any mistakes, or if there any improvements I could make. Thanks.


## Bibliography. ##

Web Hypertext Application Technology Working Group (WHATWG). [HTML5 Draft Standard, 13 November 2009, &sect;11 Rendering.][2]

World Wide Web Consortium (W3C). [HTML 5 differences from HTML 4, Working Draft, 25 August 2009.][10]


[1]: http://hypsometry.com
[2]: http://www.whatwg.org/specs/web-apps/current-work/multipage/rendering.html
[3]: http://github.com/cboone/hypsometric-css/blob/master/html5/html5-defaults.css
[4]: http://www.whatwg.org/specs/web-apps/current-work/multipage/index.html
[5]: http://www.w3.org/TR/html5-diff/#absent-elements
[6]: http://www.w3.org/TR/html5-diff/#absent-attributes
[7]: http://www.whatwg.org/specs/web-apps/current-work/multipage/rendering.html#bindings
[8]: https://developer.mozilla.org/En/CSS/-moz-binding
[9]: http://www.whatwg.org/specs/web-apps/current-work/multipage/interactive-elements.html#the-details-element
[10]: http://www.w3.org/TR/html5-diff/
