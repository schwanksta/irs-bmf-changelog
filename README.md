# irs-bmf-changelog
Creates a changelog for the [IRS' exempt org business master files](https://www.irs.gov/charities-non-profits/exempt-organizations-business-master-file-extract-eo-bmf). Every day at 2pm eastern it downloads the BMF files, figures out how many additions, modifications or deletions there are, then commits each of the state-by-state files.

We use the state-by-state files because of GitHub's file size limitation. Each file is a list of a state's active nonprofits, except eo4.csv, which contains international and Puerto Rico-based nonprofits.
