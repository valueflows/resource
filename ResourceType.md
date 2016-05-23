# vf:ResourceType

A resource type defines the kind of resource, often organized in a taxonomy of general to specific definitions.  The resource type is not concrete.

## Object Properties
(relationships with other entities)

**vf:parent**: A more general type of resource.  For example, Herb is the parent resource type of Anise Hyssop, Goldenrod, Nettles, Red Clover, etc.  Besides its usefulness in understanding taxonomies of resource types, this can be useful when one can define a general recipe that will work for many more specific types of resources.


## Data Properties
(attributes)

**vf:isSubstitutable**: For a resource type, defines if any resources of that type can be freely substituted for any other resource of that type when used, consumed, traded, etc. For example, "B9R-1-red DLP resin photopolymer" is probably a substitutable resource type.  While each resource for a resource type called "English-Spanish translation" is probably not substitutable because each will be a different document.


Concepts not yet included that might be needed:
* ResourceType unit of use, pricing, resource class (to tie together the same type of resource in different forms, like Carrots-case and Carrots-5 lb bag are all Carrot).
