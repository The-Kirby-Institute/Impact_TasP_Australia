# Impact and effectiveness of U=U on HIV in Australia

This project uses a simple analysis to calculate the impact and
cost-effectiveness of early initiation of antiretroviral therapy (ART) to
achieve undetectable viral load and untransmissable HIV (U=U) which is also
known as treatment-as-prevention (TasP). 

All calculations are primarily conducted using R (version 4.2.2) with associated
packages (svglite 2.1.0; captioner 2.2.3; cowplot 1.1.1; scales 1.2.0; forcats
0.5.1; stringr 1.4.0; dplyr 1.0.9; purrr; 0.3.4; readr 2.1.2; tidyr 1.2.0;
tibble 3.1.8; ggplot2 3.3.6; tidyverse 1.3.2). Please report an issue if you
want to run the code or contact Rgray@kirby.unsw.edu.au.  The code will be
updated as required to correct issues. Please check for updated versions
periodically.

**Repository owner:** Richard T. Gray; [github/leftygray](https://github.com/leftygray); 
[orcid.org/0000-0002-2885-0483](https://orcid.org/0000-0002-2885-0483)

**Affiliation:** [_The Kirby Institute_](https://kirby.unsw.edu.au/), UNSW Sydney, Sydney NSW 2052, Australia

**For any inquiries, please contact Rgray@kirby.unsw.edu.au** or flag an issue.

### Code summary and manuscript

The code for the project calculations has been incorporated into a Quarto
(version 1.3.326) markdown document `Impact_Tasp_Australia-skeleton.qmd`. This
document forms a skeleton manuscript for submission to a peer-reviewed journal
and is in some ways a preprint. All the materials required to run the markdown
script to reproduce the manuscript results and figures are included in this
repository including the references and CSL file. 

Cleaned data inputs used for the calculations and the final results are
available in the `output` directory. The script reads in two `.csv` input files
and saves all the script variables and calculation results in three dated `.Rda`
files.  Summary results and figures are saved in the `outputs\figures` directory
with dated file names with the date corresponding to the input files.

### Disclaimer

This code has been made publicly available for transparency and replication
purposes. We take no responsibility for results generated with code and their
interpretation but are happy to assist with its use and application. 
