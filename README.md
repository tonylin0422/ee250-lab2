# ee250-lab2
Question 1: 
- The reliability of UDP decreased when the 50% loss was added. This is because UDP is connectionless and does not require
  acknowledgement before sending data packets. If packets are lost, UDP does not retransmit it.
    
Question 2: 
- The reliability of TCP did not change at all, and all data packets were sent eventually (sometimes with a delay).
  This is because TCP implements error detection and acknowledgements, and retransmits when a packet is dropped.
  
Question 3: 
- The speed of TCP slightly decreased with delays. This is because of error processsing and
  retransmission when a packet is lost. 

Question 4: 
- I used AI LLMs to help understand the tcp_server.c code, specifically regarding some of the syntax and what
  a file directory is. 
