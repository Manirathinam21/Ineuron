# Ineuron
Ineuron | Perceptron
       
## Add URL -
[Git Handbook](https://guides.github.com/introduction/git-handbook/)       

## Add IMAGE -
![Git Image](plots/add.png)

## Python code-
```bash
git add . && git commit -m "first commit" && git push origin main 

```
```python
def prepare_data(df):
    """it is used to separate the dependent variables and independent features
    Args:
        df (pd.DataFrame): its the pandas DataFrame to
    Returns:
        tuple: it returns the tuples of dependent variables and independent variables
    """
    logging.info("Preparing the data by segregating the independent and dependent variables")
    x = df.drop("y", axis=1)
    y = df["y"]
    return x, y

```