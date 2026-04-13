# Stock Portfolio Analysis

## Project Title
**Stock Portfolio Optimization Using Network Analysis**

## Description
This project focuses on optimizing stock portfolios using network analysis techniques. By leveraging network theory, we can better understand the relationships between different stocks and make more informed investment choices.

## Problem Statement
Active investing requires careful selection of stocks based on their potential for growth and risk assessment. Traditional methods often fail to capture the complex interactions between stocks, leading to suboptimal portfolio performance.

## Proposed Approach
Our approach utilizes network analysis and clustering methods to analyze stock relationships, providing insights that can help optimize portfolios. We will create a network of stocks where edges represent correlation, and apply clustering algorithms to group stocks based on their relationships.

## Network Topological Parameters
The analysis will include various network topological parameters:
- **Degree Centrality**: Measures the number of direct connections a stock has within the network.
- **Betweenness Centrality**: Indicates how often a stock acts as a bridge along the shortest path between two other stocks.
- **Closeness Centrality**: Reflects how quickly a stock can interact with all other stocks in the network.

## Data Information
The dataset used for this analysis consists of the S&P 500 components from 2011 to 2020. This data includes historical prices, volumes, and fundamental indicators for each stock in the index, allowing for comprehensive analysis.

## Installation Instructions
To get started, clone the repository and install the required libraries:
```bash
git clone https://github.com/cyberpavan123/stockportfolioanalysis.git
cd stockportfolioanalysis
pip install -r requirements.txt
```

## Usage Instructions
After setting up the environment, you can run the main analysis script:
```bash
python analysis.py
```
Make sure to check the generated outputs in the `results/` folder.

## Expected Results and Outputs
The expected outcomes of this analysis include:
- Visualizations of the stock network
- Clustering results indicating optimal stock groups
- Performance metrics for portfolios optimized using these clusters

## References
1. Markowitz, H. (1952). "Portfolio Selection". *The Journal of Finance*, 7(1), 77-91.
2. Newman, M. (2006). "Finding Community Structure in Networks Using the Eigenvectors of Matrices". *Physical Review E*, 74(3), 036104.
3. Clustering Methods for Stock Price Prediction, Journal of Finance and Economics.

## License
This project is licensed under the MIT License.