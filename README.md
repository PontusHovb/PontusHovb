## Hi there 👋

My name is Pontus and I'm a 1st year **MSc-student in Financial Mathematics at KTH** - Royal Institute of Technology with previous exchange studies at **National University of Singapore (NUS)** and a completed BSc in Industrial Engineering & Management from KTH. Selected coursework include Portfolio Theory \& Risk Management, Quantitative Finance, Machine Learning, Language Engineering, Probability Theory, Calculus, Applied Computer Science, Regression Analysis, Game Theory and Markov Processes.

Previous professional experience includes **Visiting Associate @ BCG Platinion** (tech/IT-strategy consulting internship), **Junior Quantitative Analyst @ Söderberg & Partners** building and maintaining quantitative models for money market, fixed income and equity funds using Python (pandas, numpy, scikit-learn), SQL and VBA. I've also worked as **Intern/business developer @ If P&C Insurance** in commerical pricing where I analyzed claims data to assess, model and price commerical property risk using SQL & SAS as well as building dashboards for portfolio follow-up in PowerBI using DAX and PowerQuery.

Programming experience in **Python**, **SQL**, **VBA** and **R** with some experience in MATLAB, JavaScript and C/C++.

# Projects 🚀
## [The Impact of the Momentum-Factor on Performance 📘](https://github.com/PontusHovb/Bachelor-Thesis)
Bachelor Thesis in Mathematical Statistics - KTH Royal Institute of Technology <br />
**Authors**: Pontus Hovberger & Hugo Brunlid <br />
<div style="display: flex; justify-content: center; align-items: center;">
    <div style="text-align: center; margin: 0 10px;">
        <img width="200" alt="Singlefactor model" src="https://github.com/PontusHovb/Bachelor-Thesis/blob/main/Figures/Singlefactor%20model.png"/>
        <p>Momentum coefficient over time for singlefactor model</p>
    </div>
    <img width="25" src="https://github.com/PontusHovb/Sudoku/assets/67122081/5818307d-976f-4cfc-9ad9-cf1ef711ceb1"/>
    <div style="text-align: center; margin: 0 10px;">
        <img width="300" alt="Multifactor model" src="https://github.com/PontusHovb/Bachelor-Thesis/blob/main/Figures/Multifactor%20model.png"/>
        <p>Momentum coefficient over time for multifactor model</p>
    </div>
</div>

---

In this thesis we explored the kurtosis of momentum, and 'momentum crashes' both from 2008 as discussed in previous research but also in the light of recent covid-19 stock crash. This is done both using a singlefactor model split by Morningstar Category (based on style and size orienation) and also a multifactor model that in addition to momentum (excess past returns) incorporates size orientation, style orientation and management fee are used to predict excess future returns. Findings of predictive power and longevity of momentum by Carhart are still true for US Equity funds 2000-2023 although impact of size & style factors have significantly changed since Carhart Four-Factor model was first presented in 1997. 
<div style="display: flex; justify-content: center; align-items: center;">
    <div style="text-align: center; margin: 0 10px;">
        <img width="200" alt="Average excess return per decile (2000-2023)" src="https://github.com/PontusHovb/Bachelor-Thesis/blob/main/Figures/Average%20Excess%20Return%20for%20each%20Decile.png"/>
        <p>Average yearly excess returns for each decile (2000-2023)</p>
    </div>
    <img width="25" src="https://github.com/PontusHovb/Sudoku/assets/67122081/5818307d-976f-4cfc-9ad9-cf1ef711ceb1"/>
    <div style="text-align: center; margin: 0 10px;">
        <img width="300" alt="Average excess return per decile (1962-1987)" src="https://github.com/PontusHovb/Bachelor-Thesis/blob/main/Figures/Carhart%20Four-Factor%20model.png"/>
        <p>Average yearly excess returns for each decile (1962-1987) (Carhart, 1997</p>
    </div>
</div>

---

- 💻 **Languages:** Python (pandas, numpy, scikit-learn, jupyter notebook)
- 🔑 **Keywords:** Momentum, Carhart Four-Factor Model, Multifactor Model, Momentum Crashes 
  
## [Sudoku Solver 🧩](https://github.com/PontusHovb/Sudoku-Solver)
<div style="display: flex; justify-content: center; align-items: center;">
    <div style="text-align: center; margin: 0 10px;">
        <img width="200" alt="Backtracking" src="https://github.com/PontusHovb/Sudoku/blob/master/GIFs%20%26%20Graphs/bruteforce_lookahead.gif"/>
        <p>Backtracking Algorithm</p>
    </div>
    <img width="25" src="https://github.com/PontusHovb/Sudoku/assets/67122081/5818307d-976f-4cfc-9ad9-cf1ef711ceb1"/>
    <div style="text-align: center; margin: 0 10px;">
        <img width="300" alt="Average time per sudoku" src="https://github.com/PontusHovb/Sudoku/blob/master/GIFs%20%26%20Graphs/average_time.png"/>
        <p>Average time to solve each sudoku</p>
    </div>
    <img width="25" src="https://github.com/PontusHovb/Sudoku/assets/67122081/5818307d-976f-4cfc-9ad9-cf1ef711ceb1"/>
    <div style="text-align: center; margin: 0 10px;">
        <img width="200" alt="Crook's Algorithm" src="https://github.com/PontusHovb/Sudoku/blob/master/GIFs%20%26%20Graphs/crooks_algorithm.gif"/>
        <p>Crook's Algorithm</p>
    </div>
</div>

---

In this project I have implemented different algorithms (bruteforce, backtracking, candidate checking, placefinding, and Crook's algorithm) for solving sudokus to test both their speed, accuracy, and solving ability. This is done both in Python and C to build the most efficient and quickest algorithms. While bruteforce and backtracking algorithms are fast and reliable to solve all sudokus, they have lower accuracy (a lot of wrong tries before reaching the correct solution). Instead, more human-like algorithms such as the pen-and-paper based Crook's Algorithm can perform on similar level in terms of speed and solving ability but with perfect accuracy (only inputting a number if it is correct).

- 💻 **Languages:** Python, C
- 🔑 **Keywords:** Bruteforce, backtracking, candidate checking, placefinding, and Crook's algorithm
