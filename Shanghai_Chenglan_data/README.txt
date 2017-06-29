Shanghai_Chenglan_data
a)./crawl_data.ipynb
Take ./chenglan_product.txt as input, creat and visit the products’ urls, get product information, write them to ./Data/
b)./form_dataframe.ipynb 
Read the raw data from ./Data/, cleaning and write them into ./Result/sh2016.csv
c) ./data_analysis.ipynb
Use ./Result/sh2016.csv to do some analysis, like get the top 3 consumers and top 2 providers in  shanghai, or get the relations between the consumers and providers, results in ./Result/
d) data visualization
In ./Demo, show the consumers and providers distributions in Shanghai, see the connections between them by provider_buyer_connections.html