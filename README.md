![](https://github.com/PSLeon24/PSLeon24/assets/59058869/16f7a08f-ec50-4058-aa1d-478d4514ede6)

# Yeongmin Ko

**AI Engineer, [DeepAuto.ai](https://deepauto.ai)**

Agentic AI &nbsp;·&nbsp; Generative Models &nbsp;·&nbsp; Computer Vision

<a href="mailto:yeongminko@deepauto.ai">Email</a> &nbsp;·&nbsp;
<a href="https://github.com/PSLeon24">GitHub</a> &nbsp;·&nbsp;
<a href="https://scholar.google.com/citations?hl=en&user=c-j-mAsAAAAJ">Google Scholar</a> &nbsp;·&nbsp;
<a href="https://psleon.tistory.com">Blog</a>
<br>

I focus on agentic AI and computer vision tasks with practical real-world applications: developing agentic AI systems that interpret Piping and instrumentation diagrams (P&IDs) and transform them into structured engineering data, designing adversarial perturbations to disrupt deepfake synthesis, and building real-time human posture feedback systems, such as powerlifting form correction.
<br>

## Research

**Engineering Diagram Digitization.** (Ongoing research; findings have not yet undergone peer review.)
P&IDs encode process topology through equipment, instruments, and their interconnections, but PDF representations often lack explicit machine-readable structure. I work on reconstructing this topology as an enriched knowledge graph, tracing pipe runs through reducers, T-junctions, and off-page connectors while tracking line continuity and identifying line-number changes. The goal is to automatically generate structured Line Listings and Instrument Listings from raw P&ID PDFs, including FROM/TO connectivity, line identifiers, operating pressure, and other engineering attributes.

**Bilateral Asymmetry in Medical Imaging.** (Ongoing research; findings have not yet undergone peer review.)
Recent models that consider information from paired organs can improve overall predictive performance, but this benefit may not extend to patients with substantial left–right asymmetry. I investigate whether and when bilateral fusion improves population-level performance at the expense of predictions for asymmetric cases, and whether asymmetry-aware approaches can mitigate this trade-off without sacrificing overall accuracy.

**Adversarial Protection against Deepfakes.**
I proposed an adversarial protection method that disrupts the unauthorized use of facial images in diffusion-based deepfake generation by applying perturbations to the original images before synthesis, rather than detecting manipulated content afterward. My latest method, AEGIS, is presented in a manuscript currently under review at *Pattern Recognition*. Earlier research in this direction received a Paper Award at the 2024 IEIE Autumn Annual Conference.

**Low-light Object Detection.**
I proposed an approach to improve object detection in nighttime industrial environments, where poor illumination limits detection reliability. The approach combines diffusion-based data augmentation during training with low-light image enhancement at inference time, without modifying the underlying detector architecture.

**Real-time Human Pose Estimation and Posture Correction.**
I proposed a real-time posture correction system using human pose estimation to assess exercise form and provide corrective feedback during the three major powerlifting movements: squat, bench press, and deadlift. Unlike post-workout video analysis, the system provides immediate feedback during exercise. This work was published in *IEEE Access* and has been [cited 33 times](https://scholar.google.com/citations?view_op=view_citation&hl=en&user=c-j-mAsAAAAJ&citation_for_view=c-j-mAsAAAAJ:u5HHmVD_uO8C).

<br>

## Education

<table>
<tr><td width="128" valign="top"><b>M.S.</b><br><sub>Feb 2026</sub></td>
<td><b>Information Convergence Engineering</b> (Artificial Intelligence)<br>
Pusan National University<br>
<sub><b>GPA: 4.50/4.50</b> &nbsp;·&nbsp; Graduated one semester early</sub><br>
<sub>Visual Intelligence and Perception Laboratory &nbsp;·&nbsp; Advisor: Prof. Jinsun Park</sub></td></tr>

<tr><td valign="top"><b>B.S.</b><br><sub>Aug 2024</sub></td>
<td><b>Computer Engineering</b><br>
Dongguk University<br>
<sub><b>GPA: 4.33/4.50</b> &nbsp;·&nbsp; Graduated one semester early</sub><br>
<sub>Data Analytics Laboratory &nbsp;·&nbsp; Advisor: Prof. So-Hyun Park</sub></td></tr>
</table>

<br>


## Publications

#### International Journal

<table>
<tr><td width="132" valign="top"><b>Under review</b></td>
<td><b>Dataset for Automatic Piano Performance Evaluation with Human Ratings</b><br>
Chuluunsaikhan, T., <b>Ko, Y.-M.</b>, Park, S.-H.<br>
<i>Scientific Data</i></td></tr>

<tr><td width="132" valign="top"><b>Under review</b></td>
<td><b>AEGIS</b><br>
<b>Ko, Y.-M.</b>, et al.<br>
<i>Pattern Recognition</i></td></tr>

<tr><td valign="top"><b>2024</b></td>
<td><b>Real-Time AI Posture Correction for Powerlifting Exercises Using YOLOv5 and MediaPipe</b><br>
<b>Ko, Y.-M.</b>, Nasridinov, A., Park, S.-H.<br>
<i>IEEE Access</i>, 2024.
&nbsp;<b><a href="https://scholar.google.com/citations?view_op=view_citation&hl=en&user=c-j-mAsAAAAJ&citation_for_view=c-j-mAsAAAAJ:u5HHmVD_uO8C">Cited by 33</a></b>
&nbsp;<a href="https://ieeexplore.ieee.org/abstract/document/10798440">paper</a>
&nbsp;<a href="https://github.com/PSLeon24/AI_Exercise_Pose_Feedback">code</a></td></tr>
</table>

#### Domestic Journal

<table>
<tr><td width="132" valign="top"><b>2025</b></td>
<td><b>Low-Light Data Augmentation-based Object Detection for Nighttime Smart Yard Safety Management</b><br>
<b>Ko, Y.-M.</b>, Park, J.-S.<br>
<i>Journal of the Institute of Electronics and Information Engineers (IEIE)</i>, 2025.
&nbsp;<a href="https://github.com/PSLeon24/Data-Augmentation-for-Robust-Object-Detection-in-Low-Light-Conditions">code</a><br>
<b>KCI Excellent Accredited Journal</b> <sub>— the highest tier of the Korea Citation Index</sub></td></tr>
</table>

#### Domestic Conference

<table>
<tr><td width="132" valign="top"><b>2025</b></td>
<td><b>Stable Diffusion-based Deepfake Creation Disruption Using Adversarial Attacks</b><br>
<b>Ko, Y.-M.</b>, Park, J.-S.<br>
<i>37th Workshop on Image Processing and Image Understanding (IPIU)</i>, 2025.
&nbsp;<a href="https://github.com/PSLeon24/Anti-StableDiffusion">code</a></td></tr>

<tr><td valign="top"><b>2025</b></td>
<td><b>Approximation of Omnidirectional Camera Distortion Models for COLMAP Using a Virtual Checkerboard</b><br>
Park, H.-S., Park, J.-H., <b>Ko, Y.-M.</b>, Park, J.-S.<br>
<i>Summer Annual Conference of the Institute of Electronics and Information Engineers (IEIE)</i>, 2025.</td></tr>

<tr><td valign="top"><b>2024</b> &nbsp;🏅</td>
<td><b>Disrupting Deepfake Generation with KL Divergence-based Adversarial Attacks</b><br>
<b>Ko, Y.-M.</b>, Park, H.-S., Park, J.-S.<br>
<i>Autumn Annual Conference of the Institute of Electronics and Information Engineers (IEIE)</i>, 2024, pp. 1178–1182.
&nbsp;<b>Paper Award</b></td></tr>
</table>

<br>

## Code

**[Low-Light Object Detection](https://github.com/PSLeon24/Data-Augmentation-for-Robust-Object-Detection-in-Low-Light-Conditions)** — framework for object
detection under the low-light and nighttime conditions of smart-yard environments; the
system behind the IEIE journal paper.

**[Anti-StableDiffusion](https://github.com/PSLeon24/Anti-StableDiffusion)** — adversarial
method that disrupts deepfake generation through the Stable Diffusion img2img pipeline;
the system behind the IPIU 2025 paper.

**[AI Exercise Pose Feedback](https://github.com/PSLeon24/AI_Exercise_Pose_Feedback)** — real-time
powerlifting form correction with YOLOv5 and MediaPipe; the system behind the *IEEE Access* paper.

**[Paper Implementations](https://github.com/PSLeon24/Paper-Implementation-with-PyTorch)** — models
from papers, reimplemented in PyTorch.

<br>

## AI Foundations

Study notes, mathematical foundations, and hands-on implementations of core AI methods.

| Repository | Contents |
| --- | --- |
| **[Linear Algebra](https://github.com/PSLeon24/Linear_Algebra)** | Notes and exercises from a linear algebra course |
| **[Mathematical Statistics](https://github.com/PSLeon24/Mathematical_Statistics)** | A short course in mathematical statistics |
| **[Calculus](https://github.com/PSLeon24/Calculus)** | A short course in calculus for data science |
| **[Artificial Intelligence](https://github.com/PSLeon24/Artificial_Intelligence)** | Coursework and practice across AI methods |
| **[PyTorch](https://github.com/PSLeon24/PyTorch_Tutorial)** | Working through PyTorch from the fundamentals |
| **[Multiple View Geometry](https://github.com/PSLeon24/MultipleView_Geometry_in_Computer_Vision)** | Multiple view geometry for computer vision |
| **[Generative Image Models](https://github.com/PSLeon24/Generative_Image_Models)** | Generative image models implemented from scratch |
| **[Paper Reading (CV)](https://github.com/PSLeon24/Reading-Paper-for-CV)** | Papers read while studying computer vision during the M.S. |

<br>

## Tools

`Python` &nbsp;`PyTorch` &nbsp;`NumPy` &nbsp;`pandas` &nbsp;`scikit-learn` &nbsp;`CUDA` &nbsp;`Linux` &nbsp;`Docker` &nbsp;`AWS`

<details>
<summary>Earlier Web & Mobile Projects</summary>

<br>

`Java` `Spring Boot` `Django` `Node.js` `Express` `React` `JavaScript` `MySQL` `SQL Server` `Firebase` `Android`

</details>

<details>
<summary>Earlier projects and coursework</summary>

<br>

| Project | Description | Date |
| --- | --- | --- |
| [Piano Keyboard Detection](https://github.com/PSLeon24/Piano_Keyboard_Detection) | Keyboard detector with YOLOv5 and SSD-MobileNet | 2023.08 |
| [CEM Community](https://github.com/PSLeon24/CEM_Community) | Computer Engineering major community site | 2023.10–12 |
| [MinFlix](https://github.com/PSLeon24/MinFlix) | Movie review web service in React | 2024.01 |
| [Israeli–Palestinian Data Analysis](https://github.com/PSLeon24/Israeli-Palestinian_Data_Analysis_Project) | Fatalities data analysis · [Kaggle](https://www.kaggle.com/code/psleon8245/middle-east-war-data-analysis-project/notebook) | 2023.10–12 |
| [Stack Overflow Developer Survey Analysis](https://github.com/PSLeon24/Stack_Overflow_Developer_Survey_Data_Analysis) | 2023 Developer Survey analysis | 2023.11–12 |
| [EDA on Student Study Performance](https://github.com/PSLeon24/Artificial_Intelligence/tree/main/Mid-Term%20Project) | Coursework EDA · [Kaggle](https://www.kaggle.com/code/psleon8245/eda-on-student-study-performance) | 2024.04 |
| [Today, Diary](https://github.com/PSLeon24/Today-Diary) | Android diary app | 2022.11–12 |
| [AnimeFaceAI](https://github.com/PSLeon24/animefaceai) | Lookalike anime character finder · [demo](https://animefaceai.netlify.app/) | 2020.07–08 |

</details>

<details>
<summary>Security disclosures reported in the press</summary>

<br>

- XSS vulnerabilities in Naver Blog and a middle-school bulletin board — [DailySecu](https://www.dailysecu.com/news/articleView.html?idxno=5998)
- Hyperlink-handling issues in KakaoTalk and KakaoStory — [DailySecu](https://www.dailysecu.com/news/articleView.html?idxno=6412)

</details>

