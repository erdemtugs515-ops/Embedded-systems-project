# Embedded-systems-project

RFID Logging system.

# 1. Our Idea
  It will be a simple smart home object that can log, write and read RFID pass keys for a door lock system. 

 
 
  1.1 Plan: The Raspberry pi Pico will be hooked up to a SQlite database that is interacting with a locally hosted Front end. all events will be logged on this Database and be visible to system admins.
# 2. Structure of the project.

   2.1 General flow:
     RFID card -> RFID reader ↓
		                     	Pico W -> Wi-Fi -> Backend↓
						                                      SQLite -> JS-> Front end
 
   2.2 Visualized structure:
   
   <img width="271" height="571" alt="Pico_architecture_final" src="https://github.com/user-attachments/assets/da927793-98bb-427b-83f6-8deb53ceed95" />

   2.3 Development limits
       
	   2.3.1 Language: Due to the system strain caused by Python and our unfamiliarity of C++, the entire project will be written using MicroPy.
       
	   2.3.2 Hardware: Hardware limitations could limit on how we implement certain features in the final product.

	   2.3.3 Full component list: Raspberry Pi Pico W, 2.4 GHz Antenna, RFID Reader/Writer, LED Light, Buzzer
# 3. BACKLOG: TBD
