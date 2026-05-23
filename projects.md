---
layout: page
title: Personal Projects
---

Here are more detailed descriptions of the projects I have been involved in so far, from most to least recent.

### Semantic Based Prediction Planning - Parasol
My most recent and newest project. For effective collaboration, robots must do more than just react; they need to anticipate. This requires inferring unobservable human intentions and predicting future actions. Anticipatory behavior is the next frontier in fluent human-robot collaboration (HRC), moving from reactive to proactive robots. This project aims to synthesize current prediction methods with core motion planning methods, as current prediction methods such as Bayesian methods, Markov Models, and Supervised Deep Learning are no longer sufficient. We aim to solve those utilizing planning methods. When researching how to implement and analyze these methods, however, we had trouble finding literature fully investigating this. After reading over 70 papers on prediction and planning methods, we decided to formalize our findings and are in the process of writing a literature review.

### HAS-RRT: Motion Planning for Protein-Ligand Interactions - Parasol
Last semester, my project was aimed at using Hierarchical Annotated Skeleton RRT (HASRRT) to evaluate whether binding sites in proteins are accessible. A key principle of drug design is how ligands bind to proteins, and how those interactions determine the behavior of the protein. We planned to utilize HAS-RRT to help ligands traverse the configuration space within a protein to find the lowest-energy path to their target binding site. Compared to other motion planning algorithms (Basic RRT, DR-RRT, EET, etc.), HAS-RRT has shown significant runtime and efficiency improvements. 


### Drive Doctor
Since August 2024, I have been collaborating with a team of 3 to design and develop a Google Chrome extension that seamlessly manages and organizes Google Drive files. Built with Python, HTML/CSS, JSON, and JavaScript, the extension leverages Flask to bridge the front and back end, enabling dynamic file creation directly from the browser. We have also integrated a custom LLM pipeline using the MiniLM Sentence Transformer from Hugging Face to perform semantic similarity analysis, allowing the extension to intelligently categorize and organize files into relevant folders.

### Miscelaneous Machine Projects
Within the multiple classes I have taken at UIUC, including Data Structures, Algorithms, and Systems Programming, I have had the opportunity to complete dozens of machine projects. These helped me not only solidify my understanding of computational design and systems, but apply them in a practical sense. My top three so far are Seam Carving (resize images without loss of quality utilizing the seam carving method), Shell (build a command line that can handle built-in shell commands, logical operators, and SIGINT handling), and Nonstop Networking (build a Server that can handle a very large number of concurrent clients for file sharing, as well as a Client to use with said server).
