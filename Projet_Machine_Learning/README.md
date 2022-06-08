### Initulé du projet :

    Projet Machine Learning pour la prédiction des prix des véhicules au niveau du marché américain

### Etudiant du groupe :

    Ayoub HAJJI

### Les bibliothèques nécessaires pour le projet :

    import pandas as pd
    import matplotlib.pyplot as plt
    import seaborn as sns
    from sklearn.model_selection import train_test_split
    from sklearn.linear_model import LinearRegression
    from sklearn.linear_model import LassoCV,RidgeCV
    from sklearn.neighbors import KNeighborsRegressor
    from sklearn.svm import SVR
    from sklearn.tree import DecisionTreeRegressor
    from sklearn.ensemble import RandomForestRegressor , AdaBoostRegressor ,GradientBoostingRegressor
    from sklearn.preprocessing import StandardScaler,MinMaxScaler
    from sklearn.metrics import mean_squared_error,mean_absolute_error
