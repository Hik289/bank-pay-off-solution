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

**Figure 1.** The overview figure frames the repository as a small payoff-analysis workflow: assumptions enter the notebook model, experiments produce payoff surfaces, and report artifacts capture the final interpretation.

## Scope

This repository is organized as a conference-style research artifact for parameterized payoff surfaces and scenario analysis. Bank Payoff Solution organizes notebook and report artifacts for studying parameterized payoff surfaces, kernelized response behavior, and scenario-level result interpretation. It is best used as a reproducible research workspace: open the notebooks, adjust the payoff parameters, and compare the exported reports.

The README is structured for fast inspection by reviewers and future collaborators: it states the artifact scope, the main entry points, the reproduction path, and the outputs that should be checked after a run.

## Artifact Contents

| Component | Role |
| --- | --- |
| `one demo- {kernel5, a=0.1,b=0.5,d=5}.nb` | worked Mathematica notebook for the reference demo case. |
| `XinyuanSong.nb` | exploratory notebook for payoff derivations and parameter checks. |
| `model 9.11.22.pdf` | static model write-up used as the main reference document. |
| `results.docx` | saved result notes for comparison and reporting. |

## Reproduction Guide

1. `git clone git@github.com:Hik289/bank-pay-off-solution.git`
2. Open the `.nb` notebooks in Wolfram Mathematica.
3. Use the PDF and DOCX files as reference outputs when checking new parameter settings.

For a full rerun, record the data window, random seed, software versions, machine type, and command used for each experiment. Keep raw datasets outside Git unless they are small public fixtures.

## Experimental Workflow

| Stage | What to Check |
| --- | --- |
| Setup | Confirm local data paths, environment packages, and any MATLAB or notebook paths before running experiments. |
| Run | Execute the smallest script or notebook first, then scale to the full experiment once outputs match expectations. |
| Inspect | Compare generated figures, logs, tables, and saved result folders against the intended analysis. |
| Extend | Add new experiments as separate scripts or notebooks with explicit names instead of overwriting existing artifacts. |

## Expected Outputs

- Recreated figures, tables, notebooks, reports, or saved result files from the listed entry points.
- A clear mapping from each experiment command to its generated output location.
- Updated notes when a script depends on local data, private paths, or external software.

## Paper or Reference

No external paper link is currently attached to this project. For now, the code, notebooks, and notes in this repository are the primary reference artifact.

## Citation

If this repository supports academic work, cite the linked paper when available. Otherwise cite the repository version used in your experiment.

```bibtex
@misc{bank_pay_off_solution_artifact_2026,
  title = {{Bank Payoff Solution}},
  author = {Hik289},
  year = {2026},
  howpublished = {\url{https://github.com/Hik289/bank-pay-off-solution}},
  note = {Research artifact}
}
```

## License

No explicit license file is included yet. Add one before public reuse, redistribution, or package release.

## Reviewer Notes

| Item | Status |
| --- | --- |
| Code | Included in this repository. |
| Data | Expected to be configured locally unless a small fixture is committed. |
| Environment | Base dependencies are listed in the reproduction guide; pin a lockfile for archival release. |
| Results | Store generated artifacts under the existing result, report, log, or output folders. |
