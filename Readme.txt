This script converts Thunderbird message filters to Evolution message filters.

CAUTION: This is a very early version and only supports a very small set of possible filter commands supported by Thunderbird. However, the author would be happy if the functionality could be extended in the future.

Tested with Python 2.7.12

Usage: filtersThunder2Evo thunderFilters evoFilters evoMailRoot
Have a look at the 'examples' directory and run the examples using the runExample script.

Currently supports:
- filtering of sender, subject, recipient and message body
- supported comparators are 'is', 'contains'
- 'any' or 'all' for grouping the conditions
- 'Move to folder' is the only supported action

Limitations:
- special characters should be avoided for all email folder names as well as filter names
- only works with mail addresses ending on '.com' or '.de' for parsing reasons. However, this can be easily extended


Version: 0.01
Created in 05/2017 by Thorben Casper
