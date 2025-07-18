# July 17 (Official Start)
Today, i started researching components, since the MCU on the RubberDucky is unknown (i think). I thought about doing this on an Atmega32U4, but it would be super slow + Atmel chips are expensive. So i started looking for STM32 chips with USB HID capabilities, i didn't find much, then i asked for some help in a discord server, then found the STM32F411 (thank you pera :3)
<img width="1038" height="113" alt="image" src="https://github.com/user-attachments/assets/d8d8d6a5-c5ba-45b1-bd18-3016ab722a6b" />
Bonus on the F411, besides it being CRAZY fast, it's also the same size as a 32U4. So i could just swap it on my first concept without changing much of my original concept.

**Images of the original concept:**
(yes, EasyEDA symbols are weird)
<img width="1277" height="679" alt="image" src="https://github.com/user-attachments/assets/e061f46c-6d7b-4ae6-bf47-1880ac337f1e" />

# KiwiKey V1
After that, i added the F411, and got my first version of it:
<img width="613" height="766" alt="image" src="https://github.com/user-attachments/assets/d0dcd9d9-38de-42ed-9b83-0b883e766a01" />
<img width="1190" height="845" alt="image" src="https://github.com/user-attachments/assets/c6914d58-4bb4-4f21-a566-ceed8a730689" />

But now i've done some fixing in the schematic, and some rerouting on the PCB (V1.1)
<img width="1190" height="845" alt="SCH_MainBoard_1-P1_2025-07-17" src="https://github.com/user-attachments/assets/57ba16c0-3c82-4d96-8d04-1abb1d474ebe" />
<img width="249" height="648" alt="image" src="https://github.com/user-attachments/assets/596e6f70-19f6-453b-bee3-ebbfc89de3b3" />

I still have a lot to fix though, still need to add more stuff, such as decoupling caps, et cetera.



