## Overview

This project demonstrates a simple A/B testing example using Python. It compares the conversion rates of two different versions of a website's landing page (A and B) to determine which version performs better in terms of conversion rate. The project utilizes a two-proportion z-test to determine if the observed difference between the conversion rates is statistically significant.

## Dependencies

* Python 3.6+
* numpy
* statsmodels

To install the required packages, run the following command:

```
pip install numpy statsmodels
```

## Dataset

The project simulates the conversion rates for landing pages A and B using NumPy's random.binomial function. The conversion rates and the number of visitors for each page are set using the following variables:

* conversion_rate_A: Simulated conversion rate for page A.
* conversion_rate_B: Simulated conversion rate for page B.
* n_visitors_A: Number of visitors for page A.
* n_visitors_B: Number of visitors for page B.

These variables can be modified to reflect different conversion rates and visitor counts as needed.