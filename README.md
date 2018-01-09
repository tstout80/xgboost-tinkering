# xgboost-tinkering
Testing/Optimization of various ensemble/tree methods with xgboost and sklearn in a Jupyter notebook. Completely WIP.

### A word on the code.
Most of the code here is mine or is an adaptation of code used in the course "Extreme Gradient Boosting with XGBoost" on Coursera.

Link: https://campus.datacamp.com/courses/extreme-gradient-boosting-with-xgboost/

Check it out, it's a good course. Unfortunately it does not explain how to actually install xgboost on YOUR machine, which takes
	some work with git, as well as at the command line. If you want to know how I installed on a Win7 Anaconda Py3.6 environment, go here:

Link: https://www.ibm.com/developerworks/community/blogs/jfp/entry/Installing_XGBoost_For_Anaconda_on_Windows?lang=en

## Graphviz
Only using the usual 'conda install graphviz' (or '!conda install graphviz', if you're executing in Jupyter) will return an ImportError on import,
as it only installs the C version of graphviz. After the previous command completes, using 'conda install python-graphviz' resolved the issue for me.

Go here to learn more:
Link: https://github.com/conda/conda/issues/1851



v0.1 - inital commit

