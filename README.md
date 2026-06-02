# Confidence-Internals
This study focuses on estimating the average durability of print-heads used in personal computers, measured in millions of characters printed before failure. Due to the destructive nature of testing, only a small sample of 15 print-heads is analyzed.

To estimate the true population mean durability, confidence intervals are constructed using two different approaches. First, a 99% confidence interval is calculated using the sample standard deviation and the t-distribution, which is appropriate when the population standard deviation is unknown and the sample size is small. This method accounts for additional uncertainty in the estimate.

Second, a 99% confidence interval is constructed using the known population standard deviation of 0.2 million characters, applying the z-distribution. This approach is used when population variability is known and provides a more precise estimate.

The resulting intervals provide a range of plausible values for the true mean durability of print-heads, helping manufacturers make informed decisions about product quality and reliability.
