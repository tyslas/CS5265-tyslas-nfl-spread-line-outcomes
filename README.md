# CS5262-tyslas-nfl-spread-line-outcomes

#### Performance Metrics
For this project I will use Precision as my main performance metric to determine the value of the model.
I will calculate this with the following formula:

- `Precision = TP / (TP + FP)`
    - I will mainly focus the number times the model is able to correctly pick the winner of the game.
    - If this is successful I will also use Precision to determine if the model can correctly predict when winning or losing teams can cover the spread
    - If this is successful I will also use Precision to determine if the model can correctly predict when total points in the game will be greater than the over/under line 
    - An example confusion matrix for evaluating Precision based on the winning team of each game could look like what's shown below:
    ```yaml
                        Predicted:
                        Win       Loss
    Actual:   Win       50          10
              Loss      5           35

    ```

After examining Precision, I will evaluate the Profitability of the model
- Profitability
  - I will attempt to do this by calculating the net profit or return on investment (ROI) based on the betting each of the above strategies
    - This will require considering stake size and bet frequency

# Comments/Feedback from Derius
Recommend adding header # References section
Recommand adding link https://www.kaggle.com/datasets/tobycrabtree/nfl-scores-and-betting-data to references
