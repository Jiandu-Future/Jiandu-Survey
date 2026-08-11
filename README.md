# Computational Heritage of Ancient Chinese Bamboo and Wooden Slips from Preservation to Intelligent Interpretation

> **Jiandu-Survey** is a living survey and resource hub for computational research on ancient Chinese bamboo and wooden slips (簡牘 / 简牍), spanning **preservation, documentation, recovery, recognition, reconstruction, and intelligent interpretation**.

[![Survey](https://img.shields.io/badge/Type-Living%20Survey-blue)](https://github.com/Jiandu-Future/Jiandu-Survey)  [![Datasets](https://img.shields.io/badge/Resources-Datasets%20%26%20Benchmarks-orange)](#jiandu-datasets-and-benchmarks)

This repository accompanies the Review **“Computational Heritage of Ancient Chinese Bamboo and Wooden Slips from Preservation to Intelligent Interpretation.”** It curates online scholarly resources, datasets, code, representative publications, and methodological developments relevant to the computational study of Jiandu.

**Project page:** https://github.com/Jiandu-Future/Jiandu-Survey  
**Paper:** journal citation to be updated after publication  
**Last resource verification:** 2026-08-11

---

## Update History

- **2026-08-09** — Rebuilt the repository index from the latest 75-reference, five-figure Review manuscript.
- **2026-08-09** — Expanded the Online Resource section with Jiandu-specific data platforms, scholarly databases, rejoining resources, research centres, museums, and comparative textual/palaeographic resources.
- **2026-08-10** — Added a task-oriented Jiandu dataset and benchmark catalogue.
- **2026-08-11** — Aligned the README with the latest manuscript: seven evidence scales, dataset availability, author list, and updated bibliographic metadata.

> New datasets, papers, digital collections, code releases, corrected metadata, and stable project links will be added continuously.

---

### Inclusion principles

Resources are prioritized when they directly study ancient Chinese bamboo or wooden slips. Closely related work on ancient Chinese manuscripts, historical documents, oracle-bone inscriptions, or general heritage computing is included only when it supplies a method, benchmark, infrastructure principle, or evaluation framework that is directly transferable to Jiandu. Such entries are marked **Related / transferable** in the paper index.

The accompanying paper is a **narrative, problem-oriented Review** rather than a systematic or scoping review. Literature searches covered Web of Science (Core Collection), Scopus, China National Knowledge Infrastructure (CNKI), and Google Scholar; searches and online-resource checks were last updated on **11 August 2026**.

---

## Citation

The final journal citation will be added after publication. For pre-publication use:

```bibtex
@article{xu2026computationaljiandu,
  title   = {Computational Heritage of Ancient Chinese Bamboo and Wooden Slips from Preservation to Intelligent Interpretation},
  author  = {Xu, Cheng and Liu, Zhen and Zhang, Cheng and Yuan, Jiazheng and Chen, Lu and Yang, Yu and Zhou, Hua and Zhang, Ziying},
  year    = {2026},
  note    = {Review manuscript}
}
```

Repository citation:

```bibtex
@misc{jiandu_survey_2026,
  title        = {Jiandu-Survey: Computational Heritage of Ancient Chinese Bamboo and Wooden Slips},
  author       = {Xu, Cheng and Liu, Zhen and Zhang, Cheng and Yuan, Jiazheng and Chen, Lu and Yang, Yu and Zhou, Hua and Zhang, Ziying},
  year         = {2026},
  howpublished = {GitHub},
  url          = {https://github.com/Jiandu-Future/Jiandu-Survey}
}
```

---

## Table of Contents

- [Conceptual Framework](#conceptual-framework)
- [Online Resource](#online-resource)
  - [Core Jiandu Data and Scholarly Platforms](#core-jiandu-data-and-scholarly-platforms)
  - [Rejoining and Manuscript Reconstruction Resources](#rejoining-and-manuscript-reconstruction-resources)
  - [Research Centres and Scholarly Portals](#research-centres-and-scholarly-portals)
  - [Museums and Collection Portals](#museums-and-collection-portals)
  - [Related Textual and Palaeographic Resources](#related-textual-and-palaeographic-resources)
  - [Open Code and Dataset Repositories](#open-code-and-dataset-repositories)
- [Jiandu Datasets and Benchmarks](#jiandu-datasets-and-benchmarks)
  - [Recognition and Representation](#recognition-and-representation)
  - [Detection Binarization and Restoration](#detection-binarization-and-restoration)
  - [Multimodal and 3D Data](#multimodal-and-3d-data)
  - [Scribe Analysis](#scribe-analysis)
  - [Fragment Rejoining](#fragment-rejoining)
- [Paper Index: 75 References](#paper-index-75-references)
  - [Related surveys and field overviews](#related-surveys-and-field-overviews)
  - [Foundational Jiandu and manuscript studies](#foundational-jiandu-and-manuscript-studies)
  - [Conservation, deterioration and acquisition](#conservation-deterioration-and-acquisition)
  - [Digitization, standards and database infrastructure](#digitization-standards-and-database-infrastructure)
  - [Multimodal documentation, registration and geometry](#multimodal-documentation-registration-and-geometry)
  - [Image enhancement, detection, segmentation and binarization](#image-enhancement-detection-segmentation-and-binarization)
  - [Restoration, ink enhancement and super-resolution](#restoration-ink-enhancement-and-super-resolution)
  - [Character recognition and multigranular representation](#character-recognition-and-multigranular-representation)
  - [Fragment rejoining, scribe analysis and manuscript reconstruction](#fragment-rejoining-scribe-analysis-and-manuscript-reconstruction)
  - [Digital editions, knowledge, language models and agents](#digital-editions-knowledge-language-models-and-agents)
  - [FAIR data, provenance and trustworthy heritage AI](#fair-data-provenance-and-trustworthy-heritage-ai)
- [Research Gaps and Priorities](#research-gaps-and-priorities)
- [Repository Structure](#repository-structure)
- [Resource and Rights Notes](#resource-and-rights-notes)
- [Data Availability](#data-availability)
- [Maintainers](#maintainers)

---

# Conceptual Framework

The Review organizes Jiandu computational heritage across **seven interconnected evidence scales**:

```text
Material → Surface → Character → Fragment → Slip → Manuscript → Meaning
```

| Scale | Core evidence | Typical computational questions |
|---|---|---|
| **Material** | bamboo/wood composition, deterioration, moisture, fractures, conservation state | What survives, and what can be safely documented? |
| **Surface** | ink, stains, cracks, texture, curvature, spectral response | Which traces are observable under different modalities? |
| **Character** | strokes, components, variants, damaged glyphs | Detection, segmentation, restoration, recognition |
| **Fragment** | edges, fractures, texture, morphology, local refit compatibility | Edge analysis, matching, physics-guided refitting, relation modelling |
| **Slip** | dimensions, orientation, handwriting, layout, verso traces | Geometry/alignment, grouping, sequencing, scribe analysis |
| **Manuscript** | fragment/slip relations, binding evidence, order, textual continuity | Rejoining, sequencing, manuscript reconstruction |
| **Meaning** | transcription, linguistic annotation, parallels, historical context | Retrieval, knowledge integration, interpretation |

The seven scales are summarized into four analytical layers: **material condition → digital evidence → textual structure → scholarly interpretation**. Across the framework, **provenance, evidential sufficiency, uncertainty, cross-scale consistency, expert validation, transparency, and conservation ethics** are treated as cross-cutting requirements.

# Online Resource

> Access conditions change over time. The status below was checked on **2026-08-11**. Always follow the original institution's licence, copyright, registration, download, and citation requirements.

## Core Jiandu Data and Scholarly Platforms

| Resource | Institution / Type | Main value for Jiandu research | Access | Project Page |
|---|---|---|---|---|
| 简牍学术资源数据共享平台 / Jiandu Academic Resource Data Sharing Platform | Northwest Normal University | Integrated Jiandu resource platform; object, transcription, glyph, catalogue, literature and expert databases; intelligent search | Public portal; some resources subject to platform authorization/terms | https://jiandu.nwnu.edu.cn/ |
| DeepJiandu | Northwest Normal University / Science Data Bank | 7,416 infrared full-slip images; 99,852 annotated character instances; 2,242 categories | Public dataset | https://doi.org/10.57760/sciencedb.08560 |
| 武汉大学简帛网 / Center of Bamboo and Silk Manuscripts | Wuhan University | Jiandu scholarship, newly published research, reading notes, bibliography, academic news and links | Public scholarly portal | https://www.bsm.org.cn/ |
| 中国古代简帛字形、辞例数据库 / Ancient Bamboo-and-Silk Glyph & Concordance Database | Wuhan University | Searchable ancient glyph forms and contextual examples from Chu, Qin and Han bamboo/silk materials | Searchable; registration/access restrictions may apply | http://www.bsm.org.cn/zxcl/ |
| 简牍字典开发计划 / Jiandu Dictionary Development Project | Open Museum project | Open-database exploration for Jiandu glyph and lexicographic organization | Public project page | https://openmuseum.tw/muse/curation/3c5b9129f04f565bdb4e20558eeb369d |

## Rejoining and Manuscript Reconstruction Resources

| Resource | Institution / Project | Coverage | Access | Project Page |
|---|---|---|---|---|
| 贯联汗青：简牍缀合信息库 | Fudan University Center for Research on Chinese Excavated Classics and Paleography | More than 2,100 published rejoining records from major Northwestern Han-slip corpora; slip numbers, transcriptions, rejoiners, sources and notes | Free / continuously updated | https://www.fdgwz.org.cn/GuanLianHanQing/Home |
| WisePanda | Physics-driven fragment rejoining project | Bamboo236, Bamboo1350, Wood670 and Wood3833 benchmarks; physics-informed matching and rejoining | Interactive project; code/data subject to project terms | https://wisepanda.tech/ |
| WisePanda Code Ocean capsule | Code Ocean | Reproducible code resource for physics-driven rejoining | Public project capsule | https://codeocean.com/capsule/0259823/tree |

## Research Centres and Scholarly Portals

| Resource | Main relevance | Project Page |
|---|---|---|
| 清华大学出土文献研究与保护中心 / Tsinghua Research and Conservation Center for Excavated Texts | Tsinghua Warring States bamboo slips; excavated-text research, conservation, palaeography and the journal *Excavated Documents* | https://www.ctwx.tsinghua.edu.cn/ |
| 复旦大学出土文献与古文字研究中心 / Fudan Center for Research on Chinese Excavated Classics and Paleography | Excavated texts, palaeography, academic articles, research forums and rejoining resources | https://www.fdgwz.org.cn/ |
| 武汉大学简帛研究中心 / Center of Bamboo and Silk Manuscripts | Bamboo-and-silk manuscripts, palaeography, textual reconstruction and Jiandu scholarship | https://www.bsm.org.cn/ |
| *Bamboo and Silk* | Diamond Open Access peer-reviewed journal focused on excavated bamboo and silk manuscripts | https://brill.com/view/journals/bsms/bsms-overview.xml?language=en |
| 中国出土文献研究会 / Research Society for Chinese Excavated Texts | International scholarly resource focused on Warring States Chu slips, Qin slips, Han slips and related excavated texts | https://www.shutudo.org/ |

## Museums and Collection Portals

| Resource | Collection / Function | Project Page |
|---|---|---|
| 长沙简牍博物馆 / Changsha Jiandu Museum | Specialized museum for collection, conservation, research and display of bamboo and wooden slips | https://www.chinajiandu.cn/Home/Index |
| 甘肃简牍博物馆 / Gansu Jiandu Museum | Museum portal with exhibitions, collection display/data and academic research on Northwestern Jiandu | https://www.jiandumuseum.cn/homepage |
| 里耶秦简博物馆 / Liye Qin Slips Museum | Liye Qin administrative slips; collections, exhibitions, virtual hall and public knowledge resources | https://www.lybwg.com.cn/ |

## Related Textual and Palaeographic Resources

| Resource | Relevance | Project Page |
|---|---|---|
| Chinese Text Project | Open-access pre-modern Chinese textual corpus useful for transmitted-text parallels and contextual comparison | https://ctext.org/ |
| 汉语多功能字库 / Multi-function Chinese Character Database | Archaic script forms, component trees, etymological explanations and *Shuowen Jiezi* tools | https://humanum.arts.cuhk.edu.hk/Lexis/lexi-mf/ |

## Open Code and Dataset Repositories

| Project | Task / Resource | Repository |
|---|---|---|
| WA-Net / Chu730 | Chu bamboo-and-silk character recognition; Chu730 dataset pointer | https://github.com/Nancy45-ui/WA-Net |
| CHUBS | Large-scale Chu bamboo-slip glyph, detection and POS resources | https://huggingface.co/datasets/chen-yingfa/CHUBS |
| Chujian | Code accompanying the multimodal multi-granularity tokenizer | https://github.com/THUNLP/Chujian |
| MRA-Net / HanBamboo | Binarization code; repository provides a sample subset of HanBamboo and model resources | https://github.com/cszhangLMU/MRA-Net |
| BambInk | Self-supervised ink enhancement; code/data/results | https://github.com/cszhangLMU/BambInk |
| Tsinghua bamboo-slip scribe dataset | Scribe-verification dataset repository | https://github.com/LMJ557557/Dataset-of-Tsinghua-Bamboo-Slip-Scribe-Verification-Using-Siamese-Networks |
| DeepJiandu baseline configuration | MMOCR text-detection configuration referenced by the dataset paper | https://github.com/open-mmlab/mmocr/tree/main/configs/textdet |
| EpiAgent | Transferable agent-centric ancient-inscription restoration system | https://github.com/blackprotoss/EpiAgent |

---

# Jiandu Datasets and Benchmarks

The catalogue below mirrors the compact, task-oriented dataset organization used in OBI-Survey, while retaining Jiandu-specific material and manuscript tasks.

Availability was last checked against the manuscript dataset table on **11 August 2026**. Access labels:

- **Public** — public access to the reported dataset/source is available.
- **Partial / Request** — a partial public release is available, with additional or complete data available on request.
- **Request** — the complete processed dataset is available on request.
- **See paper** — the complete processed dataset is not publicly available or access was not reported in the manuscript.
- **Public project** — an associated project/code/resource is public even when it is not a formal benchmark row in the manuscript table.

## Recognition and Representation

| Dataset | Year | Type / Source | Scale | Classes | Paper | Project Page | Access |
|---|---:|---|---:|---:|---|---|---|
| Chu730 | 2025 | Character images / multiple Chu collections | 38,894 images | 730 | WA-Net | [Link](https://github.com/Nancy45-ui/WA-Net) | Public |
| CHUBS | 2025 | Character + slip images / 15 Chu sources | 102,722 characters; 5,033 slips; 164 documents | — | Multi-Modal Multi-Granularity Tokenizer for Chu Bamboo Slips | [Link](https://huggingface.co/datasets/chen-yingfa/CHUBS) | Public |
| DeepJiandu | 2025 | Infrared full-slip images / multiple Jiandu collections | 7,416 images; 99,852 instances | 2,242 | DeepJiandu Dataset for Character Detection and Recognition on Jiandu Manuscript | [Link](https://doi.org/10.57760/sciencedb.08560) | Public |
| zgzj1001 | 2026 | Character images / Tsinghua Warring States slips | 19,042 raw; 26,564 augmented | 1,001 | Recognition of Warring States bamboo slip characters via a self-supervised bilateral branch network | [Link](https://doi.org/10.1038/s40494-026-02740-z) | Request |

## Detection Binarization and Restoration

| Dataset / benchmark | Year | Task | Source / Type | Scale | Resolution | Project Page | Access |
|---|---:|---|---|---:|---|---|---|
| JianduMix† | 2026 | Detection | DeepJiandu-derived infrared mosaics | 5,000 images | 640×640 | [Link](https://doi.org/10.1038/s40494-026-02639-9) | Request |
| HanBamboo | 2025 | Binarization | Severely degraded infrared bamboo slips | 1,000 images | — | [Link](https://github.com/cszhangLMU/MRA-Net) | Request (sample/code public) |
| Qin–Han paired set† | 2025 | Restoration | Primarily Shuihudi Qin-slip characters | 500 pairs | 64×64 | [Link](https://doi.org/10.1038/s40494-025-01870-0) | Request |
| Jiandu character set† | 2026 | Restoration / recognition | Multiple periods and collections | 61,872-image corpus; 13,520-image experimental subset; 3,747 categories | — | [Link](https://doi.org/10.1038/s40494-026-02414-w) | Request |
| Liye Qin Slips Paired Dataset | 2026 | Restoration | Liye Qin-slip character triplets | 600 triplets; 148 categories | 64×64 | [Link](https://doi.org/10.1038/s40494-026-02434-6) | Request |
| Liye semi-supervised set† | 2026 | Semi-supervised restoration | Liye Qin slips | 875 labelled pairs + 10,091 unlabelled | — | [Link](https://doi.org/10.1038/s40494-026-02785-0) | See paper |
| DSF-SR set† | 2026 | Super-resolution | Mixed sources / DeepJiandu | 15,893 LR–HR pairs | 64→128/256* | [Link](https://doi.org/10.1038/s40494-026-02495-7) | See paper |
| BambInk resources | 2025 | Ink enhancement | Real-world bamboo manuscripts | See paper | — | [Link](https://github.com/cszhangLMU/BambInk) | Public project |

> † Descriptive label used in this repository when the source paper does not assign a formal benchmark name. `*` denotes standardized experimental LR/HR sizes rather than native collection resolution.

## Multimodal and 3D Data

| Dataset / benchmark | Year | Modality | Source | Scale | Project Page | Access |
|---|---:|---|---|---:|---|---|
| Diwan IR–visible set† | 2026 | Visible + infrared | Diwan Han slips | >840 image pairs | [Link](https://doi.org/10.1038/s40494-026-02368-z) | Public |
| Jiandu RGB-D set† | 2026 | RGB-D / point cloud | Jiandu fragments | 4 fragment sets | [Link](https://doi.org/10.1038/s40494-026-02533-4) | Public |

## Scribe Analysis

| Dataset | Year | Source | Scale | Classes | Project Page | Access |
|---|---:|---|---:|---:|---|---|
| Tsinghua bamboo-slip scribe dataset | 2026 | Tsinghua Warring States bamboo slips | 15,745 character images | 11 scribe categories | [Link](https://github.com/LMJ557557/Dataset-of-Tsinghua-Bamboo-Slip-Scribe-Verification-Using-Siamese-Networks) | Public |

## Fragment Rejoining

| Benchmark | Year | Material / Source | Scale | Main task | Project Page | Access |
|---|---:|---|---:|---|---|---|
| Bamboo236 | 2026 | Bamboo / Shuihudi Tomb 77 | 236 fragments (118 verified pairs) | Pair matching / rejoining | [Link](https://wisepanda.tech/) | Partial / Request |
| Bamboo1350 | 2026 | Bamboo / Shuihudi Tomb 77 | 1,350-fragment candidate pool | Large-pool retrieval | [Link](https://codeocean.com/capsule/0259823/tree) | Partial / Request |
| Wood670 | 2026 | Wooden slips | 670 fragments (335 verified pairs) | Pair matching / rejoining | [Link](https://wisepanda.tech/) | Partial / Request |
| Wood3833 | 2026 | Wooden slips | 3,833-fragment candidate pool | Large-pool retrieval | [Link](https://codeocean.com/capsule/0259823/tree) | Partial / Request |

---

# Paper Index: 75 References

## Related surveys and field overviews

| # | Paper | Venue & Year | Focus | Scope |
|---:|---|---|---|---|
| 1 | A Review of the Digitization of Bamboo and Silk Documents | Lantai World (8): 23–24 (2011) | Early review of bamboo-and-silk digitization | Jiandu-specific |
| 2 | [Progress and Prospects of Bamboo Slips Digitization: A Preliminary Exploration of Digital-Intelligent Development of Liye Qin Slips](https://doi.org/10.13438/j.cnki.jdzk.2025.06.011) | Journal of Jishou University (Natural Sciences Edition) 46(6): 83–89 (2025) | Jiandu digitization, image processing and Liye-focused outlook | Jiandu-specific |
| 3 | [Oracle bone inscriptions information processing: a comprehensive survey](https://doi.org/10.1038/s40494-026-02511-w) | npj Heritage Science 14: 220 (2026) | Task-centric benchmark for ancient-script survey design | Related / transferable |

## Foundational Jiandu and manuscript studies

| # | Paper | Venue & Year | Focus | Scope |
|---:|---|---|---|---|
| 4 | [Early Chinese Manuscripts: Including Addenda and Corrigenda to New Sources of Early Chinese History: An Introduction to the Reading of Inscriptions and Manuscripts](https://doi.org/10.1017/S0362502800000997) | Early China 23: 247–337 (1998) | Foundations of early Chinese manuscript studies | Foundational |
| 5 | Written on Bamboo and Silk: The Beginnings of Chinese Books and Inscriptions | University of Chicago Press (2004) | Material history of bamboo, silk and early Chinese books | Foundational |
| 6 | [The Embodied Text: Establishing Textual Identity in Early Chinese Manuscripts](https://doi.org/10.1163/9789004243811) | Brill (2013) | Material form and textual identity | Foundational |
| 7 | [Reconstruction of Early Chinese Bamboo and Wood Manuscripts: A Review (1900–2010)](https://doi.org/10.25592/uhhfdm.9812) | Centre for the Study of Manuscript Cultures, University of Hamburg No. 5 (2016) | Review of bamboo/wood manuscript reconstruction, 1900–2010 | Foundational |
| 8 | [Manuscript culture in early China: Editors' introduction](https://doi.org/10.1080/00094633.2017.1420287) | Chinese Studies in History 50(3): 167–171 (2017) | Early Chinese manuscript culture and interpretation | Foundational |
| 9 | [The Neglected ``Backyard'' of Early Chinese Manuscripts: How an Analysis of the Verso of Bamboo Slips Can Enable the Reconstruction of a Manuscript Roll](https://doi.org/10.11588/heidok.00023213) | heiDOK, Heidelberg University Document Repository (2017) | Verso evidence for slip-order reconstruction | Foundational |
| 10 | [Single- and Multi-Piece Manuscripts in Early Imperial China: On the Background and Significance of a Terminological Distinction](https://doi.org/10.1017/eac.2018.3) | Early China 41: 245–295 (2018) | Single- versus multi-piece manuscript forms | Foundational |
| 11 | [Ancient Chinese Scrolls as Evolving Entities: Implications for Reconstruction and Description](https://doi.org/10.1163/24689246-20230035) | Bamboo and Silk 6(2): 296–328 (2023) | Manuscripts as evolving material entities | Foundational |

## Conservation, deterioration and acquisition

| # | Paper | Venue & Year | Focus | Scope |
|---:|---|---|---|---|
| 12 | [Investigation into the deterioration process of archaeological bamboo strips of China from four different periods by chemical and anatomical analysis](https://doi.org/10.1016/j.polymdegradstab.2014.06.022) | Polymer Degradation and Stability 109: 71–78 (2014) | Chemical and anatomical deterioration of archaeological bamboo | Jiandu-specific |
| 13 | [Micromorphological and chemical aspects of archaeological bamboos under long-term waterlogged condition](https://doi.org/10.1016/j.ibiod.2013.08.008) | International Biodeterioration & Biodegradation 86: 115–121 (2014) | Micromorphology of waterlogged archaeological bamboo | Jiandu-specific |
| 14 | [Research on extraction of fragile bamboo slips by underwater temporary solidification in original state](https://doi.org/10.1016/j.culher.2021.08.008) | Journal of Cultural Heritage 51: 174–181 (2021) | Underwater temporary solidification for fragile-slip extraction | Jiandu-specific |
| 15 | Protection and requirements in the image information acquisition process of bamboo and wooden slips | Excavated Documents (1): 13–19 (2023) | Conservation requirements for Jiandu image acquisition | Jiandu-specific |
| 16 | [Artificial simulated aging of bamboo slips and its degradation mechanism](https://doi.org/10.1016/j.polymdegradstab.2025.111254) | Polymer Degradation and Stability 235: 111254 (2025) | Artificial ageing and degradation mechanisms | Jiandu-specific |
| 17 | [Degradation state and preservation quality of archaeological bamboo from a 2000-year-old Chinese royal tomb](https://doi.org/10.1038/s40494-025-01758-z) | npj Heritage Science 13: 223 (2025) | Multiscale preservation-state assessment | Jiandu-specific |
| 18 | [Environmental Filtering Drives Microbial Community Shifts and Functional Niche Differentiation of Fungi in Waterlogged and Dried Archeological Bamboo Slips](https://doi.org/10.3390/jof12010066) | Journal of Fungi 12(1): 66 (2026) | Microbial shifts in waterlogged and dried slips | Jiandu-specific |

## Digitization, standards and database infrastructure

| # | Paper | Venue & Year | Focus | Scope |
|---:|---|---|---|---|
| 19 | Practical Difficulties in the Study and Organization of Bamboo and Wooden Slips and Directions for Jiandu Digitization | Journal of Ludong University (Philosophy and Social Sciences Edition) 28(6): 22–25 (2011) | Practical challenges and directions for Jiandu digitization | Jiandu-specific |
| 20 | On Standardization Issues in the Digitization of Bamboo and Wooden Slips | Journal of Ludong University (Philosophy and Social Sciences Edition) 29(3): 55–60 (2012) | Digitization standards | Jiandu-specific |
| 21 | Standardization of Basic Corpus Processing in the Construction of a Qin–Han Bamboo-Slip Corpus | Chinese Character Studies (2): 53–56 (2014) | Qin–Han corpus processing standards | Jiandu-specific |
| 22 | A Preliminary Analysis of Database Construction for Bamboo and Silk Documents | Jianghan Archaeology (5): 128–130 (2017) | Bamboo-and-silk database construction | Jiandu-specific |
| 23 | Assessing the Digitization of the Guodian Chu Slips: Standards for the Development of Excavated-Document Databases | Digital Humanities (4): 77–90 (2023) | Guodian digitization and excavated-document database standards | Jiandu-specific |

## Multimodal documentation, registration and geometry

| # | Paper | Venue & Year | Focus | Scope |
|---:|---|---|---|---|
| 24 | [Virtual cleaning and unwrapping of non-invasively digitized soiled bamboo scrolls](https://doi.org/10.1038/s41598-019-39447-0) | Scientific Reports 9: 2311 (2019) | CT-based virtual cleaning and unwrapping | Jiandu-specific |
| 25 | [Adaptive multi-feature fusion for visible-infrared image registration and character enhancement of bamboo slips](https://doi.org/10.1038/s40494-026-02368-z) | npj Heritage Science 14: 96 (2026) | Visible–infrared registration and enhancement | Jiandu-specific |
| 26 | [Jiandu point cloud registration using high-resolution data and generalized t-student kernel](https://doi.org/10.1038/s40494-026-02533-4) | npj Heritage Science 14: 267 (2026) | High-resolution Jiandu point-cloud registration | Jiandu-specific |
| 27 | [Physics-Guided Multistep Deformation Reversal for Ancient Bamboo Slip Restoration](https://openaccess.thecvf.com/content/CVPR2026/html/Tang_Physics-Guided_Multistep_Deformation_Reversal_for_Ancient_Bamboo_Slip_Restoration_CVPR_2026_paper.html) | Proceedings of the IEEE/CVF Conference on Computer Vision and Pattern Recognition (CVPR): 34061–34071 (2026) | Physics-guided deformation reversal | Jiandu-specific |
| 28 | [SSA-based adaptive infrared-visible image fusion for ink enhancement in ancient bamboo slips](https://doi.org/10.1038/s40494-025-02293-7) | npj Heritage Science 14: 25 (2026) | Visible–infrared fusion for ink enhancement | Jiandu-specific |

## Image enhancement, detection, segmentation and binarization

| # | Paper | Venue & Year | Focus | Scope |
|---:|---|---|---|---|
| 29 | Character Segmentation Algorithm for Jiandu Images | Science Technology and Engineering 7(21): 5584–5589, 5608 (2007) | Early Jiandu character segmentation | Jiandu-specific |
| 30 | Application of Unsharp Masking to Character Enhancement in Jiandu Images | Microcomputer Information 24(3): 241–242 (2008) | Unsharp-mask character enhancement | Jiandu-specific |
| 31 | Application of the Canny Edge Detector to Jiandu Character Restoration | Microcomputer Information 24(9): 241–242, 250 (2008) | Canny-based damaged-character restoration | Jiandu-specific |
| 32 | Application of Multiscale Retinex to Jiandu Image Enhancement | Computer Science 36(3): 288–290 (2009) | Multiscale Retinex enhancement | Jiandu-specific |
| 33 | [Character segmentation and restoration of Qin-Han bamboo slips using local auto-focus thresholding method](https://doi.org/10.1007/s11042-022-11988-z) | Multimedia Tools and Applications 81(6): 8199–8213 (2022) | Adaptive thresholding, segmentation and restoration | Jiandu-specific |
| 34 | [U-Net Architecture for Ancient Handwritten Chinese Character Detection in Han Dynasty Wooden Slips](https://doi.org/10.1587/transfun.2023SMP0007) | IEICE Transactions on Fundamentals of Electronics, Communications and Computer Sciences E106.A(11): 1406–1415 (2023) | U-Net detection on Han wooden slips | Jiandu-specific |
| 35 | [Method for Qin Bamboo Slip Text Detection Based on an Enhanced DBNet Model](https://doi.org/10.1109/AIIM64537.2024.10934214) | 2024 4th International Symposium on Artificial Intelligence and Intelligent Manufacturing: 952–958 (2024) | Enhanced DBNet for Qin-slip text detection | Jiandu-specific |
| 36 | [A feature-enhanced text detection model for Jiandu manuscripts](https://doi.org/10.1038/s40494-025-01807-7) | npj Heritage Science 13: 355 (2025) | Feature-enhanced Jiandu text detection | Jiandu-specific |
| 37 | [Binarizing Severely Degraded Ancient Bamboo Slips: Dataset and Baseline](https://bmvc2025.bmva.org/proceedings/1177/) | Proceedings of the 36th British Machine Vision Conference (2025) | HanBamboo dataset and binarization baseline | Jiandu-specific |
| 38 | [A mask-fusion detection method for character integrity preservation and adhesion segmentation in Jiandu manuscripts](https://doi.org/10.1038/s40494-026-02725-y) | npj Heritage Science (2026) | Adhesion segmentation and character-integrity preservation | Jiandu-specific |
| 39 | [DDSF-YOLO for accurate multi-scale text detection in Jiandu images](https://doi.org/10.1038/s40494-026-02639-9) | npj Heritage Science 14: 399 (2026) | Multi-scale Jiandu detection with DDSF-YOLO | Jiandu-specific |

## Restoration, ink enhancement and super-resolution

| # | Paper | Venue & Year | Focus | Scope |
|---:|---|---|---|---|
| 40 | [Research on the Qin Bamboo Slip Character Images Inpainting Algorithm Based on the Context Encoder Model](https://doi.org/10.1117/12.3044958) | Fourth International Conference on Computer Graphics, Image, and Virtualization (ICCGIV 2024), Proceedings of SPIE 13288: 132880V (2024) | Context-encoder character inpainting | Jiandu-specific |
| 41 | [Character restoration of Qin and Han bamboo slips based on improved conditional generative adversarial networks](https://doi.org/10.1038/s40494-025-01870-0) | npj Heritage Science 13: 278 (2025) | Conditional-GAN character restoration | Jiandu-specific |
| 42 | [Ink Enhancement for Ancient Bamboo Manuscripts Using Iterative Restoration-Degradation Adversarial Learning](https://bmvc2025.bmva.org/proceedings/988/) | Proceedings of the 36th British Machine Vision Conference (2025) | Self-supervised faded-ink enhancement | Jiandu-specific |
| 43 | [Restoration of ancient Japanese manuscripts via the diffusion denoising restoration model and color space-based masking](https://doi.org/10.1038/s40494-025-02214-8) | npj Heritage Science 13: 634 (2025) | Transferable diffusion restoration for historical manuscripts | Related / transferable |
| 44 | [A JianDu character restoration method based on cross-domain debiased Fourier fusion and parameterized coordinate query](https://doi.org/10.1038/s40494-026-02414-w) | npj Heritage Science 14: 159 (2026) | Fourier-domain restoration and coordinate querying | Jiandu-specific |
| 45 | [Dual-stream disentangled super-resolution for bamboo slip text images](https://doi.org/10.1038/s40494-026-02495-7) | npj Heritage Science 14: 229 (2026) | Dual-stream super-resolution for Jiandu text images | Jiandu-specific |
| 46 | [Physics-Guided Diffusion Models for Ancient Bamboo Script Restoration](https://doi.org/10.1109/ICASSP55912.2026.11463967) | 2026 IEEE International Conference on Acoustics, Speech and Signal Processing (ICASSP): 20052–20056 (2026) | Physics-guided diffusion restoration | Jiandu-specific |
| 47 | [Restoration of Liye Qin slips characters using generative adversarial network with effective connected component constraint](https://doi.org/10.1038/s40494-026-02434-6) | npj Heritage Science 14: 194 (2026) | Structure-aware Liye character restoration | Jiandu-specific |
| 48 | [Semi-supervised restoration of damaged characters in Liye Qin bamboo slips](https://doi.org/10.1038/s40494-026-02785-0) | npj Heritage Science (2026) | Semi-supervised Liye restoration | Jiandu-specific |

## Character recognition and multigranular representation

| # | Paper | Venue & Year | Focus | Scope |
|---:|---|---|---|---|
| 49 | [Multi-scene ancient Chinese text recognition](https://doi.org/10.1016/j.neucom.2019.10.029) | Neurocomputing 377: 64–72 (2020) | Cross-scene ancient Chinese recognition | Related / transferable |
| 50 | [Ancient Chinese Recognition Method Based on Attention Mechanism](https://doi.org/10.1109/IC-NIDC54101.2021.9660518) | 2021 7th IEEE International Conference on Network Intelligence and Digital Content (IC-NIDC): 309–313 (2021) | Attention-based ancient Chinese recognition | Related / transferable |
| 51 | [Multi-scene ancient Chinese text recognition with deep coupled alignments](https://doi.org/10.1016/j.asoc.2021.107475) | Applied Soft Computing 108: 107475 (2021) | Deep coupled alignment across scenes | Related / transferable |
| 52 | [Qin character recognition using hybrid HOG feature and SVM model](https://doi.org/10.55092/pcs2023020041) | Proceedings of Computer Science 1: 0041 (2023) | HOG + SVM Qin-character recognition | Jiandu-specific |
| 53 | [DeepJiandu Dataset for Character Detection and Recognition on Jiandu Manuscript](https://doi.org/10.1038/s41597-025-04716-3) | Scientific Data 12: 398 (2025) | DeepJiandu detection/recognition dataset | Jiandu-specific |
| 54 | [HUNet: Hierarchical universal network for multi-type ancient Chinese character recognition](https://doi.org/10.1038/s40494-025-01813-9) | npj Heritage Science 13: 281 (2025) | Hierarchical multi-type ancient-character recognition | Related / transferable |
| 55 | [Multi-Modal Multi-Granularity Tokenizer for Chu Bamboo Slips](https://aclanthology.org/2025.coling-main.414/) | Proceedings of the 31st International Conference on Computational Linguistics: 6201–6211 (2025) | Multimodal, multigranular Chu-slip representation | Jiandu-specific |
| 56 | [WA-Net: Wavelet Integrated Attention Network for Silk and Bamboo Character Recognition](https://doi.org/10.1016/j.engappai.2024.109674) | Engineering Applications of Artificial Intelligence 140: 109674 (2025) | Wavelet-attention recognition and Chu730 | Jiandu-specific |
| 57 | [Leveraging progressive domain adaptation for unsupervised cross-domain oracle bone inscription recognition](https://doi.org/10.1038/s40494-026-02690-6) | npj Heritage Science (2026) | Transferable cross-domain adaptation for ancient scripts | Related / transferable |
| 58 | [MCHDoc: A Comprehensive Benchmark for Reading Multi-Carrier Chinese Historical Documents](https://openaccess.thecvf.com/content/CVPR2026/html/Sheng_MCHDoc_A_Comprehensive_Benchmark_for_Reading_Multi-Carrier_Chinese_Historical_Documents_CVPR_2026_paper.html) | Proceedings of the IEEE/CVF Conference on Computer Vision and Pattern Recognition: 38722–38731 (2026) | Cross-carrier historical-document benchmark | Related / transferable |
| 59 | [Recognition of Warring States bamboo slip characters via a self-supervised bilateral branch network](https://doi.org/10.1038/s40494-026-02740-z) | npj Heritage Science (2026) | Self-supervised Warring States slip recognition | Jiandu-specific |

## Fragment rejoining, scribe analysis and manuscript reconstruction

| # | Paper | Venue & Year | Focus | Scope |
|---:|---|---|---|---|
| 60 | Research on the Restoration of Liang Zhong of the Tsinghua Bamboo Slips | Excavated Documents 20(4): 1–19 (2024) | Evidence-centred reconstruction of Tsinghua Liang Zhong | Jiandu-specific |
| 61 | [Rejoining fragmented ancient bamboo slips with physics-driven deep learning](https://doi.org/10.1038/s41467-026-70361-y) | Nature Communications 17: 3550 (2026) | Physics-driven fragment rejoining (WisePanda) | Jiandu-specific |
| 62 | [Tsinghua bamboo slip scribe verification using Siamese networks](https://doi.org/10.1038/s40494-026-02416-8) | npj Heritage Science 14: 147 (2026) | Siamese-network scribe verification | Jiandu-specific |

## Digital editions, knowledge, language models and agents

| # | Paper | Venue & Year | Focus | Scope |
|---:|---|---|---|---|
| 63 | [Can Large Language Model Comprehend Ancient Chinese? A Preliminary Test on ACLUE](https://aclanthology.org/2023.alp-1.9/) | Proceedings of the Ancient Language Processing Workshop: 80–87 (2023) | Benchmarking LLM comprehension of Ancient Chinese | Related / transferable |
| 64 | [Linking past insights with contemporary understanding: an ontological and knowledge graph approach to the transmission of ancient Chinese classics](https://doi.org/10.1186/s40494-024-01504-x) | Heritage Science 12: 382 (2024) | Ontology and knowledge graph for Chinese classics | Related / transferable |
| 65 | [A large-scale dataset for Chinese historical document recognition and analysis](https://doi.org/10.1038/s41597-025-04495-x) | Scientific Data 12: 169 (2025) | Large-scale historical-document data infrastructure | Related / transferable |
| 66 | [A multi agent classical Chinese translation method based on large language models](https://doi.org/10.1038/s41598-025-23904-0) | Scientific Reports 15: 40160 (2025) | Multi-agent Classical Chinese translation | Related / transferable |
| 67 | [Contextualizing ancient texts with generative neural networks](https://doi.org/10.1038/s41586-025-09292-5) | Nature 645: 141–147 (2025) | Human–AI contextualization of ancient texts | Related / transferable |
| 68 | [Using Cross-Linguistic Data Formats to Enhance the Annotation of Ancient Chinese Documents Written on Bamboo Slips](https://doi.org/10.18653/v1/2025.alp-1.4) | Proceedings of the Second Workshop on Ancient Language Processing: 31–37 (2025) | Machine-actionable bamboo-slip digital editions | Jiandu-specific |
| 69 | [ACSE: An Ancient Character Semantic-Aware Embedding for Large Language Models](https://doi.org/10.18653/v1/2026.findings-acl.437) | Findings of the Association for Computational Linguistics: ACL 2026: 9000–9012 (2026) | Ancient-character semantic-aware LLM embedding | Related / transferable |
| 70 | [AncientBench: Towards Comprehensive Evaluation on Excavated and Transmitted Chinese Corpora](https://doi.org/10.1609/aaai.v40i41.40823) | Proceedings of the AAAI Conference on Artificial Intelligence 40(41): 35167–35175 (2026) | Excavated/transmitted Chinese LLM benchmark | Related / transferable |
| 71 | [Designing Narrative Reconstruction from Bamboo Slips: A RAG-Agent Approach for Cultural Scene Generation](https://doi.org/10.21606/drs.2026.1738) | DRS2026: Design Research Society International Conference (2026) | Liye RAG-Agent for grounded narrative reconstruction | Jiandu-specific |
| 72 | [EpiAgent: An Agent-Centric System for Ancient Inscription Restoration](https://openaccess.thecvf.com/content/CVPR2026/html/Zhu_EpiAgent_An_Agent-Centric_System_for_Ancient_Inscription_Restoration_CVPR_2026_paper.html) | Proceedings of the IEEE/CVF Conference on Computer Vision and Pattern Recognition: 39304–39313 (2026) | Agent-centric ancient-inscription restoration | Related / transferable |

## FAIR data, provenance and trustworthy heritage AI

| # | Paper | Venue & Year | Focus | Scope |
|---:|---|---|---|---|
| 73 | [Developing practices for FAIR and linked data in Heritage Science](https://doi.org/10.1038/s40494-025-01598-x) | npj Heritage Science 13: 53 (2025) | FAIR and linked-data practices in heritage science | Related / transferable |
| 74 | [Interoperable provenance data for heritage crime monitoring of architectural elements](https://doi.org/10.1038/s40494-025-01919-0) | npj Heritage Science 14: 4 (2026) | Interoperable provenance for heritage records | Related / transferable |
| 75 | [Towards trustworthy AI in cultural heritage](https://doi.org/10.1038/s40494-026-02403-z) | npj Heritage Science 14: 131 (2026) | Trustworthy and explainable AI in cultural heritage | Related / transferable |


---

# Research Gaps and Priorities

The current literature and resource landscape suggests five priorities:

1. **Interoperable multiscale data.** Existing resources remain fragmented across character labels, pixel masks, multimodal image pairs, point clouds, scribe labels, and fragment matches. Future datasets should connect material observations, digital surrogates, characters, fragments, slips, manuscripts, and scholarly annotations through stable identifiers.
2. **Cross-collection and cross-material evaluation.** Random within-dataset splits should be complemented by cross-site, cross-period, cross-scribe, cross-device, cross-modality, cross-material, and external-institution validation.
3. **Heritage-specific evaluation.** Visual quality and task accuracy should be distinguished from structural fidelity and heritage fidelity. Generated completion must not become indistinguishable from observed evidence.
4. **Provenance and uncertainty.** Jiandu workflows should distinguish observed evidence, recovered evidence, inferred evidence, retrieved evidence, and generated hypotheses.
5. **Human-centred intelligent systems.** Multimodal models, RAG, and research agents should coordinate evidence and specialist tools while leaving final scholarly acceptance of restoration, joins, sequences, scribal attributions, and disputed readings explicit and revisable.

---

# Repository Structure

A compact structure similar to OBI-Survey is sufficient for the first public release:

```text
Jiandu-Survey/
├── README.md
├── LICENSE
├── CITATION.cff
├── CONTRIBUTING.md
│
├── image/
│   ├── Figure1.png
│   ├── Figure2.png
│   ├── Figure3.png
│   ├── Figure4.png
│   └── Figure5.png
│
└── bibliography/
    └── sn-bibliography.bib
```

If the resource index grows substantially, the dataset and paper tables can later be split into `resources/` and `papers/` subpages while keeping this README as the main navigation page.

---

# Resource and Rights Notes

- This repository is a **scholarly index and curation project**. Inclusion does not transfer copyright or redistribution rights.
- Copyright, licences, access restrictions, and citation requirements for linked datasets, images, museum resources, code, and publications remain with their original creators and institutions.
- Some Jiandu platforms permit scholarly access but restrict bulk downloading, automated scraping, redistribution, or commercial reuse. Always consult the original terms of use.
- `Public`, `Partial`, and `Request` describe the access state observed during curation and may change.
- If a link, access statement, dataset statistic, or attribution is inaccurate or outdated, please open an issue or pull request.

---

# Data Availability

No new datasets were generated in the accompanying Review. The datasets, publications, digital resources, code repositories, and project links discussed in the article are curated and continuously updated through this repository:

**https://github.com/Jiandu-Future/Jiandu-Survey**

---

# Maintainers

**Cheng Xu**  
Beijing Key Laboratory of Cultural Heritage Agent, Beijing Union University  
Email: `xucheng@buu.edu.cn`

<p align="center"><b>Jiandu-Survey</b><br>Preservation · Documentation · Recovery · Recognition · Reconstruction · Interpretation</p>
