# ARC_Solver
Data and code for attempting to solve the Abstract Reasoning Corpus (ARC) Challenge.
# Description of Data
- **finetune_spaces.csv** - Training data from the train dataset.  The dataset contains 341 items instead of the 400 in the ARC Challenge.  The reason is that this data was modified to work with the GPT-3 Davinci model, which is limited to 4096 characters.
- **finetune_spaces_curie.csv** - Same as above, but limited to 2048 characters.  This reduced the number of items to 239.

The JSONL files with the same names as the above files are the final file to be used for the fine tuning.
