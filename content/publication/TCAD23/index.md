---
title: "r-map: Relating Implementation and Specification in Hardware Refinement Checking"

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here 
# and it will be replaced with their full name and linked to their profile.
authors:
- admin
- Guangyu Hu
- Hongce Zhang


# Author notes (optional)

date: "2023-06-01T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2023-06-01T00:00:00Z"

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

url_pdf: 'https://ieeexplore.ieee.org/abstract/document/10178019'
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
Refinement checking is an important formal verification method that checks if a hardware implementation complies with (in other words, refines) a given specification. It has been widely used in processor and nonprocessor verification. In refinement checking, a refinement mapping is needed to relate the implementation and the specification. Despite the wide adoption of refinement checking, there is currently no general format or standard for the mapping—most prior works employed a certain property specification language (e.g., the SystemVerilog assertion) to write ad-hoc properties that describe the mapping relation. These manually written properties are usually not well structured and are often difficult to design or understand. In this article, we present r−map , a language for refinement mapping. r−map relates the implementation and the specification in a more concise and comprehensible way. We evaluate r−map in the refinement checking of practical hardware designs. In our case study, r−map shows a significant reduction of human efforts compared to manually writing refinement properties. We also show how r−map can help to scale up formal verification.