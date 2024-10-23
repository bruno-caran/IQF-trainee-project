<h1>General Information <dt></dt></h1>
Quantitative asset allocation strategy utilizing factor investing and forecasting returns using multiple regression models. 

Full performance attribution, including graphics, is available by downloading the [raw .html file]([link](https://github.com/bruno-caran/IQF-trainee-project/blob/main/quantstats-tearsheet.html)).  The dataset is available in the .zip file.

<h1>Strategy Tearsheet <dt></dt></h1>
<h4>19 Feb, 2001 - 9 May, 2023</h4>
<div id="right"> <h3>Key Performance Metrics</h3> <table><thead><tr><th>Metric</th><th>Strategy</th><th>Benchmark</th></tr></thead><tbody><tr><td>Cumulative Return</td><td>29,232.85%</td><td>533.17%</td></tr><tr><td>CAGR﹪</td><td>29.12%</td><td>8.66%</td></tr><tr><td colspan="3"><hr></td></tr><tr><td>Sharpe</td><td>2.18</td><td>1.02</td></tr><tr><td>Prob. Sharpe Ratio</td><td>100.0%</td><td>98.19%</td></tr><tr><td>Smart Sharpe</td><td>2.15</td><td>1.0</td></tr><tr><td>Sortino</td><td>4.88</td><td>1.45</td></tr><tr><td>Smart Sortino</td><td>4.81</td><td>1.43</td></tr><tr><td>Sortino/√2</td><td>3.45</td><td>1.03</td></tr><tr><td>Smart Sortino/√2</td><td>3.4</td><td>1.01</td></tr><tr><td>Omega</td><td>1.76</td><td>1.76</td></tr><tr><td colspan="3"><hr></td></tr><tr><td>Max Drawdown</td><td>-46.87%</td><td>-56.45%</td></tr><tr><td>Longest DD Days</td><td>749</td><td>2492</td></tr><tr><td>Volatility (ann.)</td><td>69.28%</td><td>58.5%</td></tr><tr><td>R^2</td><td>0.07</td><td>0.07</td></tr><tr><td>Information Ratio</td><td>0.07</td><td>0.07</td></tr><tr><td>Calmar</td><td>0.62</td><td>0.15</td></tr><tr><td>Skew</td><td>7.18</td><td>-0.45</td></tr><tr><td>Kurtosis</td><td>111.17</td><td>3.33</td></tr><tr><td colspan="3"><hr></td></tr><tr><td>Expected Daily</td><td>0.52%</td><td>0.17%</td></tr><tr><td>Expected Monthly</td><td>2.14%</td><td>0.69%</td></tr><tr><td>Expected Yearly</td><td>28.02%</td><td>8.35%</td></tr><tr><td>Kelly Criterion</td><td>22.82%</td><td>4.38%</td></tr><tr><td>Risk of Ruin</td><td>0.0%</td><td>0.0%</td></tr><tr><td>Daily Value-at-Risk</td><td>-6.58%</td><td>-5.83%</td></tr><tr><td>Expected Shortfall (cVaR)</td><td>-6.58%</td><td>-5.83%</td></tr><tr><td colspan="3"><hr></td></tr><tr><td>Max Consecutive Wins</td><td>10</td><td>11</td></tr><tr><td>Max Consecutive Losses</td><td>8</td><td>7</td></tr><tr><td>Gain/Pain Ratio</td><td>0.76</td><td>0.18</td></tr><tr><td>Gain/Pain (1M)</td><td>1.55</td><td>0.41</td></tr><tr><td colspan="3"><hr></td></tr><tr><td>Payoff Ratio</td><td>1.34</td><td>0.89</td></tr><tr><td>Profit Factor</td><td>1.76</td><td>1.18</td></tr><tr><td>Common Sense Ratio</td><td>2.46</td><td>1.22</td></tr><tr><td>CPC Index</td><td>1.31</td><td>0.58</td></tr><tr><td>Tail Ratio</td><td>1.4</td><td>1.03</td></tr><tr><td>Outlier Win Ratio</td><td>4.21</td><td>3.63</td></tr><tr><td>Outlier Loss Ratio</td><td>4.27</td><td>2.84</td></tr><tr><td colspan="3"><hr></td></tr><tr><td>MTD</td><td>0.56%</td><td>3.05%</td></tr><tr><td>3M</td><td>1.0%</td><td>-0.66%</td></tr><tr><td>6M</td><td>1.34%</td><td>-9.35%</td></tr><tr><td>YTD</td><td>6.45%</td><td>-1.49%</td></tr><tr><td>1Y</td><td>11.43%</td><td>0.45%</td></tr><tr><td>3Y (ann.)</td><td>24.64%</td><td>3.25%</td></tr><tr><td>5Y (ann.)</td><td>28.19%</td><td>7.21%</td></tr><tr><td>10Y (ann.)</td><td>25.41%</td><td>6.8%</td></tr><tr><td>All-time (ann.)</td><td>29.12%</td><td>8.66%</td></tr><tr><td colspan="3"><hr></td></tr><tr><td>Best Day</td><td>70.65%</td><td>18.34%</td></tr><tr><td>Worst Day</td><td>-20.98%</td><td>-21.46%</td></tr><tr><td>Best Month</td><td>74.71%</td><td>18.55%</td></tr><tr><td>Worst Month</td><td>-29.06%</td><td>-29.1%</td></tr><tr><td>Best Year</td><td>151.86%</td><td>96.23%</td></tr><tr><td>Worst Year</td><td>-43.68%</td><td>-41.12%</td></tr><tr><td colspan="3"><hr></td></tr><tr><td>Avg. Drawdown</td><td>-5.95%</td><td>-9.78%</td></tr><tr><td>Avg. Drawdown Days</td><td>78</td><td>154</td></tr><tr><td>Recovery Factor</td><td>623.69</td><td>9.44</td></tr><tr><td>Ulcer Index</td><td>0.13</td><td>0.2</td></tr><tr><td>Serenity Index</td><td>399.67</td><td>2.72</td></tr><tr><td colspan="3"><hr></td></tr><tr><td>Avg. Up Month</td><td>7.42%</td><td>6.4%</td></tr><tr><td>Avg. Down Month</td><td>-4.2%</td><td>-7.04%</td></tr><tr><td>Win Days</td><td>55.85%</td><td>54.95%</td></tr><tr><td>Win Month</td><td>61.0%</td><td>54.48%</td></tr><tr><td>Win Quarter</td><td>65.17%</td><td>60.0%</td></tr><tr><td>Win Year</td><td>78.26%</td><td>56.52%</td></tr><tr><td colspan="3"><hr></td></tr><tr><td>Beta</td><td>0.32</td><td>-</td></tr><tr><td>Alpha</td><td>1.32</td><td>-</td></tr><tr><td>Correlation</td><td>26.64%</td><td>-</td></tr><tr><td>Treynor Ratio</td><td>92644.55%</td><td>-</td></tr></tbody></table> <div id="eoy"><h3>EOY Returns vs Benchmark</h3> <table><thead><tr><th>Year</th><th>Benchmark</th><th>Strategy</th><th>Multiplier</th><th>Won</th></tr></thead><tbody><tr><td>2001</td><td>-21.04</td><td>24.60</td><td>-1.17</td><td>+</td></tr><tr><td>2002</td><td>-15.90</td><td>-16.85</td><td>1.06</td><td>-</td></tr><tr><td>2003</td><td>96.23</td><td>127.87</td><td>1.33</td><td>+</td></tr><tr><td>2004</td><td>18.83</td><td>89.08</td><td>4.73</td><td>+</td></tr><tr><td>2005</td><td>27.24</td><td>2.68</td><td>0.10</td><td>-</td></tr><tr><td>2006</td><td>33.43</td><td>18.13</td><td>0.54</td><td>-</td></tr><tr><td>2007</td><td>43.65</td><td>151.86</td><td>3.48</td><td>+</td></tr><tr><td>2008</td><td>-41.12</td><td>-43.68</td><td>1.06</td><td>-</td></tr><tr><td>2009</td><td>82.33</td><td>83.29</td><td>1.01</td><td>+</td></tr><tr><td>2010</td><td>-0.80</td><td>80.88</td><td>-101.23</td><td>+</td></tr><tr><td>2011</td><td>-16.91</td><td>-5.02</td><td>0.30</td><td>+</td></tr><tr><td>2012</td><td>7.83</td><td>18.38</td><td>2.35</td><td>+</td></tr><tr><td>2013</td><td>-15.51</td><td>17.88</td><td>-1.15</td><td>+</td></tr><tr><td>2014</td><td>-1.20</td><td>-2.49</td><td>2.07</td><td>-</td></tr><tr><td>2015</td><td>-14.58</td><td>10.88</td><td>-0.75</td><td>+</td></tr><tr><td>2016</td><td>34.85</td><td>36.74</td><td>1.05</td><td>+</td></tr><tr><td>2017</td><td>28.17</td><td>35.06</td><td>1.24</td><td>+</td></tr><tr><td>2018</td><td>13.49</td><td>39.63</td><td>2.94</td><td>+</td></tr><tr><td>2019</td><td>37.45</td><td>78.42</td><td>2.09</td><td>+</td></tr><tr><td>2020</td><td>1.88</td><td>42.72</td><td>22.70</td><td>+</td></tr><tr><td>2021</td><td>-11.60</td><td>-8.09</td><td>0.70</td><td>+</td></tr><tr><td>2022</td><td>3.02</td><td>25.12</td><td>8.33</td><td>+</td></tr><tr><td>2023</td><td>-1.49</td><td>6.45</td><td>-4.32</td><td>+</td></tr></tbody></table></div>  </div>
