---
  - Entities are things in Drupal
  - Drupal 6 custom things where nodes or custom
  - Drupal 7 the entity-field system brought the CCK into core without making everything a node
  - Users, Taxonomy Terms, and Nodes, are all Entities
  - A bundle is a collection of fields instances on an Entity
  - A field instance is a place for complex data in a Entity Bundle
  - A property is simple storage for Entity level data
  - Properties are linked to an Entity, such as Node. Fields are linked to the Bundle, such as Content Type.
  - Properties are stored on the entity's table and fields are stored in their own table.
  - Not all content should entities, fields, or properties. Sometimes a table should just be a table. - BTMash
---

### Entities

Entities are things in Drupal; things do not have to be nodes.

 - A bundle is a collection of fields instances on an Entity
 - A field instance is a place for complex data in a Entity Bundle
 - A property is simple storage for Entity level data

Properties are linked to an Entity, such as Node. Fields are linked to the Bundle, such as Content Type.

Properties are stored on the entity's table and fields are stored in their own table.