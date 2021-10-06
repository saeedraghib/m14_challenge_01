# *Algorithmic Trading - (m14_challenge_01):*<br><br>

## **Description:**<br>
In this Challenge, you’ll assume the role of a financial advisor at one of the top five financial advisory firms in the world. Your firm constantly competes with the other major firms to manage and automatically trade assets in a highly dynamic environment. In recent years, your firm has heavily profited by using computer algorithms that can buy and sell faster than human traders.

The speed of these transactions gave your firm a competitive advantage early on. But, people still need to specifically program these systems, which limits their ability to adapt to new data. You’re thus planning to improve the existing algorithmic trading systems and maintain the firm’s competitive advantage in the market. To do so, you’ll enhance the existing trading signals with machine learning algorithms that can adapt to new data.

In a Jupyter notebook, you’ll do the following:
<br>

You’ll combine your new algorithmic trading skills with your existing skills in financial Python programming and machine learning to create an algorithmic trading bot that learns and adapts to new data and evolving markets:

### ***Task 1:***<br>
Implement an algorithmic trading strategy that uses machine learning to automate the trade decisions.
<br>
### ***Task 2:***<br>
Adjust the input parameters to optimize the trading algorithm.
<br>
### ***Task 3:***<br>
Train a new machine learning model and compare its performance to that of a baseline model.
<br>
<br>

---
## RESULTS<br>

Here are the results:
<br>

### <U>MODEL 1</U>: 
#### Baseline with the SMA short window of 4 & long window of 100 and DateOffset of 3 months
<br>
<img src="Resources/final_plot_step07_longWindow100_3.png" alt="First Model" style="height: 300px; width:450px">
<br>
The Strategy returns started off similar to actual returns. However, starting from middle of 2017they began performing better than actual returns.
<br>
<br>

### <U>MODEL 2</U>: 
#### Baseline with the SMA short window of 4 & long window of 200 and DateOffset of 3 months
<br>
<img src="Resources/final_plot_step07_longWindow200_3.png" alt="First Model" style="height: 300px; width:450px">
<br>
The Strategy returns started off performing better than actual returns, however, starting from 2nd half of 2016, they performed inferior to actual returns, with one exception of 1st half of 2020, where the performed better than actual returns.
<br>
<br>

### <U>MODEL 3</U>: 
#### Baseline with the SMA short window of 4 & long window of 200 and DateOffset of 24 months
<br>
<img src="Resources/final_plot_step07_longWindow200_24.png" alt="First Model" style="height: 300px; width:450px">
<br>
The Strategy returns started off performing lower than actual returns, however, starting from 1st half of 2020, they performed far better than actual returns.
<br>
<br>
<b>Conclusions</b>: 
<br>
Model 3 seems to be the best. The strategy performs incredibly better than model 1 or model 2.
<br>
<br>

### <U>MODEL 4</U>: 
#### Baseline with the SMA short window of 4 & long window of 200 and DateOffset of 24 months
<br>
<img src="Resources/final_plot_regressionModel_model04.png" alt="First Model" style="height: 300px; width:450px">
<br>
<b>Conclusions</b>: 
<br>
Using Logistic Regression, Model 4's Strategic Regressions performed better than  Actual Returns starting starting 1st half of 2020.
<br>
<br>

## <U>Technologies</U>: 
<br>
The following packages and dependicies are needed for the proper functioning of the application:
<br>
### **pandas**:<br>
### **numpy**:<br>
### **pathlib**:<br>
### **hvplot**:<br>
### **matplotlib.pyplot**:<br>
### **sklearn**:<br>
<br>

---

## Usage

In order to run the program, type the following at the terminal prompt:
* ### python sr_machine_learning_trading_bot.ipynb

---

## Contributors

**Name:** Saeed A Raghib<br>
**Contact:** saeed_raghib@msn.com

---

## License

### Universit of California at Berkeley EXTENSION
