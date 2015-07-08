# ISO100-Stock
ISO100 Stock Software Python Edition version Alpha 1.0.
Crated by group 'ISO 100'
Group Member: Xu Hao, Tea Shaw, Yuki Tam, Eva Lam, Wu Cong, etc.
Created on: 2015/7/8

This software aims to get stock data from the Internet and analyze it with our mathematical model.

File Definition:
stk_lst.py: Get all of the stock number and stock name of A-Shares and insert the data to Mysqlte DB table 'stk_lst'
stk_prc.py: Get all the price and price-related infomation of all A-Shares and insert the data to Mysqlte DB table 'stk_prc'
stk_cpt.py (half done): Get the stock capital data of all A-Shares and insert the data to Mysqlite DB table 'stk_cpt'
stock.sqlite: The database that stores all the infomation generated by above script