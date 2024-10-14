# Telemedicine-Ai-Assistant Project

## Project Overview
The Telemedicine Ai Assistant is designed to revolutionize patient engagement and streamline healthcare service and delivery through Large language model Airtificial intelligence and automation tools.
This Ai-driven solution enhances accessibility to healthcare services, reduces administrative burdens on medical staff, improves patient outcomes through timely and relevant information. By automating routine processes, healthcare providers can focus more on patient care and less on administrative tasks, ultimately increasing efficiency and satisfaction within the healthcare ecosystem. In an era where didital health solutions are paramount, the Telemedicine Ai Assistant positions itself as a crucial tool in modernizing healthcare delivery and improving overall healthcare business and management.


### Technologies Used
- **Voiceflow**: For designing and deploying voice and text interactions.
- **Make.com (formerly Integromat)**: For automating workflows and processes.
- **Airtable**: For managing data related to patients and appointments.

### Functionality Overview
Provide a brief explanation of each functionality:
- **Personalized Symptom Assessment**: Users can input their symptoms using simple text commands, receiving immediate feedback and recommendations.
- **Appointment Automation**: Enables users to book, reschedule, or cancel doctor appointments directly through text commands.
- **Medical Test Booking**: Facilitates the scheduling of medical tests based on doctor recommendations.
- **User Engagement**: Interactive text responses to keep users informed and engaged.
- **Lead Generation**: Captures user information for potential follow-up and marketing purposes.


  ### Target Audience

  The primary users will be patients seeking convenient and efficient healthcare solutions, as well as healthcare providers looking to improve patient engagement and streamline operations.

  ### Workflows and Automations
  This project implements an AI Conversational Assistant workflow using Voiceflow, integrating various automation tools to enhance user experience and streamline operations.

  #### Workflow Components:
  -**User Authentication**:
  1. ***Sign-Up***: New users can register through the assistant, with their information automatically saved in a CRM powered by Airtable via Make.com automation.
       ![sign up workflow](https://github.com/Elson72/Telemedicine-Ai-Assistant/blob/main/itura%20sign%20up.png)
     
       ![Assistant chat](https://github.com/Elson72/Telemedicine-Ai-Assistant/blob/main/chat%20assistant%20start.jpg)
     
  3. ***Login***: Registered users log in using their email, validated through a one-time code sent to their inbox. User data is fetched from Airtable using Make.com integration.
     ![log in work flow](https://github.com/Elson72/Telemedicine-Ai-Assistant/blob/main/itura%20log%20in.png)
     
     ![log in](https://github.com/Elson72/Telemedicine-Ai-Assistant/blob/main/chat%20assistant%20log%20in%20one%20time%20code.jpg)
     
     ![successful log in](https://github.com/Elson72/Telemedicine-Ai-Assistant/blob/main/chat%20assistant%20successful%20log%20in%20and%20main%20menu.jpg)
     
      ![one time code](https://github.com/Elson72/Telemedicine-Ai-Assistant/blob/main/one%20time%20code%20inbox%20message.jpg)

 -**Symptom Assessment**:
Leverages GPT-4 to conduct a preliminary assessment of user symptoms through engineered prompts, providing personalized feedback based on user input.
     ![symptom assesment workflow](https://github.com/Elson72/Telemedicine-Ai-Assistant/blob/main/itura%20symptom%20assessment.png)
     
     ![symptom assesment](https://github.com/Elson72/Telemedicine-Ai-Assistant/blob/main/chat%20assistant%20symptom%20assesment.jpg)

 -**Virtual Doctor Booking**:
Users can schedule virtual consultations via Google Meet. Bookings are automated through Make.com and registered in the Airtable CRM for record-keeping and follow-up.
   ![workflow](https://github.com/Elson72/Telemedicine-Ai-Assistant/blob/main/appointment%20sechedule%20and%20availability%20check.png)
   
    ![airtable doc bookings](https://github.com/Elson72/Telemedicine-Ai-Assistant/blob/main/aitable%20doctor%20appointment.png)
    
     ![doctor appointment confirmation](https://github.com/Elson72/Telemedicine-Ai-Assistant/blob/main/doctor%20appointment%20%20confirmation.png)
   

 -**Test Booking**:
The workflow includes an intent flow for booking medical tests. Users can view available tests fetched from Airtable, with each booking automatically logged into the CRM via Make.com automation.
This workflow exemplifies an efficient, automated approach to user interaction and service delivery, enhancing the overall healthcare experience for users.
   ![test workflow](https://github.com/Elson72/Telemedicine-Ai-Assistant/blob/main/Test%20start.png)
   
   ![test booking](https://github.com/Elson72/Telemedicine-Ai-Assistant/blob/main/test%20booking.png)
   
   ![test info](https://github.com/Elson72/Telemedicine-Ai-Assistant/blob/main/test%20info%20fetch.png)
   
   ![test info](https://github.com/Elson72/Telemedicine-Ai-Assistant/blob/main/tests%20details.png)
   
   ![test bookings](https://github.com/Elson72/Telemedicine-Ai-Assistant/blob/main/airtable%20test%20booking.png)
   
   ![test confirmation](https://github.com/Elson72/Telemedicine-Ai-Assistant/blob/main/test%20booking%20confirmation.png)


