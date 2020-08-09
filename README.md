This repository demonstrates how to integrate [GitHub Actions](https://docs.github.com/en/actions) to (upon a new commit):

- Automatically train a small Random Forest Regressor model on the [wine quality dataset](https://www.kaggle.com/uciml/red-wine-quality-cortez-et-al-2009).
- Automatically log the training and other important model metrics to Weights and Biases (`wandb`). 
- Cache Python dependencies so that old dependencies do not get installed each time a run is triggered. 
- Generate a `metrics.csv` file after a run is successfully completed. 

![](https://i.ibb.co/JqZWHDC/image.png)

## Acknowledgements

[This video](https://www.youtube.com/watch?v=9BgIDqAzfuA) by DVCorg helped me a lot to clear the initial concepts regarding GitHub Actions. 
