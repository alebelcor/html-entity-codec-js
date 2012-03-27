
HTML ENTITY CODEC
==========================

A JavaScript implementation of the OWASP ESAPI (Enterprise Security API) for HTML encoding according to <a href="http://www.owasp.org/index.php/XSS_(Cross_Site_Scripting)_Prevention_Cheat_Sheet#RULE_.231_-_HTML_Escape_Before_Inserting_Untrusted_Data_into_HTML_Element_Content">RULE#1 of the XSS Prevention Cheat Sheet</a>

<a href="http://www.owasp.org">OWASP (The Open Web Application Security Project)</a>

How to use
----------
To encode a string, pass it to the `encodeForHTML()` method of the `HTML_ENTITY_CODEC` object.

For example:
`HTML_ENTITY_CODEC.encodeForHTML('<i>test</i>'); // '&lt;i&gt;test&lt;&#x2f;i&gt;'`

Author
------

**Alejandro Beltran**

+ http://twitter.com/alebelcor
+ http://github.com/alebelcor
