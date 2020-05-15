## situps number path uncomfortable
* greet
  - utter_situps_number
* inform_number_situps
  - utter_situps_description
* start OR affirm
  - utter_feedback_lower_back
* feedback_lower_back_question OR affirm OR start
  - utter_feedback_affirmative 
* inform_number_situps OR thanks OR start
  - utter_feedback_progress
* affirm
  - utter_feedback_progress_affirmative
* start OR affirm OR complete 
  -utter_metrics

## situps number path comfortable
* greet
  - utter_situps_number
* inform_number_situps
  - utter_situps_description
* start OR affirm 
  - utter_feedback_lower_back
* feedback_lower_back_question OR affirm OR start
  - utter_feedback_affirmative
* inform_number_situps OR thanks OR start
  - utter_feedback_progress
* deny
  - utter_feedback_progress_negative
* start OR affirm OR complete
  -utter_metrics

## torso question path
* torso
 - action_torso


## happy path
* deny
  - utter_greet
* mood_great
  - utter_happy

## sad path 1
* deny
  - utter_greet
* mood_unhappy
  - utter_cheer_up
  - utter_did_that_help
* affirm
  - utter_happy

## sad path 2
* deny
  - utter_greet
* mood_unhappy
  - utter_cheer_up
  - utter_did_that_help
* deny
  - utter_goodbye

## say goodbye
* goodbye
  - utter_goodbye

