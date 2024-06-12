# ai-powered-litreview
This repository contains two main components: Abstract Screening and Information Extraction. These tools utilize the GeminiAI model to streamline the process of academic literature review, significantly reducing manual workload and enhancing the efficiency of information extraction from scientific texts.
## Table of Contents
- [Introduction](#introduction)
- [Abstract Screening](#abstract-screening)
- [Information Extraction](#information-extraction)
- [Installation](#installation)
- [Usage](#usage)
- [License](#license)

## Introduction
The proliferation of scientific literature necessitates efficient review mechanisms. This project integrates AI tools with vector databases to automate the screening and extraction of relevant information from academic papers. The two main scripts included are:

Abstract Screening: Takes a CSV file containing titles and abstracts and screens them for relevance.
Information Extraction: Uses the GeminiAI API to extract detailed information from the shortlisted papers.

## Abstract Screening
#Description
The AbstractScreening script processes a CSV file with titles and abstracts of scientific papers. It screens each entry for relevance based on predefined criteria, outputting the results in a new CSV file.

#Input
A CSV file containing titles and abstracts of scientific papers.
#Output
A CSV file with screened results, indicating which papers are relevant and which are not.

## Information Extraction
#Description
The InformationExtraction script utilizes the GeminiAI API to extract detailed information from the shortlisted papers. This includes methodologies, algorithms, and other critical details mentioned in the abstracts.

#Requirements
GeminiAI API Key
#Input
A list of relevant papers from the AbstractScreening output.
#Output
Extracted information saved in a structured format for further analysis.

## Installation
<!-- Content for Installation -->

## Usage
<!-- Content for Usage -->

## License
<!-- Content for License -->
