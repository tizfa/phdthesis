# My PhD thesis
This is the repository containing my PhD thesis entitled "COMPUTING FRAMEWORKS AND APPLICATIONS FOR TEXT PROCESSING ON BIG DATA".

## Abstract of the thesis
The extreme popularity gained in the last years by Internet, and the Web in particular, as the main communication tool used by users and companies, has determined an exponential growth of generated information potentially useful for data analysis tasks. 
A large part of this generated data is represented by textual content, which is an information type completely unstructured (or marginally structured, e.g., HTML), which requires complex statistical and linguistic analyses to obtain helpful structured and semantic information from the original data. 
Analyzing large amount of texts is not a trivial task. 
Existing text mining software and libraries are generally optimized for sequential code execution on single machines. 
Furthermore, these software packages usually provide a limited set of specific features for text analyses, imposing to programmers to spend a relevant effort in the integration tasks required to build complete software solutions. In addition, no existing big data processing tools provide specialized libraries able to natively process textual contents. This issue's solution is demanded to developers, which have to provide ingenious integration strategies case per case, without the possibility to use a systematic and well defined approach.

In this thesis, we worked on overcoming these limitations by investigating three possible big data application scenarios in which we want to show how to approach text mining problems with effective integration strategies of different technologies and deployment of innovative software tools aiming at simplifying the work of developers.  

In first scenario, covering standalone efficient tools operating with small/medium amount of data, we first introduce JaTeCS, a sequential text processing framework which offers many of the tools needed by developers to perform complete experimentations on text analytics problems. The software offers a powerful data structure called Index which allows programmers to easily access and manipulate analyzed information. Moreover, JaTeCS covers, in a "plug and play" programming style, all the steps and components that are usually part of a complete text mining pipeline: data acquisition, data preprocessing, data indexing, data models learning and data models evaluation.

We then move to analyze two specific use cases of such application scenario which make extensive use of JaTeCS as the core textual processing framework for the designed solutions. In the first use case we propose an automatic classifier for company websites to be used as a support tool for classification task  of companies by industry sector. As a second case study, we  show how to build a mobile apps classification system working on custom taxonomies defined by users. In both cases, we use several of the methods and algorithms provided by JaTeCS to build and evaluate the systems.

We then explore a second application scenario in which the focus is on processing high amount of textual information using computation environments based on multithread single machines or of distributed type. In this context, we propose and evaluate Processfast, a new multi-thread data processing library offering the possibility to easily use task and data parallelism approaches  inside the same application. We also present distributed solutions by proposing NLP4Spark, a data ingestion library built over Apache Spark and similar in spirit to JaTeCS, which offers a clean and concise API to conveniently access and transform  managed data. As an interesting case study of "big data" technologies integration, we also show how to build a social media application ingesting data from Twitter and which is used as monitoring/support tool for emergency responders in crisis management of man-made/natural disasters.

We conclude our thesis by exploring a third application scenario in which deep learning methods are used to learn complex models over large amount of data. We thus present a novel deep learning method called Text2Vis which is a cross-media retrieval neural network able to translate a textual query into a visual space query and thus use this visual representation to search for similar images into a large storage of images.


## Download
Here you can download the PDF of my thesis: [Phd thesis](https://github.com/tizfa/phdthesis/raw/master/thesis.pdf)
