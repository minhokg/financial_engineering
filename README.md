# Efficient Portfolio

This is a project for dealing with an efficient portfolio by using python.

## 1. Definition of Efficient Portfolio.

An efficient portfolio is a portfolio (a combination of various financial assets) that offers the highest expected return for a given level of risk, or the lowest level of risk for a given expected return.

We can express the above sentence as the next mathematical formula

$$
\min_{\mu_{p}=c}\sigma_{p}^{2}\text{ or }\max_{\sigma_{p}^{2}=c}\mu_{p}
$$

To understand the above condition formulas vividly, I'm going to set a portfolio comprised of two virtual stocks: A and B 

Let $x_{A}$ and $x_{B}$ as portions of stock A and B each. That is, $x_{A} + x_{B} = 1$. So portfolio $R = x_{A}$

Among many generated simulations, an efficient portfolio can be selected based on return or risk a project already set. Efficient Portfolios are expressed as an efficient frontier. We will see the efficient frontier line later. 

## 2. Example of Efficient Portfolio

In this project, I will tackle korean five companys: 
1. LG Electronics
2. Naver
3. KEPCO (Korea Electric Power Corporation)
4. Samsung Electronics 
5. Yuhan

I generated 50000 portfolio simulations and plotted them. Also I drew an efficient frontier as below 

![efficient portfolio](https://user-images.githubusercontent.com/90128043/222964721-2f9383e1-a31f-4235-82ef-f788019efe64.jpg)
