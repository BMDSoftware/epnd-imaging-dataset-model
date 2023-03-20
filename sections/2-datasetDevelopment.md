## Imaging Model Development


### Existing Dataset Models Review


An analysis of most filled fields in EMIF Catalogue was performed, in order to help establish required/optional fields.
During the analysis some very populated fields included:

* Identifier
* Name
* Principal Investigator
* Location
* …

Moreover, there is a public EMIF-AD ontology that can be found [EMIF-AD ontology](https://bioportal.bioontology.org/ontologies/EMIF-AD). 
This ontology is based on the EMIF-AD Catalogue and it is used to annotate EMIF-AD datasets.

Before proposing the Imaging Dataset Model for the EPND project, a review of existing imaging models and vocabularies was conducted. The purpose of this review was to identify any relevant fields or properties that could be included in the Imaging Dataset Model and to ensure compatibility with existing models and vocabularies. Several notable models and one vocabulary were reviewed in this process: eBRAINS, the Neuroimaging Data Model (NIDM), BIDS, SPARC, DATS, etc. The review of these models and vocabularies is presented in the following table.

<figure id="mermaid-model-overview">
    <embed src="figures/datasetModelsReview/Standard Overview.html" width="100%", height="300px">
    <figcaption>Model Standards Overview</figcaption>
</figure>

The review of existing models and vocabularies provided valuable insights into relevant fields and properties that could be included in the Imaging Dataset Model for the EPND project. By leveraging these existing resources, the Imaging Dataset Model can be designed to be interoperable with DCAT and easier to be extended, while also be compatible with established standards and practices in the field.


### EPND Model - DCAT Properties

The following considerations were kept when developing the model:

* Decision to keep model simple
  * Create model centered around DCAT vocabulary
* Establish mandatory/recommended dcat:Dataset properties

The following table represents the ideal DCAT properties to implement into the imaging dataset model:

<figure id="dcat-properties">
    <div>
    <span id="dcat-properties-span" data-include-format="markdown" data-include="figures/dcat-properties.md"></span>
    </div>
    <figcaption>Proposed DCAT fields to be used. These have been tagged as recommended (R) or mandatory (M) fields.</figcaption>
</figure>
