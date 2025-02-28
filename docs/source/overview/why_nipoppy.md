# Why Nipoppy?

This is why Nipoppy was created.

It is a result of data-wrangling PTSD from our own experiences as data managers and researchers. Nipoppy helps researchers to translate FAIR principles into practice by providing a step-by-step protocol together with a specification and Python package to navigate the steps of data curation, processing, tracking, and more!

Consider the following premise: there is a newly collected (or shared or downloaded) dataset with (supposedly) N subjects with (somewhat complete) imaging and tabular (demographic and clinical) data that needs to be 1) processed 2) analyzed and 3) published ASAP (reviewer 2 is waiting!).

As it turns out, you are the chosen (or bravely volunteered - in that case you probably are not fully informed on acquired data) person to manage all these tasks and you have been provided with a path to a directory on harddrive (local or external or cloud). The drive contains both large imaging files and a set of spreadsheets with inspired data organizational principles and _NaM1ng_eCcEntriCit1es_.

If this sounds (too) familiar, then we empathize with your discombobulation, overwhelm, and frustration. As you stare into the data dump, depending on level of the documentation, you may be faced with several questions:

- How many subjects are recruited?
- Do we have information on multiple visits/follow-ups?
- What data types from imaging and non-imaging assessments are available?
- How should I name and organize imaging and tabular data?
- How do I process all the data in a reproducible manner?
- How do I track availability, missing values and data updates?
- How do I generate analysis-ready data for my paper?

If this is hard enough for a single dataset, imagine coordinating these efforts to ensure consistent data curation and processing across multiple datasets! Even when the data are in [BIDS](https://bids.neuroimaging.io/) (bless the standard and its maintainers), there are a number of questions that a full study processing adventure needs to address.

Given the heterogeneity in data, tools, and usage practices, we don’t think there is one technical solution that fits all. Thus, Nipoppy tries to engage with the users to show and instill best-practices that would empower them to make better decisions for their custom research workflows. We hope to proliferate [FAIR](https://www.go-fair.org/fair-principles/) datasets in the global community - neuroimaging and beyond - striving towards more open, reproducible, and translational neuroscience research.

Or you can just use it to sleep better after a day of data wrangling…
