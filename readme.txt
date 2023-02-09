This job will detect the possible delimeter from the list ("," or ";" or "|" or "#" or "$" or "\t") of input file and prepare the standard output file with fix delimeter tilde (~). Job will take input as number of column of input file thru context parameter.

1. Number of column in Input file, all files should have same number of columns if there is multiple file.
2. Detect delimeter of input files from the list of pre defined delimeter. If any other delimeter is available in files then first this need to handle in job.
3. Output delimeter can be set thru context parameter.
4. If pre defined delimeter is not found in input file then it will notify the user with message.

