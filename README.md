# Resource
Vocab about Economic Resources and Economic ResourceTypes.

We think of Economy in the original sense of [management of our household](https://en.wikipedia.org/wiki/Economy).

## What's the difference?

An Economic Resource is anything that valuable to anybody. We prefer to think of use value, so anything that is useful to anybody, but Economic Resources also often have exchange value.

An Economic Resource may also be an input to or an output from a process or transferred in an exchange.
A ResourceType defines what type of thing the Resource is.

So, for example, most things offered for sale on an e-commerce site are ResourceTypes.
The one in a box delivered to your door is a Resource.

Or the description of the book entitled "The Power of Babel: A Natural History of Language", ISBN ISBN-13: 978-0060520854,
is a ResourceType. Your library may have two copies that you can check out. Those are Resources.

Or, if you can eat it or drive it or give it to someone, it's a Resource.

## Model

![uml model](https://raw.githubusercontent.com/valueflows/resource/master/images/uml.png)

![VOWL model](https://raw.githubusercontent.com/valueflows/resource/master/images/vowl.png)

[open diagram with interactive WebVOWL](http://vowl.visualdataweb.org/webvowl/index.html#iri=https://raw.githubusercontent.com/valueflows/resource/master/resource.ttl)

## Definitions

* [vf:Resource](https://github.com/valueflows/resource/blob/master/Resource.md)

## ResourceTypes are a Taxonomy

That means they can be defined very broadly and generally and maybe vaguely, or they can be defined very narrowly,
but fit into broader categories. Like the Tree of Life.

![tree of life](https://upload.wikimedia.org/wikipedia/commons/thumb/7/70/Phylogenetic_tree.svg/450px-Phylogenetic_tree.svg.png)

So, for example, you may want an apple. Or you may want a green apple. Or you may want a Granny Smith apple.
Or you may want a Granny Smith apple from your neighboring farm.

## Identification and Behaviors of Resources

#### Inventory

Resources can be inventoried, not inventoried but could be, or it doesn't make sense to think about inventory.
* Inventoried: You want to keep track of it, changes in quantity, and how many you have right now.
* Not inventoried: You could keep track of it (it is a material item), but it isn't worth it.  This usually happens for quantities of small or hard to measure items that are obtained in bulk, like solder or bolts.  In this case, you have to look at the actual resource to see if you need more, the system won't tell you.
* Not applicable: This is for types of work (unless scheduled), services, and other resources that cannot be observed.

#### Tracking

Tracking IDs are usually single properties, like lot or batch ID for food and drugs, animal ID for livestock, and serial number for serialized products. Lots can be split up, but serial numbers uniquely identify a particular resource wherever it may be and whoever may have rights to it.

#### Unique identifiers fo resources

This can vary.  And people can be allowed within some boundaries of agreement to specify which combination of other properties would constitute identifiers.

Here are some examples from manufacturing situations:

* Unique identifier = an assigned serialized identifier, which is unique across manufacturers, due to agreements in an industry.  Examples are computers, vehicles, and other equipment.
* Unique identifier = resourceType + lotID + location + owner: so in other words, the owner of the rights was part of the unique identifier of the resource, and if the resource got transferred from one owner to another, the first owner's resources would be decremented, and the second owner's resources would be incremented. 

Note in the last case, a transfer of rights means a different resource. This is common with resources that are not serialized, where one logical resource has a quantity greater than 1, and the individual instances are substitutable. (Think nuts and bolts, grain, strawberries, bottles of beer in cases, etc.)

## Use Cases

* [Make 3D printed part](https://github.com/valueflows/valueflows/blob/master/use-cases/make-3d-printed-part.md)
* [Porridge preparation](https://github.com/valueflows/valueflows/blob/master/use-cases/porridge-preparation.md)
* [Olive oil request](https://github.com/valueflows/valueflows/blob/master/use-cases/olive-oil-request.md)
* [Dental Care](https://github.com/valueflows/valueflows/blob/master/use-cases/dental-care.md)

