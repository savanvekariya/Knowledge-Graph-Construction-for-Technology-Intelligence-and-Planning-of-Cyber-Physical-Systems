# Knowledge Graph Construction for Technology Intelligence and Planning of Cyber-Physical Systems

Resources:-

- https://ieeexplore.ieee.org/document/8651708
- https://www.ijraset.com/research-paper/optimal-operation-of-automotive-electrical-system
- https://ieeexplore.ieee.org/document/9719242
- https://ieeexplore.ieee.org/document/8651708

## File Descriptions

### File #1: 01_corpus.zip

- **Filename:** 01_corpus.zip
- **File Format:** Zipped CSV file
- **Content Description:** A corpus of documents relevant to "automotive electrical systems."
- **Structure:** Header + 46848 rows
- **Columns/Attributes:**
  - `doc_id`: Unique identifier
  - `doc_type`: Document genre (NEWS: news article, SCIENCE: research publication, PATENT: patent filing, PROJECT_DESCR: research project)
  - `doc_sub_type`: Subgenre of the document
  - `title`: Title of the document
  - `doc_date`: Publication date, or filing date for patents
  - `url`: Web link to the document
  - `score_relevance`: Measure for goodness of fit to search query, ranging from 0 to 1

### File #2: 02_keyphrases.csv

- **Filename:** 02_keyphrases.csv
- **File Format:** CSV file
- **Content Description:** List of keyphrases relevant to automotive electrical systems extracted from the corpus.
- **Structure:** Header + 3623 rows
- **Columns/Attributes:**
  - `topic_id`: Unique identifier
  - `term`: Short descriptor
  - `nb_{news, science, patent}`: Number of documents matching the topic within the corpus of the specified genre
  - `nb_{news, science, patent}_topic`: Number of documents matching the topic within the database
  - `npmi_{news, science, patent}`: Normalized pointwise mutual information of the topic, ranging from -1 to 1
  - `npmi_{max, min}`: Maximum/minimum nPMI across genres

### File #3: 03_semantic_network.cys

- **Filename:** 03_semantic_network.cys
- **File Format:** Cytoscape network session
- **Content Description:** Complete semantic network for automotive electrical systems, including MCL-clustered semantic network and ChatGPT generated network.

### File #4: 04_semantic_network_MCL_clustered.pdf

- **Filename:** 04_semantic_network_MCL_clustered.pdf
- **File Format:** PDF image
- **Content Description:** Image of the complete, MCL clustered semantic network for automotive electrical systems.

### File #5: LLM_GenialOntologyKG.html

- **Filename:** LLM_GenialOntologyKG.html
- **File Format:** HTML File
- **Content Description:** Knowledge graph generated using GPT model with the Genial ontology.

### File #6: LLM_InnovationOntologyKG.html

- **Filename:** LLM_InnovationOntologyKG.html
- **File Format:** HTML File
- **Content Description:** Knowledge graph generated using GPT model with the Innovation ontology.

### File #7: LLM_GENIALOntBFO.owl

- **Filename:** LLM_GENIALOntBFO.owl
- **File Format:** OWL File
- **Content Description:** Genial ontology

### File #8: LLM_InnovationOntology.owl

- **Filename:** LLM_InnovationOntology.owl
- **File Format:** OWL File
- **Content Description:** Innovation ontology
