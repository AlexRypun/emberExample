# emberExample

In this example e-shop products feature is implemented according to Ember.js philosophy. There are a few core elements: router, routes, controllers, components, models, helpers, and templates.

`Router` defines URL handler (nested routes are used).

`Routes` are used for data retrieving. There are two nested routes: one for products page (retrieves all products with related data), another for one product page (retrieves a concrete product with related data).

A `Controller` is used for common product functions declaration and for query parameters managing.

Each `Component` is an isolated piece of code for particular element logic implementation. There are components for a product page, for a product list page, and for a product teaser (a product representation in a list).

A `Template` is an HTML structure for UI rendering. Each template is connected to a particular route or component.

A `Model` is an object that represents the underlying data of an entity. Model relations are used (e.g. Product has many ProductTranslations).

A `Helper` is a function that can compute values and is used in templates. Translate helper computes the right text according to the current language.

Most of Ember.js features are used in this example (nested routes, components, computed properties, observers, ember data relationships, helpers, services).

**OOP usage:**
- components are a representation of incapsulation;
- services are examples of dependency injection;
- models use inheritance.
