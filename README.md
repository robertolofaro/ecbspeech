# ecbspeech
see https://robertolofaro.com/ECBSpeech

## AIM

This dataset is part of a data-driven OpenData experiment started in 2018, using initially the CSV released by the European Central Bank (henceforth ECB) to enable its use in data science projects, with the content of speeches 

Updated then by checking on a weekly basis which new speeches had been released, and generated an application that, using the CSV initial format as migrated into a new format with additional columns, computes words frequencies; currently the processing side computes frequencies in any language, but then only speeches in English are used to compute frequencies across all the speeches 

## APPLICATION

The application using the SQLite version of this dataset (with additional tables) is on https://robertolofaro.com/ECBSpeech

The application uses a framework that I had created for other purposes, enabling to search clicking on a tag cloud, and then showing a list of speakers whose speeches contained that work, and in which year they used it; by clicking then on the speaker's name, a list of all the speeches and interviews is listed, with links to the content on the ECB website

## ADDITIONAL ITEMS

The dataset and associated sample R notebook is on https://www.kaggle.com/robertolofaro/ecb-speeches-1997-to-20191122-frequencies-dm


