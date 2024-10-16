# Photography-Business-Botpress-AI-Chatbot
*Complete WhatsApp flow for a photography business. Ask AI for general information, follow steps to book a photography package.*

You can try it the Botpress WebChat preview: https://cdn.botpress.cloud/webchat/v2.2/shareable.html?configUrl=https://files.bpcontent.cloud/2024/10/16/20/20241016202619-4RSBNTAX.json

## Goals ##

* Automate the booking process, which is currently done manually — saving time for the business owner.
* Provide a great user experience for clients, especially recurring ones.
* Allow new clients to have a natural first contact conversation to ask for information.

## Main Workflow: ##

<img width="1200" alt="Screenshot 2024-10-16 at 22 43 16" src="https://github.com/user-attachments/assets/b27c6a02-a15e-4940-8809-9fb0c8d85ea7">

## Info Option - Ask AI General Information ##
You can have a natural conversation with the agent (OpenAI GPT-4 Mini).
It will answer queries using the knowledge base specific to the business: providing context information, details on services offered with pricing, and explaining policies.
Can speak *any* language — but the fixed parts are in Spanish.

<img width="300" alt="Screenshot 2024-10-16 at 23 11 08" src="https://github.com/user-attachments/assets/ff1e47d0-6f74-46eb-99f4-ba594d49293b">

## Book Service Directly ##

<img width="1200" alt="Screenshot 2024-10-16 at 22 46 44" src="https://github.com/user-attachments/assets/8deaac03-d202-4ce0-84d2-9228e2fe7856">

A series of fixed steps to book a specific photo package.
It uses images and videos to provide a great user experience and showcase the photographer's work.

<img width="300" alt="Screenshot 2024-10-16 at 22 55 02" src="https://github.com/user-attachments/assets/4c176e93-ff72-42be-adb3-0d92c8acd45c">

Check that the order is correct with the client:

<img width="300" alt="Screenshot 2024-10-16 at 22 56 26" src="https://github.com/user-attachments/assets/34674b0b-09ca-4c7f-a766-167558549671">

## Get User Contact Info and Service Details ##

<img width="1200" alt="Screenshot 2024-10-16 at 23 01 54" src="https://github.com/user-attachments/assets/a834a616-cbfb-4784-b60f-21416e9221da">

A mix of AI and fixed steps to collect user information quickly and reliably:

<img width="300" alt="Screenshot 2024-10-16 at 23 27 08" src="https://github.com/user-attachments/assets/65c41330-6c4b-4d3a-9389-522a3eede62b">

## Save Reservation Details in Google Sheets ##

Uses the Make.com integration to trigger a scenario and save the data into Google Sheets.

<img width="1160" alt="Screenshot 2024-10-16 at 23 07 07" src="https://github.com/user-attachments/assets/38d2789c-1b84-4b61-a36e-01a02a7e95df">

