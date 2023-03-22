
| Text/Question      | DCAT Property                         | RDF Property           | Value Range                                        |
| ------------------ | ------------------------------------- | ---------------------- | -------------------------------------------------- |
| Acronym / ID       | Resource.identifier                   | dcterms:identifier     |                                                    |
| Name               | Resource.title                        | dcterms:title          |                                                    |
| Description        | Resource.description                  | dcterms:description    |                                                    |
| Publisher          | Resource.publisher                    | dcterms:publisher      |                                                    |
| Contact Point      | Resource.contact point                | dcat:contactPoint      |                                                    |
| Date Published     | Resource.release date                 | dcterms:issued         |                                                    |
| Last Update        | Resource.update/modification date     | dcterms:modified       |                                                    |
| Dataset version    | Resource.version                      | dcat:version           |                                                    |
| Temporal Coverage  | Dataset.temporal coverage             | dcterms:temporal       |                                                    |
| Spatial Coverage   | Dataset.spatial/geographical coverage | dcterms:spatial        |                                                    |
| Access rights      | Resource.access rights                | dcterms:accessRights   |                                                    |
| License            | Resource.license                      | dcterms:license        |                                                    |
| Main reference     | Resource.is referenced by             | dcterms:isReferencedBy |                                                    |
| Number of subjects | N.A.                                  | rdfs:Literal           |                                                    |
| Age range          | N.A.                                  |                        |                                                    |
| Modality           | N.A.                                  | "snomedct:363679005"   | ... 1..N / rdfs:Literal / list of modality         |
| Body Region        | N.A.                                  | "snomedct:364402001"   | ... 1..N / rdfs:Literal / list of body regions     |
| Disease(s)         | N.A.                                  | "snomedct:64572001"    | ... 1..N / rdfs:Literal / list of diseases         |
| Anonimization      | N.A.                                  | restricted             | "Anonimized, Pseudoanonimized, Identifiable names" |
| Image formats      | N.A.                                  | restricted             | "TIFF, JPEG, DICOM, NIFTI, etc."                   |
| Image annotations  | N.A.                                  | restricted             | "Yes, No"                                          |
| Image resolution   | N.A.                                  | restricted             | Resolutions (e.g. 512x512)                         |
| Image quality      | N.A.                                  | restricted             | "High, Medium, Low"                                |
| Image analysis     | N.A.                                  | restricted             | "Yes, No"                                          |
| Image processing   | N.A.                                  | restricted             | "Yes, No"                                          |
