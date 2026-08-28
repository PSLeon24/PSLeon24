<div align="center">

![](https://github.com/PSLeon24/PSLeon24/assets/59058869/16f7a08f-ec50-4058-aa1d-478d4514ede6)

# Yeongmin Ko &nbsp;·&nbsp; 고영민

**AI Engineer, [DeepAuto.ai](https://deepauto.ai)**

Computer Vision &nbsp;·&nbsp; Engineering Diagram Digitalization &nbsp;·&nbsp; Adversarial Attack (Anti-Deepfake &amp; Robustness) &nbsp;·&nbsp; Medical Imaging &nbsp;·&nbsp; Diffusion Models

<a href="mailto:yeongminko@deepauto.ai">Email</a> &nbsp;·&nbsp;
<a href="https://github.com/PSLeon24">GitHub</a> &nbsp;·&nbsp;
<a href="https://scholar.google.com/citations?hl=en&user=c-j-mAsAAAAJ">Google Scholar</a> &nbsp;·&nbsp;
<a href="https://psleon.tistory.com">Blog</a> &nbsp;·&nbsp;
Project Page <sub>(TBA)</sub>

</div>

<br>

I work on vision problems whose output has to be usable by someone: engineering
drawings a machine can query, faces that resist deepfake synthesis, and lifting
form corrected while the lift is happening.

<br>

## Research

**Engineering diagram digitalization.**
A piping and instrumentation diagram encodes a complete process topology — equipment,
instruments, and the lines that connect them — but stores it as drawing primitives
rather than as structure, so no downstream system can query it. I work on recovering
that structure: parsing a drawing into nodes and directed edges, where each pipe run
is an edge whose identity must persist across the reducers, tag breaks, and line
crossings that interrupt it. The goal is a diagram that can be searched, validated,
and simulated rather than read by hand.

**Paired-organ medical imaging.**
Bilateral models improve population accuracy by sharing evidence between an organ and
its fellow. The same sharing degrades the asymmetric patients whose two organs
disagree — precisely those for whom an accurate reading matters most. The question is
when aggregating correlated observations helps a population while harming an
individual, and what a model should do about it.

**Adversarial attacks on diffusion models.**
Protecting faces from deepfake synthesis by making them unusable as generation inputs,
rather than by detecting synthetic output after the fact. AEGIS, under review at
*Pattern Recognition*, is the most recent work in this line; an earlier paper in the
same direction received a paper award at IEIE 2024.

**Low-light object detection.**
Detection on industrial yard footage where the imaging condition itself is the
bottleneck, addressed through low-light data augmentation rather than by changing the
detector.

**Real-time pose estimation.**
Form correction for the three powerlifting movements, designed to give feedback during
the lift rather than from a recording afterwards. Published in *IEEE Access* and
[cited 28 times](https://scholar.google.com/citations?view_op=view_citation&hl=en&user=c-j-mAsAAAAJ&citation_for_view=c-j-mAsAAAAJ:u5HHmVD_uO8C).

<br>

## Education

<table>
<tr><td width="128" valign="top"><b>M.S.</b><br><sub>Feb 2026</sub></td>
<td><b>Information Convergence Engineering</b>, Artificial Intelligence major<br>
Pusan National University<br>
<sub>Visual Intelligence and Perception Laboratory &nbsp;·&nbsp; advised by Prof. Jinsun Park</sub></td></tr>

<tr><td valign="top"><b>B.S.</b><br><sub>Aug 2024</sub></td>
<td><b>Computer Engineering</b><br>
Dongguk University</td></tr>
</table>

<br>

## Publications

#### International Journal

<table>
<tr><td width="132" valign="top"><b>Under review</b></td>
<td><b>AEGIS</b><br>
<b>Ko, Y.</b> et al.<br>
<i>Pattern Recognition</i> (Elsevier). &nbsp;<sub>project page: TBA</sub></td></tr>

<tr><td valign="top"><b>2024</b></td>
<td>Real-Time AI Posture Correction for Powerlifting Exercises Using YOLOv5 and MediaPipe<br>
<b>Ko, Y.-M.</b>, Nasridinov, A., Park, S.-H.<br>
<i>IEEE Access</i>, 2024.
&nbsp;<b><a href="https://scholar.google.com/citations?view_op=view_citation&hl=en&user=c-j-mAsAAAAJ&citation_for_view=c-j-mAsAAAAJ:u5HHmVD_uO8C">Cited by 28</a></b>
&nbsp;<a href="https://ieeexplore.ieee.org/abstract/document/10798440">paper</a>
&nbsp;<a href="https://github.com/PSLeon24/AI_Exercise_Pose_Feedback">code</a></td></tr>
</table>

#### Domestic Journal

<table>
<tr><td width="132" valign="top"><b>2025</b></td>
<td>Low-Light Data Augmentation-based Object Detection for Nighttime Smart Yard Safety Management<br>
<b>Ko, Y.</b>, Park, J.<br>
<i>Journal of the Institute of Electronics and Information Engineers (IEIE)</i>, 2025.<br>
<b>KCI Excellence-Accredited</b> <sub>— the highest tier of the Korea Citation Index</sub></td></tr>
</table>

#### Domestic Conference

<table>
<tr><td width="132" valign="top"><b>2025</b></td>
<td>Stable Diffusion-based Deepfake Creation Disruption Using Adversarial Attacks<br>
<b>Ko, Y.</b>, Park, J.<br>
<i>37th Workshop on Image Processing and Image Understanding (IPIU)</i>, 2025.</td></tr>

<tr><td valign="top"><b>2025</b></td>
<td>Approximation of Omnidirectional Camera Distortion Models for COLMAP Using a Virtual Checkerboard<br>
Park, H., Park, J., <b>Ko, Y.</b>, Park, J.<br>
<i>Summer Annual Conference of the Institute of Electronics and Information Engineers (IEIE)</i>, 2025.</td></tr>

<tr><td valign="top"><b>2024</b> &nbsp;🏅</td>
<td>Disrupting Deepfake Generation with KL Divergence-based Adversarial Attacks<br>
<b>Ko, Y.</b>, Park, H., Park, J.<br>
<i>Autumn Annual Conference of the Institute of Electronics and Information Engineers (IEIE)</i>, 2024, pp. 1178–1182.
&nbsp;<b>Paper Award</b></td></tr>
</table>

<br>

## Work in Progress

<sub>Not yet peer reviewed. No results are reported here.</sub>

**Graph digitalization of P&ID drawings.** Recovering the process graph a piping and
instrumentation diagram encodes — what connects to what, and in which direction — by
treating each pipe run as an edge whose identity must hold across the reducers, tag
breaks, and crossings that interrupt it, rather than as a symbol-detection problem.

**Binocular asymmetry in paired-organ grading.** Measuring what bilateral fusion costs
the patients whose two organs disagree, identifying the mechanism behind that cost, and
testing whether a correction recovers it without giving up the population-level gain.
Evaluated on retinal grading, knee osteoarthritis, and mammography under a single
protocol, so the finding is not a property of one dataset.

<br>

## Code

**[Anti-StableDiffusion](https://github.com/PSLeon24/Anti-StableDiffusion)** — adversarial
method that disrupts deepfake generation through the Stable Diffusion img2img pipeline.

**[AI Exercise Pose Feedback](https://github.com/PSLeon24/AI_Exercise_Pose_Feedback)** — real-time
powerlifting form correction with YOLOv5 and MediaPipe; the system behind the *IEEE Access* paper.

**[Paper Implementations](https://github.com/PSLeon24/Paper-Implementation-with-PyTorch)** — models
from papers, reimplemented in PyTorch.

<br>

## Mathematical Foundations

Notes and worked exercises from studying the mathematics the models rest on.

| Repository | Contents |
| --- | --- |
| **[Linear Algebra](https://github.com/PSLeon24/Linear_Algebra)** | Notes and exercises from a linear algebra course |
| **[Mathematical Statistics](https://github.com/PSLeon24/Mathematical_Statistics)** | A short course in mathematical statistics |
| **[Calculus](https://github.com/PSLeon24/Calculus)** | A short course in calculus for data science |
| **[Artificial Intelligence](https://github.com/PSLeon24/Artificial_Intelligence)** | Coursework and practice across AI methods |
| **[PyTorch](https://github.com/PSLeon24/PyTorch_Tutorial)** | Working through PyTorch from the fundamentals |

<br>

## Tools

`Python` &nbsp;`PyTorch` &nbsp;`NumPy` &nbsp;`pandas` &nbsp;`scikit-learn` &nbsp;`CUDA` &nbsp;`Linux` &nbsp;`Docker` &nbsp;`AWS`

<details>
<summary>Web and mobile, from earlier work</summary>

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

<br>

<div align="center">
  <img src="https://github-readme-activity-graph.vercel.app/graph?username=PSLeon24&custom_title=&bg_color=0d1117&color=8b949e&line=58a6ff&point=58a6ff&area_color=1f6feb&title_color=8b949e&area=true&hide_border=true&radius=4" alt="Contribution activity" width="100%">
</div>
