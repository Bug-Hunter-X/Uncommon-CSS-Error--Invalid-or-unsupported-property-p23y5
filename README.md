# Uncommon CSS Error: Invalid or unsupported property

This repository demonstrates a common yet sometimes elusive CSS bug related to using invalid or unsupported properties.  This can stem from incorrect vendor prefix usage (like `-webkit-`, `-moz-`, etc.) or employing properties that are no longer part of the CSS specification.  The problem often manifests as unexpected rendering or layout issues that are difficult to trace.

The `bug.css` file contains the erroneous CSS.  `bugSolution.css` provides the corrected code.

**Key Learning:**
* Always verify property support across target browsers.  Use tools like caniuse.com to check compatibility.
* Avoid deprecated properties; replace them with their modern equivalents.
* Double-check vendor prefix usage. Often, unprefixed versions are now widely supported.