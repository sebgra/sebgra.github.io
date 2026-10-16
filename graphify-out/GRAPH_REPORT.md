# Graph Report - sebgra.github.io  (2026-10-16)

## Corpus Check
- 157 files · ~89,692 words
- Verdict: corpus is large enough that graph structure adds value.
- Unclassified: 54 file(s) not represented in the graph (top: .scss 19, (none) 10, .css 8)

## Summary
- 451 nodes · 772 edges · 33 communities (17 shown, 16 thin omitted)
- Extraction: 80% EXTRACTED · 19% INFERRED · 1% AMBIGUOUS · INFERRED: 148 edges (avg confidence: 0.86)
- Token cost: 445,541 input · 0 output

## Community Hubs (Navigation)
- Minified Theme JS Bundle
- Archive & Profile Includes
- Jekyll Site Configuration
- CV & Talkmap Python Scripts
- CV Career & Projects
- NPM Package Manifest
- CGR DNA Classifier Models
- Hicberg Research Output
- Markdown Page Generators
- CV Pages & Data
- About & Community Pages
- Blog Posts & Archives
- JeBiF Outreach Activities
- Optimizers & Overfitting
- Analytics Providers
- 1D CNN on DNA
- Comment Provider Embeds
- Terms & Privacy
- Web App Manifest
- Portfolio Templates
- Placeholder Paper 1
- Placeholder Paper 2
- Placeholder Paper 3
- Site Logo Theme
- CV JSON Update Script
- Google+ Comments
- 404 Page
- Placeholder Avatar

## God Nodes (most connected - your core abstractions)
1. `base_path include` - 34 edges
2. `e()` - 16 edges
3. `Archive Item (generic/publication/teaching)` - 15 edges
4. `Default Layout` - 15 edges
5. `ICTE 2024 Poster - Hicberg` - 15 edges
6. `N()` - 14 edges
7. `o()` - 14 edges
8. `l()` - 14 edges
9. `s()` - 14 edges
10. `create_cv_json()` - 14 edges

## Surprising Connections (you probably didn't know these)
- `Authors Data (placeholder authors)` --semantically_similar_to--> `Author Profile (Sebastien Gradit, PhD)`  [INFERRED] [semantically similar]
  _data/authors.yml → _config.yml
- `UI Text Localization (en, es, fr, tr, pt, it, zh, ...)` --references--> `Jekyll Site Configuration`  [INFERRED]
  _data/ui-text.yml → _config.yml
- `Draft Post (placeholder)` --references--> `Jekyll Site Configuration`  [INFERRED]
  _drafts/post-draft.md → _config.yml
- `Main Navigation Menu` --references--> `Jekyll Collections (teaching, publications, portfolio, talks, softwares)`  [INFERRED]
  _data/navigation.yml → _config.yml
- `Tutorial 1 on Relevant Topic (template)` --references--> `Jekyll Collections (teaching, publications, portfolio, talks, softwares)`  [INFERRED]
  _templates/_talks/2013-03-01-tutorial-1.md → _config.yml

## Import Cycles
- None detected.

## Hyperedges (group relationships)
- **Jekyll content collection templates** — _templates__publications_2009_10_01_paper_title_number_1_template, _templates__publications_2010_10_01_paper_title_number_2_template, _templates__talks_2012_03_01_talk_1_template, _templates__talks_2013_03_01_tutorial_1_template, _templates__teaching_2014_spring_teaching_1_template, _config_collections [INFERRED 0.85]
- **Staticman comment data store** — _data_comments_layout_comments_comment_1470944006665_comment, _data_comments_layout_comments_comment_1470944162041_comment, _data_comments_markup_syntax_highlighting_comment_1470969665387_comment, _data_comments_welcome_to_jekyll_comment_1470942205700_comment, _data_comments_welcome_to_jekyll_comment_1470942247755_comment, _data_comments_welcome_to_jekyll_comment_1470942265819_comment, _data_comments_welcome_to_jekyll_comment_1470942493518_comment, _config_staticman [INFERRED 0.95]
- **Local/Docker site build pipeline** — readme_local_development, readme_docker_workflow, docker_compose_jekyll_site_service, _config_docker_docker_config_override, _config_site_config [INFERRED 0.85]
- **Analytics provider strategy selected by site.analytics.provider** — _includes_analytics, _includes_analytics_providers_google, _includes_analytics_providers_google_universal, _includes_analytics_providers_google_analytics_4, _includes_analytics_providers_custom [EXTRACTED 1.00]
- **Pluggable comment provider embeds driven by site.comments** — _includes_comments_providers_custom, _includes_comments_providers_discourse, _includes_comments_providers_disqus, _includes_comments_providers_facebook, _includes_comments_providers_google_plus [INFERRED 0.85]
- **Archive list item template variants (publication, talk, CV)** — _includes_archive_single, _includes_archive_single_cv, _includes_archive_single_talk, _includes_archive_single_talk_cv [INFERRED 0.95]
- **Comments rendering flow** — _includes_comments, _includes_comments_providers_scripts, _includes_comments_providers_staticman, _includes_comment_provider_switch, _includes_comment [EXTRACTED 1.00]
- **Includes localized via ui-text data** — _includes_paginator, _includes_post_pagination, _includes_read_time, _includes_social_share, _includes_tag_list, _includes_footer, _data_ui_text_localization [EXTRACTED 1.00]
- **Jekyll layout inheritance chain (compress -> default -> page layouts)** — _layouts_compress, _layouts_default, _layouts_single, _layouts_archive, _layouts_talk, _layouts_splash, _layouts_archive_taxonomy, _layouts_cv_layout [EXTRACTED 1.00]
- **Archive-layout listing pages rendering items via archive-single include** — _pages_category_archive, _pages_collection_archive, _pages_page_archive, _pages_portfolio, _pages_publications, _includes_archive_single [EXTRACTED 1.00]
- **Pages sharing /nmp/ redirect_from (conflicting redirects)** — _pages_hackathons, _pages_non_menu_page, _pages_community_involvement [EXTRACTED 1.00]
- **Hicberg research dissemination (paper, thesis, talks)** — _publications_2025_xx_xx_hicberg_paper, _publications_2024_12_17_thesis_manuscript, _talks_talk_ismb_2023, _talks_talk_icte_2024, _talks_talk_jobim_2024, _talks_talk_inception_2024 [INFERRED 0.95]
- **Yeast retrotransposon findings via Hicberg** — retrotransposons, cohesin, two_micron_plasmid, saccharomyces_cerevisiae [EXTRACTED 1.00]
- **Jekyll archive listing pages** — _pages_sitemap, _pages_tag_archive, _pages_teaching, _pages_year_archive, archive_single_include [EXTRACTED 1.00]
- **Hicberg ambiguous-read reassignment pipeline** — files_icte_2024_poster_hi_c, files_icte_2024_poster_ambiguous_reads, files_icte_2024_poster_statistical_inference_reassignment, files_icte_2024_poster_polymer_contact_law, files_icte_2024_poster_hicberg [EXTRACTED 1.00]
- **Hicberg yeast retrotransposon findings** — files_icte_2024_poster_retrotransposons, files_icte_2024_poster_cohesin, files_icte_2024_poster_two_micron_plasmid, files_icte_2024_poster_saccharomyces_cerevisiae, files_jobim_2024_poster_pdf_157_ty1_benchtop_validation [INFERRED 0.85]
- **Academic template placeholder assets (sample papers, slides, avatar)** — files_paper1_sample_pdf, files_paper2_sample_pdf, files_paper3_sample_pdf, files_slides1_sample_slides, files_slides2_sample_slides, files_slides3_sample_slides, images_profile_placeholder_avatar [INFERRED 0.85]
- **DNA CNN pipeline: one-hot encoding -> convolution -> max pooling** — images_post_images_article_1_one_hot_encoding, images_post_images_article_1_convolution_example, images_post_images_article_1_max_pooling, images_post_images_article_1_receptor_field [INFERRED 0.85]
- **Training curves comparison: SGD vs Adam vs Adam+Dropout** — images_post_images_article_1_sgd_results, images_post_images_article_1_adam_results, images_post_images_article_1_dropout_effect [INFERRED 0.85]
- **CGR-to-CNN DNA Classification Pipeline** — images_post_images_article_2_chaos_game_representation, images_post_images_article_2_cnn_conv_dropout_backbone, images_post_images_article_2_dna_sequence_classification [INFERRED 0.85]
- **CNN Model Variants (Base, CNN+SVM, DNA-LeNet)** — images_post_images_article_2_base_model_1, images_post_images_article_2_cnn_svm, images_post_images_article_2_dna_lenet [INFERRED 0.85]
- **Classifier comparison for DNA sequence classification (SVM vs base NN vs LeNet)** — images_post_images_article_2_svm, images_post_images_article_2_base_neural_model, images_post_images_article_2_lenet, images_post_images_article_2_dna_sequence_classification [INFERRED 0.85]

## Communities (33 total, 16 thin omitted)

### Community 0 - "Minified Theme JS Bundle"
Cohesion: 0.06
Nodes (54): a(), At(), Be(), bt(), c(), e(), ct(), $e() (+46 more)

### Community 1 - "Archive & Profile Includes"
Cohesion: 0.09
Nodes (55): UI Text Localization (site.data.ui-text[site.locale]), Archive Item (generic/publication/teaching), Archive Item (CV publication), Post front-matter metadata (title, venue, citation, paperurl, slidesurl, bibtexurl, teaser), Archive Item (talk), Archive Item (CV talk), Author Profile Sidebar, Author data (site.author / site.data.authors) (+47 more)

### Community 2 - "Jekyll Site Configuration"
Cohesion: 0.06
Nodes (43): Author Profile (Sebastien Gradit, PhD), Jekyll Collections (teaching, publications, portfolio, talks, softwares), Custom Domain sebastiengradit.com, Docker Config Override (empty url), Institut Pasteur, Jekyll Plugins (feed, gist, paginate, sitemap, redirect-from, jemoji), Kramdown GFM Markdown + Rouge, Publication Categories (books, manuscripts, conferences) (+35 more)

### Community 3 - "CV & Talkmap Python Scripts"
Cohesion: 0.09
Nodes (13): create_cv_json(), DateTimeEncoder, extract_author_info(), main(), parse_config(), parse_education(), parse_markdown_cv(), parse_portfolio() (+5 more)

### Community 4 - "CV Career & Projects"
Cohesion: 0.11
Nodes (38): Bioequivalence simulations (Danone Nutricia Research), Curriculum Vitae (academic/ML), ESM-2 protein foundation model, Hicberg paper (Genome Research, 2026), Foot orthotics biomechanical models (CABOMA, Universite de Montreal), Deep learning prediction of 2-micron plasmid interactions from nucleosome occupancy, Curriculum Vitae (industry), S. cerevisiae rDNA behavior under stress (heat, oxidative) (+30 more)

### Community 5 - "NPM Package Manifest"
Cohesion: 0.06
Nodes (32): bugs, url, contributors, dependencies, fitvids, jquery, jquery-smooth-scroll, magnific-popup (+24 more)

### Community 6 - "CGR DNA Classifier Models"
Cohesion: 0.11
Nodes (23): Base Model Training Loss/Accuracy Curves, Base CNN Model Architecture Diagram, Base Model Training Curves (jpg), Base Neural Network Model (~92% train / ~80% val acc, overfitting after ~300 epochs), CGR Quadrant Grid Diagram, CGR Examples per Class (7 classes), CGR Path Construction Diagram, CGR Representation 32x32 per Class (+15 more)

### Community 7 - "Hicberg Research Output"
Cohesion: 0.17
Nodes (21): Softwares Page, Talk Map Page, Talks, Presentations and Posters Page, PhD Thesis: Using statistical profiling to decipher hidden chromatin contacts resulting from repeated sequences, Hicberg: Reconstruction of genomic signals from repeated elements (Genome Research), ICTE 2024 Poster: Hicberg, Inception 2024 Talk (Institut Pasteur), ISMB/ECCB 2023: Statistical inference of repeated sequence contacts in Hi-C maps (+13 more)

### Community 9 - "CV Pages & Data"
Cohesion: 0.15
Nodes (15): _config.yml, CV JSON data, CV Data (site.data.cv, JSON Resume schema), Site Navigation Data (site.data.navigation), CV Template Include, Archive Layout with Content, CV, CV (JSON) (+7 more)

### Community 10 - "About & Community Pages"
Cohesion: 0.18
Nodes (15): About Page (Hi I'm Sébastien Gradit), AI models for omics data, bioinfo-fr.net blog, Hicberg (genomics tool), Pasteur Institute, Sébastien Gradit, Community Involvement, Jeunes Bioinformaticiens de France (JeBiF) (+7 more)

### Community 11 - "Blog Posts & Archives"
Cohesion: 0.22
Nodes (10): Sitemap Page, Posts by Tags Page, Teaching Page, Blog Posts Year Archive Page, Bioinformatics and AI: A First Step, Bioinformatics and AI: CNNs for bioinformatics, Teaching Experience 2 (template), archive-single.html include (+2 more)

### Community 12 - "JeBiF Outreach Activities"
Cohesion: 0.48
Nodes (7): Les aventures de Nounours (outreach), BioStream live streams, JOBIM 2024 Poster - JeBiF RSG France, ISCB Student Council (RSG France), JeBiF - Association des Jeunes Bioinformaticiens de France, JOBIM conference (JeBiF@JOBIM), Les Bioinformations newsletter

### Community 13 - "Optimizers & Overfitting"
Cohesion: 0.33
Nodes (6): Adam Optimizer, Adam Training Results (loss/accuracy curves), Dropout Effect Training Results, Overfitting, SGD Optimizer, SGD Training Results (loss/accuracy curves)

### Community 14 - "Analytics Providers"
Cohesion: 0.60
Nodes (6): Analytics Provider Dispatcher, Custom Analytics Snippet, Legacy Google Analytics (ga.js) Include, Google Analytics 4 (gtag) Include, Google Universal Analytics Include, site.analytics config (provider, google.tracking_id)

### Community 15 - "1D CNN on DNA"
Cohesion: 0.40
Nodes (6): 1D Convolution on One-Hot DNA Diagram, 1D Convolutional Neural Network for DNA, DNA Double Helix Illustration, Max Pooling Diagram, One-Hot Encoding of DNA Sequence, Receptive Field Diagram

### Community 16 - "Comment Provider Embeds"
Cohesion: 0.67
Nodes (4): Discourse Comments Embed, Disqus Comments Embed, Facebook Comments SDK, site.comments config (discourse.server, disqus.shortname, facebook.appid)

### Community 17 - "Terms & Privacy"
Cohesion: 0.67
Nodes (3): Terms and Privacy Policy Page, Disqus comments, Google Analytics

## Ambiguous Edges - Review These
- `Community Involvement` → `Page not in menu`  [AMBIGUOUS]
  _pages/community_involvement.md · relation: conceptually_related_to
- `Hackathons` → `Page not in menu`  [AMBIGUOUS]
  _pages/hackathons.md · relation: conceptually_related_to
- `Paper 1 (placeholder sample PDF)` → `Slides 1 (placeholder slides)`  [AMBIGUOUS]
  files/slides1.pdf · relation: conceptually_related_to
- `Paper 2 (placeholder sample PDF)` → `Slides 2 (placeholder slides)`  [AMBIGUOUS]
  files/slides2.pdf · relation: conceptually_related_to
- `Paper 3 (placeholder sample PDF)` → `Slides 3 (placeholder slides)`  [AMBIGUOUS]
  files/slides3.pdf · relation: conceptually_related_to

## Knowledge Gaps
- **86 isolated node(s):** `fitvids`, `jquery`, `jquery-smooth-scroll`, `magnific-popup`, `onchange` (+81 more)
  These have ≤1 connection - possible missing edges or undocumented components. (Counts symbols only; 172 node(s) total have ≤1 connection when file, concept and rationale nodes are included.)
- **16 thin communities (<3 nodes) omitted from report** — run `graphify query` to explore isolated nodes.

## Suggested Questions
_Questions this graph is uniquely positioned to answer:_

- **Why does `Scripts Include` connect `Archive & Profile Includes` to `Minified Theme JS Bundle`, `Analytics Providers`?**
  _High betweenness centrality (0.078) - this node is a cross-community bridge._
- **Are the 10 inferred relationships involving `e()` (e.g. with `main.min.js` and `et()`) actually correct?**
  _`e()` has 10 INFERRED edges - model-reasoned connections that need verification._
- **What connects `fitvids`, `jquery`, `jquery-smooth-scroll` to the rest of the system?**
  _86 weakly-connected nodes found - possible documentation gaps or missing edges._
- **Should `Minified Theme JS Bundle` be split into smaller, more focused modules?**
  _Cohesion score 0.06393606393606394 - nodes in this community are weakly interconnected._
- **Why does `base_path include` connect `Archive & Profile Includes` to `Comment Provider Embeds`, `CV Pages & Data`, `About & Community Pages`?**
  _High betweenness centrality (0.057) - this node is a cross-community bridge._

### Low-confidence Hints
_AMBIGUOUS edges — the extractor was unsure. Verify before acting on these._

- **What is the exact relationship between `Community Involvement` and `Page not in menu`?**
  _Edge tagged AMBIGUOUS (relation: conceptually_related_to) - confidence is low._
- **What is the exact relationship between `Hackathons` and `Page not in menu`?**
  _Edge tagged AMBIGUOUS (relation: conceptually_related_to) - confidence is low._