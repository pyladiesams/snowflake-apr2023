# An introduction to Data Science using Snowflake 

### Presentation: [Presentation_name](workshop/Presentation_template.pptx)

## Workshop description

In this session, you will learn how Snowflake can enable and accelerate end-to-end Data Science workflows. 
We will train and deploy a model using the Snowpark library for Python and build a Streamlit app that allows business users to consume the results of our model predictions in a simple web app - all using pure Python, without any front-end experience required.

## Requirements

* Git
* Python 3.8
    * Note that we will be creating a Python environment with 3.8
* Miniconda
* A Snowflake account with [Anaconda Packages enabled by ORGADMIN](https://docs.snowflake.com/en/developer-guide/udf/python/udf-python-packages#using-third-party-packages-from-anaconda). If you do not have a Snowflake account, you can register for a [free trial account](https://signup.snowflake.com). Choose the Enterprise edition.


## Usage
* Clone the repository and navigate to the **workshop** folder
* Install the required libraries with conda:  `conda env create -f jupyter_env.yml`
* Activate new environment: `conda activate snowpark_pyladies`
* Update `connection.json` with your Snowflake credentials
* Install the Snowflake extension for VS code
* Run the scripts and the notebooks
* After deploying the model, open a terminal window and run `streamlit run 3-Snowpark_Streamlit_Revenue_Prediction.py`    
* Congratulations! You have just created a cool app to showcase your predictive powers :rocket:     

Quick Recap :snowman: : You've successfully performed data engineering tasks and trained a Linear Regression model to predict future ROI (Return On Investment) of variable advertising spend budgets across multiple channels using Snowpark for Python and scikit-learn. And then you created a Streamlit application that uses that model to generate predictions on new budget allocations based on user input.


## Video record
Re-watch [this YouTube stream](https://bit.ly/3kMM8N8)


## Keep-up the learning

For an up-to-date versions, please refer to the [QuickStart Guide](https://quickstarts.snowflake.com/guide/getting_started_with_dataengineering_ml_using_snowpark_python/index.html).

## Credits
This workshop was set up by @pyladiesams and @avecaile and @iamontheinet


