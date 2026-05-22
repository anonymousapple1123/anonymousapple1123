# README

## Professional Summary
Passionate software developer with experience in compiled and interpreted languages. Skilled in multi-platform application development, GUI design, and mathematical computation codebases. Focused on performant, maintainable systems with local LLM integration for developer tooling.

## Technical Skills
- **Languages:** C++, C, Java, Python, C3, Odin  
- **Tools:** Git, Docker, Vim  
- **Technologies:** PyQt6, multi‑threading, LLM integration (local)  
- **Systems:** Linux, Windows, macOS

## Projects (selected)

### Code Review Assistant
- **Tech:** Python, C++, PyQt6, Ollama  
- **Summary:** High‑performance GUI app with hybrid Python/C++ architecture for local LLM‑powered code reviews.  
- **Highlights:**
  - Local LLM integration for offline code analysis and suggestions.  
  - Adaptive streaming with buffering for responsive UI during model outputs.  
  - Hybrid architecture: C++ core for CPU‑intensive tasks, Python for orchestration and UI.

### Cupcake
- **Tech:** C++, Shell, Ollama  
- **Summary:** CLI tool that uses a specialized local LLM to summarize repositories and auto‑generate documentation.  
- **Highlights:**
  - Fast repository summarization workflow.  
  - Designed for automated README/CHANGELOG generation and doc drafts.

### Algebraic Calculator
- **Tech:** C++  
- **Summary:** Command‑line application for complex‑number arithmetic and matrix operations.  
- **Highlights:**
  - Support for complex arithmetic, matrix addition/multiplication/inversion.  
  - Designed for precision and performance in numeric computations.

### Additional Projects
- GUI Attendance Calculator (Python / PyQt6)  
- Crypto Morph (encryption / decryption utilities)

## Architecture & Design Notes
- Prefer hybrid designs: native C++ modules for compute‑heavy paths, Python for UI and integration.  
- Use multi‑threading to keep GUIs responsive while performing I/O or model inference.  
- Local LLMs (e.g., Ollama) run in isolated environments; design for streaming outputs and back‑pressure handling.  
- Keep CLI tools simple, scriptable, and composable in shell pipelines.

## Contribution
- Open to issues and pull requests.  
- Follow conventional commits, include tests for functional changes, and keep API compatibility in modules used by multiple projects.

## Contact
- See profile for contact links and project‑specific issue trackers.

<!-- End of README -->
