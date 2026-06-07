
<img src="Gallery/QoS.png" width="700" alt="QoS">
We're gonna make an alias for 2 IP addresses.


<img src="Gallery/QoS2.png" width="700" alt="QoS">
Name an alias HighBW, and add 2 IP addresses (that you wish to be prioritized) 

<img src="Gallery/QoS3.png" width="700" alt="QoS">
Go to traffic shaper --> Wizard. and configure the shaper. I'm going to select GuestWIFI for the inteface.

<img src="Gallery/QoS4.png" width="700" alt="QoS">
I want to prioritize VoIP traffic. so enable that, i set the connecttion parameters to 10 Mbits U/L and 20 Mbits D/L.

<img src="Gallery/QoS5.png" width="700" alt="QoS">
<img src="Gallery/QoS6.png" width="700" alt="QoS">

Then, I'll prioritize some networking protocols like; MSRDP, VNC PPTP and IPSec over other networking protocols.


<img src="Gallery/QoS7.png" width="700" alt="QoS">
Next, I want to do a floating rule and change the outbound port for MSRDP, convert it to 3391. 

<img src="Gallery/dst.png" width="700" alt="QoS">
