# Sample-Versus-Population-Variance
>Objective: This project provides a Python simulation to demonstrate why we divide by 𝑛−1 instead of 𝑛 when calculating sample variance. It helps to clarify the concept of unbiased estimation in statistics and illustrates the effectiveness of Bessel's correction.
- To simulate the calculation of variance for sample data.
- To explain why the sample variance uses 𝑛−1 instead of 𝑛 for unbiased estimation.
- To visualize how sample size affects the accuracy of variance estimates.
## Files
1. Understanding_Variance.ipynb: Python script containing the simulation code.
2. README.md: This file.
## Key Functions
1. **population_variance(data)**: Calculates the population variance by dividing by 𝑛.
2. **sample_variance(data)**: Calculates the sample variance by dividing by 𝑛−1.
3. **draw_sample(population, sample_size)**: Draws a random sample of a specified size from the population dataset.
## Results
- Smaller samples often underestimate the population variance.
- Larger samples provide more accurate estimates of the population variance.
- Bessel’s correction (using 𝑛−1) adjusts for bias and becomes more effective with larger sample sizes.
## Conclusion
The simulation highlights the importance of Bessel's correction in providing an unbiased estimate of the population variance. By adjusting for bias, sample variance calculations become more accurate, significantly as sample sizes increase.


