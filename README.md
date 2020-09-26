# Machine-Learning-Per-Title-Encoding
Implement Machine-Learning methods on Youtube videos (Per-Title Encoding) 

# Description
Nowadays video streaming plays an important role in our daily lives. To achieve the best video quality, some important attributes should be taken into consideration.
For example internet bandwidth is one those. Some companies like Netflix, Amazon and YouTube have tried to provide the best video quality according to different 
internet bandwidths to satisfy their user’s demands, therefore these companies have offered some solutions to reach this goal.

one of the main approaches which is suitable for most of the videos having a diverse set of pixel complexities, is the fixed bitrate ladder approach.
This approach came with a set of problems such as video artifacts in high-complexity videos or waste of bandwidth, in low-complex videos.


One optimal quality metric approach developed by Netflix is VMAF (Video Multi-Method Assessment Fusion).Here we have three machine learning 
methods Linear Regression, Support Vector Regression & Random Forest to predict VMAF to find the optimal video quality for different videos based on their content.
## Code steps

    1 : RD_Curves and Convex_hull_Final .ipynb
    2 : Blind_Cross_Validation_and_Split_Dataset_Final.ipynb
    3 : Leave_One_Out_validation_Final.ipynb
    
## Installation

Use the package manager [pip](https://pip.pypa.io/en/stable/) to install libraries or you can do it by conda.

```bash
pip install scikit-learn

```

```bash
pip install numpy
pip install pandas
pip install scipy
pip install matplotlib
```

## Results

I have found out that among these methods the Random Forest method was giving the most optimal results regarding the MSE and RMSE values. 
on the other hand the results obtained from the linear regression method 
re relatively not optimal.

## Contributing
Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.

## Dependency

The code is base on our Data_set so you just need to modify code a bit.
    
