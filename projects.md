---
layout: page
title: Projects  
description: A description of project milestones expectations and deliverables.
has_children: true
nav_order: 3
---

# Milestones 

Project Milestones - Overview

| **Milestones** | **Brief Description**                                                                                                                                                                                                                     | **Due Date** | **Grade %** |
| -------------- |-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------| ------------ | ----------- |
| **MS1**        | *Project Proposals, Team formation -*  Students select a project from the given list, formulate a proposal and form teams. Staff reviews proposals and return feedback and project approvals by 01/07.                                                                      | **12/30**    | **5**       |
| **MS2**        | *MLOps Infrastructure & Advanced Training Workflows -* Building atomic containers, versioned data pipelines, and scalable computing solutions.                                                                                            | **01/20**    | **10**      |
| **MS3**        | *Scalable and Moduler Computing Infrastructure -* Extending advanced training workflows with Tensorflow, experiment tracking, multi-GPU training and serverless training.                                                                 | **02/10**    | **15**      |
| **MS4**        | **Midterm Presentation** - Presenting a fully functional CLI-based mega pipeline application with model optimization, performance monitoring, and severless inference.                                                                    | **02/24**    | **25**      |
| **MS5**        | *Full-Stack Development -* Design a user-friendly frontend developed around working API calls and design documents.                                                                                                                       | **03/30**    | **10**      |
| **MS6**        | **Final Presentation and Deliverables** - Students will finish by working through deployment and scaling, documenting the project through a published Medium post, a 6-minute video presentation, and a well-organized GitHub repository. | **TBD**    | **35**      |

Guidelines, submission instruction for milestones (and medium page) for future project events will be posted as they approach.


# Project Options

## Option A
## Pavlos-Wisperer
### Project Lead: Aamir A. Ansari

### Problem Statement
Automatic Speech Recognition (ASR) is a technology that converts spoken language into written text, enabling machines to understand and process human speech. In online education, ASR plays a crucial role in video transcription by automatically converting spoken words in educational videos into accurate and searchable text. This facilitates the creation of subtitles, enhances accessibility for diverse learners, and enables efficient content indexing, making educational materials more inclusive and easily navigable.

The objective of this project is to develop an Automatic Speech Recognition using the architecture of the state-of-the-art ASR, OpenAI's Whisper model. This model will be used specifically to identify Professor Pavlos's voice and hence we will fine-tune the model on his voice and generate accurate transcriptions. 

### Objectives
1.	Collect and preprocess speech recognition datasets.
2.	Develop a OpenAI Whisper based transformer model to generate transcripts from Professor Pavlos’s videos.
3.	Implement a scalable backend to handle multiple queries.
4.	Design an intuitive and user-friendly frontend.
5.	Integrate a large language model to provide summary and key points of the video using the generated transcripts.

### Learning Emphasis 
The project will focus on building complex transformer-based ASR model and building a scalable application to make it accessible to the end users. Also, we will learn about large language models and prompt engineering.

### Application Mock Design
The application will comprise of the following:
1.	An interface to upload the videos or taking URL of the videos.
2.	Separate web page to show the processed videos.
3.	Separate web pages to display the results of each video that comprise of the transcript, the video, the summary and the key points. 


### Research and Development
We will review the literature about Automatic Speech Recognition systems and their working including the OpenAI Whisper. Additionally, we’ll look into signal processing and techniques like Fourier Transform and its variations, that would be relevant for us in preprocessing. Finally, we’ll read about large language models and zero shot inference. 

### Fun Factor
Exploring the intersection of signal processing and deep learning is a fascinating aspect, which makes this project more attractive.

### Limitations and Risks
1.	Computational limitations when training and deploying complex models.
___


## Option B
## [Information Extraction & Surveillance in the Biomedical Industry](https://docs.google.com/document/d/e/2PACX-1vS8q075KH0sff7eC29oJ9RO0MfzVHVdq4zQJAVK_p1D1WqjdM5OX7uo90_RrWKRqN1W9qz8H0K5yy_0/pub)
### Project Lead: Shivas Jayaram

### **Background and Motivation**
With the explosion of information to users daily, challenges to keep up with the most relevant and up to date information is an ongoing challenge. Information extraction is the process of extracting valuable structured data from unstructured text. In the past year,  Large Language Models (LLMs) have reshaped the natural language processing (NLP) landscape.  Large language models have demonstrated remarkable capabilities in understanding and generating text. However, extracting structured information from unstructured text remains a challenge. Especially in a very domain specific context with tasks such as named entity recognition, relation extraction, and entity linking. 

The motivation for this project is to explore the  advancements in information extraction techniques using LLMs. Language models like BERT and its flavors can already do a great job in NLP tasks such as named entity recognition, relation extraction, and entity linking. However, this effort is to apply LLMs on text documents for similar tasks. Once the document is converted into structured data, surveillance on this data can help users get the exact information they are looking for quickly. 


### **Problem Statement**
The goal of this project is to explore the advancements and potential of leveraging large language models for extracting structured information from unstructured text. The aim is to showcase innovative research and methodologies that harness the power of LLMs to overcome the challenges of information extraction, such as named entity recognition, relation extraction, and entity linking. By converting documents into structured representations, the monitoring and surveillance of large amounts of information become manageable and provide insights in a timely manner.


### **Objectives**
* Build a web scraper to collect data from various data sources
* Evaluate a few LLMs for these NLP tasks: named entity recognition, relation extraction, and entity linking.
* Integrate LLM(s) into a ML pipeline to convert unstructured to structured data.
* Design and develop a strategy to fine tune, generate prompts, and manage LLM tasks so they can be easily expanded.
* Integrate regular language models into data pipelines for document classification or other smaller tasks to help manage data.
* Design and implement a user friendly dashboard / app


### [Refere here for more details](https://docs.google.com/document/d/e/2PACX-1vS8q075KH0sff7eC29oJ9RO0MfzVHVdq4zQJAVK_p1D1WqjdM5OX7uo90_RrWKRqN1W9qz8H0K5yy_0/pub)




---

## Option C
## Scientific Click-Bait

## Enhancing Academic Paper Visibility with Intelligent Title Generation

### Project Lead: Pavlos Protopapas

**Project Overview**

This initiative taps into the expansive NASA/ADS database, maintained by the Harvard-Smithsonian Center for Astrophysics. This database is a treasure trove of astronomy-related research papers, made searchable through a robust system. Significantly, the NASA/ADS API offers insights into papers and their engagement metrics, such as readership statistics.

The project's mission is to build a web application designed to boost the visibility and impact of academic papers. Researchers will upload their papers onto this platform, which will then employ advanced algorithms to craft a compelling, optimized title. These titles are intended to capture the paper's core subject matter while simultaneously being tailored to attract more readers. This approach seeks to narrow the divide between detailed scholarly work and approachable, intriguing titles that draw a broader audience.

**Key Objectives**

1. Deploy language models to summarize a broad range of papers from the ADS API.
2. Fine-tune these models for targeted title generation.
3. Develop models to forecast and enhance title readability.
4. Construct a robust backend system for handling multiple user requests.
5. Design a straightforward, engaging user interface.



**Application Mockup Design**

The application will feature:

1. A portal for paper uploads or direct URL submissions.
2. Options to receive several title and abstract suggestions.

**Data Handling**

**Data Acquisition via ADS API:**

- **Data Source**: The primary data for model training will be sourced from the ADS API.
- **Data Characteristics**: This data will include the paper's content, title, and reader engagement metrics.

**User Engagement**

Pavlos, your professor, will be the inaugural user, providing first-hand feedback and insights.

**Challenges and Constraints**

1. Technical and computational challenges in training and deploying sophisticated models.

## Option D
## ASTROMER-Lining
### Project Lead: Pavlos Protopapas, Ignacio Becker, Anshika Gupta, Aamir A. Ansari

[ASTROMER](https://arxiv.org/pdf/2205.01677.pdf) is a transformer-based model for generating representations of light curves, pretrained in a self-supervised manner without human-labeled data. Trained on millions of R-band light sequences, its adaptability allows easy retraining on new sources, making it applicable to various surveys. The model extracts powerful light curve embeddings, enhancing the training of classifiers and regressors. 

In this project; ASTROMER-Lining(That's just pipelining services for ASTROMER) we would develop and enhance the exisiting pipelines of the ASTROMER including the data pipeline and training pipelines. In the end, we provide a web application where the users can select the service of either to fine-tune or pre-train with the dataset they provide. 

**Objectives**
1. Understand ASTROMER and build the pre-training pipeline.
2. Using the pre-trained models to build fine-tuning pipeline.
3. Building a scalabale application to for users to use ASTROMER services, which are: a) To get Embeddings from pre-trained models, fine-tune and get weights, pre-train and get weights for the model. 


**Application Mockup Design**

1. The landing page will accept a file containing light_curves and choose from the services.
2. Provide download options for embeddings or a cloud link to check back and download the weights.

**About Data**
We will be using the MACHO dataset mentioned in the paper. Each light curve in the data contains the [Modified Julian Date](https://core2.gsfc.nasa.gov/time/) and corresponding magnitudes.


---

## Option E
## OptiBench Prime
### Project Lead: Aamir A. Ansari

Large language models are like language superheroes, armed with billions of brainy parameters. They're really good at understanding language intricacies—how words fit together and what they mean. Imagine these models as tech wizards using massive datasets to get super smart at language tasks. They're the cool tools making artificial intelligence smarter and more useful every day!

So lets embark on a pragmatic exploration with our project, "OptiBench Prime" where we systematically assess large language models across various benchmarks, offering a realistic and methodical analysis. The OptiBench Prime Framework simplifies the intricate process of evaluation, presenting findings in an engaging dashboard. Join us in navigating the realm of language models with practicality and precision.

**Objectives**
1. Understanding the origins of large language models and quantization schemes.
2. Setting up pipelines to run large language models on various taks with zero shot inference and multishot inference(Prompt Engineering Pro Max XD).
3. Setting up pipelines to run large language models on various taks by perfoming task specific fine-tuning these models.
4.  Building a dashboard to display results of all the experiments performed. Just a heads up, its not going to be a table on a web page. 

**Challenegs**
The compute cost for some of the open-source models might be high, however with their quantized versions we will be able to fit them in smaller gpu's. But is somethings to note be aware of.

**About Data**
We will consider standard datasets that are being used for various natural language processing tasks. For instance, to evaluate llms on named entity recoginition tasks, one standard dataset is [CoNLL-2003](https://arxiv.org/pdf/cs/0306050v1.pdf). Also, we will choose multiple datasets for evaluation on the same task.