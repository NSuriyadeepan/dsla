---
title: "Apache Jena"
description: "open source semantic web tool"
lead: "Jena is an open source tool for the semantic web"
keywords: 
    - NoSQL
    - OWL
    - RDF
    - Semantic Web
    - Triples
contributors:
    - Daniel Hinders
    - Shreyans Jain
    - Andra Ferrara
date: 2020-10-24T00:00:00+00:00
lastmod: 2021-05-19T14:33:00+00:00
draft: false
toc: true
plotly: false
images: []
weight: 100
menu:
    docs:
        parent: "KnowledgeObjects"
---

# Apache Jena

In 2000, HP Labs began developing Jena and in 2010 Jena became part of the Apache Software Foundation [1]. Jena is open source and written in Java. Jena is a tool for the semantic web with Java libraries and APIs to develop tool and applications. Key distinguishes for Jena is its support of OWL and tools to publish RDF data. The semantic web, sometimes called web 3.0, is based on a concept of storing data differently than conventional relational databases. Storing data in RDF triples allows linkages between data that might otherwise remain disconnected. Jena is an application that provides the tools to help developers build applications to store, query and organize data in this RDF triples format.

There are several key elements to Jena that are best understood with a basic understanding of RDF. RDF or Resource Description Framework is a way to model and connect resources or objects. The building blocks in RDF are triples. Triples are built specifically in the Subject.Predicate.Object format. An example of a triple would be ```Wine.Color.Red```.

The data model that is created storing data this way becomes a semantic graph. Jena is built to provide tools to work with RDF and the semantic web. Jena has some key libraries and capabilities that are key for developers buying into building applications in the ontological model. Jena RDF API is key to reading and building triples and RDF graphs. The Jena RDF API provides the basic create, read, update and delete functionality for dealing with triples in RDF. The Jena ARQ processor is another important tool in Jena’s tool kit that enables query using SPARQL [2]. On other key distinguisher of Jena is its support for OWL. OWL or the Web Ontology Language is way represent and build semantics of data similar but more extensible than RDF [3].

[1] The Apache Software Foundation, “What is Jena?” Web page, Oct-2018 [Online]. Available:
https://jena.apache.org/about_jena/about.html

[2] The Apache Software Foundation, “ARQ - A SPARQL Processor for Jena” Web page, Oct-2018 [Online]. Available: https://jena.apache.org/documentation/query/

[3] WC3, “OWL Web Ontology Language Guide.” Web page, Nov-2009 [Online]. Available:
https://www.w3.org/TR/2004/REC-owl-guide-20040210/#Introduction
