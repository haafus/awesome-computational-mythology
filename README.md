# Awesome Computational Mythology [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

> A curated list of resources for the computational, comparative, and quantitative study of myth, folklore, and traditional narrative — indexes, corpora, datasets, methods, tools, ontologies, key papers, scholars, venues, and text libraries.

**Scope.** Resources for studying myth/folklore/traditional narrative *computationally, comparatively, or quantitatively*. **In:** indexes, corpora, folklore databases and archives, contextual datasets, methods, tools, ontologies, quantitative/DH studies, text libraries. The list distinguishes classification indexes, research-ready corpora, archival collections and search interfaces, and contextual data used in comparative analysis. **Out:** general mythology retellings, single-tradition popularizations, and non-computational reference works (unless a standard apparatus like TMI/ATU). This is a **neutral community list**.

## Contents

- [Motif & tale-type indexes](#motif--tale-type-indexes)
- [Corpora & annotated datasets](#corpora--annotated-datasets)
- [Folklore databases & archives](#folklore-databases--archives)
- [Cross-cultural & areal databases](#cross-cultural--areal-databases)
- [Contextual data](#contextual-data)
- [Digital text libraries](#digital-text-libraries)
- [Encyclopedias & reference works](#encyclopedias--reference-works)
- [Ontologies & linked open data](#ontologies--linked-open-data)
- [Methods & techniques](#methods--techniques)
- [Tools & software](#tools--software)
- [Landmark papers](#landmark-papers)
- [Scholars & labs](#scholars--labs)
- [Venues & journals](#venues--journals)
- [Projects](#projects)
- [See also](#see-also)

## Motif & tale-type indexes

- [Thompson Motif-Index (TMI)](https://archive.org/details/motifindexoffolk0000stit) - Stith Thompson, *Motif-Index of Folk-Literature*, rev. ed. 1955–58: ~46,000 narrative motifs in a place-value taxonomy (A–Z). Digital editions: the *Trilogy* CSVs, Katja Mellmann's `TMI_as_CSV`, [`fbkarsdorp/tmi`](https://github.com/fbkarsdorp/tmi), [folkmasa.org](https://www.folkmasa.org/).
- [Aarne–Thompson–Uther (ATU)](https://www.folklorefellows.fi/ffc-editors/recent-volumes/ffc-280-289/ffc-284-286/) - Hans-Jörg Uther, *The Types of International Folktales*, FFC 284–286 (Helsinki, 2004): 2,247 tale types; successor to Aarne–Thompson (AaTh/AT).
- [Berezkin & Duvakin — Analytical Catalogue of World Mythology and Folklore](https://www.areasofmyths.com) - 3,488 areal motifs in 14 lettered chapters, attested across ~1,050 traditions and 65 macro-areas (also at mapsofmyths.com; per-tradition map coordinates published with it). Described by its compiler in [*Folklore and mythology catalogue: its lay-out and potential for research*](https://sisu.ut.ee/wp-content/uploads/sites/172/berezkin_folklore_and_mythology_catalogue_its_lay-1_out_and_potential_for_research.pdf) (RMN Newsletter 10, 2015).
- [El-Shamy — *A Motif Index of The Thousand and One Nights*](https://folklore.indiana.edu/research/publications/emeriti-publications/2006-a-motif-index.html) - Hasan El-Shamy (Indiana University Press, 2006); companion to his *Folk Traditions of the Arab World* (1995).
- [Christiansen — *The Migratory Legends* (ML)](https://www.folklorefellows.fi/ffc-catalogue/) - The migratory-legend type index (FFC 175, 1958).
- [СУС (Sravnitel'nyj Ukazatel' Sjuzhetov)](https://ruthenia.ru/folklore/bspisok.html) - The East-Slavic comparative tale-type index (Barag et al., Leningrad, 1979); the link is a bibliography of folklore indexes that records it.
- [Perry Index](https://guides.library.harvard.edu/folk_and_myth/indices) - Aesopic fable types.

## Corpora & annotated datasets

- [GOLEM](https://aclanthology.org/2024.lrec-main.689/) - Gold-standard motif corpus (Yarlott et al., LREC-COLING 2024): 7,955 articles, 26,078 motif candidates over 34 types, labelled for *use*-type; few-shot classification of that use-type peaks at only 41%, which is what makes it a hard benchmark.
- [Annotated Folktales / "Trilogy"](https://github.com/j-hagedorn/trilogy) - Open ATU-annotated corpus (Hagedorn & Darányi, 2022) of 1,518 texts over 182 tale types (CC-BY-SA); the [data paper](https://openhumanitiesdata.metajnl.com/articles/10.5334/johd.78) is in *Journal of Open Humanities Data*. An SVM over TF-IDF on its ten best-populated classes reaches F1 0.8–1.0 (Eklund et al. 2023, below).
- [Dutch Folktale Database (Verhalenbank)](https://www.verhalenbank.nl) - The Meertens Institute folktale collection; also searchable through ISEBEL.
- [FairytaleQA](https://github.com/neuhai/FairytaleQA_Dataset) - Question-answering dataset over fairy tales.
- [Folklore Database](https://folkloredatabase.com/) - Searchable global discovery database of 286,878 narratives from hundreds of sources, with English translations and metadata including motifs, cultural origins, geography, and bibliographic references. It incorporates established indexes, including ATU, Thompson, and Berezkin–Duvakin. Mytheme annotations are being rebuilt with an LLM, and mytheme search is currently unavailable. Rights and reuse conditions vary across source materials; the database should not be treated as a uniformly open or bulk-downloadable corpus. Check item-level provenance and rights, and contact the curator for research access.
- [FILTER Finnic Runosong Database](https://blogs.helsinki.fi/filter-project/tools/) - Integrated database of Estonian, Finnish, Karelian, and Ingrian runosong materials (approx. 250,000 texts across related corpora), with metadata and computational similarity tools; includes ERAB, SKVR, and unpublished Finnish runosongs.
- [Decoding Hidden Heritages](https://www.hiddenheritages.ai/) - Searchable corpus of 5,500+ Scottish and Irish folktales from archival manuscripts and printed sources, including AI-assisted transcriptions and AT tale-type metadata; project outputs derive from the School of Scottish Studies Archives and the Irish National Folklore Collection.
- [Multilingual Folk Tale Database (MFTD)](http://www.mftd.org) - Folk tales and their translations in many languages; the site is temporarily offline.
- [ProppLearner](https://academic.oup.com/dsh/article/32/2/284/2957394) - Proppian-function-annotated Russian folktales (Finlayson); see also Finlayson's [2012 dissertation, *Learning Narrative Structure from Annotated Folktales*](https://groups.csail.mit.edu/genesis/papers/Finlayson%202011.pdf), which develops the Analogical Story Merging (ASM) approach.
- [Arabian Nights motif corpus](https://arxiv.org/abs/2603.19283) - 2,670 motif expressions over 200 motifs in 58,450 sentences, indexed against El-Shamy (Alyami & Finlayson, 2026; preprint); the first motif-indexing corpus for a single work.
- [MIME](https://aclanthology.org/2024.nlpcss-1.4/) - Reports on a motif's *implicit* meaning drawn from indexes, Wikipedia, informants and social media (Acharya et al., NLP+CSS 2024); concludes culture-bearer input is not optional.

## Folklore databases & archives

Digital repositories and search systems for folklore materials, including archival records, field collections, oral narratives, songs, and legends. Unlike research-ready corpora, these resources preserve collection context, media, and archival metadata; unlike motif indexes, they are not primarily classification schemes.

- [ISEBEL — Intelligent Search Engine for Belief Legends](https://search.isebel.eu/) - Cross-archive search over Dutch, Flemish, Danish, North-East German, and Icelandic legend databases; links records to their source collections.
- [WossiDia — Digital Wossidlo Archive](https://apps.wossidia.de/webapp/run) - Digitized North-East German folklore archive based on the Wossidlo collection.
- [Folke](https://sok.folke.isof.se/) - Swedish digital archive of historical folklore records from the Institute for Language and Folklore (Isof), including manuscripts, questionnaires, and recordings; transcribed texts are also available as a downloadable corpus under CC BY 4.0.
- [Sagnagrunnur](https://sagnagrunnur.arnastofnun.is/english/) - Geographically mapped database of published Icelandic legends, with linked extensions for Shetland and Orkney and connections to archival sound recordings.
- [Danish Folklore Nexus](https://scando.ist.berkeley.edu/folklorenexus/) - Searchable collection of Danish legends developed by the Scandinavian Section at UC Berkeley.
- [Danish Folklore Archive, Royal Danish Library](https://www.kb.dk/en/find-materials/collections/folklore-archive) - Manuscripts, audio, images, video, and books documenting Danish folklore and everyday life.
- [Estonian Folklore Archives — digital databases](https://www.folklore.ee/en/dbases/) - Genre- and region-based databases of digitized Estonian folklore texts.
- [Estonian Runosongs Database](https://www.folklore.ee/regilaul/andmebaas/) - Searchable archive of runosongs with information about place, collector, and singer.
- [Digital Archives of Latvian Folklore](https://garamantas.lv/?lang=en) - Digitized Latvian folklore collections.
- [SAMLA](https://samla.no/) - Norwegian digital folklore archive connecting collections from the Ethno-Folkloristic Archive, Norwegian Folklore Archives, and Norwegian Ethnological Research.
- [Suomen Kansan Vanhat Runot (SKVR)](https://skvr.fi/) - Digital edition of Finnish, Karelian, and Ingrian oral poetry, with published and unpublished collection materials.
- [Tobar an Dualchais / Kist o Riches](https://www.tobarandualchais.co.uk/) - Sound recordings of Scottish traditions, including legends and songs.
- [Dúchas — National Folklore Collection](https://www.duchas.ie/en) - Digitized Irish folklore manuscripts, photographs, and audio, including the Schools’ Collection; public transcriptions and a folktale index.
- [Croatian Institute of Ethnology and Folklore Research — Archive Collections](https://www.ief.hr/en/archive/collections/) - Folklore and ethnographic documents, manuscript collections, and sound recordings on Croatian traditional culture.
- [Finnish Literature Society Archives](https://www.finlit.fi/en/archives/archive-materials-on-traditional-and-contemporary-culture/) - Folklore and oral-history collections from Finland, Karelia, and Ingria, including manuscripts, photographs, recordings, and videos.
- [Ashliman's Folktexts](https://sites.pitt.edu/~dash/folktexts.html) - D. L. Ashliman's ATU-organized collection of folklore texts.

## Cross-cultural & areal databases

Structured comparative databases and reference systems that bring together cultural, religious, or historical information across societies.

- [Seshat: Global History Databank](https://seshatdatabank.info) - Structured data on past societies, institutions, and social complexity.
- [Database of Religious History (DRH)](https://religiondatabase.org) - Expert-coded data on religious groups, practices, and places.
- [eHRAF World Cultures](https://ehrafworldcultures.yale.edu/) - Cross-cultural ethnographic materials with subject indexing (subscription).

## Contextual data

Structured information needed to interpret distributions, model contact, and control for historical, geographic, linguistic, and social relationships. These resources complement folklore corpora and motif indexes rather than replacing them.

- [D-PLACE](https://d-place.org) - Language, culture, environment, and geographic information for human societies; includes the Ethnographic Atlas.
- [Glottolog](https://glottolog.org) - Language classification, genealogical relationships, and bibliographic metadata.
- [Historical Basemaps](https://github.com/aourednik/historical-basemaps) - Dated political boundaries in GeoJSON for historical-geographic analysis.

## Digital text libraries

- [Perseus Digital Library](http://www.perseus.tufts.edu) - Greek and Latin texts (+ First1KGreek).
- [Internet Sacred Text Archive](https://www.sacred-texts.com) - Religious, mythological and folklore texts.
- [ETCSL](https://etcsl.orinst.ox.ac.uk) - Electronic Text Corpus of Sumerian Literature.
- [ORACC](http://oracc.museum.upenn.edu) - Open Richly Annotated Cuneiform Corpus.
- [Thesaurus Linguae Aegyptiae](https://thesaurus-linguae-aegyptiae.de) - Corpus and lexicon of Ancient Egyptian.
- [GRETIL](https://gretil.sub.uni-goettingen.de) - Electronic texts in Indian languages.
- [Chinese Text Project](https://ctext.org) - Pre-modern Chinese texts.
- [CBETA](https://www.cbeta.org) - Chinese Buddhist Electronic Text Association.
- [SuttaCentral](https://suttacentral.net) - Early Buddhist texts.
- [Sefaria](https://www.sefaria.org) - Jewish texts.
- [CELT](https://celt.ucc.ie) - Corpus of Electronic Texts (Irish).
- [OpenITI](https://openiti.org) - Open Islamicate Texts Initiative.
- [TITUS](https://titus.uni-frankfurt.de) - Indo-European text materials.
- [Digital Corpus of Sanskrit](http://www.sanskrit-linguistics.org/dcs/) - Morphologically analysed Sanskrit.
- [Heimskringla.no](https://heimskringla.no) - Old Norse–Icelandic texts.
- [Icelandic Saga Database](https://sagadb.org/downloads) - Old Norse–Icelandic sagas.
- [SEAL](https://seal.huji.ac.il/) - Sources of Early Akkadian Literature.
- [Hethitologie-Portal Mainz](https://www.hethport.uni-wuerzburg.de/) - Hittite text corpus and concordance.
- [Avesta.org](https://www.avesta.org/) - Zoroastrian archives.
- [SAT Daizōkyō](https://21dzk.l.u-tokyo.ac.jp/SAT/) - Buddhist canon in classical Chinese.
- [Kanripo](https://www.kanripo.org/) - Classical Chinese canons.
- [BDRC](https://www.bdrc.io/) - Buddhist Digital Resource Center (Tibetan).
- [Project Gutenberg](https://www.gutenberg.org) - Public-domain books.
- [Internet Archive](https://archive.org) - Scanned books and texts.
- [HathiTrust](https://www.hathitrust.org) - Digitized research-library collections.

## Encyclopedias & reference works

- [The Mythology of All Races](https://en.wikipedia.org/wiki/The_Mythology_of_All_Races) - Gray/Moore, eds., 13 vols.
- [Encyclopedia of Religion](https://archive.org/search?query=title%3A%28encyclopedia+of+religion%29+AND+creator%3A%28eliade%29) - Eliade, ed. (1987); 2nd ed. Jones (2005).
- [Мифы народов мира](https://ru.wikipedia.org/wiki/%D0%9C%D0%B8%D1%84%D1%8B_%D0%BD%D0%B0%D1%80%D0%BE%D0%B4%D0%BE%D0%B2_%D0%BC%D0%B8%D1%80%D0%B0) - The two-volume Soviet mythological encyclopedia (Tokarev, ed.).
- [Dictionary of Mythology](https://archive.org/details/greekegyptianmyt00bonn) - Bonnefoy, *Mythologies* (English ed. under Doniger); the link is one of its paperback volumes.
- [New Larousse Encyclopedia of Mythology](https://archive.org/details/newlarousseencyc00guir) - Guirand, ed.
- [Wörterbuch der Mythologie](https://de.wikipedia.org/wiki/W%C3%B6rterbuch_der_Mythologie) - Haussig, ed.
- [Enzyklopädie des Märchens](https://adw-goe.de/cs/enzmaer/) - The reference encyclopedia of the folktale.

## Ontologies & linked open data

- [DFKI Linked Data for Folktales](https://www-live.dfki.de/fileadmin/user_upload/import/6181_LDL-2012-declerck.pdf) - OWL/RDF/SKOS + lemon modelling of ATU/TMI (Declerck et al.).
- [Ontology of Greek Mythology (OGM)](https://www.semantic-web-journal.net/content/greek-mythology-knowledge-graph-chaos-zeus-and-beyond) - Wikidata-based ontology of Greek mythological characters (Pastor-Sánchez et al.).
- [MANTO](https://www.manto-myth.org) - Linked data on Greek mythological entities and relations.
- [GLOS — Geographic Lens on Stories](https://kgeographer.org/glos/) - Geographic modelling of stories (Grossner et al.).
- [SKOS](https://www.w3.org/2004/02/skos/) - Vocabulary standard.
- [lemon](https://www.w3.org/2016/05/ontolex/) - Lexicon model (OntoLex-Lemon).
- [CIDOC-CRM](https://cidoc-crm.org/) - Cultural-heritage ontology.
- [Wikidata P2540](https://www.wikidata.org/wiki/Property:P2540) - Wikidata property for the ATU tale-type ID.

## Methods & techniques

Methods are grouped along the research workflow, from preparing primary sources to comparative inference. A computational result depends on the quality and provenance of source material as much as on the model used downstream.

### Digitization, transcription & source preparation

- [OCR](https://en.wikipedia.org/wiki/Optical_character_recognition) - Optical character recognition for printed texts; assess language- and period-specific error rates before downstream analysis.
- [HTR](https://readcoop.eu/transkribus/) - Handwritten Text Recognition for manuscripts and archival documents.
- [IIIF](https://iiif.io/) - Interoperability framework for publishing and working with digitized manuscripts, images, and archival objects.
- [TEI Guidelines](https://tei-c.org/guidelines/) - XML vocabulary for representing textual structure, editorial interventions, manuscript witnesses, and metadata.
- [Text normalization & annotation](https://www.tei-c.org/) - Encoding orthographic variants, editorial expansions, segmentation, language, genre, and named entities while retaining links to source witnesses.

### Entity resolution, alignment & multilingual processing

- [Named-entity recognition and linking](https://spacy.io/usage/linguistic-features#named-entities) - Identify and reconcile people, places, groups, and named beings across spelling variants, languages, and documents.
- [Record linkage / entity resolution](https://en.wikipedia.org/wiki/Record_linkage) - Match duplicate or related archival records and normalize references to characters, places, informants, and narrative variants.
- [Text alignment](https://hunalign.github.io/) - Align translations, parallel versions, and related passages across editions or languages.
- [Multilingual NLP](https://huggingface.co/docs/transformers) - Language identification, cross-lingual embeddings, machine translation, and multilingual classification; validate performance for low-resource and historical languages.

### Quantitative analysis & comparative inference

- [Motif induction / detection from text](https://en.wikipedia.org/wiki/Motif_(folkloristics)) - The open problem; formally fluid motifs, weak detectors, classical baselines competitive with LLMs.
- [Tale-type / narrative classification](https://en.wikipedia.org/wiki/Document_classification) - SVM+TF-IDF, transformers, story embeddings.
- [Topic modeling](https://en.wikipedia.org/wiki/Topic_model) - LDA, Labeled-LDA, BERTopic (+ c-TF-IDF, KeyBERT).
- [Embeddings](https://en.wikipedia.org/wiki/Sentence_embedding) - SBERT/Sentence-Transformers, LaBSE, BGE-M3, E5; **story embeddings** (plot- not style-similarity).
- [Dimensionality reduction & clustering](https://umap-learn.readthedocs.io/) - UMAP, t-SNE; HDBSCAN; NeighborNet.
- [Phylogenetics of narrative](https://en.wikipedia.org/wiki/Computational_phylogenetics) - Bayesian phylogenetics (BEAST, MrBayes), ancestral-state reconstruction, phylomemetics.
- [Seriation & pseudo-time](https://en.wikipedia.org/wiki/Seriation_(archaeology)) - Correspondence-analysis seriation; single-cell pseudotime (DPT, Slingshot) applied to motif ordering.
- [Networks](https://en.wikipedia.org/wiki/Network_motif) - Character-interaction networks; network motifs (mfinder, FANMOD); block models; nestedness (NODF).
- [Cross-cultural statistics](https://en.wikipedia.org/wiki/Galton%27s_problem) - Galton's problem, restricted-permutation nulls, Mantel tests, F_ST, and resistance surfaces; account for collection provenance, sampling intensity, genre, and historical recording bias.
- [Dating & chronology](https://en.wikipedia.org/wiki/Tip_dating) - Tip-dating ([review, Syst. Biol. 2026](https://academic.oup.com/sysbio/article/75/1/156/8262818)), language-tree calibration, and models that admit horizontal transfer ([Hum. Soc. Sci. Commun. 2022](https://www.nature.com/articles/s41599-022-01211-7)); biogeographic bounds and textual *terminus ante quem* floors.

## Tools & software

### Text processing, search & semantic analysis

- [MOMFER](https://momfer.meertens.knaw.nl/) - Motif finder over the Dutch Folktale Database.
- [Sentence-Transformers](https://www.sbert.net) - Embedding infrastructure for semantic search and similarity.
- [Runoregi](https://runoregi.fi/) - Interface for exploring computational similarity results across Finnic oral poetry, developed within the FILTER project.
- [BERTopic](https://maartengr.github.io/BERTopic/) - Topic modeling.
- [MALLET](http://mallet.cs.umass.edu/) - Topic modeling toolkit; widely used for LDA.
- [`uhhlt/story-emb`](https://huggingface.co/uhhlt/story-emb) - Story-similarity embedding model (Hatzel & Biemann).

### Phylogenetics & comparative analysis

- [SplitsTree](https://software-ab.cs.uni-tuebingen.de/download/splitstree6/) - Phylogenetic networks.
- [BEAST2](https://www.beast2.org) - Bayesian phylogenetics.
- [MrBayes](https://nbisweden.github.io/MrBayes/) - Bayesian phylogenetics.

### Network analysis

- [Gephi](https://gephi.org) - Network analysis and visualization.
- [FANMOD](https://doi.org/10.1093/bioinformatics/btl038) - Network-motif detection (Wernicke & Rasche, Bioinformatics 2006).

## Landmark papers

### Computational folkloristics & narrative analysis

- [Computational Folkloristics](https://doi.org/10.1145/2209249.2209267) - Abello, Broadwell & Tangherlini (CACM, 2012).
- [A Very Brief History of Computational Folkloristics](https://doi.org/10.1515/fabula-2023-0001) - Lauer (Fabula, 2023).
- [Learning Narrative Structure from Annotated Folktales](https://groups.csail.mit.edu/genesis/papers/Finlayson%202011.pdf) - Finlayson (PhD dissertation, MIT, 2012); introduces Analogical Story Merging (ASM) to induce abstract narrative structure from semantically annotated event sequences.
- [An NLP-based Cross-Document Approach to Narrative Structure Discovery](https://doi.org/10.1093/llc/fqu055) - Reiter, Frank & Hellwig (*Literary and Linguistic Computing*, 2014, 29(4), 583–605); aligns event and participant representations across documents.
- [Story Embeddings](https://aclanthology.org/2024.emnlp-main.339/) - Hatzel & Biemann (EMNLP 2024).

### Motif detection, indexing & classification

- [Learning a Better Motif Index: Toward Automated Motif Extraction](https://doi.org/10.4230/OASIcs.CMN.2016.7) - Yarlott & Finlayson (CMN 2016); supervised extraction of known and novel folklore motifs.
- [Teaching Tale Types to a Computer](https://doi.org/10.1515/fabula-2023-0005) - Eklund, Hagedorn & Darányi (Fabula, 2023); SVM over TF-IDF on the ten best-populated ATU classes.
- [Testing and Adapting the Representational Abilities of Large Language Models on Folktales in Low-Resource Languages](https://aclanthology.org/2024.nlp4dh-1.31/) - Meaney, Alex & Lamb (NLP4DH, 2024); compares LLMs and classical baselines on low-resource folktales.
- [Large language models for folktale type automation based on motifs: Cinderella case study](https://arxiv.org/abs/2510.18561) - Arčon, Robnik-Šikonja & Tratnik (preprint, 2025); zero-shot motif-presence checks and critique of rigid motif typologies.
- [Automated Motif Indexing on the Arabian Nights](https://arxiv.org/pdf/2603.19283) - Alyami & Finlayson (preprint, 2026); fine-tuned Llama-3 evaluated against known index entries.
- [Mining Motifs in Fairy Tales](https://aclanthology.org/2026.oracle-main.16/) - Shahsavari, Mayer & Suchanek (ORACLE/ACL, 2026); LLM-generated motif descriptions followed by embeddings and clustering.

### Comparative mythology, cultural evolution & phylogenetics

- [Comparative phylogenetic analyses uncover the ancient roots of Indo-European folktales](https://doi.org/10.1098/rsos.150645) - Sara Graça da Silva & Jamshid Tehrani (R. Soc. Open Sci., 2016).
- [The Phylogeny of Little Red Riding Hood](https://doi.org/10.1371/journal.pone.0078871) - Tehrani (PLoS ONE, 2013).
- [Polyphemus: a Palaeolithic tale?](https://shs.hal.science/halshs-00932197/document) - d'Huy (2013); with [*The Cosmic Hunt*](https://shs.hal.science/halshs-02280068/document) (Nouvelle Mythologie Comparée 4, 2018), core works in his phylogenetic-mythology programme.
- [A Large-Scale Study of World Myths](https://doi.org/10.3176/tr.2018.4.05) - Thuillard, Le Quellec, d’Huy & Berezkin (*Trames*, 2018, 22(4), 407–424); network and clustering analysis of motif geography.
- [Worldwide patterns in mythology echo the human expansion out of Africa](https://www.biorxiv.org/content/10.1101/2025.01.24.634692v1.full) - Motif distances compared with geographic and genetic distances on the Berezkin catalogue (bioRxiv, 2025).

### Networks & quantitative approaches

- [Universal Properties of Mythological Networks](https://doi.org/10.1209/0295-5075/99/28002) - Mac Carron & Kenna (EPL, 2012).

### Data, corpora & infrastructure

- [GOLEM](https://aclanthology.org/2024.lrec-main.689.pdf) - Yarlott et al. (LREC-COLING 2024); the corpus is listed above.
- [Kestemont et al. "Forgotten Books"](https://doi.org/10.1126/science.abl7655) - Survival estimation of medieval narrative (Science, 2022).
- [MOMFER: A Search Engine of Thompson's Motif-Index](https://doi.org/10.1080/0015587X.2015.1006954) - Karsdorp, van der Meulen, Meder & van den Bosch (Folklore, 2015); semantic rather than string search over the TMI.

## Scholars & labs

Researchers and groups working on computational folkloristics, narrative analysis, cultural evolution, and the digital study of myth. The list is selective rather than exhaustive; entries are grouped by their main research connection to this field.

### Computational folkloristics, narrative, and text analysis

- [Timothy R. Tangherlini](https://cstms.berkeley.edu/people/timothy-tangherlini/) - Computational approaches to folklore, literature, and culture; studies the circulation of stories, legends, and rumors through social networks.
- [Folgert Karsdorp](https://www.karsdorp.io/) - Computational cultural evolution; develops quantitative methods to study cultural change, diversity, and transmission while accounting for biases in historical collections.
- [Theo Meder](https://meertens.knaw.nl/en/medewerker/meder-prof-dr-th-theo-2/) - Dutch folktales and storytelling culture; coordinates the Dutch Folktale Database and works on the documentation and transmission of folk narratives.
- [Mark A. Finlayson](https://users.cs.fiu.edu/~markaf/) - Computational models of narrative, narrative structure extraction, story understanding, and richly annotated story corpora.
- [Franziska Pannach](https://fpannach.github.io/) - NLP and Semantic Web methods for mythological and folkloric narratives; involved in the GOLEM and STRATA projects.
- [Mike Kestemont](https://www.uantwerpen.be/en/staff/mike-kestemont/research/) - Computational humanities, machine learning, stylometry, and quantitative analysis of historical and premodern texts.
- [Gerhard Lauer](https://researchprofiles.uni-mainz.de/12914-gerhard-lauer) - Computational folktale studies and quantitative approaches to the history and transmission of narrative traditions.
- [Antal van den Bosch](https://www.uu.nl/staff/APJvandenBosch) - Computational linguistics and language technology, including methods relevant to the analysis of historical and cultural text collections.

### Comparative mythology and cultural evolution

- [Jamshid J. Tehrani](https://duracuk-www01-production.terminalfour.net/staff/jamie-tehrani/) - Cultural evolution and phylogenetic approaches to the transmission and diversification of folktales and other popular narratives.
- [Sara Graça da Silva](https://novaresearch.unl.pt/en/persons/sara-gra%C3%A7a-da-silva/) - Comparative and evolutionary approaches to folktales, including the distribution and history of narrative motifs.
- [Julien d’Huy](https://college-de-france.academia.edu/JuliendHuy) - Computational and phylogenetic approaches to comparative mythology and the reconstruction of myth histories.
- [Jean-Loïc Le Quellec](https://www.cnrseditions.fr/auteur/jean-loic-le-quellec/) - Comparative mythology, rock art, and the geographic and historical distribution of mythological motifs.
- [Yuri Berezkin](https://eusp.org/people/berezkin) - Comparative mythology and the geographic distribution of folklore and mythological motifs; compiler of a large-scale analytical catalogue of world mythology.
- Ralph Kenna and [Pádraig Mac Carron](https://pure.ul.ie/en/persons/padraig-maccarron/) - Network-science approaches to mythology and the quantitative analysis of mythological narratives.
- [Marc Thuillard](https://orcid.org/0009-0006-6007-1427) - Quantitative and geographic analysis of world-myth motif distributions.

### Research groups and labs in folkloristics and cultural analysis

- [CognAC Lab — Florida International University](https://cognac.cs.fiu.edu/) - Computational modeling of culture, narrative, language, and cognition; research combines AI, NLP, cognitive science, and digital humanities.
- [Meertens Institute](https://meertens.knaw.nl/en/) - Dutch research institute for language and culture, including ethnology, oral culture, and the documentation and study of folk narratives.
- [Cultural Analytics Lab, UC Berkeley](https://culturalanalytics.berkeley.edu/) - Develops computational methods for studying cultural production, including literature and folklore, using NLP, machine learning, and network analysis.
- [DFG Myth Research Group STRATA](https://fmw.iza.uni-goettingen.de/de/556429.html) - Research group (2019–2023) investigating layers and historical development of ancient mythological narratives through textual and comparative analysis.

### Cultural evolution and adjacent research centres

- [GOLEM — Graphs and Ontologies for Literary Evolution Models](https://golemlab.eu/) - Research project developing graph- and ontology-based methods to study the evolution of literary works and cultural traits, using fanfiction corpora; its connection to folklore is comparative and methodological.
- [Max Planck Institute for Evolutionary Anthropology — Linguistic and Cultural Evolution](https://www.eva.mpg.de/linguistic-and-cultural-evolution/) - Research on the evolution, diversity, and transmission of language and culture, providing broader evolutionary frameworks relevant to narrative transmission.
- [Center for Digital Narrative, University of Bergen](https://www4.uib.no/en/research/research-centres/center-for-digital-narrative) - Humanities-led research on digital narrative and computational storytelling, including work on algorithmic folklore and changing cultural forms.
- [Computational Narrative Systems, University of Bergen](https://www4.uib.no/en/research/research-groups/computational-narrative-systems) - Research group within the Center for Digital Narrative combining narrative theory, computational creativity, and computer science to model narrative systems.
- [Narrative Intelligence Lab, Columbia University](https://nil.columbia.edu/) - Studies how stories shape shared beliefs, combining literary theory, sociology, linguistics, and computation.

## Venues & journals

- [CHR](https://computational-humanities-research.org/) - Computational Humanities Research.
- [ADHO Digital Humanities (DH)](https://adho.org/conference/) - The annual DH conference.
- [LaTeCH-CLfL](https://sighum.wordpress.com/) - NLP for Cultural Heritage, Social Sciences & Literature (ACL SIGHUM).
- [ISFNR](https://www.isfnr.org/) - International Society for Folk Narrative Research.
- [CMN](https://narrative.csail.mit.edu/) - Computational Models of Narrative.
- [NLP4DH](https://www.nlp4dh.com/) - NLP for Digital Humanities workshop.
- [AI4DH](https://ai4dh.eu) - AI methods for research of folkloristic narratives (Ljubljana strand).
- [Fabula](https://www.degruyter.com/journal/key/fabl/html) - Journal of folktale studies.
- [Journal of American Folklore](https://www.jstor.org/journal/jamerfolk) - Journal of the American Folklore Society.
- [Journal of Cultural Analytics](https://culturalanalytics.org) - Computational cultural studies.
- [Journal of Folklore Research](https://iupress.org/journals/jfr/) - Folklore journal from Indiana University Press.
- [Folklore](https://www.tandfonline.com/journals/rfol20) - Journal of the Folklore Society.
- [Journal of Open Humanities Data](https://openhumanitiesdata.metajnl.com) - For corpus and dataset papers.
- [Evolutionary Human Sciences](https://www.cambridge.org/core/journals/evolutionary-human-sciences) - Where folktale phylogenetics and cultural-evolution results usually land.
- [Royal Society Open Science](https://royalsocietypublishing.org/journal/rsos) - The other usual home for them, including the da Silva & Tehrani paper.

## Projects

- [Mythoscope](https://mythoscope.io) - A comparative-mythology framework: semantic space + LLM-extracted graphs + a TMI↔ATU↔Berezkin motif crosswalk. *(This list is maintained by a Mythoscope contributor; it is a neutral community resource.)*

GOLEM, MANTO, DRH and GLOS are listed in the sections above.

## See also

- [awesome-nlp](https://github.com/keon/awesome-nlp) - Natural language processing.
- [awesome-digital-humanities](https://github.com/dh-tech/awesome-digital-humanities) - Digital humanities.
- [awesome-computational-social-science](https://github.com/gesiscss/awesome-computational-social-science) - Computational social science.
- [awesome-network-analysis](https://github.com/briatte/awesome-network-analysis) - Network analysis.

Suggest more via PR.

## Contributing

Contributions welcome! Read [contributing.md](contributing.md) and open a pull request. Entry format: `- [Name](https://…) - Description.` (papers: `- [Title](https://…) - Author(s) (venue, year).`). By contributing you agree to the [code of conduct](code-of-conduct.md).
