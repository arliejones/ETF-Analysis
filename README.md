# Exchange Trade Fund Analysis

This program builds a financial database and web application by using SQL, Python, and the Voilà library to analyze the performance of a hypothetical fintech ETF for potential investment.

----

## Technologies
This application is written in Jupyter Lab Notebook in the Python programming language. The Python libraries, tools, and modules used in this application are Pandas, NumPy, hvPlot, SQLAlchemy, and Voilà. Documentation shown below:

[Pandas](https://pandas.pydata.org/docs/index.html), [NumPy](https://numpy.org/doc/), [hvPlot](https://hvplot.holoviz.org/), [SQLAlchemy](https://docs.sqlalchemy.org/en/14/), [Voilà](https://voila.readthedocs.io/en/stable/)

----

## Installation Guide
This program uses the Pandas library. If the user is not already running an environment that includes Pandas, then they will need to intall the library. Instructions shown in the installation guide --> [Pandas Installation Guide](https://pandas.pydata.org/docs/getting_started/install.html)

This program also uses SQLAlchemy and Voilà. To confirm that theses libraries are installed in your environment, open a terminal window and complete the following steps:

1. Activate your dev environment

2. Run the following command to ensure SQLAlchemy installation:

        conda list sqlalchemy
        
If SQLAlchemy is already installed, 'sqlalchemy' and its version number will display in your terminal. 

3. If sqlalchemy is not installed, run the following command to install it:

        pip install SQLAlchemy
       
4. If your dev environment is not already open, reopen it

5. Run the following command to install Voila:

        conda install -c conda-forge voila
        
6. Confirm the installation:
    
        conda list voila
        
If Voilà successfully installed, 'voila' and its version number will display in your terminal.
    
*This program is run in an Anaconda environment. Installation for libraries may be different for other environments.*

----

## Usage
For the program to run correctly, the user must make sure that all libraries and modules are correctly imported in the beginning of the code. This looks like:

    import pandas as pd
    
    import hvplot.pandas

    import numpy as np
    
    import sqlalchemy as sql


**The program is comprised of 4 parts:**

1. Analyze a single asset in the ETF

2. Optimize data access with advanced SQL queries

3. Analyze the ETF portfolio

4. Deploy the notebook as a web application

The when deployed as a web application via Voila, the program will look like this:

https://user-images.githubusercontent.com/101435438/168150800-e9b433e2-db74-4049-bccc-199d55291ee9.mov


----

## Contributors

Arlie Jones

[E-mail](arliejones98@gmail.com)  |  [LinkedIn](https://www.linkedin.com/in/arlie-jones-020092159/)

----

## License

None
