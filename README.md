# A proposed update for the classification and description of bacterial lipolytic enzymes

This is a repository for the deposit and classification of lipolytic enzymes based on the proposed classification system in Hitch and Clavel (2019) (https://peerj.com/articles/7249/).


The current classification system includes the following families;

|Family| Sub-family| Type protein| Accession| Function|
| -----|----|---- | ------------|-------------|
|Family I| 1|| D50587| True lipase|
||2|| X70354| True lipase|
||3|| D11455| True lipase|
||4|| M74010| True lipase|
||5|| U78785| True lipase|
||6|| M12715| True lipase / Phospholipase|
||7|| X99255| True lipase|
||8| Lip1| Q3IF07| True lipase|
||9| LipG| DQ458963| True lipase|
||10| RlipE1| FJ529693| -|
||11| MPlaG| EU285670| True lipase / Phospholipase|
|Family II||| P10480| Secreted acyltranferase|
|Family III||| M86351| Extracellular lipase|
|Family IV||| X62835| Esterase|
|Family V||| M58445| PHA-depolymerase|
|Family VI||| D90904| Carboxylesterases|
|Family VII||| Q01470| Carbamate hydrolase|
|Family VIII||| AAA99492| Stereoselective esterase|
|Family IX|| phaZ7| AY026355| Poly(3-hydroxylbutyrate) depolymerase|
|Family X|| EstD| NP_228147| Carboxylesterase|
|Family XI|| EstA| ABY60416| Esterase|
|Family XII|| LipEH166| EU515239| Lipase|
|Family XIII|| Est30| AY186197| Carboxylesterase|
|Family XIV|| EstA3| NP_623858| Carboxylesterase|
|Family XV|| EstGtA2| AEN92268| Carboxylesterase|
|Family XVI|| LipSM54| AGF29555| Lipase|
|Family XVII|| LipJ2| KX096709| Lipase|
|Family XVIII|| plaB| EF408871| Phosphatidylcholine-specific phospholipase|
|Family XIX|| LipSM| KX353755| Lipase|
|Family XX|| FLS18D| ACL67852| Esterase|
|Family XXI|| FnL| ABS61180| Lipase|
|Family XXII|| EstD2| GQ866023| Secreted esterase|
|Family XXIII|| LipA| ACJ13070| Lipase|
|Family XXIV|| Rv0045c| NP_214559| Esterase|
|Family XXV|| EM3L4| GQ340926| Lipase|
|Family XXVI|| EstGS| HQ156900| Secreted esterase|
|Family XXVII|| EstGH| HQ156914| Esterase|
|Family XXVIII|| LipR| YP_345621| Lipase|
|Family XXIX|| EstGX1| HQ262952| Lipase|
|Family XXX|| EstP2K| JN001203| Esterase|
|Family XXXI|| Est12| KF313138| Esterase|
|Family XXXII|| Est9x| AFR79233| Lipase|
|Family XXXIII|| EstDZ2| KX301277| Secreted carboxylesterase|
|Family XXXIV|| Est22| GAC12013| Homoserine transacetylase|
|Family XXXV|| AcXE2| ACM59679| Acetyl xylan esterase|

## Compare a new lipolytic enzyme to the representatives
If you have a novel lipolytic enzyme and wish to either identify which family it belongs to or confirm it as a novel family we have provided the Pairwise_analysis.ipynb file as used in our paper.

### Requirements
- Jupyter notebook
- Python
- ClustalW

### Method
- Place your proteins amino acid sequence into the latest 'Type_proteins_[MONTH]_[YEAR].faa' file
- Open and run the commands within the 'Pairwise_analysis.ipynb' script
- This will produce a file called 'Pairwise_similarities.csv'
- Within this file the similarity of your protein to each representative is provided
- Sequence similarity below 60% indicates novelty, a value above 60% suggests your protein may be a member of the matching family. To confirm this compare the biochemical properties of your protein and that of the representative it matched to identify if they belong to the same family


## Addition of a new lipolytic enzyme 
If you wish to include a novel lipolytic enzyme within this classification system please open an issue on this repository and provide both your lipases amino acid sequence and the paper in which you describe the biochemical properties of your protein. We will then confirm the sequence novelty of your protein along with its published biochemical properties and place it within the classification system.
