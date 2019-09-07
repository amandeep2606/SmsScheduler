# SmsScheduler

This app takes the following arguments, and schedules the sms
according to Date &amp; time of
schedule as per geography.

1. Csv file (mobile number, country)
2. Schedule time.
3. Message text body.

This app use sms-magic api for sending sms.

### Required Environment variables:

apiKey is required env variable

export apiKey=sms-magic api key

For apiKey you have to create an account with smsmagic and verify your email.


### Run application

1. git clone https://github.com/amandeep2606/SmsScheduler.git
2. pip install -r requirements.txt
3. put a .csv file containing mobile numbers and country
3. python service.py





