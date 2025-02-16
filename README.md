# kb-builder

# Knowledge Base Builder - experiment to integrate some knowledge representations 
(is possible /within sight/ knowledge representation examples: vectorsemantics /extended to hyperpolytopes/, knowledge graphs and/or relatives, formal logics, M² paradigm)

### Motivations
Current mainstream knowledge representations of genAI systems (as vectorsemantics, prompts and RAG background embeddings /as mostly based vectorsemantics too/) are insufficient alone to achieve cogAI, that is cognitive level AI.
(cogAI := collective noun of human cognition based, deep understanding targeted AIs)

### Goals
1. Build an persistent, queryable, maintainable (content-modifiable and -expandable) store from some formats of documents.
2. Provide API for update and upload content to store, as well as query informations from store.

### Requirements
- Integrate as many as possible knowledge representations from the list below:
  - vectorsemantics /extended to hyperpolytopes/
  - knowledge graphs and/or relatives /mind maps, semantic nets, ontologies,... etc./
  - formal logics /not only classical, but modal, temporal, many-valued, fuzzy,... etc./
  - M² paradigm /mental patterns & models/
  - ... etc
- Input: documents with some file formats /pdf, epub,... etc./ with processable concrete content scope and document metamodell
- Persistent store to background storage by store-manager(s) /maybe multiparadigm DB server or multple DB servers with different paradigms: relation, vector, graph,... etc./
- REST endpoint for API with functionalities update, upload and several queries

### Solution
Vision, architecture and implementation details...

#### Vision
Principles (following Randall Davis's roles of knowledge representations):
- prediction model, that is simulation mechanism
- ontology, that is concept-system
- formal logics, that is reasoning ruleset
- language, that is communication/narrative-thought tool/system
- computational model, that is execution/runtime/resource-provider architecture/environment/mechanism

Issues (following Ron Brachman):
- implementation paradigm/method
- meta-representation mechanism
- invompleteness, uncertainty
- universalities and existentialities (necessity and opportunity)
- fact changes tracking (non-monotonic reasoning)
- practical/convenient expressiveness
- amortization effectiveness

Knowledge representation constructions / metaphores (with examples):
- Abstract space
  - Continuous vectorspace (word embedding)
  - Discrete topologic space (knowledge graph)
  - Hybrid (syntax hyperpolytope)
- Symmetry based (?)
  - Transformation based
  - Pattern and model based
  - Set, category, other unstructured / fuzzy collection
- Language
  - Grammatical
    - Formal (logics)
    - Natural (human language)
  - Probabilitical (molecular biology pathways)
  - Ecosystemical (meta-*-omics)

...

#### Architecture
Multitier: client - FE - BE - EIS

Subtiers: any HTTP client (no implemented UI) - REST endpoint controllers - services - persistence logic (DAO) - persistence server (DB)
...

#### Implementation details
Business functions (REST EPs), KR operations/integrations and data model(s)...

##### Business functions (REST endpoints)
...

##### Knowledge representation operations (interfaces)
...

##### Data model
...

