# AIML-Project-Series2
College Admission Chatbot

Testing the Application:

Using Postman: 
    Create a New POST Request:

            Open Postman and click on "New" to create a new request.
            Select "Request" from the dropdown.

    Set the URL to http://127.0.0.1:5000/chat:

             In the new request window, set the request type to POST using the dropdown menu next to the URL field.
             Enter http://127.0.0.1:5000/chat in the URL field.
    Configure the Request Body:

             Click on the "Body" tab below the URL field.
             Select the "raw" radio button.
             Choose "JSON" from the dropdown menu next to the "raw" option.
    Enter the JSON Object:
             {
                 "message": "What are the admission requirements?"
             }

    Send the Request:
               Click the "Send" button.
               Check the response that appears in the lower section of the Postman window. It should contain a JSON response from your Flask application.
                ![Screenshot 2024-05-29 152539](https://github.com/NehaAby/AIML-Project-Series2/assets/86865946/62a07fd1-7349-45f3-8d15-e9101016a780)

