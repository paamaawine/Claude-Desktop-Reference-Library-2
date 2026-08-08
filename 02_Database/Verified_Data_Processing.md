# Verified Data Processing Libraries

---

## Repository 1

### Name
NumPy

### GitHub
https://github.com/numpy/numpy

### Status
Verified

### Rating
★★★★★

### Purpose
Fundamental numerical computing library for Python.

### Features
- Multi-dimensional arrays
- Matrix operations
- Linear algebra
- Random number generation
- Mathematical functions
- High-performance computing

### Claude Should Study
- Numerical computing
- Matrix operations
- Statistical calculations
- Performance optimisation

### Why We Chose It
NumPy is the foundation of scientific computing in Python and is required by many other libraries.

---

## Repository 2

### Name
Pandas

### GitHub
https://github.com/pandas-dev/pandas

### Status
Verified

### Rating
★★★★★

### Purpose
Powerful data analysis and manipulation library.

### Features
- DataFrames
- CSV import/export
- Excel support
- Data cleaning
- Grouping
- Filtering
- Aggregation

### Claude Should Study
- DataFrames
- Data cleaning
- Report generation
- Statistical analysis

### Why We Chose It
Essential for processing student records, financial reports, questionnaires and statistical datasets.

---

## Repository 3

### Name
Polars

### GitHub
https://github.com/pola-rs/polars

### Status
Verified

### Rating
★★★★★

### Purpose
High-performance DataFrame library.

### Features
- Fast DataFrames
- Lazy evaluation
- Parallel execution
- CSV
- Parquet
- SQL support

### Claude Should Study
- Large dataset processing
- Performance optimisation
- Parallel data analysis

### Why We Chose It
Excellent for processing millions of records much faster than traditional approaches.

---

## Repository 4

### Name
PyArrow

### GitHub
https://github.com/apache/arrow

### Status
Verified

### Rating
★★★★★

### Purpose
Apache Arrow implementation for Python.

### Features
- Columnar data
- Parquet
- Feather
- High-speed data transfer
- Memory efficiency

### Claude Should Study
- Efficient storage
- Data interchange
- Large datasets

### Why We Chose It
Ideal for enterprise applications handling large datasets.

---

## Repository 5

### Name
Dask

### GitHub
https://github.com/dask/dask

### Status
Verified

### Rating
★★★★★

### Purpose
Parallel computing library.

### Features
- Distributed computing
- Parallel processing
- Large DataFrames
- Task scheduling

### Claude Should Study
- Parallel processing
- Large-scale computation
- Performance optimisation

### Why We Chose It
Allows desktop applications to process datasets larger than available memory.

---

## Repository 6

### Name
SciPy

### GitHub
https://github.com/scipy/scipy

### Status
Verified

### Rating
★★★★★

### Purpose
Scientific computing library.

### Features
- Optimisation
- Signal processing
- Statistics
- Linear algebra
- Interpolation

### Claude Should Study
- Scientific computing
- Statistical analysis
- Mathematical modelling

### Why We Chose It
Provides advanced mathematical tools beyond NumPy.

---

## Repository 7

### Name
datatable

### GitHub
https://github.com/h2oai/datatable

### Status
Verified

### Rating
★★★★★

### Purpose
Fast tabular data processing.

### Features
- Large datasets
- Fast joins
- Filtering
- Aggregation
- CSV processing

### Claude Should Study
- High-speed data manipulation
- Large file processing

### Why We Chose It
Suitable for enterprise applications processing extensive datasets.

---

## Repository 8

### Name
petl

### GitHub
https://github.com/petl-developers/petl

### Status
Verified

### Rating
★★★★★

### Purpose
Extract, Transform and Load (ETL) library.

### Features
- Data extraction
- Data transformation
- CSV
- Excel
- SQL
- JSON

### Claude Should Study
- ETL pipelines
- Data migration
- Data cleaning

### Why We Chose It
Useful for importing and transforming data from multiple sources.

---

## Repository 9

### Name
vaex

### GitHub
https://github.com/vaexio/vaex

### Status
Verified

### Rating
★★★★★

### Purpose
Out-of-core DataFrame library.

### Features
- Billion-row datasets
- Virtual columns
- Memory mapping
- Fast filtering

### Claude Should Study
- Big data processing
- Memory-efficient analysis

### Why We Chose It
Handles extremely large datasets without exhausting system memory.

---

## Repository 10

### Name
pyjanitor

### GitHub
https://github.com/pyjanitor-devs/pyjanitor

### Status
Verified

### Rating
★★★★★

### Purpose
Data cleaning library for Pandas.

### Features
- Clean column names
- Remove duplicates
- Data transformation
- Missing value handling

### Claude Should Study
- Data cleaning
- Data preparation
- Data quality

### Why We Chose It
Makes datasets cleaner and easier to analyse before reporting or machine learning.

---

## Summary

### Primary Recommendation
- NumPy
- Pandas
- SciPy
- Polars

### Secondary Recommendation
- Dask
- PyArrow
- datatable
- petl
- vaex
- pyjanitor

### Best Use Cases
- Student information systems
- Senate approval records
- Transcript processing
- Research data analysis
- Financial reporting
- Questionnaire analysis
- Statistical software
- Enterprise reporting
- ETL workflows
- Big data applications

# Verified Data Processing Standards

Claude should use reliable and well-tested Python tools for data processing.

## Pandas

Pandas should be the preferred library for structured tabular data processing.

Suitable tasks include:

- Data cleaning
- Filtering
- Sorting
- Grouping
- Merging
- Reshaping
- Missing-value handling
- Descriptive statistics
- Import and export

GitHub Repository:

https://github.com/pandas-dev/pandas

Status: APPROVED

## NumPy

NumPy should be used for numerical operations and array-based computation.

Suitable tasks include:

- Numerical arrays
- Mathematical operations
- Matrix operations
- Statistical calculations
- Numerical transformations

GitHub Repository:

https://github.com/numpy/numpy

Status: APPROVED

## Data Cleaning

Imported data should be checked before analysis.

Check for:

- Missing values
- Duplicate records
- Invalid values
- Incorrect data types
- Inconsistent categories
- Impossible values
- Incorrect dates

## Missing Values

Missing values should be handled according to the nature of the data.

Possible approaches include:

- Removing records
- Replacing values
- Forward filling
- Backward filling
- Statistical imputation

The chosen method should be documented.

## Data Types

Columns should use appropriate data types.

Examples include:

- Integer
- Float
- String
- Boolean
- Date
- DateTime
- Categorical

Correct data types improve processing and reduce errors.

## Duplicate Records

Check for duplicate records where duplicates could affect the results.

Do not automatically delete duplicates without determining whether they are genuine duplicates.

## Data Validation

Validate important datasets before analysis.

Check:

- Row counts
- Column names
- Data types
- Value ranges
- Required fields
- Duplicate records
- Missing values

## Large Datasets

Large datasets should be processed efficiently.

Consider:

- Chunked processing
- Filtering before loading
- Efficient data types
- Vectorised operations
- Database queries

Avoid unnecessary copies of large datasets.

## Import and Export

Common formats include:

- CSV
- Excel
- JSON
- Parquet
- SQL databases

Validate imported files before processing them.

## Reproducibility

Data-processing steps should be reproducible.

Important transformations should be documented or implemented in reusable functions.

## Data Processing Checklist

- [ ] Appropriate library selected
- [ ] Data types checked
- [ ] Missing values checked
- [ ] Duplicate records checked
- [ ] Invalid values checked
- [ ] Data validated
- [ ] Large datasets handled efficiently
- [ ] Transformations documented
- [ ] Import and export tested
- [ ] Processing is reproducible
