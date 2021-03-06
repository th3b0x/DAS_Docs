# [Data Armature Systems System (DASS)](#section-title) Schema Documentation  

### [Contents](#section-content)

1. Title  
2. Contents  
3. Reference Information  
  1. Introduction  
  2. Prefixes  
4. Theory of System  
5. Vocabulary Definitions  
6. Citations  

### [Reference Information](#section-reference)

#### Introduction

##### About The Data Armature Systems Project

[A machine readable description of the project can be found by clicking this link.](https://github.com/th3b0x/DAS_Docs/tree/master/src/DAS_project.ttl)  
[A human readable description of the project can be found by clicking this link.](https://github.com/th3b0x/DAS_Docs/blob/master/README.md)

##### About This Document
This is a markdown-formatted non-normative non-standardized non-committee-approved documentation file.  
[This file describes the dass.rdfs "Data Armature Systems System" or "DASS" Namespace.](https://github.com/th3b0x/Armature/blob/master/src/resources/rdf/dass.rdfs/)  
In the rest of this document, the Data Armature Systems System Namespace and Schema will be referred to as either "DASS" or `dass.rdfs` or "the System" for brevity and ease of document generation.  
This intended audience for this document is "intelligent agents that understand RDF notation standards and conventions".

#### [Prefixes](#section-prefix)

```
@base <file:///> .
@prefix rdf: <http://www.w3.org/1999/02/22-rdf-syntax-ns#> .
@prefix rdfs: <http://www.w3.org/2000/01/rdf-schema#> .
@prefix dass: <https://github.com/th3b0x/Armature/blob/master/src/resources/rdf/dass.rdfs/> .
```

The `@base` establishes a canonical base URI pointing at the system root for localhost  
The `@rdf` prefix references the RDF Schema for the RDF vocabulary terms in the RDF Namespace, defined in [RDF 1.1 Concepts](https://www.w3.org/TR/rdf11-concepts/)  
The `@rdfs` prefix references the RDF Schema for the RDFS vocabulary terms in the RDFS Namespace, defined in  [RDF Schema 1.1](https://www.w3.org/TR/rdf-schema/)  
The `@dass` prefix references the RDF Schema for the System Utility Software vocabulary terms in the DASS Namespace, which has the following definition formats:  
 *  [Machine Readable](https://github.com/th3b0x/Armature/blob/master/src/resources/rdf/dass.rdfs/)
 *  [Human Readable](https://github.com/th3b0x/DAS_Docs/tree/master/doc/dass.md)

### [Theory of System](#section-theory)

The Armature system is a [user agent](https://en.wikipedia.org/wiki/User_agent) that is [intelligent](https://en.wikipedia.org/wiki/Intelligent_agent) by merit of its ability to adapt behavior based upon knowledge.  
The Armature system utilizes an architecture centered around knowledge-driven behavior.  
The System provides a metadata resource to enable knowledge-based reasoning to facilitate agency in automation and behavior on the part of the user agent with the goal of aiding the user in fulfilling its goals.  
The System is intended to be utilized as an input to a system that utilizes RDF and RDFS to describe and query information resources.  An example of such a system is [Armature](https://github.com/th3b0x/Armature) .  
The System provides a vocabulary that can be used to describe utility software present on a system that can be used to achieve the user agents's goals.  An example of such a type of software is `grep` which can be used to fulfill goals related to text discovery.  
The vocabulary provided by the System is the base [terminological component (Tbox)](https://en.wikipedia.org/wiki/Tbox) necessary for building the Armature system's Operating System knowledge base.  

### [Vocabulary Definitions](#section-vocabulary)

### [Citations](#section-citation)
