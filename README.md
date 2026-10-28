# Awesome Computational Mythology [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

> A curated list of resources for the computational, comparative, and quantitative study of
> myth, folklore, and traditional narrative — indexes, corpora, datasets, methods, tools,
> ontologies, key papers, scholars, venues, and text libraries.

**Scope.** Resources for studying myth/folklore/traditional narrative *computationally,
comparatively, or quantitatively*. **In:** indexes, corpora, datasets, methods, tools,
ontologies, quantitative/DH studies, text libraries. **Out:** general mythology retellings,
single-tradition popularizations, and non-computational reference works (unless a standard
apparatus like TMI/ATU). This is a **neutral community list**.

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
- [Contributing](#contributing)

## Motif & tale-type indexes

- **Thompson Motif-Index (TMI)** — Stith Thompson, *Motif-Index of Folk-Literature*, rev. ed.
  1955–58. ~46,000 narrative motifs, place-value taxonomy (A–Z). Digital editions: the
  *Trilogy* CSVs, Katja Mellmann's `TMI_as_CSV`, [`fbkarsdorp/tmi`](https://github.com/fbkarsdorp/tmi), folkmasa.org.
- **Aarne–Thompson–Uther (ATU)** — Hans-Jörg Uther, *The Types of International Folktales*,
  FFC 284–286 (Helsinki, 2004). 2,247 tale types. Successor to Aarne–Thompson (AaTh/AT).
- **Berezkin & Duvakin — Analytical Catalogue of World Mythology and Folklore** — 3,488 areal
  motifs in 14 lettered chapters, attested across ~1,050 traditions and 65 macro-areas
  ([areasofmyths.com](https://www.areasofmyths.com) / mapsofmyths.com; per-tradition map coordinates published with it).
  Described by its compiler in [*Folklore and mythology catalogue: its lay-out and potential for
  research*](https://sisu.ut.ee/wp-content/uploads/sites/172/berezkin_folklore_and_mythology_catalogue_its_lay-1_out_and_potential_for_research.pdf) (RMN Newsletter 10, 2015).
- **El-Shamy — *Motif Index of the Thousand and One Nights*** and *Folk Traditions of the Arab
  World*.
- **Christiansen — *The Migratory Legends* (ML)** — the migratory-legend type index.
- **СУС (Sravnitel'nyj Ukazatel' Sjuzhetov)** — the East-Slavic comparative tale-type index.
- **Perry Index** — Aesopic fable types.

## Corpora & annotated datasets

- **[GOLEM](https://aclanthology.org/2024.lrec-main.689/)** (Yarlott et al., LREC-COLING 2024) — gold-standard motif corpus: 7,955 articles,
  26,078 motif candidates over 34 types, labelled for *use*-type; few-shot classification of that
  use-type peaks at only 41%, which is what makes it a hard benchmark.
- **[Annotated Folktales / "Trilogy"](https://github.com/j-hagedorn/trilogy)** (Hagedorn & Darányi, 2022) — open ATU-annotated corpus
  of 1,518 texts over 182 tale types (CC-BY-SA); the [data
  paper](https://openhumanitiesdata.metajnl.com/articles/10.5334/johd.78) is in *Journal of Open Humanities Data*. An SVM over TF-IDF on its ten
  best-populated classes reaches F1 0.8–1.0 (Eklund et al. 2023, below).
- **[MOMFER](https://momfer.meertens.knaw.nl/)** — the Meertens Motif Finder over the Dutch Folktale Database.
- **[Dutch Folktale Database (Verhalenbank)](https://www.verhalenbank.nl)** — the Meertens Institute folktale collection.
- **[ISEBEL](https://isebel.eu/)** — cross-archive search over multiple European folk-narrative databases.
- **[FairytaleQA](https://github.com/neuhai/FairytaleQA_Dataset)** — question-answering dataset over fairy tales.
- **Multilingual Folk Tale Database (MFTD)** — [mftd.org](http://www.mftd.org).
- **[Ashliman's Folktexts](https://sites.pitt.edu/~dash/folktexts.html)** — D. L. Ashliman's ATU-organized folklore archive.
- **[ProppLearner](https://academic.oup.com/dsh/article/32/2/284/2957394)** — Proppian-function-annotated Russian folktales (Finlayson).
- **[Kestemont et al. "Forgotten Books"](https://doi.org/10.1126/science.abl7655)** (Science, 2022) — survival estimation of medieval
  narrative.
- **[Arabian Nights motif corpus](https://arxiv.org/abs/2603.19283)** (Alyami & Finlayson, 2026; preprint) — 2,670 motif expressions over
  200 motifs in 58,450 sentences, indexed against El-Shamy; the first motif-indexing corpus for a
  single work.
- **[MIME](https://aclanthology.org/2024.nlpcss-1.4/)** (Acharya et al., NLP+CSS 2024) — reports on a motif's *implicit* meaning drawn
  from indexes, Wikipedia, informants and social media; concludes culture-bearer input is not optional.

## Cross-cultural & areal databases

- **[D-PLACE](https://d-place.org)** — Database of Places, Language, Culture and Environment
  (incl. the *Ethnographic Atlas*; subsistence, social structure).
- **[Glottolog](https://glottolog.org)** — language classification + family metadata.
- **[Seshat: Global History Databank](https://seshatdatabank.info)**.
- **[Database of Religious History (DRH)](https://religiondatabase.org)**.
- **eHRAF World Cultures** — ethnography (Yale HRAF; subscription).
- **[MANTO](https://www.manto-myth.org)** — Greek myth entities/relations database.
- **[Theoi Greek Mythology](https://www.theoi.com)**.
- **[historical-basemaps](https://github.com/aourednik/historical-basemaps)** — dated world political boundaries as GeoJSON (CC-BY-SA);
  the usual source for testing historical contact corridors.

## Digital text libraries

- **[Perseus Digital Library](http://www.perseus.tufts.edu)** (+ First1KGreek).
- **[Internet Sacred Text Archive](https://www.sacred-texts.com)**.
- **[ETCSL](https://etcsl.orinst.ox.ac.uk)** — Electronic Text Corpus of Sumerian Literature.
- **[ORACC](http://oracc.museum.upenn.edu)** — Open Richly Annotated Cuneiform Corpus.
- **[Thesaurus Linguae Aegyptiae](https://thesaurus-linguae-aegyptiae.de)**.
- **[GRETIL](https://gretil.sub.uni-goettingen.de)** — electronic texts in Indian languages.
- **[Chinese Text Project](https://ctext.org)**.
- **[CBETA](https://www.cbeta.org)** — Chinese Buddhist Electronic Text Association.
- **[SuttaCentral](https://suttacentral.net)** — early Buddhist texts.
- **[Sefaria](https://www.sefaria.org)** — Jewish texts.
- **[CELT](https://celt.ucc.ie)** — Corpus of Electronic Texts (Irish).
- **[Dúchas](https://www.duchas.ie)** — National Folklore Collection of Ireland.
- **[OpenITI](https://openiti.org)** — Open Islamicate Texts Initiative.
- **[TITUS](https://titus.uni-frankfurt.de)** — Indo-European text materials.
- **[Digital Corpus of Sanskrit](http://www.sanskrit-linguistics.org/dcs/)** — morphologically analysed Sanskrit.
- **[Heimskringla.no](https://heimskringla.no)** · **[Icelandic Saga Database](https://sagadb.org/downloads)** — Old Norse–Icelandic texts.
- **[SEAL](https://seal.huji.ac.il/)** — Sources of Early Akkadian Literature.
- **[Hethitologie-Portal Mainz](https://www.hethport.uni-wuerzburg.de/)** — Hittite text corpus and concordance.
- **[Avesta.org](https://www.avesta.org/)** — Zoroastrian archives.
- **[SAT Daizōkyō](https://21dzk.l.u-tokyo.ac.jp/SAT/)** · **[Kanripo](https://www.kanripo.org/)** — Buddhist and classical Chinese canons.
- **[BDRC](https://www.bdrc.io/)** — Buddhist Digital Resource Center (Tibetan).
- **[Project Gutenberg](https://www.gutenberg.org)** · **[Internet Archive](https://archive.org)**
  · **[HathiTrust](https://www.hathitrust.org)**.

## Encyclopedias & reference works

- **The Mythology of All Races** (Gray/Moore, 13 vols).
- **Encyclopedia of Religion** (Eliade, ed.; 2nd ed. Jones).
- **Мифы народов мира** (Tokarev, ed.) — the two-volume Soviet mythological encyclopedia.
- **Dictionary of Mythology** (Bonnefoy, *Mythologies*).
- **New Larousse Encyclopedia of Mythology**.
- **Wörterbuch der Mythologie** (Haussig, ed.).
- **Enzyklopädie des Märchens** — the reference encyclopedia of the folktale.

## Ontologies & linked open data

- **DFKI Linked Data for Folktales** (Declerck et al.) — OWL/RDF/SKOS + lemon modelling of
  ATU/TMI.
- **Ontology of Greek Mythology (OGM)**.
- **[GLOS — Geographic Lens on Stories](https://kgeographer.org/glos/)** (Grossner et al.).
- Vocabularies: **SKOS**, **lemon**, **CIDOC-CRM**; **Wikidata** property P2540 (ATU tale-type ID).

## Methods & techniques

- **Motif induction / detection from text** — the open problem; formally fluid motifs, weak
  detectors, classical baselines competitive with LLMs.
- **Tale-type / narrative classification** — SVM+TF-IDF, transformers, story embeddings.
- **Topic modeling** — LDA, Labeled-LDA, BERTopic (+ c-TF-IDF, KeyBERT).
- **Embeddings** — SBERT/Sentence-Transformers, LaBSE, BGE-M3, E5; **story embeddings**
  (plot- not style-similarity).
- **Dimensionality reduction & clustering** — UMAP, t-SNE; HDBSCAN; NeighborNet.
- **Phylogenetics of narrative** — Bayesian phylogenetics (BEAST, MrBayes), ancestral-state
  reconstruction, phylomemetics.
- **Seriation & pseudo-time** — correspondence-analysis seriation; single-cell pseudotime
  (DPT, Slingshot) applied to motif ordering.
- **Networks** — character-interaction networks; network motifs (mfinder, FANMOD); block
  models; nestedness (NODF).
- **Cross-cultural statistics** — Galton's problem, restricted-permutation nulls, Mantel
  tests, F_st, resistance surfaces.
- **Dating & chronology** — tip-dating ([review, Syst. Biol. 2026](https://academic.oup.com/sysbio/article/75/1/156/8262818)), language-tree
  calibration, and models that admit horizontal transfer ([Hum. Soc. Sci. Commun.
  2022](https://www.nature.com/articles/s41599-022-01211-7)); biogeographic bounds and textual *terminus ante quem* floors.

## Tools & software

- **[MOMFER](https://momfer.meertens.knaw.nl/)** — motif finder over the Dutch Folktale Database.
- **[Sentence-Transformers](https://www.sbert.net)** — embedding infrastructure.
- **[BERTopic](https://maartengr.github.io/BERTopic/)** — topic modeling.
- **[SplitsTree](https://software-ab.cs.uni-tuebingen.de/download/splitstree6/)** /
  **[BEAST2](https://www.beast2.org)** / **[MrBayes](https://nbisweden.github.io/MrBayes/)** —
  phylogenetics.
- **[Gephi](https://gephi.org)** / **FANMOD** — network analysis / network motifs.
- **[`uhhlt/story-emb`](https://huggingface.co/uhhlt/story-emb)** — story-similarity embedding model (Hatzel & Biemann).
- **[MALLET](http://mallet.cs.umass.edu/)** — the LDA implementation most of the field's topic-model work was built on.

## Landmark papers

- Mac Carron & Kenna — [*Universal Properties of Mythological Networks*](https://doi.org/10.1209/0295-5075/99/28002) (EPL, 2012).
- Abello, Broadwell & Tangherlini — [*Computational Folkloristics*](https://doi.org/10.1145/2209249.2209267) (CACM, 2012).
- da Silva & Tehrani — [*Comparative phylogenetic analyses uncover the ancient roots of
  Indo-European folktales*](https://doi.org/10.1098/rsos.150645) (R. Soc. Open Sci., 2016).
- Tehrani — [*The Phylogeny of Little Red Riding Hood*](https://doi.org/10.1371/journal.pone.0078871) (PLoS ONE, 2013).
- d'Huy — *Cosmic Hunt* / phylogenetic mythology (2013–).
- Hatzel & Biemann — [*Story Embeddings*](https://aclanthology.org/2024.emnlp-main.339/) (EMNLP 2024).
- Yarlott et al. — [*GOLEM*](https://aclanthology.org/2024.lrec-main.689/) (LREC-COLING 2024).
- Lauer — [*A Very Brief History of Computational Folkloristics*](https://doi.org/10.1515/fabula-2023-0001) (Fabula, 2023).
- Karsdorp, van der Meulen, Meder & van den Bosch — [*MOMFER: A Search Engine of Thompson's
  Motif-Index*](https://doi.org/10.1080/0015587X.2015.1006954) (Folklore, 2015) — semantic rather than string search over the TMI.
- Eklund, Hagedorn & Darányi — [*Teaching Tale Types to a Computer*](https://doi.org/10.1515/fabula-2023-0005) (Fabula, 2023) — SVM over
  TF-IDF on the ten best-populated ATU classes.
- Meaney, Alex & Lamb — [*Testing and Adapting the Representational Abilities of Large Language
  Models on Folktales in Low-Resource Languages*](https://aclanthology.org/2024.nlp4dh-1.31/) (NLP4DH, 2024) — the field's clearest
  head-to-head: a non-contextual SVM baseline stays competitive with adapted transformers.
- Arčon, Robnik-Šikonja & Tratnik — [*Large language models for folktale type automation based on
  motifs: Cinderella case study*](https://arxiv.org/abs/2510.18561) (preprint, 2025) — zero-shot motif-presence checks, and an
  argument that the motif typology itself is too rigid.
- Alyami & Finlayson — [*Automated Motif Indexing on the Arabian Nights*](https://arxiv.org/abs/2603.19283) (preprint, 2026) — a
  fine-tuned Llama-3 at 0.85 F1 against a known index entry.
- d'Huy — [*Polyphemus: a Palaeolithic tale?*](https://shs.hal.science/halshs-00932197/document) (2013) and [*The Cosmic Hunt*](https://shs.hal.science/halshs-02280068/document) (Nouvelle
  Mythologie Comparée 4, 2018) — the phylogenetic-mythology programme.
- [*Worldwide patterns in mythology echo the human expansion out of Africa*](https://www.biorxiv.org/content/10.1101/2025.01.24.634692v1.full) (bioRxiv, 2025) —
  motif distances against geographic and genetic distance on the Berezkin catalogue.

## Scholars & labs

Timothy Tangherlini · Folgert Karsdorp · Theo Meder · Antal van den Bosch · Dong Nguyen ·
Mark Finlayson · Julien d'Huy · Jean-Loïc Le Quellec · Marc Thuillard · Yuri Berezkin ·
Jamshid Tehrani · Sara Graça da Silva · Mike Kestemont · Ralph Kenna · Pádraig Mac Carron ·
Thierry Declerck · Gerhard Lauer · Peter Broadwell · James Abello · Karl Grossner ·
Hans-Jörg Uther · Katja Mellmann · Elena Duvakin · Sándor Darányi · Josh Hagedorn ·
Johan Eklund · Victor Yarlott · William Lamb · Beatrice Alex · Marko Robnik-Šikonja.

Groups: the **[Meertens Institute](https://meertens.knaw.nl)** (Dutch Folktale Database, MOMFER) · the
the **Cognac Lab** at FIU (motif detection, GOLEM) · Durham's cultural-evolution group ·
the **[Max Planck Institute for Evolutionary Anthropology](https://www.eva.mpg.de/linguistic-and-cultural-evolution/)** · Edinburgh (Gaelic folktale NLP).

## Venues & journals

- **CHR** — Computational Humanities Research.
- **ADHO Digital Humanities (DH)** conference.
- **LaTeCH-CLfL** — NLP for Cultural Heritage, Social Sciences & Literature.
- **ISFNR** — International Society for Folk Narrative Research.
- **CMN** — Computational Models of Narrative.
- **NLP4DH** — NLP for Digital Humanities workshop.
- **[AI4DH](https://ai4dh.eu)** — AI methods for research of folkloristic narratives (Ljubljana strand).
- **[Fabula](https://www.degruyter.com/journal/key/fabl/html)** · **[Journal of American Folklore](https://www.jstor.org/journal/jamerfolk)** · **[Journal of Cultural
  Analytics](https://culturalanalytics.org)** · **Journal of Folklore Research** · **[Folklore](https://www.tandfonline.com/journals/rfol20)**.
- **[Journal of Open Humanities Data](https://openhumanitiesdata.metajnl.com)** — for corpus and dataset papers.
- **Evolutionary Human Sciences** · **Royal Society Open Science** — where folktale phylogenetics
  and cultural-evolution results usually land.

## Projects

- **[Mythoscope](https://mythoscope.io)** — a comparative-mythology framework: semantic space +
  LLM-extracted graphs + a TMI↔ATU↔Berezkin motif crosswalk. *(This list is maintained by a
  Mythoscope contributor; it is a neutral community resource.)*
- **GOLEM**, **MANTO**, **DRH**, **GLOS** — see above.

## See also

Related curated lists to cross-link with: *awesome-nlp*, *awesome-digital-humanities*,
*awesome-computational-social-science*, *awesome-network-analysis*. Suggest more via PR.

## Contributing

Contributions welcome! Read [contributing.md](contributing.md) and open a pull request. Entry
format: `**Name** — one-line description — link` (papers: `Author(s) — Title (venue, year)`).
By contributing you agree to the [code of conduct](code-of-conduct.md).

## License

[![CC0](https://licensebuttons.net/p/zero/1.0/88x31.png)](LICENSE)

To the extent possible under law, the maintainers have waived all copyright and related rights
to this work (CC0 1.0). Cite via [`CITATION.cff`](CITATION.cff).
