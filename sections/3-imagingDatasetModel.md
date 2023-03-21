# Imaging Dataset Model

## Definition

After deliberation discussed in the prior section, and analyzing the most commonly filled fields in the EMIF Catalogue, EPND extensions and analyse other models, the team proposed a version 1.0 of the Imaging Dataset Model for the EPND project. The purpose of this model is to provide a standardized way of describing imaging datasets related to neurodegenerative diseases, with the aim of facilitating data sharing and collaboration in the field. 

With the adoption of this model, we targetted that researchers and institutions can improve the discoverability, accessibility, and interoperability of their imaging datasets, and promote collaboration and innovation in the field of neurodegenerative disease research.

## Model structure

The table presented provides a list of properties relevant to the use of DCAT (Data Catalog Vocabulary) in describing datasets. It includes properties that are inherited from the DCAT Dataset class, as well as properties that have been created specifically for use in an application profile. For each property, the corresponding RDF property and the range of permissible values are provided. These details can be used to express the metadata in RDF format.


<figure style="width: 100%;">
    <div>
        <span id="imaging-dataset-model-silver" data-include-format="markdown" data-include="figures/imaging-dataset-model-silver-v1.0.md"></span>
    </div>
    <figcaption>The proposed v1.0 of the imaging dataset model: Dark green representes general fields that make use of DCAT properties, while the lighter green fields represents imaging fields.</figcaption>
</figure>

Note that some of the properties, such as dcat:version, numberOfSubjects, imageFormats, and imageAnnotations, are not part of the core DCAT specification, but may be added as needed for a specific use case. Also, the modality, bodyRegion, and disease properties are examples of custom properties that could be added to describe specific aspects of the dataset.

This proposed model is meant to be as simple as possible, without resorting to more elaborate mappings of models, such as, openMINDS. Moreover, compatiblitly with other models was considered, and also DCAT was kept in mind, as this is a standard that is widely used in the field of data catalogues.


## Formats

See the following figure for an example of JSON-LD imaging model format.

<figure style="width: 100%;">
    <pre id="imaging-model-json-ld" data-include-format="text" data-include="examples/dataset-simple.jsonld"></pre>
    <figcaption>The JSON-LD Imaging Model format.</figcaption>
</figure>


See the following figure for an example of RDF imaging model format.

<figure style="width: 100%;">
    <pre id="imaging-model-rdf" data-include-format="text" data-include="examples/dataset-simple.rdf"></pre>
    <figcaption>The RDF maging Model format.</figcaption>
</figure>
