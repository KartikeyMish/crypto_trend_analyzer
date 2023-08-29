![title](hero.png)

# Crypto Trend Analyzer

This project uses the CoinGecko API to collect data on cryptocurrency prices and trends. The data is then used to create charts and graphs using NumPy, Matplotlib, Pandas, and Tableau.

# Requirements

- python 3.6+
- numPy
- matplotlib
- pandas
- mplfinance
  
# Running Notebooks on JupyterLab with AWS S3 and EC2

To run the notebooks on JupyterLab using AWS S3 and EC2, follow these steps:

1. Clone the repository to your local machine.
2. Install the required dependencies listed in the 'Requirements' section.
3. Upload the notebook files to an Amazon S3 bucket.
4. Launch an Amazon EC2 instance with JupyterLab configured.
5. Access JupyterLab through your web browser using the public IP address of the EC2 instance.
6. In JupyterLab, navigate to the directory containing the notebook files and open them.

Why use AWS S3 and EC2 for running notebooks?

- **Scalability:** AWS S3 provides highly scalable object storage for your notebook files, and EC2 allows you to choose instance types based on your computing needs.
- **Cost-Effectiveness:** You can store your data in S3 and only pay for the storage you use. EC2 offers pay-as-you-go pricing, allowing you to select the most cost-effective instance type.
- **Performance:** EC2 instances are designed for various workloads, and you can optimize them for running data analysis tasks efficiently.
- **Collaboration:** Storing notebooks on S3 enables easy sharing and collaboration among team members.


# Instructions
1. Clone the repository
2. Install the requirements
3. Run the cryptoData.ipynb script

# Results

The results of the project are a set of charts and graphs that show the price and trend of cryptocurrency prices. The charts and graphs can be used by investors to make decisions about when to buy or sell cryptocurrency.

#### Result Sample

<img src="https://github.com/KartikeyMish/crypto_trend_analyzer/assets/76617485/778ce0ec-2a67-4b01-83b7-179a3cb23ab3" width=600 height=400>

