# Training with best represantation
The aim of this project is to achieve comparable results to orthodox approaches by using a smaller subset of our original data distribution. Traditional methods often require large datasets, which can be challenging in terms of computational resources and time. This project explores the possibility of efficiently training a classifier by selecting a representative subset of the data, resulting in comparable performance while reducing computational requirements.

## Requirements
The following packages are required to run the project:

- ipython==8.6.0
- matplotlib==3.6.0
- numpy==1.23.4
- scikit_learn==1.1.3
- torch==2.0.1
- torchvision==0.15.2
- tqdm==4.64.1
  
Please make sure you have these packages installed in your environment before running the project. You can install the the required packages with,
```
pip install -r requirements.txt
```
## Usage
1. Clone the repository to your local machine using the following command:
```
git clone https://github.com/oguzaliarslan/training-with-best-represantation
```
2. Navigate to the project directory
3. Make sure you've installed the requirements.
4. Run the cells in "main.ipynb"

## Results
Accuracies of both subset and whole dataset approach can be seen below.

![Training accuracies](https://i.imgur.com/sVhC3gf.png)


![Test accuracies](https://i.imgur.com/P8jHpPS.png)
