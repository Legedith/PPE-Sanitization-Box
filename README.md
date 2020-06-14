# PPE-Sanitization-Box

The problem PPE Sanitization Box solves
All hostipal staff and frontline workers require and use personal protective equipments to save themselves from COVID-19. Since most people use N95 masks only for one shift, it increases the amount of PPE that ends up in garbage while increasing the demand. One of the main reasons for non reusability is non availabity proper methods to saftely sanitize the masks for reuse.
We have a UV sanitization box that's controlled by Arduino to sanitize the masks. This method of sanitization is based on a research by Stanford. Here's how it works:
All masks are numbered. After using the masks, we put them in a sanitization box and feed the mask number to arduino through a keypad attached to it. Arduino then starts the UV light for 4 minutes and displays the remaining time on a LCD display. The Arduino is also connected to nodemcu which updates the realtime firebase database which is connected to an android app which tracks how many times a particular mask has been sanitized and also keeps track of how my time is left until sanitization. In addition to this, the app also prompts the user to keep the masks in isolation for three days after UV sanitization so as to remove any chance of infection (since Corona virus can survive only upto 72 hours on surfaces). After three days are over, it'll notify the user that masks are ready to be reused.


# Click on the image below to watch the demo video
[![IMAGE ALT TEXT](https://github.com/Legedith/PPE-Sanitization-Box/blob/master/img.png)](https://youtu.be/8jGi28VJXV4 "PPE Sanitization Box")
