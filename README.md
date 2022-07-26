# AutoWeird

## Running the experiment
1. [**NodePiece**](https://github.com/migalkin/NodePiece) have pre-computed a vocabulary of 20k anchor nodes (~910 MB). Download it using the download.sh script:
```bash
sh download.sh
```
2. Install the requirements from the requirements.txt
 
3. Run the code with the best hyperparameters using the main script
```bash
sh run_ogb.sh
```

### ogbl-wikikg2
Please update ogb package to version 1.3.2. 
Details of all hyperparameters can be found in run_ogb.sh.

## Note
This code is the implementation of AutoWeird. This implementation of AutoWeird for [**Open Graph Benchmak**](https://arxiv.org/abs/2005.00687) datasets (ogbl-wikikg2) is based on [**OGB**](https://github.com/snap-stanford/ogb), [**NodePiece**](https://github.com/migalkin/NodePiece), [**TripleRE**](https://github.com/LongYu-360/TripleRE-Add-NodePiece), [**InterHT**](https://github.com/destwang/InterHT), [**TranS**](https://github.com/xyznlp/trans). Thanks for their contributions.
