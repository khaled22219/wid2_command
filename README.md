# wid2 - Bulk Data Download from the World Inequality Database (WID)
# Overview:
wid2 is a Stata module designed to facilitate the bulk downloading and extraction of data from the World Inequality Database (WID). The module retrieves the most up-to-date version of WID data containing WID series data and metadata, extracts its contents, and stores them in a designated sub-folderin a selected or current directory for further use in Stata.

# Description:
wid2 is a user-contributed Stata command that automates the process of downloading and extracting the most recent WID dataset. Upon execution, the module:
    
    1. Downloads the most up-to-date version of WID data (e.g., data series, metadata, etc.). 
    2. Extracts the contents into a subdirectory named Raw Data inside the specified directory (or the current working directory if no path or option is specified).
    3. Does not affect any existing data in memory. 
    4. Automatically replaces existing data if any. 
