# SOL Token Farming Analysis - Base Chain

A comprehensive Dune Analytics dashboard analyzing SOL token farming activities and suspicious wallet behavior on the Base blockchain network.

## 🔗 Live Dashboard

[View Dashboard on Dune Analytics](https://dune.com/_john_/sol-token-farming-analysis-base-chain)

![Dashboard Preview](https://github.com/John-04/SOL-Token-Farming-Analysis---Base-Chain/blob/main/Screenshot%202026-01-31%20054539.png)
![Dashboard Preview](https://github.com/John-04/SOL-Token-Farming-Analysis---Base-Chain/blob/main/Screenshot%202026-01-31%20054553.png)
![Dashboard Preview](https://github.com/John-04/SOL-Token-Farming-Analysis---Base-Chain/blob/main/Screenshot%202026-01-31%20054608.png)

## 📊 Overview

This project provides an in-depth analysis of SOL token transfers on Base Chain, focusing on identifying potential wash trading patterns, farming behavior, and suspicious wallet activities. The dashboard tracks ERC20 token transfers and analyzes wallet interactions to detect unusual trading patterns.

## 🎯 Key Features

### 1. Wash Trading Pairs Detection
- Identifies suspicious wallet pairs engaged in potential wash trading
- Tracks round-trip transaction counts between wallet pairs
- Analyzes average transaction amounts and time differences
- Monitors min/max transaction amounts and standard deviations
- Flags wallets with abnormal trading patterns

### 2. Top Farming Wallets Analysis
- Ranks wallets by total transaction volume
- Tracks active trading days and unique counterparties
- Calculates unique recipients and senders per wallet
- Analyzes median trade sizes and coefficient of variation
- Monitors imbalance percentages and transaction patterns

### 3. Daily Farming Trends
- Visualizes daily farming activity over time
- Distinguishes between high-frequency wallets and farming volume
- Shows temporal patterns in suspicious trading behavior
- Tracks the evolution of farming activities

## 📈 Metrics Tracked

### Wash Trading Detection
- **Round Trip Count**: Number of back-and-forth transactions
- **Average Amount**: Mean transaction value
- **Average Time Difference**: Time between reciprocal transactions
- **Min/Max Minutes**: Temporal bounds of trading patterns
- **Amount Standard Deviation**: Transaction value consistency
- **Timing/Amount Flags**: Indicators of suspicious behavior

### Wallet Analysis
- **Total Transactions Sent/Received**: Overall wallet activity
- **Net Imbalance**: Difference between sent and received
- **Active Days**: Number of days with trading activity
- **Unique Recipients/Senders**: Network reach
- **Median Trade Size**: Typical transaction value
- **Coefficient of Variation**: Trading pattern consistency
- **Transaction Percentage**: Relative activity level

## 🔍 Detection Methodology

The analysis identifies suspicious behavior through:

1. **Pattern Recognition**: Detecting reciprocal transactions between wallet pairs
2. **Temporal Analysis**: Identifying unusually short time intervals between trades
3. **Volume Analysis**: Flagging consistent transaction amounts
4. **Network Analysis**: Mapping wallet interaction patterns
5. **Statistical Analysis**: Using variance and deviation to identify outliers

## 📁 Data Sources

- **Blockchain**: Base Chain
- **Token Standard**: ERC20
- **Primary Token**: SOL
- **Data Platform**: Dune Analytics

## 🚀 Use Cases

- **Regulatory Compliance**: Identifying potential market manipulation
- **Risk Assessment**: Flagging suspicious wallet behavior
- **Market Intelligence**: Understanding token farming patterns
- **Security Research**: Tracking wash trading activities
- **Due Diligence**: Investigating wallet legitimacy

## 📊 Dashboard Components

### Table 1: Wash Trading Pairs Detection
Displays wallet pairs with suspicious trading patterns, including:
- Wallet addresses (wallet_a and wallet_b)
- Transaction metrics and timing analysis
- Statistical flags for abnormal behavior

### Table 2: Top Farming Wallets
Ranks suspicious wallets by activity level, showing:
- Comprehensive transaction statistics
- Network interaction metrics
- Trading pattern indicators

### Chart: Daily Farming Trends
Time-series visualization showing:
- Daily distribution of high-frequency wallets (orange)
- Farming volume percentage (purple)
- Temporal trends in farming activity

## 🛠️ Technical Stack

- **Query Language**: SQL (Dune Analytics)
- **Blockchain**: Base Chain
- **Data Source**: On-chain ERC20 transfer events
- **Visualization**: Dune Analytics Dashboard

## 📝 Key Insights

The dashboard reveals:
- Patterns of coordinated wallet behavior
- Temporal clustering of suspicious transactions
- Networks of related farming wallets
- Abnormal trading frequency and volume patterns

## 🔐 Privacy & Ethics

This analysis is conducted on public blockchain data for:
- Educational purposes
- Market transparency
- Security research
- Pattern detection

All wallet addresses are public information available on the blockchain.

## 📊 Data Interpretation

### Normal Flags (✓ Normal)
Indicate standard trading behavior within expected parameters.

### Abnormal Patterns
Highlighted by statistical analysis flags indicating:
- Unusually consistent transaction amounts
- Suspicious timing patterns
- High-frequency reciprocal trading
- Coordinated wallet behavior

## 🤝 Contributing

Contributions are welcome! Feel free to:
- Fork the repository
- Suggest improvements to detection algorithms
- Add new analytical metrics
- Enhance visualizations

## 📄 License

This project is open source and available for educational and research purposes.

## 👤 Author

**_john_**
- Dune Analytics: [@_john_](https://dune.com/_john_)

## 📞 Contact

For questions or collaboration opportunities, please reach out through:
- GitHub Issues
- Dune Analytics platform

## ⚠️ Disclaimer

This analysis is for educational and research purposes only. It does not constitute financial advice, legal advice, or accusations of wrongdoing. The identification of patterns does not prove illegal activity and should be interpreted in conjunction with other evidence and proper investigation.

---

**Last Updated**: January 2026

*Built with ❤️ using Dune Analytics*
