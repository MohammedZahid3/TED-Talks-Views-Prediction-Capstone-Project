
![download](https://user-images.githubusercontent.com/96717126/229345854-e19e93a3-78c9-4d0b-8b1c-8a47bc75cb7c.jpg)
# Project Summary :-
**TED=Technology Entertainment And Design**

**TED is an unprofitable organisation that post videos online in Free. TED is devoted to spreading powerful ideas on just about any topic. These datasets contain over 4,000+ TED talks including transcripts in many languages. It was basically started as a conference in 1984 that designed by Richard saul wurman but due to some reasons it was unsuccesful. After 6 years in 1990 ,it back with a bang. In TED, speaker share their views and ideas to the society in 18 minutes. As of 2015, TED and its sister TEDx chapters have published more than 2000 talks for free consumption by the masses and its speaker list boasts of the likes of Al Gore, Jimmy Wales, Shahrukh Khan, and Bill Gates.**

            Slogan Of TED :- IDEAS WORTH SPREADING ⏰
          
# Objective :
- The main objective is to build a predictive model, which could help in predicting the views of the videos uploaded on the TEDx website.

# Dataset info :
- 1.Number of records: 4,005
- 2.Number of features: 19

# The dataset contains features like :
- `talk_id:` A unique identifier for each TED Talk video.
- `title:` The title of the talk.
- `speaker_1:` The primary speaker for the talk.
- `all_speakers:` A list of all the speakers for the talk.
- `occupations:` The occupations of the speakers.
- `about_speakers:` Information about the speakers, such as their backgrounds and expertise.
- `recorded_date:` The date the talk was recorded.
- `published_date:` The date the talk was published on the TED Talks YouTube channel.
- `event:` The name of the TED event where the talk was given.
- `native_lang:` The language the talk was given in.
- `available_lang:` The languages the talk is available in.
- `duration:` The length of the video.(in sec.)
- `topics:` The topics covered in the talk.
- `related talks:` Other TED Talks that are related to this talk.
- `url:` The URL of the video.
- `description:` A brief description of the talk.
- `transcript:` A transcript of the talk.

# Target Variable :
- `views:` The number of views the video has received.

# Project Work flow :-
- **Importing Neccessary Libraries**
- **Data Wrangling**

      1. Gathering Data
      2. Assessing Data
      3. Cleaning Data 
- **EDA and Features Engineering on features**
- **Features Transformation and selection**
- **Remove Multicollinearity**
- **Model implementation and Pre-processing**

      1. Train, Test and Split
      2. preprocessing using column-transformer
      3. make best pipeline         
- **Fitting the regression models and HyperParameter Tuning**
- **Final selection of the model**
- **Conclusion**

# Algorithms used for ML model implementation :-
- `Linear Regression`
- `Ridge Regression(L2)`
- `Lasso Regression(L1)`
- `DecisionTreeRegressor`
- `RandomForestRegressor`
- `AdaBoostRegressor`
- `GradientBoostingRegressor`
- `XGBRegressor`
- `VotingRegressor`
- `StackingRegressor`










