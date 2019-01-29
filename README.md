Sample Machine Learning Python project structure:

-- LICENSE
-- README.md
-- environment.yml (conda env [export > | [create|update] -n ocr-env -f ] environment.yml) 
-- setup.py (this now is a package)
-- data
    -- external
    -- raw
    -- interim
    -- processed
-- src
    -- __init__.py
    -- data
        -- __init__.py
        -- get_data.py
    -- model
        -- __init__.py
        -- manage_model.py
        -- train_model.py
    -- learn
        -- __init__.py
        -- learnPython.py
        -- learnNumpy.py
        -- learnPandas.py
        -- learnScipy.py
        -- learnMatplotlib.py
        -- learnScikit-learn.py
    -- gui
        -- __init__.py
        -- display.py
    -- cli
        -- __init__.py
        -- main.py (using varargs over click)
-- result
-- model
-- reports (quality)
-- docs (sphinx)
-- test (pytest)
-- ref (references of links, pdf white papers)

Principles: statistics, probability, logic, mathematical optimization, reinforcement learning, and control theory.
Modes: Supervised(Classification, Regression) , Unsupervised , Semi-supervised , Reinforcement
Steps: Defining a Problem, Preparing Data, Evaluating Algorithms, Improving Results, Presenting Results

Pre-requisites: Python, Numpy, pandas, scipy, matplotlib
Broadly: Data mining, Bayesian analysis, Vision processing, Language processing, 
    Forecasting/trends, weather Pattern recognition, Games, Expert systems, Robotics
Algorithms: linear regression, logistic regression, Naïve Bayes, k-means, K nearest neighbor, and Random Forest



