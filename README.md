# The-Intelligent-File-Indexer
"High-speed File Indexer for people who talk to compilers more than humans. Optimizing search complexity so I can find my notes faster than my motivation."

# 🚀 FastIndex-CLI: Automated File Search Engine

A high-performance command-line tool built to solve the "I forgot where I saved that" problem. 

### 🧠 The Logic (The Introvert's Edge)
Instead of a slow linear scan ($O(n)$), this tool uses an **Inverted Index** (Hash Map) to achieve **$O(1)$ search time**. 

### ✨ Key Features
- **Instant Lookup:** Pre-processes files into a word-to-filename mapping.
- **Memory Efficient:** Uses Python `sets` to prevent duplicate file references.
- **Scalable:** Designed to handle thousands of `.txt` notes in milliseconds.

### 🛠️ Tech Stack
- **Language:** Python 3.x
- **Data Structures:** Hash Maps (Dicts), Sets.
- **Concepts:** File I/O, Time Complexity Optimization.

### 📈 Future Roadmap
- [ ] Add PDF/Docx support.
- [ ] Implement Ranking (TF-IDF) to show the most relevant files first.
