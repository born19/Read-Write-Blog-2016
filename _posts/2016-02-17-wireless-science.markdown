---
layout: post
title:  "Wireless Science"
subtitle: "Improving the wireless experience using science!"
date:   2016-02-17 
categories: [other]
---

= ~ > touch Wireless Science;
= ~ > ls -a;

Wireless Science

= ~ > vim Wireless;
# Created 2/5/2016
# Written and saved at 7:33:21

Hello World,

**= ~ > Question = “How can I increase my internet quality using science?”**

I did research to write a rough guide on how to improve your wireless connection.

Network Speed:

Speed is a measure to understand how to quantify your speed you need to know the following terms.

Measures and Terms:

Packets Lost:
Packages that didn’t reach their destination
Latency / Ping:
Response time to a connection
Jitter:
Variance in successive ping tests
Download Speed:
How fast you can pull data from a server
Upload Speed:
How fast you can upload data to a server
Highway Consistency:
Consistency of a connection

Highway Consistency:

The first measure of quality of speed. How consistent are you reaching the max speed for a packet?

Highway Consistency % =100  Your speedMax speed for connection 

Network Quality:

Speed is not the only factor.  Often internet quality, or inconsistencies, factor into what you might consider the speed of your wireless. When you ISP is congested than you can only achieve a set speed which is lowered with more traffic. 

It is generally considered better to have a connection that is 3 Mb/s with a 99% consistency vs a 6 Mb/s connection with 50% consistency rate. Delays in re-sending packets is accountable for this delay.

If measuring consistency of a internet connection you will need both internet speed and internet flow, which is measured by only some applications. After making a graph related to this you can diagnose what went wrong.

Wi-Fi Site Surveys:

A site survey is a diagnosis of a network's strength based on a visual map. This is a good for diagnosing obstacles and router placement.

I used NetSpot to make a map of my wireless network.  I found some imperfections but found that the free version is very limited. 

Calculating wireless range:

Radio Frequency Power is usually measured in dBm or decibels with a milliwatt reference. This measures the power of a system (Router) to a reference in this case a milliwatt reference. To get a good idea of how powerful a signal is just remember that an increase of 3 dBm is about twice the output signal. 

Some basic conversions between mW and dbm  follows:

P(dBm) = 10 · log10(P(mW))
P(mW) = 10(P(dBm)/10) 

Path loss:

Path loss is the loss of power density over a distance. Every time you double the distance you reserve ¼ of the power. So ever 6 dBm’s on your router your output distance is doubled.  The biggest thing you can do to increase your wireless speed in most devices is get a better wireless receiver. This is usually measured in negative dBm’s.

Path Loss Equation:

Maximum path loss = transmit power – receiver sensitivity + gains – losses – fade margin

Electronic Design -- “Gains include any gains resulting from directional transmit and/or receive antennas. Antenna gains are usually expressed in dBi referenced to an isotropic antenna.”

Losses generally consist of two things:

Obstacles: Obstacles could absorb or reflect wifi waves.
Air Humidity: Air humidity can absorb RF energy.

Fade Margin:

The fade margin can refers to potential obstacles that could infringe on the (LOS) Line Of Site to the router. Line of sight should always be maintained with your router in order to maintain a secure connection. But the fade margin is treated like a variable that accounts for all potential things that could go wrong with a router due to the environment. 

A higher fade margin shows a better connection. A good connection is often between 12 and 20 dBms. 

Distance Formula:
Distance (km) = 10(max path loss - 32.44 - 20log(f) /20)
f = frequency in MHz
Effects of the Antenna Height:

Antennas should be higher than any obstacles they are transmitting over such as trees or cars. Antennas will also create what's called a the fresnel zone. The fresnel zone is allips around an antenna that defined by the wavelength of the signal and is used to find where a antenna should be placed so that a signal can pass over obstacles without being placed so high that it don’t broadcast to the devices below it. 



