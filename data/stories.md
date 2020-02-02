## happy path
* greet
    - utter_greet
* create_case
    - case_create_form
    - form{"name": "case_create_form"}
    - form{"name": null}
    - utter_slots_values
* thankyou
    - utter_noworries

## unhappy path
* greet
    - utter_greet
* create_case
    - case_create_form
    - form{"name": "case_create_form"}
* chitchat
    - utter_chitchat
    - case_create_form
    - form{"name": null}
    - utter_slots_values
* thankyou
    - utter_noworries

## bot challenge
* bot_challenge
  - utter_iamabot

## Tell me a joke !
* greet
    - utter_greet
* tell_joke
    - action_joke
* thankyou
    - utter_noworries

## New Story

* greet
    - utter_greet
* tell_joke
    - action_joke
* greet
* tell_joke
