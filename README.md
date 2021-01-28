# model-comparison
Model Comparison and Occam’s Razor
Data Fitting, Covariance, and Confidence Levels

University of San Francisco
Physics 302 – Scientific Computation and Machine Learning
Professor Xiaosheng Huang

Unless there are clear and strong physical reasons not to, we nearly always choose the model with the least number of parameters that can describe the data just as well as any other model.

This choice is considered an example of Occam’s Razor. Wikipedia (as of 4 pm, 2/20/2016) provides an acceptable way of stating Occam’s Razor: “Among competing hypotheses, the one with the fewest assumptions should be selected.” Though not always, often “fewest assumptions” is equated with fewest number of model parameters.

Over time (in the last several hundred years) we have found that following this principle often leads us to the actual correct model. Intuitively it may or may not be a big surprise to you; but keep it mind that we cannot justify through reasoning why this principle of economy has so often coincided with the correct model. One recent dramatic example of “the simplest model that gets the job done is the correct model” is the discovery of the Higgs Boson. Thus this principle is well worth paying attention to!

[To see why Occam’s Razor doesn’t have to lead you to the correct model, imagine this. We simulate data using an 8th order polynomial with the best-fit parameters found above. We know such a data set can be fit well with a sinusoidal model that only has two parameters (instead of 9) — nonetheless the sinusoidal model is the wrong model. If x represents time, then all we have to do to show that the sinusoidal model is wrong is to take data for a longer period of time.]
