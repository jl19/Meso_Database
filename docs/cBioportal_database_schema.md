# cBioportal Database Schema

cBioPortal is an open-source web platform for exploring, visualizing, and analyzing genomic data in cancer research. It provides access to a wide range of cancer genomics data, including somatic mutations, 
copy number alterations, gene expression, and clinical data.

The cBioPortal database schema is complex, as it involves multiple tables to store different types of genomic and clinical data. I'll provide a simplified overview of some key tables typically found in a cBioPortal database:

## 1. Cancer Study:

Represents a specific cancer study with its unique identifier.
Stores information about the study, such as its name, description, and publication details.
## 2. Patient:

Represents an individual cancer patient in the study.
Contains patient-specific information like patient ID, age, gender, and vital status.
## 3. Sample:

Represents a biological sample from a patient, which could be a tumor or a normal sample.
Contains information about the sample, such as sample ID, sample type, and tissue site.
## 4. Molecular Profile:

Stores genomic data from different molecular assays, such as DNA sequencing, RNA-seq, or copy number analysis.
Contains details about the genomic data, such as profile ID, data type, and genomic platform used.
## 5. Genetic Alteration:

Represents a genetic alteration (e.g., somatic mutation, copy number alteration) detected in a sample.
Contains information about the specific alteration, such as gene name, alteration type, and alteration status.
## 6. Clinical Data:

Stores clinical information about patients, such as disease stage, treatment details, and survival outcomes.
Contains patient-specific clinical data linked to the patient and sample identifiers.
These are just some of the core tables you might find in a cBioPortal database. In practice, there may be additional tables and relationships to accommodate the complexity of genomic data and its associations with clinical information.


