# DW-project

Data warehousing project

Assignment

# 1 Operational data sources inspection and profiling

For each dataset, you will find in the corresponding folder the dataset itself and some
documentation on the schema and/or on the interesting business questions. The
operational data sources consist in OLTP data. The business questions will guide you
in the inspection of the dataset: pay attention to focus on the most relevant tables and
fields.
For data inspection and profiling, besides PostgreSQL queries, you may rely on Tableau
Prep www.tableau.com/trial/tableau-prep.
Include in the documentation any insight you get from source inspection and profiling.

# 2 Data warehouse conceptual design

Produce a data warehouse conceptual design according to the DFM notation. Identify
the fact(s) of greatest interest for analysis, starting from the analysis of operational
sources and making some assumptions (that must be made explicit) about the workload. You may rely on the Indyco www.indyco.com tool for drawing the fact schema(s).
Motivate your design decisions and discuss dynamicity in dimensions.

# 3 Data warehouse ROLAP logical design

Starting from the conceptual design above and possibly refining the assumptions
about data volumes and workload, develop a ROLAP logical design for the data warehouse. The design must include secondary events (i.e., views). Define your fact and
dimension tables in PostgreSQL www.postgresql.org and populate them with data
from the operational sources. Any ETL approach is allowed, just motivate and illustrate in the documentation your choices, and include all the relevant files in the zip.

# 4 OLAP Queries
Specify in PostgreSQL the queries corresponding to the workload. Moreover, referring
to the specific OLAP extensions of PostgreSQL for windows and window functions,
specify at least a query for each category below
1. Comparison of summarized data at different aggregation levels [group by extensions]
2. Comparison of detailed and summarized data [window partitioning]
3. Computing rankings [window ordering]
4. Computing cumulative totals [window framing]
5. Computing mobile aggregates [window framing]

# 5 Tableau
Identify the five most relevant outcomes of your analysis and provide suitable reports
in Tableau www.tableau.com for communicating this outcomes. Include in the presentation the graphics and discuss the identified outcomes.
