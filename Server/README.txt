Server
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