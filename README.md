# classifywomenshape
This model I intent to make reccomendation who you should ware dress like actress.


Source :
These dataset, I captured it from https://bodysize.date by webscraping method and label by using Body Type Calculator from https://goodcalculators.com/body-shape-calculator/

Data Set Information :
These data are the result of a women body types. There are 6 columns information.
1. URL 2. Img_URL
3. Bust
4. Waist
5. Hip
6. Label (a women shape types)

Therefore, I will use 3 features which are Bust,Waist and Hip to classify the label or women shape types.

The result of reccomendation who you should ware dress like her, I sample the data which predicted just 10 women as the above. 
Using decision tree (cart) model due to crossvalidation highest.
