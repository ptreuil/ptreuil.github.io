## Case-Based Reasoning (CBR) Approach Using Analogy

*(Fall 2023 - Supervised by [M. Couceiro](https://members.loria.fr/mcouceiro/) and [G. Guibon](https://gguibon.github.io/) - IDMC, Université de Lorraine)*

**Group project**

Making inferences about new situations by comparing them with ones that are similar, is a common cognitive process as analogical transfer, involving drawing information from memories. Analogical transfer is implemented in Case-based reasoning (CBR) systems, so that the unseen problems are able to be solved by utilizing a set of previous cases which are stored in memory. Unlike the traditional machine learning, in the computational analogy methods, there is no need for a pre-existing trained model specific to the task ([Badra 2021](https://www.ijcai.org/Proceedings/2020/0222.pdf)). These methods depend entirely on a well-organized memory bank and the use of an effective similarity measure to operate. 

In this project, the CoAT method (Complexity-based Analogical Transfer) was used to conduct Case-Based Prediction. CoAT is based on the MeatCube algorithm which is created by Mr. Esteban Marquer. DIfferent classification and regression tasks have been tested on various dataset using this method, in order to observe if CoAT has different performances in different scenarios and with different similarity measures. A new computational cost metric was proposed, since the performance of CoAT is not comparable with the traditional neural networks models but have its own advantages (rapidity, low computational cost ...)
___________________________________________________________________________________________________________________________________________

## Variant Analysis on the Book of Ben Sira

*(School year 2022-2023 - Supervised by [F. Rey](https://ecritures.univ-lorraine.fr/membres/titulaires/rey-f) - IDMC, Université de Lorraine)*

**Group project**

As the best selling publication of all time and with this importance in various religion, the Bible exists in many differant variants. The sutdy of the diffusion of this variation, the way they were transcribe and translate give an interesting overview into the the dissemination of such ideas. This poject focused on three collection fo manuscripts from the book of Ben SIra, found in Qumrân, Massada and Cairo. The *Book of Ben Sira* or *[Book of Sirach](https://en.wikipedia.org/wiki/Book_of_Sirach)* is a wisdom book written around 180 BCE by Yeshua ben Eleazar ben Sira in ancient Hebrew. This book is usually not considered a part of the Hebrew Bible but are part of the canon of most christian churches with the notable exceptions of the protestant denominations. The goal of the project was to perform a statistical analysis of the transcription errors between the 9 manuscripts using the [Collatex](https://pypi.org/project/collatex/) library to detect the variants between the texts. This variants where then classified by type: deletion, addition, words/letters switch etc ..
___________________________________________________________________________________________________________________________________________

## Paperjam
*(Fall 2022 - Supervised by [M. Amblard](https://members.loria.fr/MAmblard/) and [M. Couceiro](https://members.loria.fr/mcouceiro/) - IDMC, Université de Lorraine)*

**Group project ([GitHub Link](https://github.com/PierreEpron/paperjam-lab) )**

Identifying scientific articles related to a specific feature is crucial for most researchers and students. The field of Natural Language Processing (NLP) has long been interested in this task. Different Information Extraction (IE) pipelines have been developed for this purpose. Most of them adopt a similar approach. They first extract mentions associated with specific entities such as tasks, materials, metrics, and methods. Then, they arrange them into coreference clusters. Lastly, they establish relationships between these clusters. This article aims to show some of the unresolved issues with that approach, by focusing on an already existing pipeline: SciREX. To achieve this, it was first necessary to set up their methodology, to which a few minor modifications were implemented.