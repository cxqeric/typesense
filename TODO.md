# Typesense: TODO

## Pre-alpha

**Search index**

- Proper JSON as input
- Storing raw JSON input to RocksDB
- ART for every indexed field
- UTF-8 support for fuzzy search
- Facets
- Filters
- Support search operators like +, - etc.

**API**

- Support the following operations:
    - create a new index
    - index a single document
    - bulk insert multiple documents
    - fetch a document by ID
    - delete a document by ID
    - query an index       

**Clustering**

- Sync every incoming write with another Typesense server