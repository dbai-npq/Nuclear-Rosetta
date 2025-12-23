# Nuclear-Rosetta ⚛️

**Deciphering and Modernizing Legacy Nuclear Physics Code in the AI Era.**

> *"Physics is eternal, but syntax is ephemeral."*

## 📖 About

Just as the **Rosetta Stone** provided the key to deciphering ancient Egyptian hieroglyphs by comparing them to known Greek, **Nuclear-Rosetta** serves as a bridge between the battle-tested legacy codes of Theoretical Nuclear Physics (mostly Fortran 77/90) and the modern era of Scientific Computing (C++, Python/JAX, Julia).

This repository is dedicated to the preservation, translation, and modernization of essential nuclear physics algorithms, leveraging the power of **Generative AI** (LLMs like Claude 3.5 Sonnet, GPT-4) to accelerate the refactoring process while maintaining rigorous scientific accuracy.

## 🚀 Mission

Theoretical nuclear physics sits on a mountain of "legacy code"—numerical routines written decades ago that are mathematically brilliant but computationally opaque.

Our goals are:
1.  **Preservation:** Rescue valuable algorithms from becoming "black boxes" or "abandonware."
2.  **Modernization:** Refactor imperative Fortran spaghetti code into modular, object-oriented, or functional paradigms.
3.  **Acceleration:** Utilize modern hardware (GPUs/TPUs) by porting logic to libraries like **JAX**, **PyTorch**, or modern **C++**.
4.  **Documentation:** Use AI to reverse-engineer variable names (e.g., turning `A(I,J)` into `Hamiltonian_Matrix[i][j]`) and generate comprehensive LaTeX documentation.

## 📂 Repository Structure

* `Legacy/`: The original source code (Fortran files, raw scripts). **Do not touch these logic-wise.** They serve as the "Ground Truth."
* `Modern/`: The refactored implementation (Python/C++).
* `Docs/`: AI-generated, human-verified explanations of the physics models and mathematical derivations.
* `Tests/`: Unit tests ensuring the output of the Modern code matches the Legacy code to machine precision.

## 🛠️ Methodology: The "AI-in-the-Loop" Workflow

We treat AI not as the author, but as a **Junior Translator**. The workflow follows strict scientific rigor:

1.  **Ingestion:** Feed legacy subroutines to the AI model.
2.  **Annotation:** AI analyzes the control flow and adds comments explaining the physical significance.
3.  **Translation:** AI suggests a modern implementation (e.g., replacing nested `DO` loops with `numpy` broadcasting).
4.  **Verification (The Human Role):**
    * **Benchmarking:** Compare numerical results against the original Fortran executable.
    * **Code Review:** Ensure no physical hallucinations occurred during translation.

## ⚠️ Scientific Disclaimer

**Trust, but Verify.**

While AI tools are powerful, they can hallucinate. A successful compilation does not guarantee physical correctness.
* All code in the `Modern` directory is subject to rigorous testing against the `Legacy` baseline.
* Users should always cross-check critical results with established literature or original binaries.

## 🤝 Contributing

Contributions are welcome! If you have a dusty `*.f` file that solves the Schrödinger equation or calculates Cross Sections, feel free to open a Pull Request.

1.  Upload the original code to `Legacy/`.
2.  Submit your modernized version to `Modern/`.
3.  Include a comparison plot or log showing identical results.

---

*Maintained by a Theoretical Nuclear Physicist exploring the AI Coding frontier.*
