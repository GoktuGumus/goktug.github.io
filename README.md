# SOFTWARE ENGINEER

[GitHub](https://github.com/goktugumus) · [LinkedIn](https://www.linkedin.com/in/goktuggumuss) · [Email](mailto:goktugg.gumuss@gmail.com)

### Technical Skills: **Python, C++, C#, Docker, LLM & RAG**

## Work Experience

**Software Engineer @ ISSD Bilişim Teknolojik A.Ş. (January 2026 - Present)**
- Developing real-time computer vision applications for intelligent transportation systems (object detection, tracking and classification).
- Deploying and optimizing deep learning models on embedded hardware (model quantization and inference optimization).
- Building machine learning and LLM-based solutions, including a RAG + function-calling assistant for natural-language querying of traffic data.
- Building dataset preparation and annotation pipelines for model training (CVAT).

**Software Engineer @ Toucan Code Labs (March 2024 - January 2026)**
- Embedded system design and development using WPF and the .NET 8 Framework.
- Maintained code bases and implemented new features/endpoints for existing .NET projects using C#.
- Used Azure DevOps and Trello to track bugs, new features, and software development milestones.

## Education

Computer Engineering, Bachelor's Degree  |  *Çankaya University (September 2023)*

## Projects

### AI-Powered Traffic Data Assistant (RAG + Function Calling)
- Designed and built an end-to-end LLM assistant that translates natural-language questions into structured REST API calls against a traffic management platform and synthesizes analytical answers from the returned data.
- Self-hosted a quantized Qwen3 8B (GGUF) model served through llama-cpp-python with full GPU offload on an NVIDIA RTX 5090 (32 GB VRAM), running in a containerized (Docker) multi-user environment.
- Implemented the orchestration layer in pure Python — prompt construction, conversation state management, tool-call parsing and validation, and API response post-processing — without relying on an agent framework.
- Built a Retrieval-Augmented Generation (RAG) pipeline on Qdrant: domain documents are chunked, embedded and indexed for top-k semantic retrieval that grounds model responses and reduces hallucination.
- Implemented JSON-schema-based function calling: intent detection, parameter extraction and validation (route, time range, metric), API invocation and result summarization.

### AccuFire
- A desktop application developed with WPF to provide remote control from a ground station.
- Backend development using the C# .NET 8 Framework.
- Thread management with async methods; multi-threading synchronized with Mutex/Semaphore primitives.
- Serial communication over COM ports between the computer and an STM32 (ARM-based) microprocessor, including connection control and data-flow management.
- Developed the simulation box software to control switches, manage switch connections and display real-time warning screens to the user.
- Real-time visualization of the data flow on graphs for monitoring and debugging.

### AccuComp
- Developed a lossless compression algorithm on a dsPIC33FJ256MC710A microcontroller that chunks and compresses data streamed from a 60-leg MAC processor.
- Prototyped in C++, then ported to C for hardware integration and higher efficiency.
- Losslessly compresses 60 incoming samples every 10 ms, saving 65% of space; compression completes in 1-2 ms on average, followed by fully lossless decompression.
- Pipeline stages: data normalization, delta coding, adaptive Huffman coding/decoding, delta decoding and data denormalization.
- Generates log files reporting the original, compressed and decompressed sizes, consistency checks between original and decompressed data, and total space saved.

### TALIA — Autonomous VTOL UAV
- Contributed to the software of an unmanned aerial vehicle capable of fully autonomous vertical take-off and landing:
  - Image processing.
  - Real-time image recording and high-FPS streaming to the ground station.
  - Fully autonomous flight.
  - Path and vehicle detection and tracking.
- ***1st Place in the 16th R&D Project Market Event***
- [GitHub Repository](https://github.com/CankayaUniversity/ceng-407-408-2022-2023-Autonomous-VTOL-Design) · [YouTube Video](https://www.youtube.com/watch?v=IkvebxVaYGU)
