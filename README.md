<div align="center">
  <!-- Wavy Cyber-Emerald & Deep Slate Header -->
  <img src="https://capsule-render.vercel.app/api?type=waving&color=0:0a0e14,50:004d40,100:00E599&height=220&section=header&text=Mohammad%20Munawwar%20Malook&fontSize=42&fontColor=ffffff&animation=fadeIn&fontAlignY=38" alt="Mohammad Munawwar Malook Header" width="100%" />

  <!-- Animated Typing SVG -->
  <a href="https://git.io/typing-svg">
    <img src="https://readme-typing-svg.herokuapp.com?font=Fira+Code&weight=600&size=18&duration=2800&pause=1000&color=00E599&center=true&vCenter=true&random=false&width=650&lines=AI%2FML+%26+Systems+Engineer;Autonomous+Multi-Agent+Architectures+(LangGraph+%2B+MCP);Deterministic+RAG+%26+Automated+RAGAS+Observability;Clinical+NLP+%26+Speech+AI+(WhisperX+%2B+LLaMA+3.2);IIT+Madras+Data+Science+%7C+2x+Peer-Reviewed+Author" alt="Typing SVG" />
  </a>

  <p align="center">
    <strong>"I architect AI systems that reason, retrieve, and survive contact with production."</strong>
  </p>

  <!-- Connect & Social Badges -->
  <p align="center">
    <a href="https://portfolio-rana-tigrina.vercel.app" target="_blank">
      <img src="https://img.shields.io/badge/Live_Portfolio-00E599?style=for-the-badge&logo=vercel&logoColor=black" alt="Portfolio"/>
    </a>
    <a href="https://www.linkedin.com/in/munawwar-malook/" target="_blank">
      <img src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn"/>
    </a>
    <a href="https://drive.google.com/file/d/1MJe_JeS904uMpLK-2C7RXV2H5HyNPaop/view?usp=sharing" target="_blank">
      <img src="https://img.shields.io/badge/Verified_Resume-4285F4?style=for-the-badge&logo=google-drive&logoColor=white" alt="Resume"/>
    </a>
    <a href="mailto:munawwar9022@gmail.com">
      <img src="https://img.shields.io/badge/Gmail-D14836?style=for-the-badge&logo=gmail&logoColor=white" alt="Email"/>
    </a>
  </p>
</div>

---

## ⚡ Verified Production Benchmarks

<div align="center">

| Metric | System / Domain | Architecture & Measured Impact |
| :---: | :--- | :--- |
| **>91%** | **Clinical Diagnosis** | Symptom identification benchmarked on par with licensed psychologists via hybrid **BioClinicalBERT + Gemini 2.0 Flash**. |
| **90%** | **Orchestration Platform** | Engineering cycle reduction at **Qapp.ai** via low-code drag-and-drop LLM orchestration deployed to production. |
| **87%** | **Enterprise RAG** | High-throughput query retrieval precision (**P@5**) using semantic chunking, ChromaDB vector indexing, and automated **RAGAS** gates. |
| **40%** | **Inference Optimization** | Token cost reduction through semantic boundary chunking and dynamic context pruning while maintaining 100% recall. |
| **65%** | **Clinical Speech AI** | Cut physician consultation documentation time using **WhisperX** diarization + local **LLaMA 3.2** HIPAA-compliant serving. |
| **2x** | **Published Research** | Peer-reviewed publications in **Taylor & Francis** (Affective Computing) & **ICSCCC** (Programmer Cognitive Dynamics). |

</div>

---

## 🧠 Production Architecture & Agent State Coordination

```python
from typing import Annotated, TypedDict
from langgraph.graph import StateGraph, END

class ProductionAgentState(TypedDict):
    task: str
    context: list[str]
    retrieval_confidence: float
    grounded_citations: list[dict]
    reflection_attempts: int

def critic_reflection_gate(state: ProductionAgentState) -> str:
    """Deterministic routing preventing hallucinated outputs and unbounded loops."""
    if state["retrieval_confidence"] >= 0.85 and len(state["grounded_citations"]) > 0:
        return "synthesize_verified_output"
    if state["reflection_attempts"] < 3:
        return "replan_query_strategy"
    return "human_in_the_loop_fallback"
```

---

## 🚀 Flagship Systems & Featured Projects

<div align="center">
  <table width="100%">
    <tr>
      <td width="50%" valign="top">
        <h3 align="center">📑 Advanced RAG System for PDF Q&A</h3>
        <p align="center">
          <a href="https://github.com/rana-tigrina/PDF-Q-and-A-Rag" target="_blank">
            <img src="https://github-readme-stats.vercel.app/api/pin/?username=rana-tigrina&repo=PDF-Q-and-A-Rag&theme=tokyonight&hide_border=true&bg_color=0d1117&title_color=00E599&icon_color=00BFFF" alt="PDF Q&A RAG"/>
          </a>
        </p>
        <p align="justify">
          High-throughput RAG engine featuring semantic chunking, multi-stage reranking, and ChromaDB vector indexing with automated RAGAS evaluation harnesses.
        </p>
        <p align="center">
          <code>LangChain</code> · <code>ChromaDB</code> · <code>RAGAS</code> · <code>FastAPI</code>
        </p>
      </td>
      <td width="50%" valign="top">
        <h3 align="center">🩺 AI Clinical & Therapy Notes Generator</h3>
        <p align="center">
          <a href="https://github.com/rana-tigrina/AI-Therpy-Notes-Maker" target="_blank">
            <img src="https://github-readme-stats.vercel.app/api/pin/?username=rana-tigrina&repo=AI-Therpy-Notes-Maker&theme=tokyonight&hide_border=true&bg_color=0d1117&title_color=00E599&icon_color=00BFFF" alt="AI Therapy Notes"/>
          </a>
        </p>
        <p align="justify">
          Automated conversion of raw consultation audio into structured clinical SOAP notes with 90% medical terminology accuracy and ICD-10 suggestions.
        </p>
        <p align="center">
          <code>WhisperX</code> · <code>LLaMA 3.2</code> · <code>BioClinicalBERT</code> · <code>Docker</code>
        </p>
      </td>
    </tr>
    <tr>
      <td width="50%" valign="top">
        <h3 align="center">⚡ Senior AI Engineer Interactive Portfolio</h3>
        <p align="center">
          <a href="https://github.com/rana-tigrina/Portfolio" target="_blank">
            <img src="https://github-readme-stats.vercel.app/api/pin/?username=rana-tigrina&repo=Portfolio&theme=tokyonight&hide_border=true&bg_color=0d1117&title_color=00E599&icon_color=00BFFF" alt="Flagship Portfolio"/>
          </a>
        </p>
        <p align="justify">
          Flagship Engineering Studio with live 2-pane CAD architecture workbenches, interactive RAG waveform simulator, and Web Audio feedback.
        </p>
        <p align="center">
          <code>Next.js 15</code> · <code>TypeScript</code> · <code>Tailwind</code> · <code>Motion</code>
        </p>
      </td>
      <td width="50%" valign="top">
        <h3 align="center">🛡️ Multi-Agent Claims Audit & MCP Assistant</h3>
        <p align="center">
          <a href="https://github.com/rana-tigrina" target="_blank">
            <img src="https://github-readme-stats.vercel.app/api/pin/?username=rana-tigrina&repo=Jan-Elaaj&theme=tokyonight&hide_border=true&bg_color=0d1117&title_color=00E599&icon_color=00BFFF" alt="Claims Audit"/>
          </a>
        </p>
        <p align="justify">
          Deterministic 5-agent state graph processing CMS Medicare policy claims with explainable discrepancy logs and Model Context Protocol (MCP) tooling.
        </p>
        <p align="center">
          <code>LangGraph</code> · <code>Gemini 2.0 Flash</code> · <code>MCP</code> · <code>FastAPI</code>
        </p>
      </td>
    </tr>
  </table>
</div>

---

## 📚 Peer-Reviewed Research & Publications

- **[Beyond Words: Multimodal Approach to Teletherapy Using Eye Gaze and Facial Expressions](https://github.com/rana-tigrina)**  
  *Taylor & Francis (2025)*  
  Proposed a multimodal AI framework combining eye-gaze tracking, facial action unit quantification, and clinical NLP to evaluate affective rapport and engagement during teletherapy encounters in real time.

- **[A Systematic Literature Review on the Impact of AI on the Cognitive Capabilities of Programmers](https://github.com/rana-tigrina)**  
  *ICSCCC (2025)*  
  Rigorous investigation evaluating 45+ empirical studies on how LLM coding agents alter developer mental models, cognitive load distributions, and architectural problem-solving habits.

---

## 🛠️ Core Engineering Arsenal

<div align="center">
  <img src="https://skillicons.dev/icons?i=python,pytorch,tensorflow,aws,docker,fastapi,postgres,redis,linux,git,bash,cpp,nextjs,typescript,tailwind" alt="Skills Arsenal" />
</div>

<br />

| Domain | Production Tools & Technologies |
| :--- | :--- |
| **Agentic AI & Orchestration** | **LangGraph**, **LangChain**, Model Context Protocol (**MCP**), CrewAI, Autonomous Tool-Calling Agents |
| **LLMs & Foundation Models** | **Gemini 2.0 Flash**, **LLaMA 3.2**, **BioClinicalBERT**, DeepSeek-R1, Mistral, WhisperX |
| **RAG & Vector Architecture** | **ChromaDB**, FAISS, Qdrant, Semantic Boundary Chunking, Cohere Rerank, Dense Passage Retrieval |
| **LLMOps & Telemetry** | **RAGAS CI/CD Gates**, **LangSmith**, **Langfuse**, OpenTelemetry, Automated Regression Harnesses |
| **Backend & Infrastructure** | **FastAPI**, Docker, AWS (EC2/S3/Lambda), PostgreSQL, Redis, Streamlit, Linux System Administration |

---

## 📊 Telemetry & GitHub Activity

<div align="center">
  <table border="0">
    <tr>
      <td align="center" width="50%">
        <img src="https://github-readme-stats.vercel.app/api?username=rana-tigrina&show_icons=true&theme=tokyonight&bg_color=0d1117&title_color=00E599&icon_color=00BFFF&text_color=c9d1d9&border_color=30363d&count_private=true&hide_border=false" width="100%" alt="GitHub Stats" />
      </td>
      <td align="center" width="50%">
        <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=rana-tigrina&layout=compact&theme=tokyonight&bg_color=0d1117&title_color=00E599&icon_color=00BFFF&text_color=c9d1d9&border_color=30363d&count_private=true&hide_border=false" width="100%" alt="Top Languages" />
      </td>
    </tr>
  </table>
</div>

---

<div align="center">
  <sub>Open for Senior AI/ML & Founding Engineer roles · Based in Delhi, India</sub>
  <br />
  <img src="https://komarev.com/ghpvc/?username=rana-tigrina&label=Profile%20Views&color=00E599&style=flat-square" alt="Profile Views" />
</div>
