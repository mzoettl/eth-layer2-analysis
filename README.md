# Ethereum Layer 2 Analysis

This is the accompanying repository for my Master's Thesis "Bridges and 2nd Layers: Quantitative Analysis of the Scaling Progress of Ethereum". 
The repository serves as a curated collection of my research findings and includes in-depth analysis of key on-chain metrics for some of the most prominent L2 projects including Arbitrum One, Optimism, dYdX, and zkSync.


- **Total Value Locked (TVL):**
  - **Escrows Utilization:**
    - Detailed metrics regarding the escrow accounts in use.
  - **Token Composition:**
    - Breakdown of the percentage of stacked tokens and their distribution across different projects.

- **Transaction Metrics:**
  - **Transaction Count:**
    - The number of transactions processed to evaluate network throughput.
  - **Transactions Per Second (TPS):**
    - A measurement of network performance in handling operations.

- **Network Participation:**
  - **Daily Active Addresses:**
    - An indicator of the active user base and engagement on the Layer 2 platforms.
   

## How to Navigate

This repository is organized into several folders, each with its specific type of content and purpose within the scope of the research. Here's what each folder contains:

### `tvl-data-collection`
This folder is the backbone of the data collection process for Total Value Locked (TVL), featuring  workflows and automated scripts designed for retrieving escrow account balances, which contribute to the TVL of the analyzed Layer 2 projects.

### `utils`
- **price-data:** Scripts that allow you to fetch price information for the top (300) ERC20 tokens.
- **block-numbers:** Code dedicated to retrieving the block number of the last block minted for each day over a specified time period.

### `data`
contains on-chain data extracts used for plotting and visualizations.

### `figures`
 All the charts, graphs, and figures generated from the analysis, which visually represent the findings and trends observed in the on-chain data.


The data was gathered exclusively through cost-FREE resources, utilizing APIs including Infura, Etherscan, CoinGecko, Ethplorer and Dune. However, due to rate limits imposed by these services,  the request frequency had to be reduced at certain points which resulted in long execution times for some of the code snippets.





