# ee250-lab2
Question 1: How did the reliability of UDP change when you added 50% loss to your local
environment? Why did this occur?
- The reliability of UDP decreased when the 50% loss was added. This is because UDP is connectionless and does not require
  acknowledgement before sending data packets. If packets are lost, UDP does not retransmit it.
    
Question 2: How did the reliability of TCP change? Why did this occur?
- The reliability of TCP did not change at all, and all data packets were sent eventually (sometimes with a delay).
  This is because TCP implements error detection and acknowledgements, and retransmits when a packet is dropped.
  
Question 3: How did the speed of the TCP response change? Why might this happen?
- The speed of TCP slightly decreased with delays. This is because of error processsing and
  retransmission when a packet is lost. 
