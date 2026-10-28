# Awesome Computational Mythology [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

> A curated list of resources for the computational, comparative, and quantitative study of myth, folklore, and traditional narrative — indexes, corpora, datasets, methods, tools, ontologies, key papers, scholars, venues, and text libraries.

**Scope.** Resources for studying myth/folklore/traditional narrative *computationally, comparatively, or quantitatively*. **In:** indexes, corpora, datasets, methods, tools, ontologies, quantitative/DH studies, text libraries. **Out:** general mythology retellings, single-tradition popularizations, and non-computational reference works (unless a standard apparatus like TMI/ATU). This is a **neutral community list**.

## Contents

- [Motif & tale-type indexes](#motif--tale-type-indexes)
- [Corpora & annotated datasets](#corpora--annotated-datasets)
- [Cross-cultural & areal databases](#cross-cultural--areal-databases)
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
- [Christiansen — *The Migratory Legends* (ML)](https://en.wikipedia.org/wiki/Reidar_Thoralf_Christiansen) - The migratory-legend type index (FFC 175, 1958).
- [СУС (Sravnitel'nyj Ukazatel' Sjuzhetov)](https://ruthenia.ru/folklore/bspisok.html) - The East-Slavic comparative tale-type index (Barag et al., Leningrad, 1979); the link is a bibliography of folklore indexes that records it.
- [Perry Index](https://en.wikipedia.org/wiki/Perry_Index) - Aesopic fable types.

## Corpora & annotated datasets

- [GOLEM](https://aclanthology.org/2024.lrec-main.689/) - Gold-standard motif corpus (Yarlott et al., LREC-COLING 2024): 7,955 articles, 26,078 motif candidates over 34 types, labelled for *use*-type; few-shot classification of that use-type peaks at only 41%, which is what makes it a hard benchmark.
- [Annotated Folktales / "Trilogy"](https://github.com/j-hagedorn/trilogy) - Open ATU-annotated corpus (Hagedorn & Darányi, 2022) of 1,518 texts over 182 tale types (CC-BY-SA); the [data paper](https://openhumanitiesdata.metajnl.com/articles/10.5334/johd.78) is in *Journal of Open Humanities Data*. An SVM over TF-IDF on its ten best-populated classes reaches F1 0.8–1.0 (Eklund et al. 2023, below).
- [Dutch Folktale Database (Verhalenbank)](https://www.verhalenbank.nl) - The Meertens Institute folktale collection.
- [ISEBEL](https://isebel.eu/) - Cross-archive search over multiple European folk-narrative databases.
- [FairytaleQA](https://github.com/neuhai/FairytaleQA_Dataset) - Question-answering dataset over fairy tales.
- [Multilingual Folk Tale Database (MFTD)](http://www.mftd.org) - Folk tales and their translations in many languages; the site is temporarily offline.
- [Ashliman's Folktexts](https://sites.pitt.edu/~dash/folktexts.html) - D. L. Ashliman's ATU-organized folklore archive.
- [ProppLearner](https://academic.oup.com/dsh/article/32/2/284/2957394) - Proppian-function-annotated Russian folktales (Finlayson).
- [Kestemont et al. "Forgotten Books"](https://doi.org/10.1126/science.abl7655) - Survival estimation of medieval narrative (Science, 2022).
- [Arabian Nights motif corpus](https://arxiv.org/abs/2603.19283) - 2,670 motif expressions over 200 motifs in 58,450 sentences, indexed against El-Shamy (Alyami & Finlayson, 2026; preprint); the first motif-indexing corpus for a single work.
- [MIME](https://aclanthology.org/2024.nlpcss-1.4/) - Reports on a motif's *implicit* meaning drawn from indexes, Wikipedia, informants and social media (Acharya et al., NLP+CSS 2024); concludes culture-bearer input is not optional.

## Cross-cultural & areal databases

- [D-PLACE](https://d-place.org) - Database of Places, Language, Culture and Environment (incl. the *Ethnographic Atlas*; subsistence, social structure).
- [Glottolog](https://glottolog.org) - Language classification and family metadata.
- [Seshat: Global History Databank](https://seshatdatabank.info) - Structured data on past societies.
- [Database of Religious History (DRH)](https://religiondatabase.org) - Expert-coded data on religious groups and places.
- [eHRAF World Cultures](https://ehrafworldcultures.yale.edu/) - Ethnography (Yale HRAF; subscription).
- [MANTO](https://www.manto-myth.org) - Greek myth entities/relations database.
- [Theoi Greek Mythology](https://www.theoi.com) - Greek mythology reference with primary-source quotations.
- [historical-basemaps](https://github.com/aourednik/historical-basemaps) - Dated world political boundaries as GeoJSON (CC-BY-SA); the usual source for testing historical contact corridors.

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
- [Dúchas](https://www.duchas.ie) - National Folklore Collection of Ireland.
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
- [GLOS — Geographic Lens on Stories](https://kgeographer.org/glos/) - Geographic modelling of stories (Grossner et al.).
- [SKOS](https://www.w3.org/2004/02/skos/) - Vocabulary standard.
- [lemon](https://www.w3.org/2016/05/ontolex/) - Lexicon model (OntoLex-Lemon).
- [CIDOC-CRM](https://cidoc-crm.org/) - Cultural-heritage ontology.
- [Wikidata P2540](https://www.wikidata.org/wiki/Property:P2540) - Wikidata property for the ATU tale-type ID.

## Methods & techniques

- [Motif induction / detection from text](https://en.wikipedia.org/wiki/Motif_(folkloristics)) - The open problem; formally fluid motifs, weak detectors, classical baselines competitive with LLMs.
- [Tale-type / narrative classification](https://en.wikipedia.org/wiki/Document_classification) - SVM+TF-IDF, transformers, story embeddings.
- [Topic modeling](https://en.wikipedia.org/wiki/Topic_model) - LDA, Labeled-LDA, BERTopic (+ c-TF-IDF, KeyBERT).
- [Embeddings](https://en.wikipedia.org/wiki/Sentence_embedding) - SBERT/Sentence-Transformers, LaBSE, BGE-M3, E5; **story embeddings** (plot- not style-similarity).
- [Dimensionality reduction & clustering](https://umap-learn.readthedocs.io/) - UMAP, t-SNE; HDBSCAN; NeighborNet.
- [Phylogenetics of narrative](https://en.wikipedia.org/wiki/Computational_phylogenetics) - Bayesian phylogenetics (BEAST, MrBayes), ancestral-state reconstruction, phylomemetics.
- [Seriation & pseudo-time](https://en.wikipedia.org/wiki/Seriation_(archaeology)) - Correspondence-analysis seriation; single-cell pseudotime (DPT, Slingshot) applied to motif ordering.
- [Networks](https://en.wikipedia.org/wiki/Network_motif) - Character-interaction networks; network motifs (mfinder, FANMOD); block models; nestedness (NODF).
- [Cross-cultural statistics](https://en.wikipedia.org/wiki/Galton%27s_problem) - Galton's problem, restricted-permutation nulls, Mantel tests, F_st, resistance surfaces.
- [Dating & chronology](https://en.wikipedia.org/wiki/Tip_dating) - Tip-dating ([review, Syst. Biol. 2026](https://academic.oup.com/sysbio/article/75/1/156/8262818)), language-tree calibration, and models that admit horizontal transfer ([Hum. Soc. Sci. Commun. 2022](https://www.nature.com/articles/s41599-022-01211-7)); biogeographic bounds and textual *terminus ante quem* floors.

## Tools & software

- [MOMFER](https://momfer.meertens.knaw.nl/) - Motif finder over the Dutch Folktale Database.
- [Sentence-Transformers](https://www.sbert.net) - Embedding infrastructure.
- [BERTopic](https://maartengr.github.io/BERTopic/) - Topic modeling.
- [SplitsTree](https://software-ab.cs.uni-tuebingen.de/download/splitstree6/) - Phylogenetic networks.
- [BEAST2](https://www.beast2.org) - Bayesian phylogenetics.
- [MrBayes](https://nbisweden.github.io/MrBayes/) - Bayesian phylogenetics.
- [Gephi](https://gephi.org) - Network analysis.
- [FANMOD](https://doi.org/10.1093/bioinformatics/btl038) - Network-motif detection (Wernicke & Rasche, Bioinformatics 2006).
- [`uhhlt/story-emb`](https://huggingface.co/uhhlt/story-emb) - Story-similarity embedding model (Hatzel & Biemann).
- [MALLET](http://mallet.cs.umass.edu/) - The LDA implementation most of the field's topic-model work was built on.

## Landmark papers

- [Universal Properties of Mythological Networks](https://doi.org/10.1209/0295-5075/99/28002) - Mac Carron & Kenna (EPL, 2012).
- [Computational Folkloristics](https://doi.org/10.1145/2209249.2209267) - Abello, Broadwell & Tangherlini (CACM, 2012).
- [Comparative phylogenetic analyses uncover the ancient roots of Indo-European folktales](https://doi.org/10.1098/rsos.150645) - Sara Graça da Silva & Jamshid Tehrani (R. Soc. Open Sci., 2016).
- [The Phylogeny of Little Red Riding Hood](https://doi.org/10.1371/journal.pone.0078871) - Tehrani (PLoS ONE, 2013).
- [Polyphemus: a Palaeolithic tale?](https://shs.hal.science/halshs-00932197/document) - d'Huy (2013); with [*The Cosmic Hunt*](https://shs.hal.science/halshs-02280068/document) (Nouvelle Mythologie Comparée 4, 2018), the core of his phylogenetic-mythology programme (2013–).
- [Story Embeddings](https://aclanthology.org/2024.emnlp-main.339/) - Hatzel & Biemann (EMNLP 2024).
- [GOLEM](https://aclanthology.org/2024.lrec-main.689.pdf) - Yarlott et al. (LREC-COLING 2024); the corpus, listed under corpora above.
- [A Very Brief History of Computational Folkloristics](https://doi.org/10.1515/fabula-2023-0001) - Lauer (Fabula, 2023).
- [MOMFER: A Search Engine of Thompson's Motif-Index](https://doi.org/10.1080/0015587X.2015.1006954) - Karsdorp, van der Meulen, Meder & van den Bosch (Folklore, 2015); semantic rather than string search over the TMI.
- [Teaching Tale Types to a Computer](https://doi.org/10.1515/fabula-2023-0005) - Eklund, Hagedorn & Darányi (Fabula, 2023); SVM over TF-IDF on the ten best-populated ATU classes.
- [Testing and Adapting the Representational Abilities of Large Language Models on Folktales in Low-Resource Languages](https://aclanthology.org/2024.nlp4dh-1.31/) - Meaney, Alex & Lamb (NLP4DH, 2024); the field's clearest head-to-head: a non-contextual SVM baseline stays competitive with adapted transformers.
- [Large language models for folktale type automation based on motifs: Cinderella case study](https://arxiv.org/abs/2510.18561) - Arčon, Robnik-Šikonja & Tratnik (preprint, 2025); zero-shot motif-presence checks, and an argument that the motif typology itself is too rigid.
- [Automated Motif Indexing on the Arabian Nights](https://arxiv.org/pdf/2603.19283) - Alyami & Finlayson (preprint, 2026); a fine-tuned Llama-3 at 0.85 F1 against a known index entry; the corpus is listed above.
- [Worldwide patterns in mythology echo the human expansion out of Africa](https://www.biorxiv.org/content/10.1101/2025.01.24.634692v1.full) - Motif distances against geographic and genetic distance on the Berezkin catalogue (bioRxiv, 2025).

## Scholars & labs

Timothy Tangherlini · Folgert Karsdorp · Theo Meder · Antal van den Bosch · Dong Nguyen · Mark Finlayson · Julien d'Huy · Jean-Loïc Le Quellec · Marc Thuillard · Yuri Berezkin · Jamshid Tehrani · Sara Graça da Silva · Mike Kestemont · Ralph Kenna · Pádraig Mac Carron · Thierry Declerck · Gerhard Lauer · Peter Broadwell · James Abello · Karl Grossner · Hans-Jörg Uther · Katja Mellmann · Elena Duvakin · Sándor Darányi · Josh Hagedorn · Johan Eklund · Victor Yarlott · William Lamb · Beatrice Alex · Marko Robnik-Šikonja.

Groups: the **[Meertens Institute](https://meertens.knaw.nl)** (Dutch Folktale Database, MOMFER) · the **Cognac Lab** at FIU (motif detection, GOLEM) · Durham's cultural-evolution group · the **[Max Planck Institute for Evolutionary Anthropology](https://www.eva.mpg.de/linguistic-and-cultural-evolution/)** · Edinburgh (Gaelic folktale NLP).

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
