# Does WikiPeep require Algolia Search?
No. Algolia is a great service but not for us. WikiPeep search was built for minimal to medium Wikis that holds around few hundreds or thousands pages.

**Note** If you are looking for a nice open source and self hosted search solution alternative to Algolia, or Elasticsearch then you may want to take a look at [Typesense](https://github.com/typesense/typesense), built in C++.

**Second note** [MeiliSearch](https://github.com/meilisearch/MeiliSearch) may be a good open source alternative also, since is fully made with Rust.

Back to our WikiPeep. We don't need an external search service functionality because WikiPeep is using IndexedDB functionality provided by modern browsers.

**TODOS** Now, looking at MeiliSearch and Typesense there is a chance to create a bridge support between WikiPeep and one of these (or both) so we can go crazy with contents - but for now WikiPeep search is strong enough to hold all the things.