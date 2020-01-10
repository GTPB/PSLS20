---
layout: page
schemadotorg:
  "@context": http://schema.org/
  "@type": CreativeWork
  "genre": TrainingMaterial

  # Course details
       # "name" -> The acronym and extended name of the course, separated by " - "
       # "description" -> Short description of the course
  name: "COURSE_SHORT - COURSE_EXTENDED_NAME"
  description: ""

  # Keywords -> Consult EDAM:Topic
  keywords:  ""

  # Audience -> Following Elixir-Tess input
  audience: ["Academia/ Research Institution", "Industry", "Non-Profit Organisation", "Healthcare"]

  # Author info
  author:
    - "@type": Organization
      name: "The Gulbenkian Training Programme in Bioinformatics"
      alternateName: "GTPB"
      sameAs: "gtpb.igc.gulbenkian.pt/bicourses/index.html"

  # predominant type of learning resources
  "learningResourceType": ["presentation", "exercise", "scripts", "handout"]

  # Contributor info
  contributor:
    - "@type": Person
      name: "Lieven Clement"
    - "@type": Person
      name: "Jeroen Gilis"


  # License & Language & url
  license: https://creativecommons.org/licenses/by/4.0/
  inLanguage: "en-us"
  url: "https://gtpb.github.io/Web_course_template/"
---

## Course Description

This intermediate level course is one of our Foundations courses. It covers essential statistical concepts and methods for extracting insights from empirical data in the life sciences. The course positions applied statistics, starting from important aspects of experimental design and data exploration. We then move into statistical modeling and data analysis. We will focus on the link between linear regression and analysis of variance. Together, these methods contribute to the study of General Linear Models. The course also introduces the basics of non-parametric testing, and addresses categorical data analysis and logistic regression.

The concepts and methods are exclusively introduced via case-studies in the life sciences. For every study we elaborate on a concrete research question and then provide a study design, which is followed by data exploration. Next, we will focus on how to model the data and elaborate on the link between model parameters and the subject matter research question.

---

### Learning objectives

The case studies will enable the participants to build self-confidence in
understanding, reading and communicating on data and data analysis
selecting appropriate statistical methods and software tools for analysing different types of data
interpreting the result of a statistical data analysis in terms of subject matter research questions and reporting them appropriately.

There is a strong emphasis in reproducible research by extensively using R/Rmarkdown scripts. This approach will enable the participants to weave statistical analyses, code, results and interpretation in webpages and PDF documents so that their entire data analysis workflow is transparent and reproducible. The course materials are designed in R/Rmarkdown, kickstarting the course participants into developing their own scripts.

---

### Practical Statistics for the Life Sciences



### [Instructors](pages/instructors.md)


---

The source for this course webpage is [in github](https://github.com/GTPB/Web_course_template).

<br/>

<a rel="license" href="http://creativecommons.org/licenses/by/4.0/"><img alt="Creative Commons License" style="border-width:0" src="https://i.creativecommons.org/l/by/4.0/88x31.png" /></a><br /><span xmlns:dct="http://purl.org/dc/terms/" property="dct:title">Web_course_template</span> by <span xmlns:cc="http://creativecommons.org/ns#" property="cc:attributionName">GTPB</span> is licensed under a <a rel="license" href="http://creativecommons.org/licenses/by/4.0/">Creative Commons Attribution 4.0 International License</a>.
