# A proposed update for the classification and description of bacterial lipolytic enzymes

This is a repository for the deposit and classification of lipolytic enzymes based on the proposed classification system in Hitch and Clavel (TBP).


The current classification system includes the following families;

[ADD TABLE HERE]

## Compare a new lipolytic enzyme to the representatives
If you have a novel lipolytic enzyme and wish to either identify which family it belongs to or confirm it as a novel family we have provided the Pairwise_analysis.ipynb file as used in our paper.

### Requirements
- Jupyter notebook
- Python
- ClustalW

### Method
- Place your proteins amino acid sequence into the 'Representative_sequences.faa' file
- Open and run the commands within the 'Pairwise_analysis.ipynb' scipt
- This will produce a file called 'Pairwise_similarities.csv'
- Within this file the similarity of your protein to each representative is provided
- Sequence similarity below 60% indicates novelty, if your sequence has a value above this compare the biochemical properties of your protein and that of the representative it matched to confirm they belong to the same family


## Addition of a new lipolytic enzyme 
Wish to include a novel lipolytic enzyme within this classification system please contact open an issue and provide both your lipases sequence and the paper in which you describe the biochemical properties of your protein. We will then confirm the sequence novelty of your protein along with its published biochemical properties and place it within the system.
