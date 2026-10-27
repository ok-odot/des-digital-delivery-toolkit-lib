# ODOT Digital Delivery Glossary

**2026 | Version 1.1**

> **DRAFT**  
> Not required practice  
> Proposed program guidance for ODOT Staff and Consultants

## Revision History

| Date   | Author                      | Version | Changes/Updates |
|--------|-----------------------------|---------|-----------------|
| 9/2026 | Digital Delivery Team   | 1.1     | Initial Release |

## Acronyms

| Acronym     | Definition                                              |
|-------------|---------------------------------------------------------|
| AASHTO      | American Association of State Highway and Transportation Officials |
| ADCMS       | Advanced Digital Construction Management Systems        |
| API         | Application Programming Interface                       |
| BIM         | Building Information Modeling                           |
| CADD        | Computer Aided Design and Drafting                      |
| CDE         | Common Data Environment                                 |
| CEL         | Cell Library                                            |
| CFG         | Configuration File                                      |
| DGN         | Design File                                             |
| DGNLIB      | DGN Library                                             |
| DGNWS       | WorkSet File                                            |
| GIS         | Geographic Information Systems                          |
| IFC         | Industry Foundation Classes                             |
| ISO         | International Organization for Standardization          |
| ITL         | Template Library                                        |
| LOIN        | Level of Information Need                               |
| LOD         | Level of Detail                                         |
| MMP         | Model Management Plan                                   |
| MPS         | Model Progression Specification                         |
| MPT         | Maintenance and Protection of Traffic                   |
| NBIMS-US™ V4| National BIM Standard-US™ Version 4                     |
| ODOT        | Oklahoma Department of Transportation                   |
| PDF         | Portable Document Format                                |
| PLTCFG      | Plot Config File                                        |
| PSET        | Print Set File                                          |
| SOP         | Standard Operating Procedure                            |
| SUE         | Subsurface Utility Engineering                          |
| TBL         | Pen Table File                                          |
| XML         | LandXML File                                            |

## Glossary

**Ancillary Asset.** See also: Asset, Asset Class. All physical assets other than pavements and bridges, as defined by 23 U.S.C. 119, that a transportation agency wishes to or does manage.

**Application Programming Interface (API).** A type of software interface that exposes information needed to enable data transfer between systems or other software without manual intervention.

**Asset.** A physical roadway infrastructure item that has value. Assets are sometimes referred to as roadway “furniture” or “features.” An asset may be a single item, such as a sign, or a linear item, such as a road or guardrail section. An asset may also be a spatial item such as a rest area or mowable acreage.

**Attribute Information.** See also: Geometric Information, Model-based Information, Properties. Information that can be expressed using characters, digits, and symbols or tokens such as mathematical symbols and punctuation marks.

**Building Information Modeling (BIM).** The use of a shared digital representation of a built asset to facilitate design, construction, and operation processes to form a reliable basis for decisions.

**Business Use Case.** A specific core function of an organization that establishes a purpose for which a set of information requirements are defined to fulfill.

**Clash Detection.** See also: Model Element. A software feature that facilitates comparing the physical geometry of a model to identify locations where model elements share the same space or are located within a clearance envelope around a model element. The software feature enables creating groups of model elements and establishing rules for the comparison of two groups. These rules can be limited to “hard clashes” where model elements share the same space or may include “soft clashes” where the model elements are within a defined proximity.

**Color Table.** A file that defines the 256-color palette used inside a DGN design file. Each color has a specific RGB value and can be mapped to plot styles. Changing the color table changes how elements appear on screen and how they print.

**Computer-Aided Design and Drafting (CADD).** See also: Model. CADD is the process of creating computer models defined by geometric parameters. The models represent a part or a system of parts that can be changed by adjusting the parameters.

**Common Data Environment (CDE).** See also: Container. A centralized repository for collecting, managing and disseminating each information container through a managed process. A CDE workflow outlines the processes to be implemented, and a CDE solution can provide the necessary technology to support those processes.

**Construction Documents.** A collection of clearly identifiable documents that describe the requirements and terms for a project. Construction documents typically include plans, specifications, standards, and working drawings. Models and/or CADD documents may be included in the definition of Plans and Working Drawings or defined as specific contractual entities in the Specifications or Special Provisions.

**Container.** See also: Common Data Environment (CDE), model. A named set of information retrievable from within a file, system, or managed environment.

**Data Governance.** A set of policies and best practices that dictate practices related to collection, generation, storage, management, access, availability, retention, archiving, and deletion of data.

**Data Structure.** The structure of and relationships among data elements.

**Digital Delivery.** An approach to project-delivery processes that utilize digital data to design, construct, inspect, and maintain physical transportation assets.

**Digital Deliverables.** See also: Contract Documents. A suite of information in a variety of digital media that together communicate the design intent.

**Dimension Style.** A saved set of rules that control how dimensions look and behave. This includes text size, arrows, units, tolerances, extension lines, and placement settings. Using a dimension style ensures all dimensions in a project follow the same formatting.

**Discipline Model.** See also: Federated Model, Model. A model or linked models related to a single discipline. Example: The superstructure model, substructure model, and detailing discipline models are linked together into a federated structural discipline model.

**Document.** Unstructured or semi-structured information relating to a given subject.

**Federated Model.** See also: Discipline Model, Model. A model compiled by referencing models together using a common spatial reference frame. A federated model is most commonly used to combine all discipline-specific models together to represent the project as a whole. However, when an individual discipline uses multiple models to develop a discipline-specific design, a federated model could be used to represent a single discipline (e.g. federated structural discipline model).

**Geometric Information.** See also: Attribute Information, Model-based Information. Information that can be expressed using geometric model elements that have properties such as shape, size, dimension, and location.

**Industry Foundation Classes (IFC).** See also: Open Data Standard. An open international standard for model-based information to facilitate information exchange between software applications. IFC includes a data schema, its documentation, the property and quantity set definitions, and the mechanism of an exchange file format. IFC version 4.3 is published as ISO 16739-1:2024, which includes coverage of information required for bridges and roads.

**Information Management.** Information management encompasses defining data, creating data architecture, modeling data, collecting or gathering data, processing data, storing and securing data, ensuring the quality of data, defining reference data, documenting metadata, ensuring data integration and interoperability, performing document and content management, designing and implementing data-warehousing solutions, and maintaining business intelligence.

**Information Requirements.** A non-technical description of the information needed by a business process to be executed, as well as the information produced by that business process. A specification for what, when, how, and for whom information is to be produced.

**Item Types.** See also: Model-Based Information, Level of Information Need. A software feature in the Bentley® MicroStation® CONNECT Edition. Item types can be used to store information about elements in the form of properties.

**Level/Layer.** A named category used to organize elements in a CAD file. Levels/layers control visibility, color, line weight, and plotting behavior. They allow designers to manage large models by grouping similar objects (for example, signs, drainage features, alignments).

**Level of Information Need (LOIN).** See also: Level of Development. A framework that defines the extent and granularity of information used to establish the minimum requirements for each model element within a discipline and/or project model(s). LOIN defines both the level of detail of the geometry and the level of information attached to model elements.

**Model.** See also: Container. A set of structured and unstructured containers that contain geometric and attribute information that represents a facility.

**Model Architecture.** See also: Schema. A hierarchical structure for information within a model container. The hierarchical structure represents physical objects using a range of logically organized model elements that may be parametrically interrelated.

**Model-Based Information.** See also: Item Types, Level of Information Need, Model. Non-graphical data that is part of a model element definition. Modern modeling software includes property fields that can be used to embed pay item numbers as attributes to elements in a 3D model.

**Model-Derived Information.** See also: Model. Data conveyed or calculated using shape and arrangement and/or location in space. Graphical data includes spatial data and non-spatial data.

**Model Element.** See also: Model. A representation of a physical object (e.g., a sign) or abstract concept (e.g., alignment, north arrow) within a model using a range of data structures like 3D points, line strings, polygons, mesh surfaces, or other parametric objects.

**Model Management Plan (MMP).** A project controls document that formalizes a standard process for project team collaboration using technology and data. The MMP and its associated standard process ensure the quality of the model-based and model-derived deliverables.

**Model Progression Specification (MPS).** See also: Model Management Plan (MMP). A table that defines the level of development and level of information required for the content to be included in an information exchange at each milestone.

**Named Boundary.** A saved boundary used to define an area of a model for drawing creation. Named Boundaries generate sheets such as plan, profile, cross sections, or detail views. They store the view location, scale, and clipping information so sheets can be updated automatically.

**Open Data Standards.** Standards for structuring data according to a schema that has been published in a format that is free to use and redistribute. Open data formats are frequently supported by software products, enabling the exchange of data.

**Parametric.** See also: Geometric Information, Model. An approach to developing geometric information where the geometric properties are interrelated through mathematical relationships and constraints.

**Print Style.** A reusable definition that stores printing (plotting) settings. This includes paper size, printer configuration, pen table assignment, raster options, and color plotting rules. Using print styles ensures consistent output across all sheets.

**Process Control.** See also: Product Control, Quality Management. The use of a preconfigured process with repeatable, reliable outputs that conform to the specifications.

**Product Control.** See also: Process Control, Quality Management. The inspection of a product to determine its conformance with the specifications.

**Property.** See also: Attribute Information, Geometric Information. Information about a model element, including the attached attribute information that provides contextual information that cannot be derived from the model element geometry, as well as information derived from the geometry, such as length, area, and location.

**Schema.** The definition of the structure to organize data for storage, exchange, and sharing, using a formal language.

**Seed File.** A template design file used to start new drawings or models. It contains predefined settings such as working units, global origin, resolution, levels, text styles, and annotation styles. Every new DGN file begins with a seed to maintain standardization.

**Sheet Index.** A managed list of all sheets in a project. The sheet index tracks sheet numbers, titles, discipline groupings, and locations. It enables automation of sheet numbering, cross-references, and drawing set organization.

**Text Favorite.** A reusable text template that inserts text with embedded fields. Text Favorites pull live data such as station, elevation, coordinates, or element properties. They ensure consistency and accuracy in automated labels.

**Text Style.** A saved collection of text formatting settings: font, height, width, justification, line spacing, annotation scale behavior, and other properties. Text Styles ensure that all project text follows the same appearance and scales correctly.

**Quality Management.** A collection of practices that ensure the quality of the products. These practices include the use of preconfigured, standardized processes and job aids that implement a standard approach to product control.