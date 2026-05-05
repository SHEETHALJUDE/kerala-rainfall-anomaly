# kerala-rainfall-anomaly
43-year rainfall anomaly analysis for Kerala using ERA5 data, SPI classification and Mann-Kendall trend test

<img width="517" height="398" alt="image" src="https://github.com/user-attachments/assets/9af636f5-6d06-44ec-b145-b9fa0ab71209" />


***************************************************

Mann-Kendall Trend Test

A non-parametric statistical test that checks whether a time series has a monotonically increasing or decreasing trend over time. Non-parametric means it makes no assumption about the distribution of the data.
It compares every pair of data points in the time series. If later values tend to be higher than earlier values, the trend is positive. The p-value tells you the probability that this pattern happened by random chance.

p < 0.05 → trend is statistically significant
p > 0.05 → cannot conclude a real trend exists

Result: p = 0.077 — very close to significance but not crossing the threshold. This is an honest and defensible scientific finding.
Anyone can draw a trendline on a graph. The Mann-Kendall test tells you whether that trend is statistically real or just visual noise. This is the difference between data visualisation and data science.
