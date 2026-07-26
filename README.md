# Bank Payoff Solution

<p align="center">
  <a href="#license"><img src="https://img.shields.io/badge/license-pending-0E7C66.svg" alt="License"></a> <a href="#paper-or-reference"><img src="https://img.shields.io/badge/paper-reference-1F4E79.svg" alt="Paper or reference"></a> <img src="https://img.shields.io/badge/language-Wolfram%20Notebook-DD1100.svg" alt="Wolfram Notebook">
</p>

<p align="center">
  <strong>Notebook-based payoff modeling for structured banking scenarios.</strong>
</p>

<p align="center">
  <img src="assets/readme-figure.png" alt="Bank Payoff Solution overview" width="100%">
</p>

## Abstract

This repository is a conference-style artifact for parameterized payoff modeling for structured banking scenarios. It packages the code and notes needed to inspect the central research question: How do payoff surfaces change under controlled kernel and scenario assumptions? The emphasis is on transparent entry points, reproducible execution, and clear separation between code, local data, and generated outputs.

## Artifact at a Glance

| Item | Details |
| --- | --- |
| Research question | How do payoff surfaces change under controlled kernel and scenario assumptions? |
| Primary artifact | Mathematica notebooks, a model PDF, and saved result notes. |
| Main entry points | `one demo- {kernel5, a=0.1,b=0.5,d=5}.nb`, `XinyuanSong.nb` |
| Expected outputs | Payoff surfaces, scenario tables, and report-ready notes. |

## Repository Structure

| Item | Details |
| --- | --- |
| `one demo- {kernel5, a=0.1,b=0.5,d=5}.nb` | worked Mathematica notebook for the reference demo case. |
| `XinyuanSong.nb` | exploratory notebook for payoff derivations and parameter checks. |
| `model 9.11.22.pdf` | static model write-up used as the main reference document. |
| `results.docx` | saved result notes for comparison and reporting. |

## Reproducibility Protocol

1. `git clone git@github.com:Hik289/bank-pay-off-solution.git`
2. Open the `.nb` notebooks in Wolfram Mathematica.
3. Use the PDF and DOCX files as reference outputs when checking new parameter settings.
4. Record the data window, random seed, software versions, machine type, and exact command used for any full rerun.
5. Store regenerated figures, tables, checkpoints, or reports under the existing result folders instead of overwriting raw inputs.

## Evaluation Protocol

| Step | Reviewer-facing check |
| --- | --- |
| Environment | Confirm the listed runtime or notebook environment starts without modifying tracked files. |
| Minimal run | Execute the smallest entry point before launching longer experiments. |
| Output check | Compare regenerated files with the expected figures, tables, logs, or reports named in this README. |
| Extension check | Add new runs as separate scripts, notebooks, or result folders with explicit names. |

## Expected Results

- The main scripts or notebooks should regenerate the project-specific artifacts listed in **Artifact at a Glance**.
- Outputs should be traceable to a command, parameter setting, and data window.
- Any private data path or machine-specific setting should be documented before sharing the artifact externally.

## Paper or Reference

No external paper link is currently attached to this project. For now, the code, notebooks, and notes in this repository are the primary reference artifact.

## Citation

If this repository supports a paper, cite the paper first and the artifact version second. If no paper is attached, cite the repository snapshot used in the experiment.

```bibtex
@misc{bank_pay_off_solution_artifact_2026,
  title = {{Bank Payoff Solution}},
  author = {Hik289},
  year = {2026},
  howpublished = {\url{https://github.com/Hik289/bank-pay-off-solution}},
  note = {Conference-style research artifact}
}
```

## License

No explicit license file is included yet. Add one before public reuse, redistribution, or package release.

## Reviewer Checklist

| Claim | How to inspect it |
| --- | --- |
| Code availability | Code and notebooks are present in the repository. |
| Reproducibility | The protocol above gives the expected setup and run order. |
| Result traceability | Generated outputs should live in named result, report, log, or output folders. |
| Extensibility | New experiments should preserve existing artifacts and add clearly named outputs. |
