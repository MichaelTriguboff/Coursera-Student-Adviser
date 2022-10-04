# Coursera-Student-Adviser
Capstone project
WARNING - This chatbot has been developed as the Capstone project for the course, Building AI Applications with Watson APIs. The chatbot is intended to be compliant with the General Data Protection Regulation (GDPR) regime.

With Discovery integration, Student Adviser has access to a Coursera catalog with information about 500 courses JSON files using advanced NLP, Concept Tagging and Keyword Extraction enrichments as data mining features. Student Adviser also has access to Coursera Help Articles to answer FAQ about the courses.

The chatbot will welcome you if you click on the following link:


I have also provided some screenshots which may be of assistance.
Facebook: 
Slack:


The improvements made to the base model as developed in accord with the instructions include:
1. with the assistance of fuzzy matching, which augments the ability of Watson Assistant to recognise misspelled entity values, and the use of slots, we have installed some background questions to facilitate the Chatbot addressing the enquirer questions. If the enquirer provides all his information (name, domicile, occupation) at once, the bot will appreciatively respond that it has all the required information. Or the bot can ask for each piece of information and acknowledge receipt of the information. The chat bot will tehn call the enquirer by name ( to try, type in 'John'). The information gleaned is discarded after the session ends
2. the chat bot with a series of option buttons at various dialogs will prompt the enquirer to continue. For example, at the Welcome Dialog,the enquirer will be asked if he wants to learn the capabilities of the bot- if the answer is 'yes', the bot will respond with its capabilities; if the answer is 'no', then the bot will ask what the enquirer would like to see- options provided being cost, courses or FAQ, and the enquirer can click on the relevant button
3. after the courses offered, the bot will ask if the enquirer wants to see the professional certificates or university programmes which accept Coursera credit.
4. if the chatbot cannot provide an answer satisfactory to the prospective student, at first instance, the coursera help web site is hyperlinked
5. the Professional Certificate sector has been augmented by a university sector with links to which universities accepte credit for Coursera courses, For example, for computer science credits, a link to Univerisyt of Michigan has been created, and for law, a link to the University of Sydney has been created. In truth, I do not know if these academic institutions accept Coursera credits.

I believe that these enhancements will assist students in finding the most appropriate courses to fufill their objectives.

With more time, the following additions may be useful:

1. determining which questions are most frequently asked, and which comments elicit the most favourable responses. If the enquirer has provided its details such as domicile and occupaiton, then the responses could be analysed by these variables.
2. maintaining a database of user questions by user beyond the duration of the session would be useful. As constructed, the context variable stores the information ( name, age, occupation and domicile) only for the duration of the session.
3. I assume that financial assistance is dependent on the domicile of the enquirer. The advice offered should be domicile dependent. There should be a automatic fill of country ( for example typing 'Austra' for Australia which would requirea separate data upload which is not permitted in the Light version.
4. I would have added links to each course so that the enquirer could further examine the particular course including learnign of prerequisites and terms and conditions
5. the site should be multilingual
