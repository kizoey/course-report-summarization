# course-report-summarization
<p align="left">
  <img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=Python&logoColor=white"/></a>&nbsp
  <img src="https://img.shields.io/badge/GoogleColab-F9AB00?style=flat-square&logo=GoogleColab&logoColor=white"/></a>&nbsp 
</p>
<b><i>Course report summarization</i></b> is a project that uses pre-trained language models to generate summary of a lecture evaulation given in <a href=https://klue.kr/>KLUE</a>. We aim to provide useful and concise information to users more intuitively by giving an one-line summary for each lecture rather than reading the whole evaluations.<br>
<br>
To give extractive summary from a given report, we studied through various summarization models including BART, T5, PEGASUS and more. Among these models, we choose to conduct experiments with <b>BertSum</b>, <b>T5</b> and <b>BART</b>. BertSum is a simple variant of BERT, a pre-trained Transformer model, that is specifically used for extractive summarization. T5, text-to-text transfer transformer, is a model that reframes all NLP tasks into a unified text-to-text-format where the input and output are always text strings, in contrast to BERT-style models that can only output either a class label or a span of the input. BART is a denoising autoencoder for pretraining sequence-to-sequence models with BERT as its encoder and GPT as its decoder.


<h2> major Contributions </h2>

- Study of papers and models for extractive/abstractive summarization
- **Extractive summarization** using various models: BertSum, T5, BART
- Crawling course evaluation data from KLUE: https://klue.kr/
- Provision of one-line summary service to Korea university students

<h2> Directory </h2>

### _algorithms_
- **bertsum**: Bertsum 모델을 이용한 생성요약
- **ket5**: T5 모델을 이용한 생성요약
- **kobart**: KoBART 모델을 이용한 생성요약
- **crawling**: KLUE(고려대학교 강의평 사이트) 크롤링 코드
- **preprocessing**: 크롤링된 강의평 데이터 전처리 코드

<h2> Demo </h2>
Demo is now released with Flask !
