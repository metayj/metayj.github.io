---
title: "An Approach for High Definition Map Information Interaction for Autonomous Driving"
authors:
- admin
- Wei Huang
- Xintao Liu
- Fengyuan Zhang
- Hangbin Wu
- Shen Ying
- Chun Liu
author_notes:
- "Equal contribution"
- "Equal contribution"
date: "2024-04-25T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2024-04-20T00:00:00Z"

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ["article-journal"]

# Publication name and optional abbreviated publication name.
publication: "*Geomatics and Information Science of Wuhan University*, 49(4)"
# publication_short: ""

abstract: Objectives High definition（HD） map plays an important role in autonomous driving. Most existing research focuses on high-resolution mapping in terms of road geometries as well as the updating of static road information in HD map. However, there is still a lack of research on dynamic information involved in road traffic networks. We focus on enriching the content of HD map in terms of the dynamic information including the dynamic information, it's meta data structure and inforamation interaction.Methods We propose a comprehensive set of content that HD map need to cover for the dynamic information based on existing work on HD map data organization and data standards. Based on this, combined with cloud ends of HD map systems and vehicle ends of autonomous driving vehicles as two information interaction terminals, a method for information interaction between cloud ends and vehicle ends under different combination modes (vehicle-cloud, vehicle-vehicle, and cloud-vehicle modes) used in HD map information system is proposed to facilitate a timely capture of dynamic information in road environments.Results (1) The vehicle-cloud information interaction mode is suitable for self-driving cars. The vehicle collects vehicle dynamic information in real time and uploads it to the cloud of the HD map information system after preprocessing, so as to realize the sharing of perception information of different vehicles in the road environment on the cloud. (2)The vehicle-to-vehicle information interaction mode is used between different self-driving cars. This mode is mainly aimed at obtaining partially vehicle dynamic information directly through vehicle-to-vehicle interaction during driving. (3)The cloud-vehicle information interaction mode is suitable for vehicles connected to the HD map information system platform. The cloud stores dynamic information, and the vehicle requests the demanding information according to its own needs. Therefore, The HD map information system continuously performs information interaction in three interaction modes, and updates information simultaneously, maintaining the freshness of dynamic information and enhancing the robustness of HD map.Conclusions However, due to the complexity and variability of the road environment, the content of dynamic information interaction we propose can only cover what happens during vehicle driving to a certain extent. For the road information that appears with a small probability,we do not conduct in-depth research, which is also the direction we need to discuss and study in the future. 

# Summary. An optional shortened abstract.
Keywords: high definition map, self-driving, dynamic information, information interaction


tags:
- Source Themes
featured: false

# links:
# - name: ""
#   url: ""
url_pdf: content/publication/journal-paper/paper.pdf
url_code: ''
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: ''
url_source: 'http://ch.whu.edu.cn/en/article/doi/10.13203/j.whugis20230166'
url_video: ''

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
image:
  caption: 'Image credit: [**Unsplash**](http://ch.whu.edu.cn/indexen.htm)'
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
slides: example
---

{{% callout note %}}
Click the *Cite* button above to demo the feature to enable visitors to import publication metadata into their reference management software.
{{% /callout %}}

