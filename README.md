# Clinical Data Sources
We are assembling a repository of clinical data sources (Electronic Health Record, Clinical trials, Imaging etc.) that are either public or have low friction application processes. If you have any comments, corrections, or know of any additional sources, please add it as a pull request.

Types of data: 

* Patient Demographics: P
* Lab tests: L
* Textual Patient Notes: T
* Imaging: I
* Other: O


| Name        | Description           | Data Types | Patient Count | Ease of Access  | Publication/Citation Guidelines |
| ----------- |:-------------------:| ------------ | ------------- | --------------- | ----------- |
| [MIMIC](https://mimic.physionet.org/)       | MIMIC is an openly available dataset developed by the MIT Lab for Computational Physiology, comprising deidentified health data associated with ~40,000 critical care patients. It includes demographics, vital signs, laboratory tests, medications, and more.| P, L, T | ~45,000 | Simple Application | [Link](http://dx.doi.org/10.1038/sdata.2016.35)|
| [Physionet 2012](https://physionet.org/challenge/2012/) | Tthe focus of the PhysioNet/CinC Challenge 2012 is to develop methods for patient-specific prediction of in-hospital mortality. Participants will use information collected during the first two days of an ICU stay to predict which patients survive their hospitalizations, and which patients do not. | P, L | 12,000 ICU stays | Public | [Link](https://www.ncbi.nlm.nih.gov/pmc/articles/PMC3965265/)|
| [i2b2](https://www.i2b2.org/NLP/DataSets/Main.php) | In order to enhance the ability of natural language processing (NLP) tools to prise increasingly fine grained information from clinical records, i2b2 has previously provided sets of fully deidentified notes from the Research Patient Data Repository at Partners HealthCare for a series of NLP Challenges organized by Dr. Ozlem Uzuner.  We are pleased to now make those notes available to the community for general research purposes. At this time we are releasing the notes (~1,500) from the first four i2b2 Challenges as i2b2 NLP Research Data Sets. A similar set of notes from the most recent i2b2 Challenge will be released on the one year anniversary of that Challenge.|T | ~1,500|Simple Application (DUA) | [Link (depends on data usage)](https://www.i2b2.org/NLP/DataSets/Main.php)
| [PRO-ACT ALS](https://nctu.partners.org/ProACT/)| PRO-ACT provides users with easy access to: 1) Over 10,700 fully de-identified clinical patient records, 2) Placebo and treatment-arm data from 23 Phase II/III clinical trials, 3) Demographic, lab, medical and family history, and other data elements, 4) More than 10 million longitudinally collected data points | P, L | 10,700 | Simple Application | [Link](https://nctu.partners.org/ProACT/Document/DisplayLatest/6)
| [Cancer Imaging Archive](http://www.cancerimagingarchive.net/) | TCIA is a service which de-identifies and hosts a large archive of medical images of cancer accessible for public download. The data are organized as “Collections”, typically patients related by a common disease (e.g. lung cancer), image modality (MRI, CT, etc) or research focus. DICOM is the primary file format used by TCIA for image storage. Supporting data related to the images such as patient outcomes, treatment details, genomics, pathology, and expert analyses are also provided when available. | I, some studies have others | Most studies < 100 | Many Public | [Usage](https://wiki.cancerimagingarchive.net/display/Public/Data+Usage+Policies+and+Restrictions) [Publication](https://www.ncbi.nlm.nih.gov/pubmed/23884657)
| [National Biomedical Imaging Archive](https://imaging.nci.nih.gov/ncia/login.jsf) | Welcome to the National Biomedical Imaging Archive (NBIA). NBIA is a searchable repository of in vivo images that provides the biomedical research community, industry, and academia with access to image archives to be used in the development and validation of analytical software tools that support: Lesion detection and classification, Accelerated diagnostic imaging decision, Quantitative imaging assessment of drug response | I | Most studies < 100 | Many Public | NA
| [Open Access Series of Imaging Studies (OASIS)](http://www.oasis-brains.org/) | The Open Access Series of Imaging Studies (OASIS) is a project aimed at making MRI data sets of the brain freely available to the scientific community. By compiling and freely distributing MRI data sets, we hope to facilitate future discoveries in basic and clinical neuroscience. OASIS is made available by the Washington University Alzheimer’s Disease Research Center, Dr. Randy Buckner at the Howard Hughes Medical Institute (HHMI) at Harvard University, the Neuroinformatics Research Group (NRG) at Washington University School of Medicine, and the Biomedical Informatics Research Network (BIRN). | I | 416 (study 1), 150 (study 2) | Public | [Study 1](https://www.ncbi.nlm.nih.gov/pubmed/17714011) [Study 2](https://www.ncbi.nlm.nih.gov/pubmed/19929323) 


<p xmlns:dct="http://purl.org/dc/terms/" xmlns:vcard="http://www.w3.org/2001/vcard-rdf/3.0#">
  <a rel="license"
     href="http://creativecommons.org/publicdomain/zero/1.0/">
    <img src="http://i.creativecommons.org/p/zero/1.0/88x31.png" style="border-style: none;" alt="CC0" />
  </a>
  <br />
  To the extent possible under law,
  <a rel="dct:publisher"
     href="https://github.com/EpistasisLab/ClinicalDataSources">
    <span property="dct:title">Brett Beaulieu-Jones</span></a>
  has waived all copyright and related or neighboring rights to
  <span property="dct:title">Open or Easy Access Clinical Data Sources for Biomedical Research</span>.
This work is published from:
<span property="vcard:Country" datatype="dct:ISO3166"
      content="US" about="https://github.com/EpistasisLab/ClinicalDataSources">
  United States</span>.
</p>
