# Claude Partner Network Learning Path



Welcome to my repository for the **Claude Partner Network (CPN)** learning path by Anthropic. This workspace acts as a centralized repository for my coursework, project labs, local execution setups, and programmatic scripts mapping directly to the official certification curriculum.



The repository is logically organized to separate theoretical concepts, API prompt engineering loops, Model Context Protocol (MCP) transport pipelines, and localized terminal agent workflows.



---



## 📂 Repository Layout



The workspace has been organized chronologically based on model interaction layers and assignment paradigms:



```text

Claude-Partner-Network/
├── 01_Intro_to_Agent_Skills/            # Conceptual Core & Declarative Instructions
│   └── (Global ~/.claude/skills handles user execution environment layouts)
│
├── 02_Building_with_Claude_API/         # SDK Core, Prompt Optimization, & RAG Pipelines
│   ├── 001_requests.ipynb                    # Request configuration and stateless handlers
│   ├── 001_thinking*.ipynb                   # Deep reasoning configurations via Extended Thinking mode
│   ├── 001_prompting*.ipynb                  # Prompt structure optimization (XML, directives)
│   ├── 001_prompt_evals*.ipynb               # Metric pipelines, dataset generation, and model scoring
│   ├── 001_tools*.ipynb                      # Multi-turn conversation workflows using sequential tools
│   ├── 002_citations_complete.ipynb          # Document grounding and citation extraction structures
│   ├── 002_embeddings.ipynb                  # Text representation generation via VoyageAI vectors
│   ├── 002_images.ipynb                      # Computer vision implementations and safety scoring steps
│   ├── 002_pdf_support.ipynb                 # Unstructured document parsing layouts
│   ├── 003_caching.ipynb                     # Computational reuse and token optimization models
│   ├── 003_tool_streaming*.ipynb             # Input JSON streaming handlers with fine-grained controls
│   ├── 003_vectordb.ipynb                    # Vector index setup and cosine distance evaluations
│   ├── 004_bm25.ipynb                        # Lexical exact-term matching engines
│   ├── 005_code_execution.ipynb              # Isolated Docker sandboxing routines via the Files API
│   ├── 005_hybrid.ipynb                      # Multi-index retrieval architectures utilizing RRF fusions
│   ├── 005_text_editor_tool.ipynb            # Built-in filesystem modification tools
│   ├── 006_web_search*.ipynb                 # Domain restrictions and dynamic validation engines
│   ├── Churn Analysis Outputs/               # Sandbox graphics (*.png) and console printouts (*.txt)
│   └── Source Documentation/                 # Context files (.pdf, .md, .json, .csv) used across RAG modules
│
├── 03_Intro_to_Model_Context_Protocol/   # Multi-Component Client & Server Implementations
│   ├── cli_project/                          # Python FastMCP data server and connection bridge labs
│   └── cli_project_COMPLETE/                 # Completed reference server architecture builds
│
└── 04_Claude_Code_in_Action/             # Terminal-Based Workflows & Automated Script Interceptions
   ├── app_starter/                           # Collaborative development runtime workspace
   ├── queries/                               # PreToolUse / PostToolUse hook customization sandboxes
   ├── queries_COMPLETED/                     # Completed reference code protection execution hooks
   ├── uigen/                                 # UI component generation testing platform repo
   └── ANALYSIS_SUMMARY.md                    # Localized workflow execution performance metrics
