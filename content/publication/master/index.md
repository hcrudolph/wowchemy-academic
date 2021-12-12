---
title: "Formal Verification of the 5G Inter-Operator Signaling Protocol"

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
- admin

# Author notes (optional)
#author_notes:

date: "2020-08-26T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2020-08-26T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["7"]

# Publication name and optional abbreviated publication name.
#publication: In *Wowchemy Conference*
#publication_short: In *ICW*

abstract: This thesis analyzes the formal security properties of the PRotocol for N32 INterconnect Security (PRINS), specified by the 3rd Generation Partnership Project (3GPP) for the purposes of protecting signaling traffic between 5G mobile networks. An emerging technology that is believed to enable a plethora of novel and potentially critical applications, it is mandatory that 5G communication be effectively secured by design. Since inter-operator signaling exhibits specific functional requirements that existing security protocols fail to address, 3GPP defines this purpose-built protocol that has yet to undergo thorough analysis by the broader research community at the time of this writing. Formal methods have successfully been used to validate and improve several security protocols in the past. The nature of this approach to verifying a system’s correctness makes it particularly suited for detecting logical flaws in the underlying design. Semiautomated tools for formal verification further aid the discovery of issues that would be non-trivial to identify by manual analysis. As part of this thesis, the PRINS specification is assessed in detail in order to understand all related message flows and derive the intended security properties. Subsequently, they are transposed into a formalized representation and verified against a model of the protocol for the popular model checker ProVerif. Although no concrete attacks substantiate from the formal verification, it is shown that the 3GPP specification contains several inconsistencies and, most notably, a lack of clarity about what the protocol is supposed to achieve. This ambiguity may potentially lead to unreliable and therefore insecure implementations. Based on these findings, a number of improvements are suggested that can help make the specification more explicit and easier to understand.

# Summary. An optional shortened abstract.
#summary:

tags: ["5G", "Security", "3GPP", "PRINS", "Formal Verification"]

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: 'publication/master/mt_hcrudolph_2020-08-26.pdf'
url_code: 'https://github.com/hcrudolph/master'
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: ''
url_source: ''
url_video: ''

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
#image:
#  caption: 'Image credit: [**Unsplash**](https://unsplash.com/photos/pLCdAaMFLTE)'
#  focal_point: ""
#  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
#projects:
#- example

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
#slides: example
---
