# Lithology-Type-Prediction
With the advancement of machine learning and artificial intelligence, the automated estimation of a bed’s complex lithology has become one of the most crucial requirements in petroleum engineering because of its important role in reservoir characterization. In the past geophysical modelling, petro-physical analysis, artificial intelligence and several statistical approaches have been implemented to estimate lithology since prediction of lithology from recorded continuous cores are very expensive and unprofitable.

As a part of my training I understood the dynamics of the data, extracted the data from the files, prepared the data and finally implemented all the theoretical knowledge to build a machine learning model to predict the structure lithology type in python.

I was provided with two kinds of files: <well_name>.LAS and All_well_Litho_Class.csv for training and testing the model. The <well_name>.LAS Files contain the version information, well information block (contains start depth (STRT.M), end depth (STOP.M), Step difference (STEP.M) and Null value replacer (-999.2500)), curve information (contains data format for well), and well data(depth logs). The All_well_Litho_Class.csv contains Common Well Name, Top Depth(meter), Base Depth(meter) and Litho Class. I had to read the log data from each well from <well_name>.LAS and assign the structure lithology type to prepare the data. For modelling, I implemented One vs Rest Logistic Regression model (OVR). Because of Low computational power I could run the code on only two dataset files and achieved a score of 46.55%. The score can get better if more dataset files are used.

Due to confidentiality reasons I could not upload the dataset.
