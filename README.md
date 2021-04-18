# Crypto Arbitrage Analysis

## *Introduction*

This program runs an analsysis on Bitcoin prices between two exchanges: **Bitstamp** and **Coinbase**.  The 3 major steps taken for this analysis are to **1) collect the data, 2) prepare the data, and 3) analyze the data.**  

---

## Technologies

**Python 3.7.9** was used to code this application, and the code is held in a **Jupyter Notebook** file.  The Python libararies used to make this app possible are: **Pandas, Pathlib, and Matplotlib.**

---

## Installation Guide

Since this is a **Jupyter Notebook** file, please open **Jupyter Lab** to run this file.

---

## Examples

Here is an example of the app in action:
![example](https://user-images.githubusercontent.com/80929342/114322646-2b981c80-9ad6-11eb-9a15-024f32aa05b3.JPG)
---

## Usage

Run the app by typing in **python app.py** and it will prompt you enter the path for CSV file containing the loans, which is **data/daily_rate_sheet.csv**: 
![Inkedstep1_LI](https://user-images.githubusercontent.com/80929342/114322877-664e8480-9ad7-11eb-84fb-aa85afd445cd.jpg)

---

Enter in the requested financial data and you will see the **debt to income ratio**, **loan to value ratio**, and the **number of qualifying loans**:

![Inkedstep2_LI](https://user-images.githubusercontent.com/80929342/114323021-2d62df80-9ad8-11eb-984c-154049e94bfd.jpg)

---

Then enter either **y** or **n** to save the qualifying loans as a CSV file.  If you choose **not** to save the file, then the app will automatically exit.  If you move forward to saying, then you must enter the path of where you want to save the file:

![Inkedstep3_LI](https://user-images.githubusercontent.com/80929342/114323142-c72a8c80-9ad8-11eb-9f2c-3b91a248b5e3.jpg)

---

## Contributors

**I would like to thank and acknowledge my UCB FINTECH Class for their questions and input that contribute to the success and knowledge base for the class!**

---

## License

No license is needed to use this app.
