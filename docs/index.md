## BIOMED210/CS270 Pharmacogenetics (PGX) Clinical Decision Support (CDS) Tool

### Background
Pharmacogenetics (PGx) represents one of the fundamental steps towards personalized medicine. With the availability of genetic tests for more than 15 years and a significant number of patients having at least one actionable genetic variant, it may seem peculiar that it isn’t more widely adopted in routine clinical practice. Pharmacogenetic tests results can identify opportunities where drugs may need to be modified, if not discontinued, due to a patient’s drug metabolism where it may be either too high or low.

We implemented a minimal viable product (MVP) that leverages the CPIC's API to retrieve the most recent drug-gene guidelines based on input of a drug and genetic phenotype. If the latter is unknown, clinicians can enter the ethnicty of the patient and the most likely genetic phenotype will be displayed in order of probability.

### Team
- [Asrar Mahib Alkrizy](https://profiles.stanford.edu/asrar-alkrizy)
- [Sergey Pavlov](https://profiles.stanford.edu/sergey-pavlov)
- [Cheyenne Ali Sadeghi](https://profiles.stanford.edu/cheyenne-sadeghi)
- [Jordan Matthew Howdges](https://profiles.stanford.edu/jordan-hodges)
- [Brian K Fung](https://profiles.stanford.edu/304676)

### Key features
- Phenotype lookup by gene (for when clinicians forget what phenotypes are available for a particular gene)
- Phenotype lookup by ethnicity (when genetic results aren't available). Will retrieve probabilities for all phenotypes sorted by the most likely on the top and return the guideline that matches the drug entered
- CPIC recommendation lookup by drug & genetic phenotype. 

### Video demonstration
<iframe width="560" height="315" src="https://www.youtube.com/embed/G_gVXigZmr0" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>

### Evaluation Survey
<iframe width="640px" height="480px" src="https://forms.office.com/Pages/ResponsePage.aspx?id=y3NlOXjzaEubyBV1XAxR8_rXTiNBFIBOqTK5xM1GSdZUN1NMWE1JNkg0QzBCWFpBNDRWTTdOTDJKNC4u&embed=true" frameborder="0" marginwidth="0" marginheight="0" style="border: none; max-width:100%; max-height:100vh" allowfullscreen webkitallowfullscreen mozallowfullscreen msallowfullscreen> </iframe>
