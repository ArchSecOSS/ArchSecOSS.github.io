---
title: "Welcome to ArchSec"
permalink : /
layout: splash
author: Bernhard Berger
author_profile: true
classes: wide

feature_row:
  - title: "Reverse Engineering"
    excerpt: "*ArchSec* uses static analysis to (semi-) automatically extended dataflow diagrams of existing software systems, making it easier to start architectural risk analysis for existing systems. Furthermore, the extracted extended dataflow diagram reflects the actual system, and there is no gap between the planned architecture and the implemented one."
    image_path: "/assets/images/reverse-engineering.png"
    alt: "Reverse engineering pictogram."
  - title: "Dataflow Diagrams"
    excerpt: "*ArchSec* employs more formal dataflow diagrams for representing architectural views of software systems. The core of these extended dataflow diagrams is its extensible schema, allowing them to define new node and edge types and specify implied attributes of such types."
    image_path: "/assets/images/dataflow-diagram.png"
    alt: "Exemplary dataflow diagram depiction."
  - title: "Security Flaws"
    excerpt: "*ArchSec* collects formalised threat descriptions in a knowledge base and automatically detects these threats in extended dataflow diagrams. The knowledge base allows non-security experts to use architectural risk analysis. Still, it offers advantages for security experts since not all security experts know all aspects of security equally well."
    image_path: "/assets/images/security-flaws.png"
    alt: "Security flaw pictogram."

#url: "#test-link"
#btn_label: "Read More"
#btn_class: "btn--inverse"

---

{: .text-justify}

# Welcome to the home of *ArchSec*.

*ArchSec* is the *Architectural Security Tool
Suite* that automates Microsoft's Threat Modeling and makes architectural risk
analysis more user-friendly. Therefore, it supports three key features:

{% include feature_row %}
