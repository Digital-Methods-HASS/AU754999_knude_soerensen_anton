# Group 33: Sentiment towards immigrant workers in Denmark: Parliamentary discourse and the oil crisis of 1973 and 1978

Group members: Benjamin Lykke Christensen & Anton Knude Sørensen

This repository contains the digital product for Group 33’s final project in Digital Archives and Methods.

## Research question

How did the sentiment towards immigrant workers (‘gæstearbejdere’/’fremmedarbejdere’) in Denmark change in the Danish Parlament (Folketinget) in relation to the oil crisis of 1973 and 1978, and is the Danish sentiment analysis tool Sentida sufficient to analyse this change in sentiment?

## Repository structure

- `data/`: Contains selected datasets from Mediestream, used to extract benchmark values for the positive and negative sentiment regardng each keyword. The articles have been manually transcribed into Google Sheet, and then converted into csv files, which could easily be uploaded in RStudio. data/ also contains datasets from Folketingstidende Forhandlinger. The datasets have been restructured with the kind help of Max Odsbjerg Petersen. This link will lead you to a GitHub with a thorough go through of how to restructure the datasets from Folketinget: https://github.com/KUBDatalab/folketingsreferater/blob/main/ekstraher_funktionen.R
   
- `script/`: R script used for keyword frequency, but mainly for Sentida analysis

## Data

The datasets from Folketingstidende are from four years: 1970, 74, 78 and 80. This covers a period of ten years, with 1970 being a year still with a booming economy, and the subsequent years being affected by the oil crisis.

## How to reproduce the analysis

1. Open the repository in RStudio.
2. Install or load the R packages listed in the scripts.
3. Use the CSV files in `data/`.
4. Run the scripts in numerical order from `scripts/`.

## License

The R scripts and project code written by the authors are licensed under the MIT License.

The authors’ own metadata, manual coding, derived tables, figures and documentation are licensed under CC BY 4.0. See `DATA_LICENSE.md`.

Original newspaper texts, Mediestream source images, PDFs, facsimiles and infrastructure are not covered by these licenses. They are historical source materials accessed through Mediestream. The repository does not redistribute Mediestream PDFs or newspaper facsimiles.

## Limitations

The corpus is shaped by Mediestream search results. Because of copyright, we could not use a tool to download large datasets containing files from Mediestream, unless they were more than 140 years old. We could therefore not make a thorough sentiment comparison between the data folk Folketinget and large datasets from Mediestream.
