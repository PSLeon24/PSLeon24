<div align="center">

![](https://github.com/PSLeon24/PSLeon24/assets/59058869/16f7a08f-ec50-4058-aa1d-478d4514ede6)

# Yeongmin Ko &nbsp;·&nbsp; 고영민

**AI Engineer, [DeepAuto.ai](https://deepauto.ai)**

Computer Vision &nbsp;·&nbsp; Adversarial Attack (Anti-Deepfake &amp; Robustness) &nbsp;·&nbsp; Medical Imaging &nbsp;·&nbsp; Diffusion Models

<a href="mailto:yeongminko@deepauto.ai">Email</a> &nbsp;·&nbsp;
<a href="https://github.com/PSLeon24">GitHub</a> &nbsp;·&nbsp;
<a href="https://scholar.google.com/citations?hl=en&user=c-j-mAsAAAAJ">Google Scholar</a> &nbsp;·&nbsp;
<a href="https://psleon.tistory.com">Blog</a> &nbsp;·&nbsp;
Project Page <sub>(TBA)</sub>

</div>

<br>

I work on the cases a model gets wrong when its average looks right.

My main research is **turning engineering drawings into graphs**. A piping and
instrumentation diagram already contains a complete process topology — equipment,
instruments, and the lines that connect them — but it holds that topology as
draughtsman's marks rather than as structure, so nothing downstream can query it.
I work on recovering it: reading a drawing as nodes and directed edges, where a pipe
is the edge and its identity has to survive every reducer, tag break and line
crossing along its route. The end state is a diagram that can be searched, checked
and simulated instead of read by eye.

Second, **paired-organ medical imaging**. Bilateral models raise population accuracy by
borrowing evidence between an organ and its fellow, and that same borrowing
systematically damages the asymmetric patients whose two organs disagree — the
patients for whom a correct reading matters most. The question is when aggregating
correlated observations helps a population and hurts an individual, and what a model
should do about it.

Third, **adversarial attacks against diffusion models**, protecting faces from being used
as material for deepfake synthesis by making them poor inputs to generation rather
than by detecting the output after the fact. AEGIS, currently under review at
*Pattern Recognition*, is the latest of that line.

Earlier work covers **detection under degraded imaging conditions** and real-time pose
estimation. It appears in IEEE Access, in the journal and conferences of the Institute
of Electronics and Information Engineers (IEIE), and at the Workshop on Image Processing
and Image Understanding (IPIU), and was recognised with a paper award at IEIE 2024.

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

<sub>**IJ** International Journal &nbsp;·&nbsp; **DJ** Domestic Journal (KCI) &nbsp;·&nbsp; **DC** Domestic Conference</sub>

#### International Journal

<table>
<tr><td width="128" valign="top"><b>IJ</b> &nbsp;Under review</td>
<td><b>AEGIS</b> &nbsp;|&nbsp; <b>Ko, Y.</b> et al.<br>
<i>Pattern Recognition</i> (Elsevier) — under review.
&nbsp;<sub>project page: TBA</sub></td></tr>

<tr><td valign="top"><b>IJ</b> &nbsp;2024</td>
<td><b>Ko, Y.-M.</b>, Nasridinov, A., Park, S.-H.<br>
Real-Time AI Posture Correction for Powerlifting Exercises Using YOLOv5 and MediaPipe.<br>
<i>IEEE Access</i>, 2024. &nbsp;<b><a href="https://scholar.google.com/citations?view_op=view_citation&hl=en&user=c-j-mAsAAAAJ&citation_for_view=c-j-mAsAAAAJ:u5HHmVD_uO8C">Cited by 28</a></b>
&nbsp;<a href="https://ieeexplore.ieee.org/abstract/document/10798440">paper</a>
&nbsp;<a href="https://github.com/PSLeon24/AI_Exercise_Pose_Feedback">code</a></td></tr>
</table>

#### Domestic Journal (KCI)

<table>
<tr><td width="128" valign="top"><b>DJ</b> &nbsp;2025</td>
<td><b>Ko, Y.</b>, Park, J.<br>
Low-Light Data Augmentation-based Object Detection for Nighttime Smart Yard Safety Management.<br>
<i>Journal of the Institute of Electronics and Information Engineers</i>, 2025.</td></tr>
</table>

#### Domestic Conference

<table>
<tr><td width="128" valign="top"><b>DC</b> &nbsp;2025</td>
<td><b>Ko, Y.</b>, Park, J.<br>
Stable Diffusion-based Deepfake Creation Disruption Using Adversarial Attacks.<br>
<i>37th Workshop on Image Processing and Image Understanding (IPIU)</i>, 2025.</td></tr>

<tr><td valign="top"><b>DC</b> &nbsp;2025</td>
<td>Park, H., Park, J., <b>Ko, Y.</b>, Park, J.<br>
Approximation of Omnidirectional Camera Distortion Models for COLMAP Using a Virtual Checkerboard.<br>
<i>Summer Annual Conference of the Institute of Electronics and Information Engineers (IEIE)</i>, 2025.</td></tr>

<tr><td valign="top"><b>DC</b> &nbsp;2024 &nbsp;🏅</td>
<td><b>Ko, Y.</b>, Park, H., Park, J.<br>
Disrupting Deepfake Generation with KL Divergence-based Adversarial Attacks.<br>
<i>Autumn Annual Conference of the Institute of Electronics and Information Engineers (IEIE)</i>, 2024, pp. 1178–1182. &nbsp;<b>Paper Award</b></td></tr>
</table>

<br>

## Ongoing Research

Work in progress. Nothing here is peer-reviewed yet, and no results are quoted.

**Graph digitalization of P&ID drawings.** Extracting the process graph a piping and
instrumentation diagram encodes — what connects to what, and in which direction —
by treating each pipe run as an edge whose identity must hold across the reducers,
tag breaks and crossings that interrupt it, rather than treating the drawing as a
symbol-detection problem.

**Binocular asymmetry in paired-organ grading.** Measuring what bilateral fusion costs
the patients whose two organs disagree, deriving where the cost comes from, and testing
whether a correction recovers it without giving up the population gain. Run across
retinal grading, knee osteoarthritis and mammography under one protocol, so the
finding is not a property of one dataset.

<br>

## Selected Projects

**AEGIS** — current first-author work, under review at *Pattern Recognition*. Project page TBA.

**[Anti-StableDiffusion](https://github.com/PSLeon24/Anti-StableDiffusion)** — an adversarial method
that disrupts deepfake generation through the Stable Diffusion img2img pipeline.

**[AI Exercise Pose Feedback](https://github.com/PSLeon24/AI_Exercise_Pose_Feedback)** — real-time
powerlifting form correction with YOLOv5 and MediaPipe; the system behind the IEEE Access paper,
which has been [cited 28 times](https://scholar.google.com/citations?view_op=view_citation&hl=en&user=c-j-mAsAAAAJ&citation_for_view=c-j-mAsAAAAJ:u5HHmVD_uO8C).

<br>

## Mathematical & AI Foundations

Worked notebooks kept while studying the mathematics the models rest on. Written to be
re-read rather than to be finished.

| Repository | Contents |
| --- | --- |
| **[Linear Algebra](https://github.com/PSLeon24/Linear_Algebra)** | Written and practised while studying linear algebra |
| **[Mathematical Statistics](https://github.com/PSLeon24/Mathematical_Statistics)** | A brief course in mathematical statistics |
| **[Calculus](https://github.com/PSLeon24/Calculus)** | A brief course in calculus for data science |
| **[Artificial Intelligence](https://github.com/PSLeon24/Artificial_Intelligence)** | Coursework and practice across AI methods |
| **[PyTorch Tutorial](https://github.com/PSLeon24/PyTorch_Tutorial)** | Working through PyTorch from the ground up |
| **[Paper Implementations](https://github.com/PSLeon24/Paper-Implementation-with-PyTorch)** | Models from papers, reimplemented in PyTorch |

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
