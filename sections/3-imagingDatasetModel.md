# Imaging Dataset Model

## Definition

After deliberation discussed in the prior section, and analyzing the most commonly filled fields in the EMIF Catalogue, EPND extensions and analyse other models, the team proposed a version 1.0 of the Imaging Dataset Model for the EPND project. The purpose of this model is to provide a standardized way of describing imaging datasets related to neurodegenerative diseases, with the aim of facilitating data sharing and collaboration in the field. 

With the adoption of this model, we targetted that researchers and institutions can improve the discoverability, accessibility, and interoperability of their imaging datasets, and promote collaboration and innovation in the field of neurodegenerative disease research.

## Model structure

The table presented provides a list of properties relevant to the use of DCAT (Data Catalog Vocabulary) in describing datasets. It includes properties that are inherited from the DCAT Dataset class, as well as properties that have been created specifically for use in an application profile. For each property, the corresponding RDF property and the range of permissible values are provided. These details can be used to express the metadata in RDF format.

- Acronym / ID: This is a unique identifier assigned to the dataset for easy reference and identification.
 
- Name: The name of the dataset, which should be a clear and concise representation of its contents.
 
- Description: A brief but detailed description of the dataset, including its purpose, contents, and potential uses.
 
- Publisher: The name of the organization or entity that published the dataset.

- Contact Point: The name and contact information (email, phone number, etc.) of the person or team responsible for managing the dataset.

- Date Published: The date on which the dataset was published or made available to the public.

- Last Update: The date on which the dataset was last updated or modified.

- Dataset version: A version number or other identifier that distinguishes different versions or releases of the dataset.

- Temporal Coverage: A description of the time period or range of dates covered by the dataset.

- Spatial Coverage: A description of the geographic area or regions covered by the dataset.

- Access Rights: A statement of the level of access granted to the dataset, such as public, private, or restricted.

- License: The legal terms and conditions under which the dataset can be used, shared, and distributed.

- Main Reference: A citation or link to a publication or other source that provides more information about the dataset.

- Number of subjects: The total number of subjects or cases included in the dataset.

- Age range: The age range of the subjects included in the dataset.

- Modality: The type or types of medical imaging used to generate the data in the dataset, such as MRI, CT, or PET.

- Body Region: The anatomical regions or systems imaged in the dataset, such as brain, heart, or abdomen.

- Disease(s): The disease or diseases being studied or diagnosed using the data in the dataset.

- Anonimization: A description of the methods used to protect the privacy and confidentiality of the subjects in the dataset, such as de-identification or pseudonymization.

- Image formats: A list of the file formats used to store the images in the dataset, such as TIFF, JPEG, or DICOM.

- Image annotations: A description of any annotations or metadata associated with the images in the dataset, such as pixel dimensions, voxel size, or image orientation.

- Image resolution: The spatial resolution of the images in the dataset, expressed in pixels per unit of length (e.g., pixels per millimeter).

- Image quality: A description of the quality or fidelity of the images in the dataset, including factors such as signal-to-noise ratio, contrast-to-noise ratio, or artifact levels.

- Image analysis: A description of any analyses or processing applied to the images in the dataset, such as segmentation, registration, or feature extraction.

- Image processing: A description of any preprocessing or postprocessing steps applied to the images in the dataset, such as noise reduction, bias correction, or filtering.

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

