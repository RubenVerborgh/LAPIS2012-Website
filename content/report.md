---
title: Report
order: 1
---

# Report
## About
This report is an edited version of the [live document](http://typewith.me/p/LAPIS2012)
created by the participants during the workshop.

### Attendees
- Craig Knoblock
- Ruben Verborgh
- Barry Norton
- Andreas Harth
- Pedro Szekely
- Sebastian Speiser
- Kjetil Kjernsmo
- Jacek Kopecky
- Stefan Scheglmann
- …

## Papers

### [The necessity of hypermedia RDF and an approach to achieve it](/papers/1/)

[Paper](http://lapis2012.linkedservices.org/papers/1.pdf)
&ndash;
[Slides](http://folk.uio.no/kjekje/2012/lapis2012.xhtml)

- We want to edit and augment data, not just GET it.
- What's this REST thing?
- Don't make developers look up the spec!
- Is Linked Data inherently RESTful?
- Mike Amundsen's H-factor classification
- What's wrong with the SPARQL Graph Store Spec?

#### Questions
- Jacek: "Hypermedia should be focused on the user." [ and developers should look up the specs ]

#### Discussion elements
- SPARQL graph protocol
- templates
- Do we need more expressive linkage rules/templates (rather than links on the resource level only?)

### [Semi-Automatically Modeling Web APIs to Create Linked APIs](/papers/2/)

[Paper](http://lapis2012.linkedservices.org/papers/2.pdf)
&ndash;
[Slides](http://lapis2012.linkedservices.org/slides/2.pdf)
&ndash;
[Powerpoint](https://www.dropbox.com/s/ouu0tcubnn0b89h/2012-05-27-LAPIS-v04.pptx)

- Automatically find out input and output types and their relationships
- Construct a semantic model based on examples
- Extracting labels
- Extracting relationships is more complicated

#### Questions
- What if the API is not resource-oriented?
- RDFS/OWL to build skeleton using DERI's extension to Google Refine?

#### Discussion elements
- How to get live weather in DBpedia?
- How do we scale up?

### [The Missing Links](/papers/3/)

[Paper](http://lapis2012.linkedservices.org/papers/3.pdf)

- Mismatch between REST and Semantic Web
- Goal: Build autonomous Web agent to fulfill a task given by people
- Focus on using services to do this
- REST = hypermedia APIs
- Rest can do posts
- How do we get dynamic relations in Semantic Web
- RESTdesc intends to solve this

#### Comments

- Via Erik Wilde: "[RFC 5988](http://tools.ietf.org/html/rfc5988#section-4.2) very specifically says that they should not be treated as being resolvable."

#### Discussion elements
- Does the REST community need the Semantic Web community?
- Are descriptions the way to go?
- Will it scale?
- How do we describe a service that uploads a photo and returns EXIF metadata differently from a service that only extracts EXIF metadata of a picture that it then forgets? [ thought: make the first a collection ]

### [Hyperdata: Update APIs for RDF Data Sources](/papers/4/)

[Paper](http://lapis2012.linkedservices.org/papers/4.pdf)
&ndash;
[Slides](http://jacek.cz/presentations/2012-05-27-lapis-hyperdata.pdf)

- We need a domain-specific API to control write access (new identifiers, security, validation, side effects)
- For RDF, we propose hyperdata.
- Three levels in the data: instance, property, and value
- Resources are a graph that contains predicate indicates that the graph contains info about the resources.
- Statement "templates" can also be contained, using reification. The object is a blank node.
It's meant to serve as a service description.

#### Questions
- What if you want inference from the reified statement?

#### Discussion elements

- Service composition
- Service descriptions vs. HATEOAS
- Linked elements/aspects of LAPIs
  - Is RDF over HTTP enough?
  - Embedded Links vs. Vocabulary vs. Outbound Navigational Links

## Open Discussion
[Use Cases](http://linkedservices.org/wiki/Use_Cases)

[Wrappers](http://linkedservices.org/wiki/Wrappers)
