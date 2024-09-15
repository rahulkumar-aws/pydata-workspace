# Introduction

Sample Data Work with Pandas.

## The Contents of "Effective Pandas"

### 1. Installation

**Create Virtual Environment**
```bash
python -m venv .venv
```
**Activate Virtual Environment**
```bash
source venv/bin/activate
```
**How to write requirements.txt**
```python
###### Requirements without Version Specifiers ######
nose
nose-cov
beautifulsoup4
#
###### Requirements with Version Specifiers ######
#   See https://www.python.org/dev/peps/pep-0440/#version-specifiers
docopt == 0.6.1             # Version Matching. Must be version 0.6.1
keyring >= 4.1.1            # Minimum version 4.1.1
coverage != 3.5             # Version Exclusion. Anything except version 3.5
Mopidy-Dirble ~= 1.1        # Compatible release. Same as >= 1.1, == 1.*
```

Two conditions can be combined with AND by separating them with a comma. In the following example, a version of 1.0 or later and 2.0 or earlier (1.0 <= ver <= 2.0) is installed.

```python
package >= 1.0, <= 2.0
```

**Install requirement.txt**
```bash
python install -r requirements.txt
```

**Create requirements.txt with `pip freeze`**
```bash
pip freeze > requirements.txt
```

### 2. Series & DataFrame Overview

### 3. Series Deep Dive

- Learn to use operations and methods
- Learn to aggregate and summarize
- Convert to the correct type
- Conditional manipulation
- Handling missing data
- Interpolation of data
- Ranking
- Binning Data
- Indexing
- Slicing
- String manipulation
- Optimization with Cython
- Date Theory
- Date conversion
- Date methods
- Grouping by dates
- Shifting Data
- Rolling Data
- Cumulative Operations
- Plotting
- Styling Plots
- Categorical Counts
- Generalization

### 4. DataFrame Deep Dive

- Summarizing Data
- Looping
- Aggregations
- Learning to .apply correctly
- Creating columns
- Memory usage
- Sorting columns
- Sorting indices
- Filtering rows
- Filtering columns
- Plotting
- Reshaping
- Dummy columns
- Pivoting
- Cross-tabulation
- Melting data
- Stacking data
- Unstacking data
- Joining Data

### 5. Time Series

- Adding timezones
- Slicing
- Cleaning missing data
- Seasonality
- Resampling
- Offset aliases
- Advanced anchoring
- Grouping

### 6. Exporting Data

- Adding Rows
- Adding Columns
- Join types
- Join validation
- Visualization

### 7. Styling Data

- Sparklines
- Style
- Colors
- Bars
- Heatmaps
- Gradients
- Captions
- CSS
- Stickiness

### 8. Debugging
