# Tropy-Vocabularies

A selection of standard vocabularies and ontologies formatted to work with [Tropy](https://tropy.org). The files were sourced in [Notation3](https://www.w3.org/TeamSubmission/n3/#namespaces) format from [Linked Open Vocabularies](https://lov.linkeddata.es/dataset/lov/vocabs) when possible, otherwise they were converted using [EasyRDF Converter](https://www.easyrdf.org/converter). Changes other than formatting, such as adding human-readable titles for Tropy, are listed in the notes below.

> [!IMPORTANT]  
> If the notes list any dependencies, then those vocabularies have to be imported first to avoid errors on Tropy.

## Notes


### [The Bibliographic Ontology](https://www.dublincore.org/specifications/bibo/bibo/)
- file: [bibo.n3](Vocabularies/bibo.n3)
- added `terms:title`
- removed redefinitions in Tropy-protected vocabularies
- removed references to obsolete/unnecessary ontologies

### [CIDOC-CRM](https://cidoc-crm.org)
- file: [CIDOC.n3](Vocabularies/CIDOC.n3)
- added `@prefix dc: <http://purl.org/dc/terms/> .`
- added `dc:title`

### [Digital Index of North American Archaeology Vocabulary](https://ux.opencontext.org/archaeology-site-data/)
> [!IMPORTANT]  
> Requires [CIDOC.n3](Vocabularies/CIDOC.n3)

- file: [dinaa.n3](Vocabularies/dinaa.n3)
- added `@prefix dc: <http://purl.org/dc/terms/> .`
- added `dc:title`
- removed redefinitions in Tropy-protected vocabularies


### [Erlangen CRM](http://erlangen-crm.org)
- file: [ecrm.n3](Vocabularies/ecrm.n3)
- added `@prefix dc: <http://purl.org/dc/terms/> .`
- added `dc:title`

### [Open Context Concepts](https://github.com/ekansa/oc-ontologies/tree/master/vocabularies)
> [!IMPORTANT]  
> Requires [CIDOC.n3](Vocabularies/CIDOC.n3), [ecrm.n3](Vocabularies/ecrm.n3), [bibo.n3](Vocabularies/bibo.n3)

- file: [open_context_general.n3](Vocabularies/open_context_general.n3)
- added `@prefix dc: <http://purl.org/dc/terms/> .`
- added `dc:title`
- removed redefinitions in Tropy-protected vocabularies

### [Open Context Zooarchaeology Annotations](https://github.com/ekansa/oc-ontologies/tree/master/vocabularies)
> [!IMPORTANT]  
> Requires [ecrm.n3](Vocabularies/ecrm.n3), [bibo.n3](Vocabularies/bibo.n3)

- file: [zooarchaeology.n3](Vocabularies/zooarchaeology.n3)
- added `@prefix dc: <http://purl.org/dc/terms/> .`
- added `dc:title`
- removed redefinitions in Tropy-protected vocabularies

### [Schema.org](https://schema.org)
- file: [schema_org.n3](Vocabularies/schema_org.n3)
- added `dc:title`

