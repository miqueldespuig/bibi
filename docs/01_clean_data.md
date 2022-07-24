# Data Cleaning

## Introduction

_Explain the common data problems and how have been solved_

## Common data problems

* Data type constrains
    * Text
    * Numerical
    * Datetime
    * Categorical 
* Data range constrains
* Uniqueness constrains

Text and categorical data problems:
* Membership constrains
* Categorical variables
    * Inconsistent categories
    * Remapping categories
* Cleaning text data

Advanced data problems:
* Uniformity
* Cross field validation
* Completeness
    * Missing Completely at Random MCAR
    * Missing at Random MAR
    * Missing Not at Random MNAR

Record linkage:
* Minimun edit distance, how close 2 strings are
* String similarity replacements --> Use string similarity to re-classify categories fuzzywuzzy process.extract
* Record Linkage, Generate Pairs. import recordLinkage
