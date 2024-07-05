---
title: "Transferable Pre-Synthesis PPA Estimation for RTL Designs With Data Augmentation Techniques"

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here 
# and it will be replaced with their full name and linked to their profile.
authors:
- admin
- Yao Lu
- Shang Liu
- Qijun Zhang
- Ceyu Xu
- Lisa Wu Wills
- Hongce Zhang
- Zhiyao Xie


# Author notes (optional)

date: "2024-07-01T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2024-07-01T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["2"]

# Publication name and optional abbreviated publication name.
publication: In IEEE Transactions on Computer-Aided Design of Integrated Circuits and Systems 
publication_short: In TCAD

abstract: 

# Summary. An optional shortened abstract.
summary: 

tags: []

# Display this page in the Featured widget?
featured: false

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: 'https://ieeexplore.ieee.org/abstract/document/10577671'
url_code: ''
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: ''
url_source: ''
url_video: ''

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 

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
In modern VLSI design flow, evaluating the quality of register-transfer level (RTL) designs involves time-consuming logic synthesis using EDA tools, a process that often slows down early optimization. While recent machine learning solutions offer some advancements, they typically struggle with maintaining high accuracy across any given RTL design. In this work, we propose an innovative transferable pre-synthesis PPA estimation framework named MasterRTL. It first converts the HDL code to a new bit-level design representation named the simple operator graph (SOG). By only adopting single-bit simple operators, this SOG proves to be a general representation that unifies different design types and styles. The SOG is also more similar to the target gate-level netlist, reducing the gap between RTL representation and netlist. In addition to the new SOG representation, Master-RTL proposes new ML methods for the RTL-stage modeling of timing, power, and area separately. Compared with state-of-theart solutions, the experiment on a comprehensive dataset with 90 different designs shows accuracy improvement by 0.33, 0.22, and 0.15 in correlation for total negative slack (TNS), worst negative slack (WNS), and power, respectively. Besides the prediction of synthesis results, MasterRTL also excels in accurately predicting layout-stage PPA based on RTL designs and in adapting across different technology nodes and process corners. Furthermore, we investigate two effective data augmentation techniques: a graph generation method and a Large Language Model (LLM)-based approach. Our results validate the effectiveness of the generated RTL designs in mitigating data shortage challenges.