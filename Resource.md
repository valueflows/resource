# vf:Resource

An economic resource, which is useful to people or the ecosystem.

## Object Properties
(relationships with other entities)

**vf:resourceType**

**vf:underlyingResource**: A more concrete resource which a resource is based upon.  For example, a resource which defines the rental of an apartment has the apartment itself as its underlying resource.  

## Data Properties
(attributes)

**vf:trackingIdentifier**: For a resource, this can be a serial number for serialized resources (like a computer), or a lot number for batched resources (like a lot of asparagus that will be distributed in smaller quantities but may need to be tracked to its source in case of an e-coli outbreak).  Or it can just be another useful identifier.

## Open Issues
* Resource stage (where it is based on the last process or transfer made for the same resource in a work flow situation, like Translation@translated, Translation@edited, Translation@proofread). [Issue#30](https://github.com/valueflows/resource/issues/30)
* Resource access rules
* Resource agent roles
