<!--
  Visual palette: indigo 0E1222 · gold D9B54E · teal 86CAD6 · text E6EDF3.
  Derived from assets/banner.jpg and used throughout the local artwork and badges.
-->

<div align="center">
  <img src="assets/banner.jpg" alt="An angel and a young man beside a river under a swirling, starry sky" width="100%" />
</div>

<br />

<p align="center">
  <img src="assets/portrait.png" alt="Portrait of Philopateer Reda" width="124" />
</p>

<h1 align="center">Philopateer Reda</h1>

<p align="center">
  <img src="https://img.shields.io/badge/Focus-Deep%20Learning%20%26%20Machine%20Learning-D9B54E?style=flat-square&labelColor=0E1222" alt="Focus: Deep Learning and Machine Learning" />
  <img src="https://img.shields.io/badge/Also-Applied%20NLP-86CAD6?style=flat-square&labelColor=0E1222" alt="Also: Applied NLP" />
</p>

<p align="center">
  <sub>Electronics &amp; Telecommunication Engineering student · Python</sub><br />
  <a href="https://www.linkedin.com/in/philopateer-reda-054881202/">LinkedIn</a>
  &nbsp;·&nbsp;
  <a href="mailto:filopateerredakamel2004@gmail.com">Email</a>
</p>

<div align="center">
  <img src="assets/divider.png" alt="" width="100%" height="4" />
</div>

<h2 align="center">About</h2>

<p>
I build machine-learning systems and the evaluation around them. My recent work covers credit-default prediction, churn modeling, and applied NLP, with an emphasis on leakage control, calibration, and reproducible experiments. I am now going deeper into neural networks and deep learning through hands-on PyTorch work.
</p>

<h2 align="center">Selected ML Work</h2>

<p align="center"><sub>Recent GCI 2026 projects in tabular modeling, validation, and decision-focused evaluation.</sub></p>

<table>
  <thead>
    <tr>
      <th align="left" colspan="2">01 &nbsp;·&nbsp; <a href="https://github.com/philopateerreda/GCI-ML-Competition">GCI-ML-Competition</a> &nbsp;<sub>Credit-Default Prediction</sub></th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td width="30%" valign="top">
        <img src="https://img.shields.io/badge/GCI%202026-Tabular%20ML%20%26%20Validation-D9B54E?style=flat-square&labelColor=0E1222" alt="GCI 2026: Tabular ML and Validation" /><br /><br />
        <b>Stack</b><br />
        <code>Python</code> <code>PyTorch</code> <code>scikit-learn</code><br />
        <code>LightGBM</code> <code>XGBoost</code> <code>CatBoost</code>
      </td>
      <td valign="top">
        <em>A leakage-safe pipeline for predicting loan default, built around trustworthy out-of-fold evaluation.</em>
        <ul>
          <li><b>Leakage control:</b> fold-local KNN target statistics and target encoding with self-exclusion, fingerprinted caches, and a label-permutation canary.</li>
          <li><b>Model selection:</b> nested-CV blending with a corrected standard-error gate; a tabular MLP sits alongside gradient-boosted trees.</li>
          <li><b>Experiment record:</b> failed tracks and leakage post-mortems remain documented instead of being hidden.</li>
        </ul>
        <b>Best public ROC-AUC: 0.76794.</b><br />
        <sub>Local cross-validation drives selection because the public leaderboard differences are smaller than their noise.</sub><br /><br />
        <a href="https://github.com/philopateerreda/GCI-ML-Competition"><b>View repository →</b></a>
      </td>
    </tr>
  </tbody>
</table>

<table>
  <thead>
    <tr>
      <th align="left" colspan="2">02 &nbsp;·&nbsp; <a href="https://github.com/philopateerreda/GCI-Final-Assignment">GCI-Final-Assignment</a> &nbsp;<sub>Churn Prediction &amp; Retention Targeting</sub></th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td width="30%" valign="top">
        <img src="https://img.shields.io/badge/GCI%202026-Calibration%20%26%20Decisioning-D9B54E?style=flat-square&labelColor=0E1222" alt="GCI 2026: Calibration and Decisioning" /><br /><br />
        <b>Stack</b><br />
        <code>Python</code> <code>LightGBM</code> <code>scikit-learn</code><br />
        <code>pandas</code> <code>Jupyter</code> <code>Matplotlib</code>
      </td>
      <td valign="top">
        <em>A calibrated churn-risk model paired with a value-aware retention policy and an explicit audit trail.</em>
        <ul>
          <li><b>Model:</b> sigmoid-calibrated LightGBM with frozen train, validation, calibration, and test partitions.</li>
          <li><b>Evaluation:</b> test ROC-AUC <b>0.6978</b>, with a bootstrap interval of <b>[0.6899, 0.7055]</b>.</li>
          <li><b>Targeting:</b> at equal contact-list size, value-aware ranking captured <b>20.83%</b> of churned recurring value versus <b>14.62%</b> for risk-only ranking.</li>
          <li><b>Limits:</b> measured ranking performance is clearly separated from retrospective, non-causal policy estimates.</li>
        </ul>
        <a href="https://github.com/philopateerreda/GCI-Final-Assignment"><b>View repository →</b></a>
      </td>
    </tr>
  </tbody>
</table>

<h2 align="center">Desktop GUI · Course Final Projects</h2>

<table>
  <thead>
    <tr>
      <th align="left" colspan="2">Two desktop applications built for the same subject</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td width="50%" valign="top">
        <h3><a href="https://github.com/philopateerreda/BulletType_desktop">BulletType</a></h3>
        <img src="https://img.shields.io/badge/Desktop-Typing%20Trainer-86CAD6?style=flat-square&labelColor=0E1222" alt="Desktop: Typing Trainer" /><br /><br />
        <code>Python</code> <code>PyQt / Tkinter</code> <code>SQLite</code>
        <p>Touch-typing practice with live WPM and accuracy tracking, local profiles, and persistent session history.</p>
        <a href="https://github.com/philopateerreda/BulletType_desktop">Desktop repository</a>
        &nbsp;·&nbsp;
        <a href="https://github.com/philopateerreda/unfinished-web-BType">React + Vite web prototype</a>
      </td>
      <td width="50%" valign="top">
        <h3><a href="https://github.com/philopateerreda/2023CollegeJavaProject">Geopolitical Flashcards</a></h3>
        <img src="https://img.shields.io/badge/Desktop-Flashcards%20%26%20Quizzes-86CAD6?style=flat-square&labelColor=0E1222" alt="Desktop: Flashcards and Quizzes" /><br /><br />
        <code>Java</code> <code>Swing</code> <code>SQL Server</code> <code>JDBC</code>
        <p>Spaced-repetition study flows, timed multiple-choice rounds, user authentication, and persistent scoreboards.</p>
        <a href="https://github.com/philopateerreda/2023CollegeJavaProject">Repository</a>
        &nbsp;·&nbsp;
        <a href="https://github.com/philopateerreda/2023CollegeJavaProject/tree/HEAD/docs/images">Screenshots</a>
      </td>
    </tr>
  </tbody>
</table>

<h2 align="center">NLP, Vision &amp; Tools</h2>

<table>
  <tr>
    <td width="50%" valign="top">
      <h4><a href="https://github.com/philopateerreda/textAnalytics">textAnalytics</a></h4>
      <sub>Text Intelligence</sub>
      <p>Readability, lexical-density, POS, NER, and vocabulary-delta analysis with SQLite history and Docker delivery.</p>
      <p><code>Python</code> <code>spaCy</code> <code>NLTK</code> <code>Docker</code></p>
    </td>
    <td width="50%" valign="top">
      <h4><a href="https://github.com/philopateerreda/IEEEVictorees4">IEEEVictorees4</a></h4>
      <sub>Applied NLP Services</sub>
      <p>Django REST text-processing services with local GGUF summarization, scoring, NER, and report generation.</p>
      <p><code>Django REST</code> <code>llama-cpp-python</code> <code>Docker</code></p>
    </td>
  </tr>
  <tr>
    <td width="50%" valign="top">
      <h4><a href="https://github.com/philopateerreda/DIP-project">DIP-project</a></h4>
      <sub>Digital Image Processing</sub>
      <p>Background subtraction, Otsu thresholding, and watershed segmentation, documented in a LaTeX report.</p>
      <p><code>OpenCV</code> <code>Otsu</code> <code>Watershed</code> <code>LaTeX</code></p>
    </td>
    <td width="50%" valign="top">
      <h4><a href="https://github.com/philopateerreda/numerical">numerical</a></h4>
      <sub>Numerical Analysis</sub>
      <p>Interactive PyQt6 workspace for root finding and polynomial interpolation.</p>
      <p><code>PyQt6</code> <code>Root Finding</code> <code>Interpolation</code></p>
    </td>
  </tr>
  <tr>
    <td width="50%" valign="top">
      <h4><a href="https://github.com/philopateerreda/discreteMathProj">discreteMathProj</a></h4>
      <sub>Discrete Mathematics</sub>
      <p>Dark-mode tools for relations, truth tables, graph connectivity, and cycle validation.</p>
      <p><code>PyQt5</code> <code>Logic</code> <code>Graph Theory</code></p>
    </td>
    <td width="50%" valign="top">
      <h4><a href="https://github.com/philopateerreda/PDFSlicer">PDFSlicer</a></h4>
      <sub>CLI Utility</sub>
      <p>TOC-driven PDF chapter extraction with page-offset compensation.</p>
      <p><code>Python</code> <code>JSON</code> <code>PDF</code></p>
    </td>
  </tr>
</table>

<h2 align="center">Toolkit</h2>

<p align="center">
  <b>Machine Learning &amp; Deep Learning</b><br />
  <img src="https://img.shields.io/badge/PyTorch-86CAD6?style=flat-square&logo=pytorch&logoColor=0E1222" alt="PyTorch" />
  <img src="https://img.shields.io/badge/scikit--learn-D9B54E?style=flat-square&logo=scikitlearn&logoColor=0E1222" alt="scikit-learn" />
  <img src="https://img.shields.io/badge/LightGBM-D9B54E?style=flat-square" alt="LightGBM" />
  <img src="https://img.shields.io/badge/XGBoost-D9B54E?style=flat-square" alt="XGBoost" />
  <img src="https://img.shields.io/badge/CatBoost-D9B54E?style=flat-square" alt="CatBoost" />
  <img src="https://img.shields.io/badge/NumPy-D9B54E?style=flat-square&logo=numpy&logoColor=0E1222" alt="NumPy" />
  <img src="https://img.shields.io/badge/pandas-D9B54E?style=flat-square&logo=pandas&logoColor=0E1222" alt="pandas" />
</p>

<p align="center">
  <b>NLP &amp; Systems</b><br />
  <img src="https://img.shields.io/badge/spaCy-D9B54E?style=flat-square&logo=spacy&logoColor=0E1222" alt="spaCy" />
  <img src="https://img.shields.io/badge/NLTK-D9B54E?style=flat-square" alt="NLTK" />
  <img src="https://img.shields.io/badge/llama--cpp--python-D9B54E?style=flat-square" alt="llama-cpp-python" />
  <img src="https://img.shields.io/badge/Django%20REST-D9B54E?style=flat-square&logo=django&logoColor=0E1222" alt="Django REST" />
  <img src="https://img.shields.io/badge/Docker-D9B54E?style=flat-square&logo=docker&logoColor=0E1222" alt="Docker" />
</p>

<p align="center">
  <sub><b>Languages:</b> Python · Java · JavaScript · C/C++ · SQL · LaTeX</sub>
</p>

<h2 align="center">Current Focus</h2>

<p align="center">
  <b>Deep learning and machine learning.</b><br />
  <sub>Neural networks · PyTorch · Validation · Calibration · Reproducible experiments</sub>
</p>

<div align="center">
  <img src="assets/divider.png" alt="" width="100%" height="4" />
</div>
