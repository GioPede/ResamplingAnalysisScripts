#ResamplingAnalysisScripts

## Sample Scripts for data Analysis
So far this is a simple python script (should be made parallel...) to perform resampling of a data set.

## Usage
Simply run _python analysis.py FILENAME.xxx [NLINES]_
Where FILENAME is expected to have a 3 charachter extension NLINES is the number of lines in the file to read and process (default is the whole file)
Ouput is located into the "FILENAME/" folder.
If more than 10⁵ lines are specified the autocorrelation function won't be computed, as it would take too long.
