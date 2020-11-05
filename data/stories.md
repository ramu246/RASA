## happy path
* greet
  - utter_greet
* mood_great
  - utter_happy

## sad path 1
* greet
  - utter_greet
* mood_unhappy
  - utter_cheer_up
  - utter_did_that_help
* affirm
  - utter_happy
  
## sad path 2
* greet
  - utter_greet
* mood_unhappy
  - utter_cheer_up
  - utter_did_that_help
* deny
  - utter_goodbye
  
## say goodbye
* goodbye
  - utter_goodbye
  
## bot challenge
* bot_challenge
  - utter_iamabot
  
## name story
* what_name
  - utter_name
  
## create
* create
  - utter_create

## create item
* create_item
  - utter_item
  
## create workflow
* Apply_workflow
  - utter_workflow
  
## create dataset
* create_dataset
  - utter_dataset

## create form
* create_form
  - utter_form
 
