master
------

0.0.5
-----

* Gracefully handle `$ref` key (instead of `type` key)

0.0.4
-----

* Don't generate an "id" attribute in Mirage Factory. Mirage is responsible for
  that

0.0.3
-----

* Support `{ type: ["string", "null"] }` style properties

0.0.2
-----

* Generate `Mirage.Factory` attributes from a JSON Schema.
* Generate `DS.hasMany` and `DS.belongsTo` relationships from JSON Schema.

0.0.1
-----

* Generate `DS.Model` classes with `DS.attr`-backed attributes from JSON Schema.
