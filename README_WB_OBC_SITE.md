Enhancements for WB OBC Website

What I added
- `enhancements.js`: injects a missing timeline search input and a set of filter buttons, and wires filtering behavior for `.tl-event` items.

How to use
1. Place `enhancements.js` in the same folder as your site HTML (or serve it from your site server).
2. Add the following just before `</body>` in your HTML (for example in WB_OBC_Website.html):

<script src="enhancements.js"></script>

Notes & next steps
- The script is non-destructive: it will add UI only if missing.
- If you want me to, I can: replace the placeholder comment blocks with real inventory tables, inline-critical CSS, or bundle the site as a static folder ready for hosting.
