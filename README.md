urlutils
========

[![Build Status](https://travis-ci.org/ernestas-poskus/urlutils.svg?branch=master)](https://travis-ci.org/ernestas-poskus/urlutils)

Golang standard URL wrapper, adds syntactic sugar and few new methods.


- ResolveURL: resolves relative URL to absolute URL
- IsAsset: matches asset URL's like: .css, .js, etc.
- IsRelative: checks whether URL is relative, e.g.: /news/article/13.html
- IsAbsolute: checks whether URL has absolute (full) path
- SameDomain: compares URL's checks if they have same domain
- AddWWW: prepends www in front of Host
- AddHTTP: adds http:// if Scheme is empty
- NormalizeDomain: strips sub-domains from Host
- StripParams: strips path, query & fragment from URL