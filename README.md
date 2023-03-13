## Automatic Classification of Japanese Formality

In this paper we propose a novel approach to automatically classify the level of formality in Japanese text, using three categories (formal, polite, and informal). We introduce new datasets that combine manually annotated sentences from existing resources, and a great number of formal sentences scrapped from the Japanese Congress. Based on our data, we propose a Transformer-based classification model for Japanese formality which obtains stateof-the-art results in benchmark datasets, as well as on our newly-introduced corpus, showing the effectiveness of our proposed approach.

Read the paper [here](https://www.anlp.jp/proceedings/annual_meeting/2023/pdf_dir/D2-5.pdf).

## Released Corpora

In this paper, we released 3 corpora specifically designed for Japanese formality, namely, DAILY, KoKai, and an reannotated dataset ReCoCoAMT_JA. All the corpora are annotated into 3 classes, 0-informal (regular form, 常体), 1-polite (polite form, 丁寧語), and 2-formal (respectful form 尊敬語 and humble form 謙譲語). 

- **DAILY**: a total of 200 examples collected from Japanese news, novels, textbooks, business letters, academic documents, etc. The dataset carries well-balanced three classes with 65, 67, and 68 sentences for the informal, polite, and formal classes, respectively. 

- **KoKai**: examples are collected from meeting minutes of the House of Representatives and the House of Councilors of Japan from 1947 to 2022. We randomly selected and labelled 1,360 examples of the entire 64,630 sentences we scrapped with 137 informal examples, 760 polite examples, and 463 formal examples.

- **ReCoCoAMT_JA**: the original dataset is released [here](https://github.com/amazon-science/contrastive-controlled-mt), where the released Japanese dataset is binary classified and contains meaningless sentences, broken/incomplete pieces, and miss label problem. We reannotate the dataset into 3 classes and get 520 informal sentences, 464 polite sentences and 12 formal sentences, with a total of 1,000 examples.  
