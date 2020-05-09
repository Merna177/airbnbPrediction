# airbnbPrediction
This challenge from Airbnb ask us to predict the “Country Destination” that a new user will make as his or her first booking based on the given data sets.


# Features:
train_users.csv-->the training set of users test_users.csv--> the test set of users id: user id date_account_created: the date of account creation timestamp_first_active: timestamp of the first activity, note that it can be earlier than date_account_created or date_first_booking because a user can search before signing up date_first_booking: date of first booking gender age signup_method signup_flow: the page a user came to signup up from language: international language preference affiliate_channel: what kind of paid marketing affiliate_provider: where the marketing is e.g. google, craigslist, other first_affiliate_tracked: whats the first marketing the user interacted with before the signing up signup_app first_device_type first_browser country_destination: this is the target variable you are to predict sessions.csv - web sessions log for users user_id: to be joined with the column 'id' in users table action action_type action_detail device_type secs_elapsed.

# My Approach
1)Data collecting: downloading all the data provided by Airbnb.
2) Data visualization: to know the relations between features and how they affect the target value
3)Data Wrangling: data cleaning,seek mistakes in data.
4)Model and Prediction: to get final results

# Dataset Resource: https://www.kaggle.com/c/airbnb-recruiting-new-user-bookings/data
My Final Score: 0.85330 in private score  , 0.84763 in public score
    
