# CSTS
It is a Spring Boot application designed to support the customers by allowing to them to send queries in multiple languages and scheduling them with a token at public offices. Functionalities of customer are select language, query the services available, select the service, view the required documents. Functionalities of Officers are request the relative token, mark the token as COMPLETE, CANCEL OR DELETE, update profile data. Functionalities of admin are adding services and documents data to appplication and mapping them correspondingly as per the rules.
### Example: 
For a service like
Service name: Application for an SSN card.
applicant can be a U.S. Citizen, international student etc.. The documents required to fulfill the service varies.

## SQL file
Use this SQL file csms.sql to setup database with MYSQL for the application.

## LLM
Configured gemma-4 31B open source model for this application, get a free API key from Google AI studio and configure API key in environment variables with key as GEMINI_API_KEY.

## UML Design Of Application
<div>
  <img src="uml_diagramj.jpg" alt="uml_diagram_png"/>
</div>
