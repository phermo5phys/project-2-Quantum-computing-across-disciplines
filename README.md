# Q-Lab — Project 2

![Q-Lab Project 2 cover](assets/github-cover.png)

## Quantum Computing, Across Disciplines

**One shared journey, read through five analytical lenses — and run end to end.**

Q-Lab Project 2 is an interdisciplinary scaffold for reading and running quantum algorithms as complete, evidence-bearing scientific workflows. It extends the double-slit bridge developed in Project 1 without claiming that slits are literally qubits or that every algorithm has the same visible structure.

The project uses an abstract **N-slit boundary object** to keep one shared picture in view while the problem changes form across physics, mathematics, quantum computation, classical evidence, software, and hardware.

## The architecture

### Eight shared conceptual coordinates

`Origin → Representation → Transformation → Interference → Measurement → Evidence → Verification → Meaning`

These are analytical coordinates, not eight boxes that must appear visibly and exactly once in every algorithm.

### Five analytical lenses

1. **Domain & Physical**
2. **Mathematical Modelling**
3. **Quantum Computation**
4. **Classical Computation & Evidence**
5. **Execution & Hardware**

The lenses describe forms of reasoning and checking, not permanent professional ownership.

### Canonical programmatic path

`Build → Translate → Validate → Transpile → Execute → Preserve Evidence → Reconstruct`

A cross-cutting quality rail asks, at every transition:

- What is the claim?
- What could fail?
- What check would reveal it?
- What evidence must be retained?
- What threshold allows the workflow to move on?

## Included deliverables

| Deliverable | Purpose |
|---|---|
| [Carousel](carousel/Q-Lab_Carousel_Project2.pdf) | The complete architecture in a mobile-first visual sequence |
| [Interdisciplinary Guide](guide/Q-Lab_Interdisciplinary_Guide.pdf) | Foundations, limitations, framework, QPE application, worksheets, and references |
| [QPE Notebook](notebook/Q_Lab_QPE.ipynb) | A guided Qiskit workflow that maps, translates, validates, transpiles, executes, preserves evidence, reconstructs, and verifies |
| [LinkedIn package](linkedin/) | Revised post text, document carousel, image order, and exported slides |
| [Project review](docs/PROJECT_REVIEW.md) | Errors found, corrections made, and remaining research limits |

## Run the notebook

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/phermo5phys/q-lab-project-2/blob/main/notebook/Q_Lab_QPE.ipynb)

The notebook installs `qiskit[visualization]==2.5.1` and uses Qiskit's built-in `BasicSimulator` for an ideal, controlled testing and prototyping run. Simulator output is not presented as hardware evidence.

### Worked example

The notebook estimates the exactly representable eigenphase

\[
\phi=\frac{3}{8}=0.011_2
\]

and preserves the chain from the declared mission to:

- the logical circuit,
- logical OpenQASM 2,
- validation checks,
- the compiled circuit and compiled OpenQASM 2,
- backend and seed metadata,
- counts and shot memory,
- the reconstructed phase,
- verification diagnostics,
- and a bounded final claim.

## Repository structure

```text
q-lab-project-2/
├── README.md
├── README_AR.md
├── GITHUB_ABOUT.md
├── CITATION.cff
├── CHANGELOG.md
├── requirements.txt
├── carousel/
├── guide/
├── notebook/
├── assets/
│   ├── github-cover.png
│   ├── github-social-preview.png
│   └── linkedin/
├── linkedin/
├── docs/
└── archive/
    └── originals/
```

## What the project claims — and does not claim

**Current status:** a theoretically grounded and visually developed interdisciplinary scaffold.

It is designed to support whole-workflow reading, evidence-aware execution, and cross-lens questioning. Whether it improves learning, coordination, solution diversity, or innovation remains an empirical question.

It is **not**:

- a universal decomposition theorem for all quantum algorithms,
- a substitute for mathematical derivation, programming skill, domain review, or hardware expertise,
- proof that the double slit physically models every algorithm,
- or evidence of quantum advantage.

## Suggested repository topics

`quantum-computing` · `qiskit` · `quantum-phase-estimation` · `quantum-education` · `interdisciplinary-research` · `boundary-objects` · `scientific-workflows` · `reproducible-research`

## Author

**Sarah Ibrahim Alkhamis**  
Concept, interdisciplinary framework, scientific narrative, visual design, and QPE workflow.

## Citation

Citation metadata is available in [`CITATION.cff`](CITATION.cff).

## Licensing status

No open-source license has been selected in this package. Reuse permissions should be requested from the author unless a separate `LICENSE` file is later added.
