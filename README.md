# endtoenddelaywithack
**USN1**:1KS16CS077 ROHIT KUMAR B R
**USN2**:1KS16CS073 RAHUL V
**USN3**:1KS16CS082 SAMPATH KUMAR

**Invoking the program:**
(value in KM) -N (value) -M (value in Mbits) -S (speed in 10^8m/s) -p (processing time in milliseconds)

**Giving the input:** Input should be given as: python E2Edelay.py --t1 15 --t2 12 --d1 4 --d2 1 -N 6 -M 20 -S 3 -p 1

**Program description:** The program takes in the input from the command prompt, and then computes the end to end delay for that input.
The source sends a packet to the router which in turn directs the data packet to the destination.
Only when the destination gets the first data packet, it sends an acknowledgement to the source.
Next, the source sends the next packet of data after receiving the acknowledgement. 
If the acknowledgement is not received, then the source will not send the next packet.

**CHALLENGES FACED AND HOW DID I ADDRESSED IT:**
Displaying N packets if N is too large
If N is too large, it gets difficult displaying output so what we did was used string formatting. So we can get predefined columns to display our output.
