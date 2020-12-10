I implemented my project via the Google Colab notebook system. The reason I wanted to use a notebook environment is to see the graphs I was producing while
doing it, it would be easier both for me and anyone reading my notebook to install the python libraries necessary and also to more easily integrate text to label
and explain graphs. I initially planned on using Jupyter, but found it harder to install libraries, and also had issues with exporting outside of the Jupyter
notebook. When downloading, I had issues with converting outside of the .ipynb notebook format, and when i tried using the nbinteract module to maintain
interactivity, I was unable to connect my workbook in GitHub to binder due to recent issues with GitHub switching from the 'master' branch to 'main'. As such,
I decided to use Google Colab, which can be accessed without the installation of any specific libraries and has a better user interface than Jupyter.

I used several libraries and modules for my project: the main ones i made use of were pandas, which allows me to use more easily editable dataframes than csv,
matplotlib.pyplot, which allows me to plot graphs, requests and urllib.requests which allow me to access webpages to obtain data from, linregress from the
scipystats module which allows me to perform linear regression, and yfinance which allows me to access data directly from yahoo finance.

I wanted to get input from the user to have some element of interactivity, and so I felt that allowing the user to test their own financial skill by guessing
whether a stock would do well relative to the market would be interesting. I then made it so that this stock is included and compared to the main financial
indexes in graphs to see their performance.

I wanted to get input from the user in the form of today's date, in order so that this program can be used in later dates and also because when I tried, getting
references to a set date input rather than a changing variable of the last value in the list led to less issues.

For my statistical analysis, I used a scatter plot to get a visual interpretation, since I am comparing 2 numerical variables, pearson's producnt moment
correlation coefficient to get a general sense of the relationship and then linear regression to see whether the relationship is a linear one.