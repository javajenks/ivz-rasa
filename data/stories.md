## happy path
* greet
    - utter_greet
* affirm
    - case_create_form
    - form{"name": "case_create_form"}
    - form{"name": null}
    - utter_slots_values
* goodbye
    - utter_noworries

## bot challenge
* bot_challenge
  - utter_iamabot

## Tell me a joke !
* greet
    - utter_greet
* listen_to_joke
    - action_joke
* thankyou
    - utter_noworries

## No case create
* greet
    - utter_greet
* deny
    - utter_noworries
