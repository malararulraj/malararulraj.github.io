---
title: "Automatic detection and classification of low-level orographic precipitation processes from space-borne radars using machine learning"
authors:
- Malarvizhi Arulraj
- Ana P. Barros
author_notes:
date: "2021-02-19T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2021-02-19T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["2"]

# Publication name and optional abbreviated publication name.
publication: "Remote Sensing of Environment, Volume 257, May 2021, 112355"
publication_short: ""

abstract: Ground-clutter is a significant cause of missed-detection and underestimation of precipitation in complex terrain from space-based radars such as the Global Precipitation Measurement Mission (GPM) Dual-frequency Precipitation Radar (DPR). This research proposes an Artificial Intelligence (AI) framework consisting of a precipitation detection model (PDM) and a precipitation regime classification model (PCM) to improve orographic precipitation retrievals from GPM-DPR using machine learning. The PDM is a Random Forest Classifier using GPM Microwave Imager (GMI) calibrated brightness temperatures (Tbs) and low-level precipitation mixing ratios from the High-Resolution Rapid Refresh (HRRR) analysis as inputs. The PCM is a Convolutional Neural Network that predicts the precipitation regime class, defined independently based on quantitative features of ground-based radar reflectivity profiles, using GPM DPR Ku-band (Ku-PR) reflectivity profiles and GMI Tbs. The AI framework is demonstrated for warm-season precipitation in the Southern Appalachian Mountains over three years (2016–2019), achieving large reductions in false alarms (77%) and missed detections (82%) relative to GPM Ku-PR precipitation products. The spatial distribution of predicted precipitation classes within the GPM overpass reflects the complex interactions between storms and topography that determine orographic precipitation regimes. For each GPM pixel, the local precipitation class informs on the vertical structure of rainfall microphysics aiming to capture low-level processes missed in GPM DPR reflectivity profiles contaminated by ground-clutter (i.e., the radar blind-zone).

# Summary. An optional shortened abstract.
Summary: AI models improve space-based radar (GPM) monitoring of orographic precipitation, NWP low-level condensed water distribution is useful to mitigate ground-clutter, The ML detection model reduces false alarms by 77% and missed detections by 82%, MRMS precipitation vertical structure classes map orographic enhancement regimes, Coupled AI-Physical retrieval can significantly reduce GPM orographic QPE errors. 

# links:
# - name: ""
#   url: ""
url_pdf: https://www.sciencedirect.com/science/article/pii/S0034425721000730
# url_code: 'https://github.com/wowchemy/wowchemy-hugo-themes'
# url_dataset: ''
# url_poster: ''
# url_project: ''
# url_slides: ''
# url_source: ''
# url_video: ''

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
slides: ""
---

