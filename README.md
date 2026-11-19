<div align="center">

<img src="./assets/banner.svg" alt="Reuben C Mathew - AI Engineer, FinTech and MLOps" width="100%"/>

<a href="https://github.com/rc-mathew"><img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=20&duration=3000&pause=1000&color=8B9CFF&center=true&vCenter=true&width=700&lines=Credit+risk+%26+fraud+ML;Production+MLOps%3A+FastAPI+%C2%B7+Docker+%C2%B7+Kubernetes;LLMs+%2B+RAG+%2B+agentic+systems;Turning+notebooks+into+deployed+systems" alt="Typing animation"/></a>

<br/>

<img src="https://img.shields.io/badge/AI%2FML%20Engineer-0b1026?style=for-the-badge&logo=tensorflow&logoColor=8b9cff"/>
<img src="https://img.shields.io/badge/MSc%20FinTech-0b1026?style=for-the-badge&logo=bitcoin&logoColor=7df9ff"/>
<img src="https://img.shields.io/badge/Bengaluru%2C%20India-0b1026?style=for-the-badge&logo=googlemaps&logoColor=d27bff"/>

<br/>

<a href="https://rc-mathew.github.io"><img src="https://img.shields.io/badge/Portfolio-rc--mathew.github.io-8b9cff?style=flat-square&logo=githubpages&logoColor=white"/></a>
<a href="https://www.linkedin.com/in/reuben-c-mathew-b8199b1b8"><img src="https://img.shields.io/badge/LinkedIn-Connect-0a66c2?style=flat-square&logo=linkedin&logoColor=white"/></a>
<img src="https://komarev.com/ghpvc/?username=rc-mathew&style=flat-square&color=8b9cff&label=Profile+views"/>

</div>

---

## About

ML engineer for credit and fraud risk, Bengaluru. MSc Financial Technology (University of Huddersfield). AI Engineer Intern at **Rubixe**.

**Latest:** [Agentic Lending Policy RAG](https://github.com/rc-mathew/agentic-lending-policy-rag), a cited-answer assistant over RBI rules and bank policies ([live demo](https://lending-policy-assistant.streamlit.app)).

**Now building**
- Deep learning fraud detection (pretrained transaction transformer, GNN)
- QLoRA transaction categoriser (fine-tuned small LLM)
- Banking risk agent (multi-agent, MCP, guardrails, evals in CI)

## Tech stack

<div align="center">

<img src="https://skillicons.dev/icons?i=python,fastapi,docker,kubernetes,aws,git,github,githubactions,pytorch,tensorflow,sklearn,pandas,numpy,postgres&perline=7" alt="Tech stack icons"/>

<br/><br/>

<img src="https://img.shields.io/badge/XGBoost-189fdd?style=flat-square"/>
<img src="https://img.shields.io/badge/MLflow-0194e2?style=flat-square&logo=mlflow&logoColor=white"/>
<img src="https://img.shields.io/badge/AWS%20SageMaker-ff9900?style=flat-square&logo=amazonaws&logoColor=white"/>
<img src="https://img.shields.io/badge/AWS%20EKS-ff9900?style=flat-square&logo=amazoneks&logoColor=white"/>
<img src="https://img.shields.io/badge/LLMs%20%2B%20RAG-8b5cf6?style=flat-square"/>
<img src="https://img.shields.io/badge/LangGraph-1c3c3c?style=flat-square&logo=langchain&logoColor=white"/>
<img src="https://img.shields.io/badge/Jupyter-f37626?style=flat-square&logo=jupyter&logoColor=white"/>

</div>

## Featured work

<table>
  <tr>
    <td colspan="2" valign="top">
      <h3><a href="https://github.com/rc-mathew/agentic-lending-policy-rag">Agentic Lending Policy RAG</a> · <a href="https://lending-policy-assistant.streamlit.app">live demo</a></h3>
      Answers lending questions from 11 RBI Directions and 7 bank policies (829 pages) with a page-level citation on every claim. Plain RAG vs a hand-written ReAct agent vs a LangGraph agent, over hybrid BM25 + dense search and a cross-encoder re-ranker, with EMI/LTV calculator tools. 60-question gold set checked by hand: 82% (plain RAG) to 91% (LangGraph); fixes judged on separate holdout questions. Guardrails, 119 offline tests in CI, runs on free tiers.<br/><br/>
      <img src="https://img.shields.io/badge/LangGraph-1c3c3c?style=flat-square&logo=langchain&logoColor=white"/>
      <img src="https://img.shields.io/badge/Qdrant-dc244c?style=flat-square"/>
      <img src="https://img.shields.io/badge/Gemini-8e75b2?style=flat-square&logo=googlegemini&logoColor=white"/>
      <img src="https://img.shields.io/badge/Streamlit-ff4b4b?style=flat-square&logo=streamlit&logoColor=white"/>
      <img src="https://img.shields.io/badge/RAG%20%2B%20Evals-8b5cf6?style=flat-square"/>
    </td>
  </tr>
  <tr>
    <td width="50%" valign="top">
      <h3>Bank GoodCredit credit risk model</h3>
      Multi-table features, XGBoost beating the benchmark Gini (0.385 vs 0.379), FastAPI on AWS SageMaker Serverless, PSI drift checks.<br/><br/>
      <img src="https://img.shields.io/badge/XGBoost-189fdd?style=flat-square"/>
      <img src="https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white"/>
      <img src="https://img.shields.io/badge/AWS%20SageMaker-ff9900?style=flat-square&logo=amazonaws&logoColor=white"/>
    </td>
    <td width="50%" valign="top">
      <h3><a href="https://github.com/rc-mathew/Customer_Transaction_Prediction_MLOps">Customer Transaction Prediction</a></h3>
      200K records, 0.886 ROC-AUC, calibration, SHAP, Kubernetes on AWS EKS, demo video.<br/><br/>
      <img src="https://img.shields.io/badge/Docker-2496ed?style=flat-square&logo=docker&logoColor=white"/>
      <img src="https://img.shields.io/badge/Kubernetes-326ce5?style=flat-square&logo=kubernetes&logoColor=white"/>
      <img src="https://img.shields.io/badge/AWS%20EKS-ff9900?style=flat-square&logo=amazoneks&logoColor=white"/>
    </td>
  </tr>
  <tr>
    <td width="50%" valign="top">
      <h3><a href="https://github.com/rc-mathew/Home_Loan_Default_ML">Home Loan Default ML</a></h3>
      Default prediction and customer risk segmentation using XGBoost and Logistic Regression.<br/><br/>
      <img src="https://img.shields.io/badge/Scikit--learn-f7931e?style=flat-square&logo=scikitlearn&logoColor=white"/>
      <img src="https://img.shields.io/badge/Credit%20Risk-0b1026?style=flat-square"/>
    </td>
    <td width="50%" valign="top">
      <h3><a href="https://rc-mathew.github.io">Portfolio website</a></h3>
      Personal site with particle effects and a dark/light toggle.<br/><br/>
      <img src="https://img.shields.io/badge/GitHub%20Pages-222?style=flat-square&logo=githubpages&logoColor=white"/>
    </td>
  </tr>
</table>

## GitHub in 3D

<div align="center">

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="./profile-3d-contrib/profile-night-rainbow.svg">
  <source media="(prefers-color-scheme: light)" srcset="./profile-3d-contrib/profile-gitblock.svg">
  <img alt="3D contribution graph" src="./profile-3d-contrib/profile-night-rainbow.svg" width="100%">
</picture>

<br/>

<img src="https://github-readme-stats.vercel.app/api?username=rc-mathew&show_icons=true&theme=tokyonight&hide_border=true&count_private=true" height="160" alt="GitHub stats"/>
<img src="https://github-readme-stats.vercel.app/api/top-langs/?username=rc-mathew&layout=compact&theme=tokyonight&hide_border=true" height="160" alt="Top languages"/>

</div>

<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&height=120&color=gradient&customColorList=12,20,24&section=footer" width="100%" alt=""/>

</div>
