Hello SpaceApps!

What The Crop! is our crowd-sourced crop alert system for farmers on the ground.

The goal of What The Crop! is to improve crop yields by providing farmers with an alert system 

Here's how they do it:

    1. Farmers SMS status of their crops
    2. They receive alerts or updates on anomalies

Just 2 steps! Examples of alerts include:

    1. Extreme weather conditions
    2. Possible pest infestation

We envision What The Crop to be able to provide insights into the crop status as well.
For example, if a farmer is spots a new kind of pest in his field, the farmer
can send us a MMS with a picture of the pest, and we should be able to use 
make use of our data source to make a guess what the pest is.

# How things work

The whatthecrop-twilio submodule takes care of notifications.

It handles:

    1. Receiving SMS from farmers
    2. Sending alerts to individual farmers or by region

It's a Python/Django app that is configure to run on IBM Bluemix, and uses Twilio for all telecommunications
