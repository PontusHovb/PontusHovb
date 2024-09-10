## Hi there 👋

My name is Pontus and I'm a final year **MSc-student in Financial Mathematics** at KTH - Royal Institute of Technology including exchange studies at **National University of Singapore (NUS)**, summer studies at **Copenhagen Business School (CBS)** and a completed BSc in Industrial Engineering & Management from KTH. Selected coursework include Portfolio Theory \& Risk Management, Quantitative Finance, Machine Learning, Language Engineering, Probability Theory, Applied Computer Science, Regression Analysis, Game Theory and Markov Processes.

Relevant professional experience includes **Junior Quant @ Söderberg & Partners** building and maintaining quantitative models for money market, fixed income and equity funds using Python (pandas, numpy, scikit-learn), SQL and VBA. I've also worked as **Visiting Associate @ BCG Platinion** (tech/IT-consulting internship) and **Intern/Business Developer @ If P&C Insurance** in commerical pricing where I analyzed claims data to assess, model and price commerical property risk using SQL & SAS as well as building dashboards for portfolio follow-up in PowerBI using DAX and PowerQuery.

- Programming experience in [**Python**](https://github.com/stars/PontusHovb/lists/python), [**SQL**](https://github.com/stars/PontusHovb/lists/sql), [**VBA**](https://github.com/stars/PontusHovb/lists/vba) and [**R**](https://github.com/stars/PontusHovb/lists/r) with some experience in [MATLAB](https://github.com/stars/PontusHovb/lists/matlab), [JavaScript](https://github.com/stars/PontusHovb/lists/javascript) and [C/C++](https://github.com/stars/PontusHovb/lists/c-c).
- Main areas of interest are [📊Quantitative Finance](https://github.com/stars/PontusHovb/lists/quant), [🤖Machine Learning & AI](https://github.com/stars/PontusHovb/lists/machine-learning-ai), [⚙️Algorithms](https://github.com/stars/PontusHovb/lists/algorithms) and [🧮Statistics](https://github.com/stars/PontusHovb/lists/statistics)

💡 Click the links to explore my previous projects within different areas and coding languages!

# Projects 🚀
## [The Impact of the Momentum-Factor on Performance 📘](https://github.com/PontusHovb/Bachelor-Thesis)
<p align="center">
    <img src="https://github.com/PontusHovb/Bachelor-Thesis/blob/main/Figures/Singlefactor%20model.png" width="400"/>
</p>
<p align="center"><i>Momentum coefficient over time for singlefactor model</i></p>

In this bachelor thesis, me and my thesis partner Hugo Brunlid explored the kurtosis of momentum, and 'momentum crashes' both from 2008 as discussed in previous research but also in the light of recent covid-19 stock crash. This is done both using a singlefactor model split by Morningstar Category (based on style and size orienation) and also a multifactor model that in addition to momentum (excess past returns) incorporates size orientation, style orientation and management fee as independent variables used to predict excess future returns.

<p align="center">
    <img src="https://github.com/PontusHovb/Bachelor-Thesis/blob/main/Figures/Momentum%20longevity.png" width="800"/>
</p>
<p align="center"><i>Portfolios of mutual funds sorted on lagged one-year return, bachelor thesis to the left (data from 2020-2023), Carhart 1997 to the right (data from 1962-1987)</i></p>

We could conclude that findings of predictive power and longevity of momentum by Carhart are valid still today although impact of size & style factors have significantly changed since Carhart Four-Factor model was first presented in 1997. 

- 💻 **Languages:** Python (pandas, numpy, scikit-learn, jupyter notebook)
- 🔑 **Keywords:** Momentum, Carhart Four-Factor Model, Multifactor Model, Momentum Crashes 

## [Option Pricing 🏦](https://github.com/PontusHovb/Option-Pricing)
In this project Binomial Model, Black Scholes and Longstaff Schwart's are implemented to calculate prices of both European and American options. For European options, a number of trading strategies are implemented, showcasing their respective payoff functions:
<p align="center">
    <img src="https://github.com/PontusHovb/Option-Pricing/blob/master/Images/TradingStrategies2.png" width="600"/>
</p>
<p align="center"><i>Bear Put Spread (left) and Long Call Butterfly Spread (right)</i></p>

Unlike European options, American options have no well-known pricing models with closed-form solutions and instead Brownian Motion is used to simulate a sample of outcomes for which Longstaff Schwart's method can be used to calculate current price of American options.
<p align="center">
    <img src="https://github.com/PontusHovb/Option-Pricing/blob/master/Images/GBM.png" width="400"/>
</p>
<p align="center"><i>Example of GBM (Geometric Brownian Motion) outcomes</i></p>

- 💻 **Languages:** Python (pandas, numpy, scipy, matplotlib, jupyter notebook)
- 🔑 **Keywords:** European Options, American Options, Binomial Model, Black-Scholes, Longstaff Schwartz

## [Sudoku Solver 🧩](https://github.com/PontusHovb/Sudoku-Solver)
<p align="center">
    <img src="https://github.com/PontusHovb/Sudoku/blob/master/GIFs%20%26%20Graphs/overview.gif" width="600" alt="Solving algorithms"/>
</p>
<p align="center"><i>Left: Backtracking Algorithm. Right: Crook's Algorithm</i></p>

In this project I have implemented different algorithms (bruteforce, backtracking, candidate checking, placefinding, and Crook's algorithm) for solving sudokus to test both their speed, accuracy, and solving ability. This is done both in Python and C to build the most efficient and quickest algorithms. While backtracking algorithm is fast and reliable to solve all sudokus, it has lower accuracy (a lot of wrong tries before reaching the correct solution). Instead, more human-like algorithms such as the pen-and-paper based Crook's Algorithm can compete on similar level in terms of speed and solving ability but with perfect accuracy (only inputting a number if it is correct).'

- 💻 **Languages:** Python, C
- 🔑 **Keywords:** Bruteforce, backtracking, candidate checking, placefinding, and Crook's algorithm

## Other projects
[📊 Quantitative Finance](https://github.com/stars/PontusHovb/lists/quant)
- [📈 **Stock**](https://github.com/PontusHovb/Stock) Retrieving and processing historic stock data in **Python (yfinance)**, which can then be used for other projects. Model future stock prices and possible outcomes with **Brownian Motion**
- [♻️ **ESG/SBTi**](https://github.com/PontusHovb/ESG-SBTi) The effect of ESG-score and SBTi on financial performance for US stocks, coded in **R**

[🤖 Machine Learning & AI](https://github.com/stars/PontusHovb/lists/machine-learning-ai)
- [🐶 **CNN**](https://github.com/PontusHovb/CNN-CIFAR-10) **Convolutional neural network (CNN)** implemented in **PyTorch** for image classification on the CIFAR-10 dataset, and compared to pre-trained AlexNet model
- [🌻 **Image classification**](https://github.com/PontusHovb/Iris-Flower-ML) Image classification on Iris Flower dataset using 5 different machine learning methods in Scikit-learn (**Decision Tree**, **Support Vector Machine**, **Random Forest**, **Naive Bayes** and **K-nearest neighbour**). Implementing **Guassian Mixture Model** and **K-means Algorithm** from scratch
- [2️⃣ **SVM**](https://github.com/PontusHovb/Support-Vector-Machine) **Support Vector Machine (SVM)** both with soft margins and kernel (linear, poly and gaussian) for classifying handwritten numbers in MINST dataset.

[⚙️ Algorithms](https://github.com/stars/PontusHovb/lists/algorithms)
- [🗂️ **Sorting algorithms**](https://github.com/PontusHovb/Sorting-Algorithms) 8 of the most common sorting algorithms implemented in **C**, and compared based on **time complexity**

[🧮 Statistics](https://github.com/stars/PontusHovb/lists/statistics)
- [🎲 **Risk game**](https://github.com/PontusHovb/Risk-Game) Estimate winning probabilities for board game *Risk* using **Markov Chains** and **Monte-Carlo simulations**
- [🌡️ **Global temperatures**](https://github.com/PontusHovb/Global-Temperatures) Studying increasing global temperatures with **regression analysis** of emission-based variables in R.
- [🔍 **Logistic regression**](https://github.com/PontusHovb/Logistic-Regression) **Logistic regression with gradient descent and stochastic gradient descent** implemented from scratch using PyTorch.

Other
- [🖼️ **Image processing**](https://github.com/PontusHovb/Image-Processing) Image processing tools built from scratch in **JavaScript** for blurring, mirroring, zooming and greyscaling images
- [📝 **CV template**](https://github.com/PontusHovb/CV-Template) CV template in **LaTeX** to create well-formatted and modular CV (add and order experiences without need for reformatting)
