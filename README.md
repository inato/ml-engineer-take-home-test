# Inato ML Engineering technical assignment

## How to Successfully Complete this Technical Assignment

1. Clone the repository provided (do **not** fork it)
2. Publish your code on your GitHub (or Gitlab, or whatever...)
3. Send us the link and tell us approximatively how much time you spent on this assignment

Note that the test should take no more than 3 hours to complete.

## Guidelines for Success

To ensure success and demonstrate your abilities, please adhere to the following guidelines:

- Start with a simple approach to have a baseline of results for comparison
- Share your code using a Jupyter notebook 
- Your code should be standalone
- The last state of your code should be production ready
- Prefer making your code production ready and your models evaluation insightful than multiplying the iteration to improve your model performance


## Brief 

- Pharmaceutical labs often write lengthy and complex clinical trial documents (protocols). At the same time, principal investigators (PIs) have written profiles detailing their capabilities and experiences (resumes). The challenge is, matching principal investigators to trials manually is time-consuming and might miss out on potential matches.

*Goal:*
Based on the input data, develop an algorithm that, provided with a trial protocol, can suggest the top 2 principal investigators based on the similarity of the provided textual documents.


## Input data details

**Principal investigators's resumes**
- 8 "resume.txt" files
- A principal investigator's resume is a document that highlights the researcher’s qualifications, experience, and accomplishments in conducting clinical or scientific research, emphasizing their expertise, leadership in previous studies, and contributions to the scientific community. It serves to demonstrate the investigator's capability and expertise to lead a research project or clinical trial, ensuring adherence to the research plan, ethical guidelines, and regulatory compliance.

**Trial protocols**
- 4 "protocol.txt" files
- A trial protocol is a detailed document that outlines the objectives, design, methodology, statistical considerations, and organization of a research project, typically in the context of clinical trials in healthcare. It serves as a blueprint that guides the conduct of the trial and ensures consistency, regulatory compliance, and ethical practice across all study sites.

**Validation**
- validation.csv
- This files provides you with final ground truth for the matching (was this site eventually selected for the trial or not). It also gives you the therapeutic area of the trial and the specialty of the principal investigator.

## Enjoy the assignment and good luck! ##
