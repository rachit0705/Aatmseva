# Aatmseva
                                                         What is the problem?
In this pandemic situation of COVID-19 Crisis where everywhere lockdown is implemented,  it’s very difficult to step outside and go to the desired place. Due to this Medical waste can’t be decomposed and there is no way out or means by which one can do it. So our App provides a solution to request a pick up for medical waste help to dump the medical waste from the individual’s place or Hospitals.

                                                     How can technology help?
With the help of our Android app we enable a platform for the user to make and accept the request made for the Disposal of the Medical waste. Our app also includes a chatbot which provides all information related to COVID-19 , Different Zones and Medical waste management. User Can also get Live Tracking Status of COVID-19 Cases for India and for other Country’s as well. Also For more Details User can visit Official WHO and MyGOV Website in a Single Click from Our App Dashboard.

Working Model -  https://www.youtube.com/watch?v=oabz19j9IVc&t=12s

                                                    	Solution description – 
 Consider the situation of Standalone Clinics and some individuals whose work revolves    
    around the usage of syringes, masks, gloves , medicines and all other medical    
    equipment have to dispose all these Medical waste after a month or two as they have 
    bulk of them all. But in this crisis where lockdown is implemented all around which 
    restricts them to do dump the waste , which become a topic of  serious concern.
    
  To fight this problem we came up with a solution to get rid of these problems and only by 
    sitting at their places they can dispose the Medical waste by Using Our App , They just   
     need to Request for Pickup , Further Municipal Workers will come and take away their 
     all Medical / Pharmacuetical / etc wastes.
    In our Medical Waste Management Feature of our app if someone has to make a request  
    They just have to fill the form containing the information regarding which type of Medical 
    Waste they have to Throw and some personal details including their Adress and Contact 
     Number.
     After all this, the request has been sent to Medical Waste Management Department 
     Then they will come at their place and take away all the Harmful and Toxic Medical 
     Wastes.
    
   As of Existing Solution , According to us there is no Simple and User Friendly Solution  
       available for Collecting Such Medical / Pharmaceutical waste from individuals home .  
       So, In this Our App provides a Solution to User where they made a Request for the 
       pickup for Wastes they have .
       In future, We build One more Application for Municipal Waste Disposing Department 
       where they will get all the Requests from Customer . From that app they can approve 
       or reject the User Requests and can come and take away all the waste and dispose in 
       proper manner.

 
                                             Solution Architecture 

a.	First the user will login (using Firebase Phone Authentication) and land up to our App dashboard.

b.	There are six tabs in the dashboard including COVID Tracker, Waste Management, Chatbot Support , Google Maps for Live Location and COVID-19 Guidelines from external links 
(i.e. WHO and MyGOV websites).

c.	For Medical Waste Pickup the user have to Signup to our Cloud Database (using Firebase Realtime Database ) , further user land up to Safety Measures page. In the sidebar there is a option to make a request for pickup.

d.	After that User needs to fill some basic details of themselves and selecting Category of Wastes and after submitting the request will be Sent.

e.	In COVID-19 tracker the user can find the current updates regarding coronavirus cases for any country with a Easy and user friendly Donut Chart Representation.

f.	Also User can talk to our Voice Enabled chatbot and ask for all the useful information regarding coronavirus guidelines, Different Zones and Medical Waste information which call IBM assistant service.


IBM Cloud Services/Systems –

Speech to text,  Watson Assistant, Text to speech

