# Bank Payoff Solution

<p align="center">
  <a href="#license"><img src="https://img.shields.io/badge/license-pending-0E7C66.svg" alt="License"></a> <a href="#paper-or-reference"><img src="https://img.shields.io/badge/paper-reference-1F4E79.svg" alt="Paper or reference"></a> <img src="https://img.shields.io/badge/language-Wolfram%20Notebook-DD1100.svg" alt="Wolfram Notebook">
</p>

<p align="center">
  <strong>Conference-style artifact for payoff modeling and scenario analysis.</strong>
</p>

<p align="center">
  <img src="assets/readme-figure.png" alt="Bank Payoff Solution overview" width="100%">
</p>

## Abstract

This repository is organized as a conference-style artifact for structured banking payoff analysis. It is written for a reviewer or collaborator who wants to identify the exact entry points, understand the expected outputs, and reproduce the core evidence without reverse-engineering the folder layout. The central question is: **How do parameterized payoff surfaces respond to changes in kernel and scenario assumptions?**

## Contribution Summary

- Notebook-first payoff modeling workflow.
- Scenario artifacts for checking parameter sensitivity.
- Report-ready outputs for comparing model assumptions.

## Artifact at a Glance

| Item | Details |
| --- | --- |
| Research question | How do parameterized payoff surfaces respond to changes in kernel and scenario assumptions? |
| Primary contribution | Notebook-first payoff modeling workflow; Scenario artifacts for checking parameter sensitivity; Report-ready outputs for comparing model assumptions |
| Main entry points | `one demo- {kernel5, a=0.1,b=0.5,d=5}.nb`, `XinyuanSong.nb` |
| Runtime | Wolfram Mathematica plus document viewers |
| Data expectation | Notebook parameters and bundled report artifacts |
| Expected evidence | Payoff surfaces, scenario tables, PDF notes, and DOCX summaries |

## Repository Structure

| Item | Details |
| --- | --- |
| Entry points | `one demo- {kernel5, a=0.1,b=0.5,d=5}.nb`, `XinyuanSong.nb` |
| Experiment assets | Notebook parameters and bundled report artifacts |
| Generated artifacts | Payoff surfaces, scenario tables, PDF notes, and DOCX summaries |
| Documentation role | README records the reproducibility protocol, reviewer-facing checks, and citation metadata |

## Reproducibility Protocol

1. Clone the repository: `git clone git@github.com:Hik289/bank-pay-off-solution.git`.
2. Prepare the runtime listed in **Artifact at a Glance**.
3. Start from the main entry points rather than auxiliary folders.
4. Run the smallest script or notebook first to verify local paths and package versions.
5. Record the command, data window, random seed, machine type, and software versions for each full run.
6. Store regenerated figures, logs, tables, checkpoints, or reports in named output folders so the original artifacts remain inspectable.

## Evaluation Protocol

| Check | Expected reviewer action |
| --- | --- |
| Entry-point clarity | Confirm the listed scripts or notebooks are the natural starting points. |
| Minimal execution | Run a small case before attempting the full experiment. |
| Output traceability | Map every regenerated output back to a command and data setting. |
| Result inspection | Compare generated artifacts with the expected evidence listed above. |
| Extension hygiene | Add new experiments as clearly named scripts, notebooks, or output folders. |

## Expected Results

A successful reproduction should produce or refresh the following evidence: Payoff surfaces, scenario tables, PDF notes, and DOCX summaries. If local datasets or machine-specific paths are required, document those paths outside the committed code before sharing the artifact.

## Known Limitations

- Large datasets, private data paths, and machine-specific settings may need local configuration.
- Some historical notebooks or scripts may reflect exploratory runs; prefer the entry points listed above for review.
- For archival release, add a pinned environment file and a small public fixture when possible.

## Paper or Reference

No external paper link is currently attached to this project. Cite the repository snapshot when using the artifact in academic work.

## Citation

If a paper is attached, cite the paper first and this artifact second. Otherwise cite the repository snapshot used for the experiment.

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

| Claim | Inspection path |
| --- | --- |
| Code availability | Core scripts, notebooks, and utilities are tracked in this repository. |
| Reproducibility | The protocol above states setup, entry points, and output expectations. |
| Data transparency | Local or private data dependencies should be documented before external release. |
| Result traceability | Generated outputs should live in named result, report, log, checkpoint, or output folders. |
