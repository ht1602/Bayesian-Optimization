# Bayesian-Optimization
This is a study notebook of BO.

It includes simple 1-D and 2-D experiment.

Both 1-D and 2-D simple experiments have a comparison with GPy package.

2-D tests BO on a couple of test problems, including functions have many local optimal, bowl-shaped, plate-shaped, valley shaped and steep-ridges. After each test problem we have comparison with sklearn package.

Some test problems say many local optimal problems perform not so well. And the plate-shaped funcion may have some problem with intialization, which can be sovles by changing the hyperparameter optimization method in GPR class.
