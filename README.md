# FrameBook(1)
Meet the Framebook(1)
<img width="1920" height="1080" alt="Framebook 170825(2)" src="https://github.com/user-attachments/assets/685f9b43-ce22-4ee0-8f06-faf4b9a535a0" />
<img width="1920" height="1080" alt="Framebook 170825" src="https://github.com/user-attachments/assets/548eba3b-5cd9-41e6-8f0e-9e45e96e7835" />

<img width="842" height="714" alt="Screenshot 2025-08-17 at 22 59 27" src="https://github.com/user-attachments/assets/f829996d-35c6-4553-be7e-ddbef65a2b50" />

<img width="929" height="613" alt="Screenshot 2025-08-17 at 23 00 57" src="https://github.com/user-attachments/assets/299bce31-4f76-41e5-8916-30ca8098b457" />
<img width="1764" height="1222" alt="image" src="https://github.com/user-attachments/assets/12f040eb-8185-4e17-b5f7-8e03779c8b75" />

<img width="870" height="626" alt="Screenshot 2025-08-17 at 23 01 19" src="https://github.com/user-attachments/assets/54d6714a-0d85-4628-8587-39479e404fa7" />
<img width="952" height="976" alt="image" src="https://github.com/user-attachments/assets/b2309ce8-8a85-42f0-bc4e-3beebdd3854a" />
<img width="1630" height="1284" alt="image" src="https://github.com/user-attachments/assets/d7a4e493-b1bf-4d00-a0c8-1dab76b00c59" />
<img width="1656" height="1306" alt="image" src="https://github.com/user-attachments/assets/a6301eca-fdb4-46f9-ab92-a8c6006bbc67" />



PROTOTYPE BOARD to investigate converting the Framework13's keyboard to USB:


<img width="1978" height="1146" alt="image" src="https://github.com/user-attachments/assets/409e6e79-1920-46bb-b1fc-503703148f5b" />


The Framebook(1) is a bit of a... different take on the Framework 16 which hopes to build a slightly less interesting laptop in favour of some nice-to-haves. It removes the 16's modular keyboard/trackpad interface in favour of the much loved keyboard from the Framework 13, sacrificing some customisation in favour of a more compact design and _much_ larger trackpad. The trackpad is for the moment still in the works, as there are currently no commercially available trackpads for 16 inch laptops with haptic feedback. I've drawn up an initial design which simply shrinks the Ploopy trackpad's design to the desired size, but have since discovered that more significant changes will be necessary as the electronics physically interfere with the size of the keyboard. You can track changes here though in the "trackpad" folder. I've opted for an aluminium chassis instead of the magnesium one on the usual Framework 16, and am leaning towards the more blocky macbook pro/air design with filleted edges to save on space. It's also got some beautifully pointless components as well. What happens if you take all the disco-flashing lights from Nothing Tech and you combine them with the genuinely thoughtful repairability of Framework? You end up with a conversation starting _and_ long-lasting computer. The current design looses two of the expansion card slots to integrate with the circuitry needed for the keyboard and trackpad, but once I've checked that the current design works I'd like to integrate the keyboard circuitry with that of the trackpad to save space and possibly return the other two card bays.

I've got some other crazy ideas as well which can be seen in the first few versions but which I've removed for simplicity in the current model. The basic premise though is to integrate a triple screen laptop setup... natively into the lid. With two dovetail joints in the rims of the lid and pogo pins to provide a simplified USB interface, you would be able to slide extra panels onto either side. I'm going to get the basics down first though before this. The other two important components are of course the screen and battery. I've settled on a screen made by Samsung with the model number ATNA60YV02-0, a 4k OLED 60hz panel which is actually shockingly close in dimensions to the current FW16 panel. This will need to be driven at a different voltage though to the current IPS display so will still need some significant development. Take a look at the "Framework 16 Screen Compatibility" thread in the forums for the latest updates. In terms of battery I'm hoping to squeeze in 99Whs worth of capacity, but can't actually find any cells available to consumers. It may be the case that I'll have to disassemble a 99Wh battery and spot weld the cells onto the BMS of the FW16 to get a solution. 

There's more fun as well! Aside from the glyphs on the back I've designed in a set of wireless charging coils - imagine if you could bring just one charger when you travel by charging your phone, earbuds and watch from the back of your computer! Alongside this there's a small OLED display on the back, (DO0241PVST06), which could show things like CPU usage, the current song playing, or remaining battery life.

  It has some drawbacks as well however. It doesnt have a webcam, instead relying on the GCam app and a magsafe mod to provide video using your phones front camera. Most people seem to use earbuds as well, so no speakers are engineered into the design. I can't afford to build it personally right now, but maybe someone else who looks for the same qualities in a laptop might.

Massive thanks to Arya for all of their hard work making a FW13 to USB adapter. Check them out here: https://github.com/CRImier/MyKiCad/tree/master/Laptop%20mods/framework_input_controller

Desinged and rendered by Joe Shapiro. Free to use with links to this repository. Be warned that this is very much conceptual.

A note on the, "Useful Datasheets folder":
These datasheets are not mine, nor do I claim them to be. They are simply a useful resource for others looking to build upon this design, and some security in the event that datasheets are moved in future. Information will be removed at the request of the company if asked. 

https://torqmaster.com/standard-friction-hinges/
