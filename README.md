# Hi, I'm Yumin Hwang 👋

**Aspiring LLM Engineer** focused on making LLM systems measurably better: retrieval quality, evaluation, and reliability.

I like to build the evaluation first, then iterate until the numbers move.

## Featured Projects

### 🔍 [RFP Advanced RAG](https://github.com/Yumin-Hwang046/rfp-advanced-rag)
QA system over 100 public-sector RFP PDFs (~7,500 pages): text, table, and GPT-Vision image parsing, with a hybrid Dense + BM25 retriever.
- **Audited my own team's evaluation after the project**: found that the "Advanced" run reused the Naive index (so table/image parsing was never measured), along with grader false positives and an uncapped-MRR artifact
- Now running a clean ablation (hybrid → +tables → +images), scored per question type
- Wrote ~79% of the final codebase in a 5-person team

`LangChain` `FAISS` `BM25` `OpenAI` `Streamlit`

### 🎨 [The Digital Curator](https://github.com/Yumin-Hwang046/Team4_ImgGeneration_Project)
Generative-AI platform that turns a restaurant's food photo into Instagram-ready ad images and copy, then uploads them automatically.
- **PM and model lead** in a 4-person team; top contributor (117 commits)
- Built the image-generation pipeline: style-reference generation and mask-based background replacement

`PyTorch` `FastAPI` `Next.js` `MySQL`

### 🕸️ [YouTube Network Topology Analysis](https://github.com/Yumin-Hwang046/youtube-network-topology-analysis)
Graph-theoretic study of the real YouTube network (SNAP data) against Erdős–Rényi, Barabási–Albert, and Watts–Strogatz models.

`NetworkX` `pandas` `NumPy`

## Tech Stack

**LLM / ML** · LangChain, OpenAI API, Gemini API, FAISS, PyTorch, Hugging Face
**Backend / Web** · Python, FastAPI, TypeScript, Next.js, React, MySQL
**Tools** · Git, Docker, Jupyter, Streamlit

## Contact

📧 hwangyumin046@gmail.com · 💼 [LinkedIn](https://www.linkedin.com/in/yumin-hwang-49b552260)
