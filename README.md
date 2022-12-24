# NGS_sc

UPDATE:
2022-12-24. Corrections were made for 1.4 and a 1.7 tasks based on this table
https://docs.google.com/spreadsheets/d/1mLhiUCg7PdmW0oENUhEi12GsAIxOeuBet9Bh4DTASMg/edit#gid=0
The corrections start and end can be found with ctrl+F FIX_START and FIX_END respectively.



RESTART RUNTIME (ctrl+M) AFTER EXECUTING THE CELL WHERE LIBRARIES ARE INSTALLED AND UNINSTALLED

This is required because matplotlib 3.5 doesn't work properly for some reason

After restart, all the cells below can be ran using "Run Below" option (ctrl+F10)

This notebook uses dataset from this research (the data includes 4 scRNA-seq experiments for healthy human DURA and 4 for MENingioma)

https://genomemedicine.biomedcentral.com/articles/10.1186/s13073-022-01051-9

All the data needed to run notebook (except for 'Acquiring annotation' section) is already in this folder. 

All the data, including .rds objects, was acquired here:

https://zenodo.org/record/6473604
