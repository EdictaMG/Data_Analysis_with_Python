# Business strategy on discounts
This repository documents a project working with raw data, cleaning and checking data for quality, and conducting analyses for a final recommendation to a fictive company Board.

I sought to answer the following two questions:
1. **Primary question:** Is it beneficial to the business' strategy to discount products?
2. **Secondary question:** How could data collection be improved?

## Situation
Eniac is a Europe-based company that sells tech products and accessories.  The company has an ongoing debate on whether or not it is beneficial to discount products.

On the one hand, the company's Marketing Team Lead believes discounts are beneficial in the long-run and that discounts improve customer acquisition, satisfcation and retention, and allow the company to grow.

On the other hand, the company's Board is worried about offering aggressive discounts.  The recent quarterly results showed an increase in orders placed, but a decrease in total revenue.  They prefer that the company positions itself in the quality segment rather than competing to offer the lowes prices in the market.

## Files
**data**
- **Eniac_raw_data:** raw data files
- **Eniac_clean_data:** cleaned data files
- **Eniac_merged_tables:** **selection of cleaned data files (tables) merged

**scripts**
- **Eniac_data_exploration:** notebooks exploring the raw data files
- **Eniac_exploration_cleaning:** notebook further exploring data, cleaning and filtering
- **Eniac_category_creation:** notebook exploring and assigning sub-categories and categories to products
- **Eniac_analyses:** notebook analysing the data to answer business questions
- **Eniac_data_development:** notebook tracing data cleaning process (start to end data size)

**documentation**
- **Eniac_data_column_description:** description of each column in the original (raw) data files
- **Eniac_presentation:** slides used for a 5 minute presentation on position regarding discounts as well as briefly data quality
- **Eniac_schemas:** schemas of original (raw) data files, cleaned data files and merged tables

## Using the files
- Save data files and notebooks to Google Drive
- Update urls (and reference file/table names) in all Colab notebooks (first section of each notebook) so that link is made to where files were actually saved
- To be able to access each data file in Google Drive, must copy file link with sharing rights (editor)

## Languages and Libraries Used
- Python (3.10.12)
- Pandas (2.2.2)
- Numpy (1.26.4)
- Matplotlib (3.8.0)
- Seaborn (0.13.2)

## Tools used
- Google Colab (or Jupyter) for notebooks
- Google Drive
