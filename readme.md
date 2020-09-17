# SAS Seminar - September 2020

## Matching of commonly used datasets

The main datasets use different firm identifiers:

- gvkey (Compustat)
- permno (Crsp)
- Central Index Key (CIK) (Audit Analytics, SEC filings)
- IBES Ticker (IBES)

Additionally, also the ticker symbol and Cusip/sedol are commonly used, as well as the firm name itself. We will look into matching these datasets.

## Topics

In this seminar we will look into matching these datasets:

#### Header vs historical values - Compustat - [1_compustat.sas](1_compustat.sas)

#### Matching Compustat with Audit Analytics -  [2_audit_analytics.sas](2_audit_analytics.sas)

#### Matching Compustat - CRSP - IBES - [3_ibes.sas](3_ibes.sas)

## SAS Studio

We will be using SAS Studio hosted by WRDS. This way, you don't need a local copy of SAS installed. Also, it is convenient to visually inspect the different datasets on WRDS. (The interface allows you to browse the datasets and click/view these.)

Link to SAS Studio (WRDS login required): [https://wrds-cloud.wharton.upenn.edu/SASStudio/index](https://wrds-cloud.wharton.upenn.edu/SASStudio/index)

### SAS tutorials

For some basic SAS tutorials, see [https://github.com/JoostImpink/SAS-bootcamp](https://github.com/JoostImpink/SAS-bootcamp)

