# wildrydes

A rebuild of the serverless website WildRydes Workshop in Vue.js with AWS Amplify CLI.
#� �U�n�i�c�o�r�n�-�S�e�r�v�e�r�l�e�s�s�
�
�

This is only source code, it no longer works as you need to create your own API

Steps:

1. First step was setting my dev environment using Cloud9 and cloning the directory used for the project.

2. hosted the static website using amplify by creating a new application.

3. in the cli i created a new user pool with Cognito so i could authenticate my users via username.

4. created an API with the POST method execution to send a request to my lambda function.

5. My lambda function requested a rideID number to verify the request and send the user his ride.
