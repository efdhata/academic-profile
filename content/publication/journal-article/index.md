---
title: "Site-Adaptation for Correcting Satellite-Derived Solar Irradiance: Performance Comparison between Various Regressive and Distribution Mapping Techniques for Application in Daejeon, South Korea"
authors:
- admin
- Chang Ki Kim
- Hyun-Goo Kim
- Boyoung Kim
- Myeongchan Oh
author_notes:
- 
- "Corresponding Author"
date: "2022-11-28T00:00:00Z"
doi: "10.3390/en15239010"

# Schedule page publish date (NOT publication's date).
publishDate: "2022-11-28T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["2"]

# Publication name and optional abbreviated publication name.
publication: "*Energies, 15*"
publication_short: ""

abstract: Satellite-derived solar irradiance is advantageous in solar resource assessment due to its high spatiotemporal availability, but its discrepancies to ground-observed values remain an issue for reliability. Site adaptation can be employed to correct these errors by using short-term high-quality ground-observed values. Recent studies have highlighted the benefits of the sequential procedure of a regressive and a distribution-mapping technique in comparison to their individual counterparts. In this paper, we attempted to improve the sequential procedure by using various distribution mapping techniques in addition to the previously proposed quantile mapping. We applied these site-adaptation techniques on the global horizontal irradiance (GHI) and direct normal irradiance (DNI) obtained from the UASIBS-KIER model in Daejeon, South Korea. The best technique, determined by a ranking methodology, can reduce the mean bias from &minus;5.04% and 13.51% to &minus;0.45% and &minus;2.02% for GHI and DNI, respectively, and improve distribution similarity by 2.5 times and 4 times for GHI and DNI, respectively. Partial regression and residual plot analysis were attempted to examine our finding that the sequential procedure is better than individual techniques for GHI, whereas the opposite is true for DNI. This is an initial study to achieve generalized site-adaptation techniques for the UASIBS-KIER model output.

# Summary. An optional shortened abstract.
summary: Site adaptation can be employed to correct satellite-derived solar irradiance that has discrepancies to ground-observed values. In this paper, we attempted to improve the sequential site-adaptation procedure by using various distribution mapping techniques in addition to the previously proposed quantile mapping.

tags:
- site-adaptation
featured: false

# links:
# - name: ""
#   url: ""
url_pdf: https://www.mdpi.com/1996-1073/15/23/9010/pdf?version=1669721791
url_code: ''
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: ''
url_source: ''
url_video: ''

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
image:
  caption: 'Example of site-adaptation'
  focal_point: ""
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects: []

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
<>slides: example
slides: ""
---

---
title: "Toward Improved Site-Adaptation for Direct Normal Irradiance: Exploiting Sky-Condition Classification for Improved Regression-Based, Quantile-Based, and Neural Network Models"
authors:
- admin
- Chang Ki Kim
- Myeongchan Oh
- Hyun-Goo Kim
author_notes:
- 
- "Corresponding Author"
date: "2024-01-10T00:00:00Z"
doi: "10.1007/s13143-023-00350-4"

# Schedule page publish date (NOT publication's date).
publishDate: "2024-01-10T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["2"]

# Publication name and optional abbreviated publication name.
publication: "*Asia-Pac J Atmos Sci, 60*"
publication_short: ""

abstract: Site adaptation has become a necessary step in resource assessment for ensuring the bankability of a renewable energy project. The process involves collecting short-term observation data to correct the long-term dataset available from the satellite-derived models, which could thus provide a more accurate estimate of the solar resource data. This study aims to enhance the site-adaptation of direct normal irradiance, as its correction remains notably challenging in comparison to global horizontal irradiance due to its larger error, which is often attributed to the complexity of cloud modeling. A new methodology for site-adaptation is proposed that exploits the use of a new indicator variable that describes the correctness of sky-condition classification by the clear-sky index. This variable has dual applications within the context of site adaptation: firstly, it is employed in the two-step binning procedure subsequent to the conventional clear-sky binning during preprocessing, and secondly, it serves as an additional input feature in machine-learning-based site adaptation. The results show that the former method can reduce the mean bias error to a mere 0.4%, while the latter is better for reducing large discrepancies as shown by the lower root mean squared error.

# Summary. An optional shortened abstract.
summary: This study introduces a variable--an indicator of sky-condition classification correctness--to be applied in two novel methodologies of site-adaptation. The use of this variable resulting in improved performance, notably in the substantial reduction of MBE toward a near-perfect value (almost 0).

tags:
- site-adaptation
featured: false

# links:
# - name: ""
#   url: ""
url_pdf: https://rdcu.be/dZu17
url_code: ''
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: ''
url_source: ''
url_video: ''

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
image:
  caption: 'Example of site-adaptation'
  focal_point: ""
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects: []

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
<>slides: example
slides: ""
---


{{% callout note %}}
Click the *Cite* button above to demo the feature to enable visitors to import publication metadata into their reference management software.
{{% /callout %}}

{{% callout note %}}
Create your slides in Markdown - click the *Slides* button to check out the example.
{{% /callout %}}

Supplementary notes can be added here, including [code, math, and images](https://wowchemy.com/docs/writing-markdown-latex/).
