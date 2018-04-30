# econ136_final_project

## Introduction
Our project's goal is to evaluate the viablitity of modeling short
term stock price patterns using a guassian process with a trained
spectral kernel. This work was inspired by previous work using a
guassian process with an RBF kernel to perform portoflio
optimization. The portoflio optimization was performed using daily
data. The trained gaussian was used to predict price of the stocks
over the next day which would be used to rebabalnce the portoflio.

In this project we fit a guassian process with a spectral kernel to
minute data. The goal is to predict the price in the next couple of
minutes. Then sell or retain the stocks based on the prediction.

We believe the spectral kernel may have the ability to find some
interesting patterns in the short term price data of the stock.  The
RBF kernel determines the covariance between data points based on
their gaussian distance. A guassian process using an RBF kernel is
essentially limited to creating a model that thinks previous data's
relevenace to future data is entirely determined by the closeness. The
spectral kernel allows for periodicity in the data. This allows a
gaussian process trained using spectral kernel to think the process
generating the data has some kind of periodicity. Meaning that a
previous point at some time period away may be more relevant than a
close point. This specteral kernel is trained using 


## Back Testing
Now we
