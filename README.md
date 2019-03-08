# A proposed update for the classification and description of bacterial lipolytic enzymes

This is a repository for the deposit and classification of lipolytic enzymes based on the proposed classification system in Hitch and Clavel (TBP).


The current classification system includes the following families;

|Family| Sub-family| Type protein| Accession| Function|
| -----|----|---- | ------------|-------------|
|Family I| 1| D50587| True lipase|
||2| X70354| True lipase|
||3| D11455| True lipase|
||4| M74010| True lipase|
||5| U78785| True lipase|
||6| M12715| True lipase|
||7| X99255| True lipase|
||8| LipG| DQ458963| True lipase|
||9| RlipE1| FJ529693| -|
||10| MPlaG| EU285670| Phospholipase|
|Family II|| P10480| Secreted acyltranferase|

Family III M86351 Extracellular lipase

Family IV X62835 Esterase

Family V M58445 PHA-depolymerase

Family VI D90904 Carboxylesterases

Family VII Q01470 Carbamate hydrolase

Family VIII AAA99492 Stereoselective esterase

Family IX phaZ7 AY026355 Poly(3-hydroxylbutyrate) depolymerase

Family X Est30 AY186197 Carboxylesterase

Family XI EstD NP_228147 Carboxylesterase

Family XII EstA ABY60416 Esterase

Family XIII plaB EF408871 Phosphatidylcholine-specific phospholipase

Family XIV LipEH166 EU515239 Lipase

Family XV FLS18D ACL67852 Esterase

Family XVI FnL ABS61180 Lipase

Family XVII EstD2 GQ866023 Secreted esterase

Family XVIII LipA ACJ13070 Lipase

Family XIX Rv0045c NP_214559 Esterase

Family XX EM3L4 GQ340926 Lipase

Family XXI EstGS HQ156900 Secreted esterase

Family XXII EstGH HQ156914 Esterase

Family XXIII EstA3 NP_623858 Carboxylesterase

Family XXIV LipR YP_345621 Lipase

Family XXV EstGX1 HQ262952 Lipase

Family XXVI EstGtA2 AEN92268 Carboxylesterase

Family XXVII EstP2K JN001203 Esterase

Family XXVIII Est12 KF313138 Esterase

Family XXIX Est9x AFR79233 Lipase

Family XXX LipSM54 AGF29555 Lipase

Family XXXI EstDZ2 KX301277 Secreted carboxylesterase

Family XXXII LipJ2 KX096709 Lipase

Family XXXIII Est22 GAC12013 Homoserine transacetylase

Family XXXIV AcXE2 ACM59679 Acetyl xylan esterase

Family XXXV LipSM KX353755 Lipase
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
