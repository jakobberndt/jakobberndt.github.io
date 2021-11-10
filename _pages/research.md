---
title: research
permalink: /research/
---

## publications

<a href="https://arxiv.org/abs/2005.00388" target="_blank">Will-They-Won't-They: A Very Large Dataset for Stance Detection on Twitter</a> (with Nigel Collier, Costanza Conforti, Chryssi Giannitsarou, Mohammad Taher Pilehvar, Flavio Toxvaerd)<br>
<em>Proceedings of the 58th Annual Meeting of the Association for Computational Linguistics</em>

<a href="https://www.aclweb.org/anthology/2020.acl-main.157/" target="_blank">[paper]</a> <!-- &nbsp; -->
<!-- <a href="https://arxiv.org/pdf/2005.00388.pdf" target="_blank">[slides]</a> -->

<details open>
<summary>Abstract</summary>
<p align="justify" style="font-size:90%">We present a new challenging stance detection dataset, called Will-They-Won't-They (WT-WT), which contains 51,284 tweets in English, making it by far the largest available dataset of the type. All the annotations are carried out by experts; therefore, the dataset constitutes a high-quality and reliable benchmark for future research in stance detection. Our experiments with a wide range of recent state-of-the-art stance detection systems show that the dataset poses a strong challenge to existing models in this domain.</p>
</details>

&nbsp;

<a href="https://www.aclweb.org/anthology/2020.findings-emnlp.365/" target="_blank">Stander: An Expert-Annotated Dataset for News Stance Detection and Evidence Retrieval</a> (with Nigel Collier, Costanza Conforti, Chryssi Giannitsarou, Mohammad Taher Pilehvar, Flavio Toxvaerd)<br>
<em>Findings of the Association for Computational Linguistics: EMNLP 2020</em>

<a href="https://www.aclweb.org/anthology/2020.findings-emnlp.365/" target="_blank">[paper]</a> <!-- &nbsp; -->
<!-- <a href="https://arxiv.org/pdf/2005.00388.pdf" target="_blank">[slides]</a> -->

<details open>
<summary>Abstract</summary>
<p align="justify" style="font-size:90%">We present a new challenging news dataset that targets both stance detection (SD) and fine-grained evidence retrieval (ER). With its 3,291 expert-annotated articles, the dataset constitutes a high-quality benchmark for future research in SD and multi-task learning.
We provide a detailed description of the corpus collection methodology and carry out an extensive analysis on the sources of disagreement between annotators, observing a correlation between their disagreement and the diffusion of uncertainty around a target in the real world.
Our experiments show that {the dataset} poses a strong challenge to recent state-of-the-art models. Notably, our dataset aligns with an existing Twitter SD dataset: their union thus addresses a key shortcoming of previous works, by providing the first dedicated resource to study multi-genre SD as well as the interplay of signals from social media and news sources in rumour verification.</p>
</details>

&nbsp;

<a href="https://www.aclweb.org/anthology/2021.wassa-1.19/" target="_blank">Synthetic Samples Improve Zero-Shot Cross-Target Generalization: A Study on Stance Detection in the Financial Domain</a> (with Nigel Collier, Costanza Conforti, Chryssi Giannitsarou, Mohammad Taher Pilehvar, Flavio Toxvaerd)<br>
<em>Proceedings of the Eleventh Workshop on Computational Approaches to Subjectivity, Sentiment and Social Media Analysis</em>

<a href="https://www.aclweb.org/anthology/2021.wassa-1.19/" target="_blank">[paper]</a> &nbsp;
<a href="https://drive.google.com/file/d/1WL9SvHAvv42qm8yNWMr-moc1mstPs_rw/view?usp=sharing" target="_blank">[poster]</a>

<details open>
<summary>Abstract</summary>
<p align="justify" style="font-size:90%">Cross-target generalization is a known problem in stance detection (SD), where systems tend to perform poorly when exposed to targets unseen during training. Given that data annotation is expensive and time-consuming, finding ways to leverage abundant unlabeled in-domain data can offer great benefits. In this paper, we apply a weakly supervised framework to enhance cross-target generalization through synthetically annotated data. We focus on Twitter SD and show experimentally that integrating synthetic data is helpful for cross-target generalization, leading to significant improvements in performance, with gains in F1 scores ranging from +3.4 to +5.1.</p>
</details>

&nbsp;

<a href="https://www.aclweb.org/anthology/2021.hackashop-1.1/" target="_blank">Adversarial Training for News Stance Detection: Leveraging Signals from a Multi-Genre Corpus</a> (with Nigel Collier, Costanza Conforti, Chryssi Giannitsarou, Marco Basaldella, Mohammad Taher Pilehvar, Flavio Toxvaerd)<br>
<em>Proceedings of the EACL Hackashop on News Media Content Analysis and Automated Report Generation</em>

<a href="https://www.aclweb.org/anthology/2021.hackashop-1.1/" target="_blank">[paper]</a> &nbsp;
<a href="https://drive.google.com/file/d/1yRprniY7ZhxB-LNCHTEg99-ympZzZyv1/view?usp=sharing" target="_blank">[poster]</a>

<details open>
<summary>Abstract</summary>
<p align="justify" style="font-size:90%">Cross-target generalization constitutes an important issue for news Stance Detection (SD). In this short paper, we investigate adversarial cross-genre SD, where knowledge from annotated user-generated data is leveraged to improve news SD on targets unseen during training. We implement a BERT-based adversarial network and show experimental performance improvements over a set of strong baselines. Given the abundance of user-generated data, which are considerably less expensive to retrieve and annotate than news articles, this constitutes a promising research direction.</p>
</details>

&nbsp;
<!--
<a href="" target="_blank">Incorporating Stock Market Signals for Twitter Stance Detection</a> (with Nigel Collier, Costanza Conforti, Chryssi Giannitsarou, Mohammad Taher Pilehvar, Flavio Toxvaerd)<br>
<em>Submitted</em>

<a href="" target="_blank">[paper]</a> &nbsp;
<a href="" target="_blank">[poster]</a>

<details open>
<summary>Abstract</summary>
<p align="justify" style="font-size:90%">Research in Stance Detection (SD) has so far focused on models which leverage purely textual input. In this short paper, we investigate multi-modal signals for SD in the financial domain: we propose a robust multi-task neural architecture that integrates textual input with high-frequency intra-day stock market data. Moreover, we extend \textsc{wt--wt}, an existing SD dataset of tweets discussing M\&A operations, with the relevant financial signal, and demonstrate experimentally that our SD system benefits from such multi-modal signals.</p>
</details>

&nbsp;
-->

## working papers

<a href="" target="_blank">Learning from Unreliable Sources</a>

<!-- <a href="" target="_blank">[paper]</a> --> 
[paper]

<details open>
<summary>Abstract</summary>
<p align="justify" style="font-size:90%">This paper studies how uncertainty about the reliability of information sources affects the equilibrium outcome in a model of rational social learning. Agents are located on nodes of an exogenously given network and are endowed with noisy private signals about an underlying state of the world. They face uncertainty about the signal distribution of their own signals and the signals of their neighbors and need to decide which sources to rely on when forming their opinions.
I show that agents exhibit a rational confirmation bias, relying predominantly on neighbors who observe similar signals. In addition, this type of uncertainty can help explain persistent disagreement. Agents may cut links to neighbors and discard their information in the formation of their opinion. This allows endogenous subgraphs to build and neighbors to hold different opinions indefinitely.</p>
</details>

<!--
&nbsp;

<a href="" target="_blank">Information Manipulation and Propagation in Social Networks</a>

<a href="" target="_blank">[paper]</a>

<details open>
<summary>Abstract</summary>
<p align="justify" style="font-size:90%">This paper presents a model of a manipulator trying to influence the collective decision of a population of agents. The novelty is to capture Bayesian persuasion followed by information diffusion in a network. Unbiased agents want the collective decision to match an unknown state of the world, while biased agents share the preferences of the manipulator. The manipulator controls the distribution of a signal. Agents communicate at a cheap talk stage. The manipulator faces a trade-off between a higher degree manipulation and higher information diffusion. The optimal degree of manipulation is inversely related to the density of biased agents. </p>
</details>
-->

&nbsp;

## work in progress

Information Manipulation and Propagation in Social Networks
