Prd.transaction.analysis

Analysis I did for quatium data analytics virtual internship

Queries used:

SELECT TOP (50) [DATE]
      ,[STORE_NBR]
      ,[LYLTY_CARD_NBR]
      ,[TXN_ID]
      ,[PROD_NBR]
      ,[PROD_NAME]
      ,[PROD_QTY]
      ,[TOT_SALES]
  FROM [VWX].[dbo].[Copy of QVI_transaction_data (2)]

This will pop up the top 50 rows of each column of data

SELECT TOP (10) [DATE]
      ,PROD_NBR [product number]
      ,PROD_NAME [product name]
      ,PROD_QTY [product quantity]
     FROM [VWX].[dbo].[Copy of QVI_transaction_data (2)]

This will show the top 10 products with the highest quantity

SELECT TOP (20) [DATE]
      ,[STORE_NBR]
      ,[LYLTY_CARD_NBR]
      ,[TXN_ID]
      ,[TOT_SALES]

This will show the top 20 scores in total sales and how much loyalty cards were used

