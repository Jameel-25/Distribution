# Binomial Distribution Analysis: Probability of Solving a Problem in Multiple Calls

## Overview

This project provides a detailed analysis of a binomial distribution model applied to a real-world scenario. The scenario involves determining the probability of solving a problem within a certain number of calls, where each call has a 0.6 probability of success.

### Problem Statement

- **Number of Calls (R)**: 15
- **Probability of Success per Call (p)**: 0.6

The analysis aims to understand the likelihood of solving the problem across different numbers of calls and to visualize the cumulative probability of success.

## Key Files

- **`BinomialDistribution.xlsx`**: Excel file containing the binomial distribution data and charts.
- **`README.md`**: This file, providing an explanation of the project and the binomial distribution analysis.

## Understanding the Chart

The Excel file contains two key columns:

1. **Probability**: The probability of solving the problem exactly at that call number.
2. **Cumulative Probability**: The probability of having solved the problem by that call number.

### Chart Explanation

- **Probability Curve (Blue)**: Shows the likelihood of solving the problem on a specific call. The peak around the 7th and 8th calls indicates where the probability is highest.
  
- **Cumulative Probability Curve (Orange)**: Displays the cumulative likelihood of solving the problem by a particular call number. The curve rises quickly and flattens, showing that after 10 calls, the chance of having solved the problem is very high.

## Usage

Clone this repository to explore the data and visualize the binomial distribution in Excel:

```bash
git clone https://github.com/Jameel-25/Distribution.git
```

Open the `BinomialDistribution.xlsx` file to see the detailed analysis and interactive charts.

## Insights

This analysis is valuable for scenarios like customer support optimization, where understanding the probability of solving an issue within a certain number of interactions can improve efficiency and resource allocation.

## Contributing

Feel free to fork this repository and submit pull requests if you'd like to improve or expand upon this analysis.

## License

This project is licensed under the MIT License. See the `LICENSE` file for more details.
