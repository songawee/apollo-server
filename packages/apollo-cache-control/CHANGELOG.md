# Changelog

### vNEXT

* Fix cache hints of `maxAge: 0` to mean "uncachable". (#2197)

* Apply `defaultMaxAge` to scalar fields on the root object. (#2210)


(Missing release notes for 0.2.0, 0.2.1, 0.2.2, 0.2.3, 0.2.4, 0.2.5, 0.3.0,
0.3.1, 0.3.2, 0.3.3, 0.3.4, and 0.4.0!)

### v0.1.1

* Fix `defaultMaxAge` feature (introduced in 0.1.0) so that `maxAge: 0` overrides the default, as previously documented.

### v0.1.0

* **New feature**: New `defaultMaxAge` constructor option. (`apollo-server-*` will be updated to allow you to pass constructor options to the extension.)


### v0.0.10

* Update peer dependencies to support `graphql@0.13`.
* Expose `context.cacheControl.cacheHint` to resolvers.

(Older versions exist but have no CHANGELOG entries.)
