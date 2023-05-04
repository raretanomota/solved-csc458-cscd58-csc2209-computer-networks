Download Link: https://assignmentchef.com/product/solved-csc458-cscd58-csc2209-computer-networks
<br>
Problem Set 1




<ol>

 <li>Suppose Host A wants to send a large file to Host B. The path from Host A to Host B has three links, of rates R1 = 500 kbps, R2 = 2 Mbps, and R3 = 1 Mbps.

  <ol>

   <li>Assuming no other traffic in the network, what is the throughput for the file transfer?</li>

   <li>Suppose the file is 4 million bytes. Dividing the file size by the throughput, roughly how long will it take to transfer the file to Host B?</li>

   <li>Repeat (a) and (b), but now with R2 reduced to 100 kbps.</li>

  </ol></li>

</ol>

<ol start="2">

 <li><img decoding="async" data-recalc-dims="1" data-src="https://i0.wp.com/www.ankitcodinghub.com/wp-content/uploads/2020/01/594.png?w=980&amp;ssl=1" class="aligncenter lazyload" src="data:image/gif;base64,R0lGODlhAQABAAAAACH5BAEKAAEALAAAAAABAAEAAAICTAEAOw==">

  <noscript>

   <img decoding="async" class="aligncenter" src="https://i0.wp.com/www.ankitcodinghub.com/wp-content/uploads/2020/01/594.png?w=980&amp;ssl=1" data-recalc-dims="1">

  </noscript>Consider the circuit‐switched network above. There are 4 circuits on each link.  Label the four switches A, B, C and D, going in the clockwise direction.

  <ol>

   <li>What is the maximum number of simultaneous connections that can be in progress at any one time in this network?</li>

   <li>Suppose that all connections are between switches A and C. What is the maximum number of simultaneous connections that can be in progress?</li>

   <li>Suppose we want to make four connections between switches A and C, and another four connections between switches B and D. Can we route these calls through the four links to accommodate all eight connections?</li>

  </ol></li>

</ol>




<ol start="3">

 <li>Consider a highway that has a tollbooth every 100 kilometers. You can think of the highway segments between tollbooths as links and the tollbooths as routers.  Suppose that cars travel (that is, propagate) on the highway at a rate of 100 km/hour (that is, when a car leaves a tollbooth, it instantaneously accelerates to 100 km/hour and maintains that speed between tollbooths).  Suppose next that 10 cars, traveling together as a caravan, follow each other in a fixed order.  You can think of each car as a bit and the caravan as a packet. Also suppose that each tollbooth services (that is, transmits) a car at a rate of one car per 12 seconds, and that it is late at night so that the caravan’s cars are the only cars on the highway.  Finally, suppose that whenever the first car of the caravan arrives at a tollbooth, it waits at the entrance until the other nine cars have arrived and lined up behind it.  (Thus the entire caravan must be stored at the tollbooth before it can begin to be forwarded.)

  <ol>

   <li>Suppose the caravan travels 150 km, beginning in front of one tollbooth, passing through a second tollbooth, and finishing just after a third tollbooth. What is the end‐to‐end delay?</li>

   <li>Repeat (a), now assuming that there are eight cars in the caravan instead of ten.</li>

  </ol></li>

</ol>







<ol start="3">

 <li>Consider sending real‐time voice from Host A to Host B over a packet‐switched network (VoIP). Host A convert analog voice to a digital 64 Kbps bit stream on the fly.  Host A then groups the bits into 56‐byte packets.  There is one link between Hosts A and B; its transmission rate is 2 Mbps and its propagation delay is 10 msec.  As soon as Host A gathers a packet, it sends it to Host B.  As soon as Host B receives an entire packet, it converts the packet’s bits to an analog signal.  How much time elapses from the time a bit is created (from the original analog signal at Host A) until the bit is decoded (as part of the analog signal at Host B)?</li>

 <li>Consider a packet of length L which begins at end system A and travels over three links to a destination end system. These three links are connected by two packet switches.   a) Let d<sub>i</sub>, s<sub>i</sub>, and R<sub>i</sub> denote the length, propagation speed, and the transmission rate of link i, for i = 1, 2, 3.  The packet switch delays each packet by d<sub>proc</sub>.  Assuming no queuing delays, in terms of d<sub>i</sub>, s<sub>i</sub>, R<sub>i</sub>, (i = 1,2,3), and L, what is the total end‐to‐end delay for the packet?</li>

 <li>b) Suppose now the packet is 1,500 bytes, the propagation speed on all three links is 2.5 x 10<sup>8</sup> m/s, the transmission rates of all three links are 2 Mbps, the packet switch processing delay is 3 msec, the length of the first link is 5,000 km, the length of the second link is 4,000 km, and the length of the last link is 1,000 km. For these values, what is the end‐to‐end delay?</li>

 <li>Suppose you would like to urgently deliver 40 terabytes data from Boston to Los Angeles. You have available a 100 Mbps dedicated link for data transfer. Would you prefer to transmit the data via this link or instead use FedEx overnight delivery?</li>

 <li>Suppose that a message 1001 1100 1010 0011 is transmitted using Internet Checksum (4‐bit word). What is the value of the checksum?</li>

</ol>

CSC458/CSCD58/CSC2209 Problem Set #1                                                          2 of 3

<ol start="8">

 <li>For the following, assume that no data compression is done, although in practice this would almost never be the case. For (a) to (c), calculate the bandwidth necessary for transmitting in real time:

  <ol>

   <li>Video at a resolution of 640×480, 3 bytes/pixel, 30 frames/second.</li>

   <li>Video at a resolution of 160×120, 1 byte/pixel, 5 frames/second.</li>

   <li>CD‐ROM music, assuming one CD holds 75 minutes’ worth and takes 650 MB.</li>

   <li>Assume a fax transmits an 8×10‐inch black‐and‐white image at a resolution of 72 pixels per inch. How long would this take over a 14.4‐kbps modem?</li>

  </ol></li>

</ol>




<ol start="9">

 <li>What is the remainder obtained by dividing x7 + x5 + 1 by the generator polynomial x3 +1?</li>

 <li>Suppose we want to transmit the message 11100011 and protect it from errors using the CRC polynomial x3 +1.

  <ol>

   <li>Use polynomial long division to determine the message that should be transmitted.</li>

   <li>Suppose the leftmost bit of the message is inverted due to noise on the transmission link. What is the result of the receiver’s CRC calculation? How does the receiver know that an error has occurred?</li>

  </ol></li>

</ol>

CSC458/CSCD58/CSC2209 Problem Set #1                                                          3 of 3