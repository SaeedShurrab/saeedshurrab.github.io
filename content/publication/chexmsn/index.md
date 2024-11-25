---
title: "Multimodal masked siamese network improves chest X-ray representation learning"
authors:
- admin
- Alejandro Guerra-Manzanares
- Farah E. Shamout
author_notes:
- "Equal contribution"
- "Equal contribution"

date: "2024-09-28T00:00:00Z"
doi: "https://doi.org/10.1038/s41598-024-74043-x"
# Schedule page publish date (NOT publication's date).
publishDate: "2024-09-28T00:00:00Z"

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ["article-journal"]

# Publication name and optional abbreviated publication name.
publication: "Nature Scientific Reports"
publication_short: ""

abstract: Self-supervised learning methods for medical images primarily rely on the imaging modality during pretraining. Although such approaches deliver promising results, they do not take advantage of the associated patient or scan information collected within Electronic Health Records (EHR). This study aims to develop a multimodal pretraining approach for chest radiographs that considers EHR data incorporation as an additional modality that during training. We propose to incorporate EHR data during self-supervised pretraining with a Masked Siamese Network (MSN) to enhance the quality of chest radiograph representations. We investigate three types of EHR data, including demographic, scan metadata, and inpatient stay information. We evaluate the multimodal MSN on three publicly available chest X-ray datasets, MIMIC-CXR, CheXpert, and NIH-14, using two vision transformer (ViT) backbones, specifically ViT-Tiny and ViT-Small. In assessing the quality of the representations through linear evaluation, our proposed method demonstrates significant improvement compared to vanilla MSN and state-of-the-art self-supervised learning baselines. In particular, our proposed method achieves an improvement of of 2%  in the Area Under the Receiver Operating Characteristic Curve (AUROC) compared to vanilla MSN and 5% to 8% compared to other baselines, including uni-modal ones. Furthermore, our findings reveal that demographic features provide the most significant performance improvement. Our work highlights the potential of EHR-enhanced self-supervised pretraining for medical imaging and opens opportunities for future research to address limitations in existing representation learning methods for other medical imaging modalities, such as neuro-, ophthalmic, and sonar imaging.
# Summary. An optional shortened abstract.
summary: Self-supervised learning methods for medical images primarily rely on the imaging modality during pretraining. Although such approaches deliver promising results, they do not take advantage of the associated patient or scan information collected within Electronic Health Records (EHR). This study aims to develop a multimodal pretraining approach for chest radiographs that considers EHR data incorporation as an additional modality that during training. We propose to incorporate EHR data during self-supervised pretraining with a Masked Siamese Network (MSN) to enhance the quality of chest radiograph representations. We investigate three types of EHR data, including demographic, scan metadata, and inpatient stay information. We evaluate the multimodal MSN on three publicly available chest X-ray datasets, MIMIC-CXR, CheXpert, and NIH-14, using two vision transformer (ViT) backbones, specifically ViT-Tiny and ViT-Small. In assessing the quality of the representations through linear evaluation, our proposed method demonstrates significant improvement compared to vanilla MSN and state-of-the-art self-supervised learning baselines. In particular, our proposed method achieves an improvement of of 2%  in the Area Under the Receiver Operating Characteristic Curve (AUROC) compared to vanilla MSN and 5% to 8% compared to other baselines, including uni-modal ones. Furthermore, our findings reveal that demographic features provide the most significant performance improvement. Our work highlights the potential of EHR-enhanced self-supervised pretraining for medical imaging and opens opportunities for future research to address limitations in existing representation learning methods for other medical imaging modalities, such as neuro-, ophthalmic, and sonar imaging.

tags:
- CXR
- EHR
- Multimodal
- SSL
featured: true

# links:
# - name: ""
#   url: ""
url_pdf: https://www.nature.com/articles/s41598-024-74043-x.pdf
url_code: 'https://github.com/nyuad-cai/CXR-EHR-MSN'
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: ''
url_source: ''
url_video: ''

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
image:
  caption: ''
  focal_point: "center"
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects: ['self-supervised']

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
# slides: example
---

<!-- {{% callout note %}}
Click the *Cite* button above to demo the feature to enable visitors to import publication metadata into their reference management software.
{{% /callout %}}

{{% callout note %}}
Create your slides in Markdown - click the *Slides* button to check out the example.
{{% /callout %}}

Add the publication's **full text** or **supplementary notes** here. You can use rich formatting such as including [code, math, and images](https://docs.hugoblox.com/content/writing-markdown-latex/). -->
