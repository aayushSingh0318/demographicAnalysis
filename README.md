

# Global Population Analysis

## Project Overview

This repository contains a Jupyter notebook `hwk6-1.ipynb` that conducts a detailed analysis of global population data. The primary dataset used in this analysis is `population.json`, which includes population statistics across different geographies and time periods.

Creating Interactive Charts to Visualize Population Shifts over Time with Altair
Baby boomers (often shortened to boomers) are the demographic cohort following the Silent Generation and preceding Generation X. The generation is generally defined as people born from 1946 to 1964, during the post–World War II baby boom. The term is also used outside the United States but the dates, the demographic context and the cultural identifiers may vary. The baby boom has been described variously as a "shockwave"and as "the pig in the python." Baby boomers are often parents of late Gen Xers and Millennials. 

Let us explore this "shockwave" by examining the US Census data available via the vega datasets package. We'll start by doing some data engineering to add a column in our population data to denote generational membership, then we will juxtapose the sex distribution of the population using a brush and linking technique we studied in the lab. Finally we will add a slider to animate the transition through time.


## Dataset

The `population.json` file contains structured data on population metrics. [Add specific details about the dataset, such as the keys included, any nested structures, the time range of the data, and the source of the data.]

## Prerequisites

Ensure you have the following requirements installed:

- Python 3.x
- Jupyter Notebook

## Dependencies

The following Python libraries are required to run the notebook:

- pandas
- json

You can install these libraries using `pip`:

```bash
pip install pandas
