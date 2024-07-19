---
title: The ENEM Challenge
summary: A University-Entrance Level Standardized Test Benchmark for AI.
tags:
- Artificial Intelligence
- ENEM
- Natural Language Processing
- Commonsense Reasoning
date: "2018-10-01"

# Optional external URL for project (replaces project detail page).
external_link: ""

# image:
#   caption: Photo by rawpixel on Unsplash
#   focal_point: Smart

#links:
# - icon: twitter
#   icon_pack: fab
#   name: Follow
#   url: https://twitter.com/georgecushen
url_dataset: "ENEMdataset.zip"
url_pdf: "ENEM-GuidingTest"
url_slides: ""
url_video: ""

# Slides (optional).
#   Associate this project with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
slides: ""
---

It is widely accepted that university entrance exams require human-level
intelligence to be satisfactorily solved. In particular, such exams
require skills such as text and image understanding, informational retrieval,
commonsense reasoning, and mathematical thinking.

Thus, university entrance exams constitute a good test for real Artificial Intelligence techniques.

The [Exame Nacional do Ensino Médio (ENEM)](https://en.wikipedia.org/wiki/Exame_Nacional_do_Ensino_M%C3%A9dio) is an advanced High-School level exam widely applied every year by the Brazilian government to students that wish to undertake a University degree.

The **ENEM Challenge** consists in designing an autonomous system that matches the performance of a human students on the exam. The overall goal is to foster and evaluate the development of Artificial Intelligence techniques that have good performance on complex cognitive tasks, not particularly designed for AI systems. In addition, this challenge aims to promote and give more visiblity to the development of NLP tools for Brazilian Portuguese.

**The informal and witty aim of the challenge is to get a digital student to be accepted at a main Brazilian university**.

# Dataset

 The ENEM exam consists of the writing of an essay and an objective part containing 180 multiple choice questions. The questions are divided into four groups of 45 questions each, namely, Humanities, Languages, Sciences and Mathematics.

 This dataset contains only the textual part of objective part, segmented in questions. Every question is divided into 3 parts:

- The _header_, contianing background knwoledge in the form of an image, text or table is given;
- The _statement_, containing the text of the question;
- The _answers_, split into five fields, each containing the text of a candidate-answer (A,B,C,D,E), along with an additional tag informing the correct answer.

In addition, every question is annotated with the following tags:

- `id`: the question number in that assessment;
- `image`: does it has an accompanying image in the exam?
- `EK`: does it require knowledge not given in the header?
- `TC`: does it require textual understanding of the header?
- `IC`: does it require understanding of the associated image?
- `DS`: does it require complex inference or domain specific knowledge?
- `MR`: does it requires transforming instructions in natural language into mathematical formula?
- `CE`: does it require treating chemical elements especially?

Currently, the challenge uses an XML version of questions taken from the exams between 2009 and 2017.

A more in-depth description of the dataset is found [here](ENEM-GuidingTest.pdf).

# Download

The 776kb zip archive containing the XML file can be downloaded [here](ENEMdataset.zip)

# Solutions

If you design a new solution, please [send me a message]({{< ref "/#contact" >}}) reporting accuracy, reference (if any) and information as below. Here is a list of current solutions:

 Paper | Accuracy | Note   
-------|----------|--------


# Citation

If you use this dataset, please cite the following work:

        @InProceedings{ ENEM-Challenge,
                author = {Silveira, Igor Cataneo and Mau\'a, Denis Deratani},
                booktitle = {Proceedings of the 6th Brazilian Conference on Intelligent Systems},
                series = {BRACIS},
                title = {University Entrance Exam as a Guiding Test for Artificial Intelligence},
                pages = {426--431},
                year = {2017}
        }