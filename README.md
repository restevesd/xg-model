# xg-model

![](/images/xG_plot2.png)

This repository contains all the necessary codes to ideally reproduce the data processing, analysis and visualization described in this article (), which is focused on how to fit a football xg model using **R software** and the public event dataset by Wyscout.

Before to use these codes you have to get this list of required datasets:

* events_England.json
* events_France.json
* events_Germany.json
* events_Italy.json
* events_Spain.json
* players.json

You can download them from [**this website**](https://figshare.com/collections/Soccer_match_event_dataset/4415000/2).


Then, I suggest to use the codes in the following order:

* 01code_load_process_rawdata.R
* 02code_feature_creation_exploratory_analysis.R
* 03code_fit_save_models.R
* 04code_evaluate_use_models.R

