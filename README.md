# Casehopper Take-Home Project: Extraordinary Ability Letter

## Background

The O-1 visa is a nonimmigrant visa for individuals who can demonstrate extraordinary ability in their field, whether that be the sciences, arts, business, or athletics. One of the requirements for the O-1 visa application is a letter of recommendation from a peer group that can speak to the applicant's abilities and achievements. This letter serves to provide an objective, independent opinion from experts in the applicant's specific field highlighting how their accomplishments and contributions demonstrate extraordinary talent beyond what is considered standard in their specialty.

The purpose of the peer recommendation is to champion the applicant's achievements and provide specific evidence for United States Citizenship and Immigration Services (USCIS) that the individual is among the small percentage at the very top of those in their field. The letter should explain in clear terms the significance of the applicant's discoveries and techniques so that even non-experts can understand their importance. It should focus on documenting international recognition, groundbreaking research that has advanced the field, and concrete achievements that set the applicant apart rather than speculative promises of future accomplishment. The goal is to compellingly demonstrate the applicant's extraordinary ability worthy of O-1 classification through the perspective of renowned experts familiar with their work.

## Task

In this project, you will be automating the drafting of a reference letter for Tom Blomfield, a current Y-Combinator partner and the ex-CEO/founder of Monzo (one of the largest neobanks in the world). This will be done from the perspective of Matt Clifford, the co-founder and CEO of Entrepreneur First. You will do so by filling a template.

### Template Format

The template for the letter contains placeholders for specific information about the beneficiary (the individual applying for the visa) and the author (the individual writing the letter). The placeholders are enclosed in square brackets (e.g., `[BENEFICIARY NAME]`). The template also includes instructions for filling in the placeholders, enclosed in double square brackets (e.g., `[[Provide another example of an accomplishment or achievement that demonstrates extraordinary ability in the beneficiary's field, based on your research]]`).

Your task is divided into two parts:

1. **Information Extraction**: Using the provided reference documents, extract relevant information to fill in the placeholders in the template. This includes details about the beneficiary's accomplishments, the author's background, and the impact of the beneficiary's work. The documents to be used are listed below:

- **Documents**:

  - Beneficiary's Resume

  - Author's Resume

- **Websites**:

  - Beneficiary's blog/personal website

  - Media covering beneficiary's accomplishments

  - Beneficiary's Wikipedia page

  - Author's company Wikipedia page

  - Author's personal website

  - Media covering author's accomplishments

All documents listed above can be found in the 'files' directory included with this project. All URLs mentioned above can be found in the file called "websites.csv" as table with two columns: **Description** and **Url**. **Description** will contain a brief description of the contents of the page listed and **Url** will contain a single url directing you to the appropriate page. For websites, feel free to only use a subset of the subpages if you deem it appropriate. The selection of the websites need not be done programmatically (you can manually select the pages you want to use). However, the information extraction from the selected websites must be done programmatically. 

2. **Template Completion**: Insert the extracted information into the appropriate placeholders in the template. Ensure that the inserted information makes sense in the context of the surrounding text and that the completed letter is coherent. The output letter should be in markdown format. The process of creating this insertion should be programmatic (i.e., You should write code to fill in the letter rather than filling it yourself).

## Resources

We recommend that you work in Jupyter Notebook using Python, but you are free to use whichever development environment you prefer. As you begin thinking about your approach, you may find it useful to reference the documentation of frameworks such as Langchain, LLAMAindex, and other popular LLM frameworks.

### API Credentials:

As using LLMs normally has an associated cost, we have included credentials to utilize Replicate's API. These can be found in the template notebook attached and can be used to utilize LLAMA2 models. These are ONLY to be utilized while you work on your solution. Unrelated utilization of these will immediately disqualify you for the rest of our recruitment process.

If you need any clarifications about the assessment please email recruiting@casehopper.com
