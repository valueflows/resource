# Resource Definitions

**vf:Resource**: An economic resource, which is useful to people or the ecosystem.

**vf:ResourceType**: A resource type defines the kind of resource, often organized in a taxonomy of general to specific definitions.  The resource type is not concrete.

**vf:parent**: A more general type of resource.  For example, Herb is the parent resource type of Anise Hyssop, Goldenrod, Nettles, Red Clover, etc.  Besides its usefulness in understanding taxonomies of resource types, this can be useful when one can define a general recipe that will work for many more specific types of resources.

**vf:underlyingResource**: A more concrete resource which a resource is based upon.  For example, a resource which defines the rental of an apartment has the apartment itself as its underlying resource.  

**vf:isSubstitutable**: For a resource type, defines if any resources of that type can be freely substituted for any other resource of that type when used, consumed, traded, etc. For example, "B9R-1-red DLP resin photopolymer" is probably a substitutable resource type.  While each resource for a resource type called "English-Spanish translation" is probably not substitutable because each will be a different document.

**vf:trackingIdentifier**: For a resource, this can be a serial number for serialized resources (like a computer), or a lot number for batched resources (like a lot of asparagus that will be distributed in smaller quantities but may need to be tracked to its source in case of an e-coli outbreak).  Or it can just be another useful identifier.

Concepts not yet included that might be needed: 
* ResourceType unit of use, pricing, resource class (to tie together the same type of resource in different forms, like Carrots-case and Carrots-5 lb bag are all Carrot).
* Resource stage (where it is based on the last process or transfer made for the same resource in a work flow situation, like Translation@translated, Translation@edited, Translation@proofread).
* Resource access rules
* Resource agent roles
