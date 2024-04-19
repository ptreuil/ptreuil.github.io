----

## CaLCUL 2024

*(Fall 2024 - Chairwoman - IDMC, Université de Lorraine)*

**Cognition and Language Conference at the University of Lorraine ([CaLCUL 2024](https://idmc.univ-lorraine.fr/calcul-2024-first-call-of-paper-ethics-and-ai/))**

The importance and impact of AI in our society do not need to be proven anymore. Like most revolutions, the initial stage of AI penetration in our daily lives was filled with experimentation and excitement.  However, as time passes and more and more people are affected by the new technology, it is critical to take a step back and think about our subject.

What are the overall impacts of our programs and models on society?

Do they affect all social groups equally and fairly? What are the positive and negative impacts and how can we maximize the benefits and minimize any harm that models can do? 

For its second edition, the Cognition and Language Conference at the University of Lorraine had for theme: “Ethics and AI”. Under my direction, some second years students have organised this event for all the master students. After a [first call for papers](calcul2024.pdf), we had the occasion to organise a review by the peer between students. In february, the volunteer students have presented the results of their different projects. For the first year like the older students, it was an opportunity to discuss our works and discover new point-of-view. The day ended on a lively debate with a slightly provocative title: **In the face of climate change, is it reasonable to keep developping highly performant but environmentally costing AIs ?**

----

## Case-Based Reasoning (CBR) Approach Using Analogy

*(Fall 2023 - Supervised by [M. Couceiro](https://members.loria.fr/mcouceiro/) and [G. Guibon](https://gguibon.github.io/) - IDMC, Université de Lorraine)*

**Group project**

Making inferences about new situations by comparing them with ones that are similar, is a common cognitive process as analogical transfer, involving drawing information from memories. Analogical transfer is implemented in Case-based reasoning (CBR) systems, so that the unseen problems are able to be solved by utilizing a set of previous cases which are stored in memory. Unlike the traditional machine learning, in the computational analogy methods, there is no need for a pre-existing trained model specific to the task ([Badra 2021](https://www.ijcai.org/Proceedings/2020/0222.pdf)). These methods depend entirely on a well-organized memory bank and the use of an effective similarity measure to operate. 

In this project, the CoAT method (Complexity-based Analogical Transfer) was used to conduct Case-Based Prediction. CoAT is based on the MeatCube algorithm which is created by Mr. Esteban Marquer. DIfferent classification and regression tasks have been tested on various dataset using this method, in order to observe if CoAT has different performances in different scenarios and with different similarity measures. A new computational cost metric was proposed, since the performance of CoAT is not comparable with the traditional neural networks models but have its own advantages (rapidity, low computational cost ...)

----

## Variant Analysis on the Book of Ben Sira

*(School year 2022-2023 - Supervised by [F. Rey](https://ecritures.univ-lorraine.fr/membres/titulaires/rey-f) - IDMC, Université de Lorraine)*

**Group project**

As the best selling publication of all time and with this importance in various religion, the Bible exists in many differant variants. The study of the diffusion of this variations, the way they were transcribe and translate give an interesting overview into the the dissemination of such ideas. This poject focused on three collections of manuscripts from the book of Ben Sira, found in Qumrân, Massada and Cairo. The *Book of Ben Sira* or *[Book of Sirach](https://en.wikipedia.org/wiki/Book_of_Sirach)* is a wisdom book written around 180 BCE by Yeshua ben Eleazar ben Sira in ancient Hebrew. This book is usually not considered a part of the Hebrew Bible but are part of the canon of most christian churches with the notable exceptions of the protestant denominations. The goal of the project was to perform a statistical analysis of the transcription errors between the 9 manuscripts using the [Collatex](https://pypi.org/project/collatex/) library to detect the variants between the texts. This variants where then classified by type: deletion, addition, words/letters switch etc ..

----

## Paperjam
*(Fall 2022 - Supervised by [M. Amblard](https://members.loria.fr/MAmblard/) and [M. Couceiro](https://members.loria.fr/mcouceiro/) - IDMC, Université de Lorraine)*

**Group project ([GitHub Link](https://github.com/PierreEpron/paperjam-lab) )**

Identifying scientific articles related to a specific feature is crucial for most researchers and students. The field of Natural Language Processing (NLP) has long been interested in this task. Different Information Extraction (IE) pipelines have been developed for this purpose. Most of them adopt a similar approach. They first extract mentions associated with specific entities such as tasks, materials, metrics, and methods. Then, they arrange them into coreference clusters. Lastly, they establish relationships between these clusters. This article aims to show some of the unresolved issues with that approach, by focusing on an already existing pipeline: SciREX. To achieve this, it was first necessary to set up their methodology, to which a few minor modifications were implemented.