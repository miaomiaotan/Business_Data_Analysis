This is a business data analysis program I finish as an interest during my part-time.
The program is based on the marketing datas which come from the Central Government Procurement Website (http://www.zycg.gov.cn/td_xxlcpxygh/platform), during January to Augest, 2016. 
I take Shanghai Chenglan Science & Technology Co.Ltd (which I worked in) as an example, to dive about the Server and Storage products data, and the data in Shanghai district.
The result are briefly shown in Analysis_Report.

The language and package I used are python, urllib2, re, BeautifulSoup, pandas, numpy, matplotlib,graphlab.

The three parts (Server data, Storage data, Shanghai district data) have many similarities in the pipeline of analysis, You can read just one of them. Instructions are as follows.


1 Server
a)./crawl_data.ipynb
Take ./server.txt as input, creat and visit the products’ urls, get product information, write them to ./Data/
b)./form_dataframe.ipynb 
Read the raw data from ./Data/, cleaning and write them into ./result/all_sale_info.csv
c) ./data_analysis.ipynb
Use ./result/all_sale_info.csv to do some analysis, also write the result to ./result/
d) data visualization
Use ./draw_his.ipynb to draw histogram plot, plot in ./Demo/histogram
Use ./use_graghlab.ipynb, plots in ./Demo/graphlab_0-4
Use creat_json_file.ipynb to write ./Demo/sunburst.html, we can view the server data interactively (try to double click on the plot) via it.


2 Storage
a)./crawl_data.ipynb
Take ./storage.txt as input, creat and visit the products’ urls, get product information, write them to ./Data/
b)./form_dataframe.ipynb 
Read the raw data from ./Data/, cleaning and write them into ./Result/all_sale_info.csv
c) ./data_analysis.ipynb
Use ./Result/all_sale_info.csv to do some analysis, also write the result to ./Result/
d) data visualization
Use creat_json_file.ipynb to write ./Demo/sunburst.html, we can view the server data interactively (try to double click on the plot) via it.


3 Shanghai_Chenglan_data
a)./crawl_data.ipynb
Take ./chenglan_product.txt as input, creat and visit the products’ urls, get product information, write them to ./Data/
b)./form_dataframe.ipynb 
Read the raw data from ./Data/, cleaning and write them into ./Result/sh2016.csv
c) ./data_analysis.ipynb
Use ./Result/sh2016.csv to do some analysis, like get the top 3 consumers and top 2 providers in  shanghai, or get the relations between the consumers and providers, results in ./Result/
d) data visualization
In ./Demo, show the consumers and providers distributions in Shanghai, see the connections between them by provider_buyer_connections.html