## happy path
* greet
    - utter_greet
* create_case
	- utter_ask_description
* inform{"description": "New case"}
	- utter_ask_category
* inform{"category":"Pricing Exception"}
	- utter_ask_security
* inform{"security":"My security"}
    - utter_slot_values

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
