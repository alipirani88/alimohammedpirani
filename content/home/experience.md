+++
# Experience widget.
widget = "experience"  # See https://sourcethemes.com/academic/docs/page-builder/
headless = true  # This file represents a page section.
active = true  # Activate this widget? true/false
weight = 40  # Order that this section will appear.

title = "Experience"
subtitle = ""

# Date format for experience
#   Refer to https://sourcethemes.com/academic/docs/customization/#date-format
date_format = "Jan 2006"

# Experiences.
#   Add/remove as many `[[experience]]` blocks below as you like.
#   Required fields are `title`, `company`, and `date_start`.
#   Leave `date_end` empty if it's your current employer.
#   Begin/end multi-line descriptions with 3 quotes `"""`.


[[experience]]
  title = "Bioinfo-Computational Biologist Intermediate"
  company = "Snitkin Lab, University of Michigan"
  company_url = "https://thesnitkinlab.com/"
  location = "Ann Arbor, MI"
  date_start = "2021-09-01"
  date_end = ""
  description = """
  - Developed protocols/pipelines to streamline bioinformatics analysis of multi-omics data for multiple collaborative large scale public health projects.
    <details>

    <summary>Selected Protocols</summary>

    <br>

    - In collaboration with sequencing core, standardized quality control and contamination detection workflow - [QC'd](https://github.com/alipirani88/QC-d) to detect data quality issues such as library preparation, plate cross contamination and barcode mismatch. Workflow includes assembly, mapping and annotation workflow for an informed QC decision making process.
    - Developed phylo-genomic analysis protocol with [SNPKIT](https://alipirani88.github.io/snpkit/) to streamline epidemiology, transmission, GWAS and feature extraction machine learning workflows.
    - Established APIs and data mining protocols to download publicly available sequencing data and incorporated into the workflows to provide global context.
    - Developed Nanopore basecalling, hybrid assembly and variant calling analysis [workflow](https://github.com/alipirani88/Nanosake) for bacterial strains. 
    - Developed a workflow called [SAMOSA](https://github.com/alipirani88/samosa) that catalogues genomic signatures for a given species and detects mixed strains from population sequencing data. It has been successfully implemented to track recurrent and mixed C. difficile infections in longitudinal patient data.
   
   <br>
   </details> 

  - Worked collaboratively in a cross functional environment to provide support and mentorship to graduates and post-docs, bioinformatics data interpretation to collaborators and clinicians. 
  - Generated hypothesis and led proof of concept pilot studies for grant proposals. (applying novel algorithms to simulated and clinical datasets)
  - Designed and set up semester long [Genomic Epidemiology course](https://github.com/Snitkin-Lab-Umich/MICRO582-EPI582-Winter-2023) for UM School of Public Health.

  <details>

  <summary>Selected Projects</summary>

  <br>

  - **Evaluated the use of SNP thresholds, as well as a novel threshold-free approach to infer transmission linkages in high-transmission setting:** Performed genomic and phylogenetic analysis of individual clusters of KPC-Kp samples collected from 256 patients in an intervention study at a long-term acute care hospital in USA.
  - **Identify colonisation risk factors for the regional spread of 4 antibiotic resistant organisms (ARO) in Nursing facilities (NF) and acute care hospitals (ACHs):** Performed genomic and phylogenetic analysis to identify risk factors associated with regional spread of multi drug resistant organisms (MDRO's). Developed workflows to detect horizontal gene transfers between these MDRO's.  
  - **Characterize infection kinetics and bacterial replication rates during bacteremia for six gram negative pathogens to gain a better understanding of bacterial physiology during infection.** Extended previously developed PTR workflow to Serratia marcescens, Klebsiella pneumoniae, Enterobacter hormaechei, Citrobacter freundii, and Acinetobacter baumannii to study their growth dynamics during bacteremia in a mouse model (spleen, kidney and liver).
  - **Data pre-processing for more informative bacterial GWAS:** Performed bioinformatics analysis for an R package called prewas to standardize preprocessing of genomic variants for bacterial GWAS studies. Prewas can be directly applied to the SNPKIT outputs for downstream GWAS studies. 

  </details>


  """

[[experience]]
  title = "Bioinfo-Computational Biologist Associate Associate"
  company = "Snitkin Lab, University of Michigan"
  company_url = "https://thesnitkinlab.com/"
  location = "Ann Arbor, MI"
  date_start = "2020-04-01"
  date_end = "2021-09-01"
  description = """
"""

[[experience]]
  title = "Research Computer Specialist"
  company = "Snitkin Lab, University of Michigan"
  company_url = "https://thesnitkinlab.com/"
  location = "Ann Arbor, MI"
  date_start = "2015-03-01"
  date_end = "2020-04-01"
  description = """
  - Established computational infrastructure from the ground up to optimally store and retrieve sequence/analysis data for multiple collaborative research projects. 
  - Developed scalable bioinformatics analysis pipelines for bacterial sequencing projects (large cohort and longitudinal studies)
  - Developed strategies to visualize processed genomics and phenotypic metadata, provide variant interpretation and diagnostics using R, Python and IGV.
  - Designed, taught and set up Bioinformatics course material for 3-day, hands-on [Microbial Genomics workshop.](https://comparative-genomics.readthedocs.io/en/latest/index.html)
  - Provided Bioinformatics support and mentorship to graduates and post-docs in their research projects.
  <details>

  <summary>Selected Projects</summary>

  <br>

  -	**Identify factors associated with Hospital-Onset Methicillin-Resistant Staphylococcus aureus Bloodstream Infections:** Performed genomic and phylogenetic analysis of Hospital-Onset methicillin-susceptible S. aureus (MSSA) and Hospital-Onset methicillin-resistant S. aureus (MRSA) BSIs for 2009–2013 at 2 hospitals.
  -	**Identify the role of patient transfers between hospitals in a year-long regional outbreak of multidrug-resistant Klebsiella pneumoniae:** Performed phylogenomic analysis that helped traced the spread of infection and transmission network across local health care network. 
  -	**Determine the role of growth rate to successful colonization and persistence of Uropathogenic Escherichia coli (UPEC) in urinary tract infections:** Developed a workflow to estimate peak-to-trough ratio from sequencing data and applied a linear regression model to calculate doubling time from PTR to determine how rapidly UPEC strains divide during human UTIs.
  - **Identify common transcriptional features of uropathogenic Ecoli upregulated in UTI:** Performed bioinformatics analysis (quality control, variant calling, illumina assembly/annotation, pacbio long read assembly) and RNA seq analysis of UPEC strains isolated from 14 UTI patients.

  </details>
  """
[[experience]]
  title = "Graduate Research Assistant/Summer Intern 2014"
  company = "Jordan Lab, Georgia Institute of Technology"
  company_url = "http://jordan.biology.gatech.edu/page/"
  location = "Atlanta, GA"
  date_start = "2014-01-01"
  date_end = "2015-01-01"
  description = """
  - Performed a systematic comparison of different typing schemes available for Bordetella pertussis and developed a novel wgMLST scheme using [Bionumerics (Applied Maths)](https://www.applied-maths.com/bionumerics). 
  <details>
  <summary>more</summary>
  In collaboration with Pertussis lab at CDC, performed genome assembly and analyzed large structural genomic arrangements in regional B. Pertussis outbreak samples collected from Vermont and California in 2014. Deployed new features to the legacy software Meningococcus Genome Informatics Platform (MGIP), an online platform used by CDC for Meningococcus surveillance using PHP and MYSQL stack.
  </details>
  """
[[experience]]
  title = "Software Engineer"
  company = "Capgemini"
  company_url = "https://www.capgemini.com/"
  location = "Bangalore, India"
  date_start = "2012-03-01"
  date_end = "2013-07-01"
  description = """
  Web application development with C# OOP, MS SQL and ASP.NET stack.
  <details>
  <summary>more</summary>
  Developed an in-house web application software called KMtool (Knowledge management tool). Defined use cases with stakeholders, developed a backend database from scratch in liason with the core database team, designed front end layout and SQL query routines to populate and visualize.
</details>
  """

+++
