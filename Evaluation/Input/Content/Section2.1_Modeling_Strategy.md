The general workflow for building an adult PBPK model has been described by Kuepfer et al. ([Kuepfer 2016](# 5 References)). Relevant information on the anthropometry (height, weight) was gathered from the respective clinical study, if reported. Information on physiological parameters (e.g. blood flows, organ volumes, hematocrit) in adults was gathered from the literature and has been incorporated in PK-Sim<sup>®</sup>) as described previously ([Willmann 2007](# 5 References)). The  applied activity and variability of plasma proteins and active processes that are integrated into PK-Sim® are described in the publicly available 'PK-Sim<sup>®</sup> Ontogeny Database Version 7.3' ([PK-Sim Ontogeny Database Version 7.3](# 5 References)).

The PBPK model was developed based on clinical data of healthy, non-obese, adult subjects obtained from the literature, covering different single doses of triazolam administered intravenously or orally as immediate release tablet in the fasted state. 

Unknown parameters were simultaneously optimized using all available PK data, in particular:

-  6 data sets following single IV administration of 5 different doses of triazolam (0.125 mg, 0.25 mg, 0.5 mg, 0.75 mg, 1 mg)
- 22 data sets following single PO administration of 3 different doses of triazolam as immediate release tablet (0.125 mg, 0.25 mg, 0.5 mg)

Structural model selection was mainly guided by visual inspection of the resulting description of data and biological plausibility. The following parameters were identified using the Parameter Identification module provided in PK-Sim<sup>®</sup> and MoBi<sup>®</sup> ([Open Systems Pharmacology Documentation](# 5 References)):

- `Dissolution time (50% dissolved)`
- `Dissolution shape`
- `Specific intestinal permeability`
- `Mucosa permeability (interstitial<->intracellular)`
- `Lipophilicity`
- `Metabolizing Enzyme - CYP3A4 - kact`

Details about input data (physicochemical, *in vitro* and clinical) can be found in [Section 2.2](#22-Data).

Details about the structural model and its parameters can be found in [Section 2.3](#23-Model-Parameters-and-Assumptions).


