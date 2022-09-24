# Coursera-Student-Adviser
Capstone project
WARNING - This chatbot has been developed as the Capstone project for the course, Building AI Applications with Watson APIs. The chatbot is intended to be compliant with the General Data Protection Regulation (GDPR) regime.

With Discovery integration, Student Adviser has access to a Coursera catalog with information about 500 courses JSON files using advanced NLP, Concept Tagging and Keyword Extraction enrichments as data mining features. Student Adviser also has access to Coursera Help Articles to answer FAQ about the courses.

The chatbot will welcome you if you click on the following link:


I have also provided some screenshots which may be of assistance.


The improvements made to the base model as developed in accord with the instructions include:
1. with the assistance of fuzzy matching, which augments the ability of Watson Assistant to recognise misspelled entity values, and the use of slots, we have installed some background questions to facilitate the Chatbot addressing the enquirer questions. The Chatbot will respond appreciatively if  the questions as to name, domicile, age, occupation are answered correctly and if there is no response, the Chatbot will enquire whether the enquirer would like to continue without providing the requested information. At this stage, no error checking has been included for a non-responsive answer.
2. an escalation process has been formalised - if the chatbot cannot provide an answer satisfactory to the prospective student, at first instance, the coursera help web site is hyperlinked, and secondly, access to human interaction is available.
3. the Professional Certificate sector has been augmented by a university sector with links to which universities accepte credit for Coursera courses, For example, for computer science credits, a link to Univerisyt of Michigan has been created, and for law, a link to the Univerisyt of Sydney has been created. In truth, I do not know if these academic institutions accept Coursera credits.

I believe that these enhancements will assist students in finding the most appropriate courses to fufill their objectives.

With more time, the following additions may be useful:

1. determining which questions are most frequently asked, and which comments elicit the most favourable responses.
2. maintaining a database of user questions by user beyond the duration of the session would be useful. As constructed, the context variable stores the information ( name, age, occupation and domicile) only for the duration of the session.
3. I assume that financial assistance is dependent on the domicile of the enquirer. The advice offered should be domicile dependent. There should be a automatic fill of country ( for example typing 'Austra' for Australia which would requirea separate data upload which is not permitted in the Light version.
