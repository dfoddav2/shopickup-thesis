# shopickup-thesis

Accompanying repository of the Shopickup project specifically for writing an IMC Krems BSc thesis in the topic. The thesis' main focus is the optimal integration of multiple shipping provider APIs into a singular system.

The application code can be found on the [following repository](https://github.com/dfoddav2/shopickup), however it is not publicly available at this time, due to the project's product nature. To gain access to the code, please contact me directly.

> [!IMPORTANT]  
> The following deadlines are set by IMC Krems and must be strictly followed:
>
> - **Thesis Proposal / Expose Submission:** 15.01.2026
> - **Thesis Submission:** 05.05.2026

## Recommended Setup

Firstly, make sure you have a LaTeX distribution installed on your system. For Windows, MiKTeX is a popular choice, while Mac users often go for MacTeX. Linux users can install TeX Live via their package manager. I will be using MacTeX for this guide.

```brew
brew install --cask mactex
```

In addition, you will need to install Zotero and the Better BibTeX plugin for reference management.

```brew
brew install --cask zotero
brew install --cask zotero-better-bibtex
```

I also recommend you install the extensions outlined in the [extensions.json](.vscode/extensions.json) file if you are using VSC as your editor.

## Starting concept

The following possible research questions are to be explored in the thesis, with each of the topic's first question being the main broader research question and the second question being a more specific sub-question to explore:

### Integration & Extensibility

1. What is the most suitable architecture for a common, extensible API adapter that integrates multiple shipping carriers with heterogeneous APIs, data formats and workflows, and what are the advantages and disadvantages of the candidate architectures?
2. What is the most appropriate architecture for a platform-agnostic integration layer that enables the application to support multiple e-commerce platforms, and what are the advantages and disadvantages of alternative approaches (adapter pattern, middleware, platform-specific plugins)?

### Evaluation & Analytics

1. How can a data analytics dashboard be designed such that merchants receive actionable insights into shipping performance and customer preferences while balancing usability, scalability, and real-time needs? - What are the advantages and disadvantages of alternative dashboard architectures (real-time vs batch, pre-aggregated vs raw access)?
2. How can the effectiveness of such a system in shipping operations be objectively evaluated, which KPIs should be used, and what are the advantages and disadvantages of different evaluation methods (A/B testing, before–after studies, qualitative interviews)?

## Relevant Guidelines

The IMC Krems thesis guidelines can be found under the directory `./guidelines/`. Namely, the following documents:

- [Cover Page Template](./guidelines/cover-page-template.pdf): The official cover page template provided by IMC Krems.
- [Manual for the formal composition of scholarly papers](manual-for-the-formal-composition-of-scholarly-papers.pdf): The official manual provided by IMC Krems for writing scholarly papers. Includes formatting guidelines, structure recommendations, and citation styles.
- [Regulation for Bachelor Papers and Bachelor Examination](regulation-for-bachelor-papers-and-bachelor-examination.pdf): The official regulation document provided by IMC Krems outlining the rules and requirements for Bachelor papers and examinations. More in dept information legal aspects of the thesis writing and examination process.
