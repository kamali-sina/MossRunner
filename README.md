# MossRunner

A bash script that extracts and cleans submission files and sends them to the Moss server for verification.

**CAUTION**: You have to download and place the moss file in the same folder as the runner to run moss automatically if desired. To download the file, run the following in a terminal:

    wget -r -np http://moss.stanford.edu/results/619603464

## How to use

To use the script, simply excute it by bash and give the .zip files to extract as command line arguments. i.e:

    bash ./moss_runner.sh example.zip example2.zip
