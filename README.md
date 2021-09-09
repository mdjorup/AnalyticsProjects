# AnalyticsProjects
This is a repository of all my (Michael Djorup) analytics projects. I grouped all of my jupyter notebooks by category. So far, I have focussed on basketball analytics. Below are brief descriptions of each of the notebooks and some findings.


## Phishing_Classification
The objective of this notebook was to classify urls as phishing or non-phishing. Given the url and some metadata about its lifetime, I extracted different features of the URL that I thought could help the models determine phishing. Achieved a testing f1-score of ~.92

## ShotClockAnalysis1
Brief analysis of how the NBA shot clock impacts make probabilities. Make probabilities steeply drop as the shot clock gets closer to 0. Make probabilities are relatively constant in the middle seconds of the shot clock. Make probabilties are highest between 20-22 seconds on the shot clock, indicating that the easiest shots to make are off of rebounds and/or fast breaks.

## SotoProfile
Here is a batting profile of the Washinton National's Juan Soto. It may be misleading that Soto's batting average is about consistent with the rest of the league on every 3 ball count. However, this project explores how the at-bat changes right after the third ball is thrown. It turns out, that Soto's expected bases on the at-bat is up to 70% higher than the league average after the third ball is thrown. This project goes in-depth into this analysis

## Volatility_Forecasting
Here is my submission for the Optiver Volatility Forcasting competition. My strategy was to extract features from the order book dataset and perform a regression analysis. It turns out that the volatility of the second level of the order book is highly correlated with the next 10 minute market price volatility.

## FourierTransform
Here is a short notebook demonstrating the Fourier transformation and the inverse Fourier transformation to an example image. It shows that we can take a noisy image, apply the Fourier transformation, reduce the image to keeping certain low frequencies (100, 400, 1600 pixels of 512x512 image) and reconstruct a smoothed image that is similar to the original through the inverse Fourier Transform. 
