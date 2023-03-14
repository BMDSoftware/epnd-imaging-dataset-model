## Imaging Model Development

### EMIF-AD Fields

An analysis of most filled fields in EMIF Catalogue was performed, in order to help establish required/optional fields.
During the analysis some very populated fields included:

* Identifier
* Name
* Principal Investigator
* Location
* …

### Existing Dataset Models Review

Review of existing models (eBRAINS, …) and vocabularies (DCAT, …)

<figure id="mermaid-model-overview">
    <embed src="figures/datasetModelsReview/Standard Overview.html" width="100%", height="300px">
    <figcaption>Model Standards Overview</figcaption>
</figure>

### Model Development - DCAT Properties

The following considerations were kept when developing the model:

* Decision to keep model simple
  * Create model centered around DCAT vocabulary
* Establish mandatory/recommended dcat:Dataset properties

The following table represents the ideal DCAT properties to implement into the imaging dataset model:

<figure id="dcat-properties">
    <div>
    <span id="dcat-properties-span" data-include-format="markdown" data-include="../figures/dcat-properties.md"></span>
    </div>
    <figcaption>Proposed DCAT fields to be used. These have been tagged as recommended (R) or mandatory (M) fields.</figcaption>
</figure>
