Data and material for the experiments and the modeling reported in _Rothe, Deverett, Mayrhofer, & Kemp (in revision). Successful structure learning from observational data._

------

`data_by_subject.csv` contains the causal structures that participants inferred in Experiments 1 to 5.

Columns:

- `exp_paper` Experiment number, same ordering as reported in the paper
- `subject` Participant ID (note, subject `1` in Experiment 1 is not the same participant as subject `1` in Experiment 2, etc.)
- `block` Block number, same ordering as reported in the paper
- `repetition` Either `1` or `2` (only relevant for Experiment 1, where each block was shown two times)
- `graph` ID of the causal structure drawn by the participant (for all 64 causal structures and their IDs, see `graphs_overview.pdf` shown below or the identical Figure C1 in the Appendix)

------

`data_model.csv` contains the aggregated responses from participants and the model predictions

Columns:

- `exp_paper`
- `block`
- `graph` In this csv file, for each block in each experiment, `graph` ranges from `1` to `64`
- `subject_rel` The percentage of participants that drew this graph in this block (i.e., sums to 1 within each block)
- `BSL` ... `LSL` Model predictions  = model posteriors over graphs (i.e., each posterior sums to 1 within each block)

-------

`instructions_outline.pdf` outlines the instructions for Experiment 1 (the footnote "Original" was not shown in the experiment). The instructions for Experiments 2 to 5  were built upon these core instructions (see Table A.1 in the Appendix for an overview and descriptions in the main text for details).

-------

`graphs_overview.pdf` 

![Context 1-18](graphs_overview.pdf)
