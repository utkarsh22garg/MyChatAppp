# MyChatAppp
Chat Application 

## FEATURES IMPLEMENTED:
 - It is a peer-to-peer based chat application i.e. any two people can chat among themselves.
 - Multiple clients can talk among themselves by changing the ip-address and target port respectively.
 - They can also send a file to each other.

## SECURITY:
   - **Confidentiality**
      * The chat messages can be secured using **AES (128 bit)** or **DES (64 bit)** (depending upon the user's choice) using a secret key.
      * The secret key is secured using **RSA** which can only be decrypted by the receiver.

   - **Integrity**
      * Hash of the encrypted message is generated using **MD-5** of 128 bit which is concatenated with the encrypted message.
      * A change of 1 bit in the message will change the hash by 50%. Thus, integrity is maintained.
	
   - **Authenticity**
      * Receiver calculates the hash of the message received and compares the hash received to check whether the message was 		 sent by the correct sender.

## HOW TO USE:
  **Step-1:** Run the MyChatAppp.jar file. (--> _minimum system requirement JRE 8.0_ <--)
  
  **Step-2:** Enter your name and press OK button.
  
  **Step-3:** Enter your port, receiver's ip-address and his port and press listen button. (make sure the receiver is also active and 
              listening)
  
  **Step-4:** Select encryption type either AES or DES.
  
  **Step-5:** Enter the message and press send or click 'Send File' to send a file from your PC.
  
## SCREENSHOTS:
<img src="https://github.com/gargmehul10/MyChatAppp/blob/master/Screenshot_1.png" height="400" alt="Screenshot"/> 
<img src="https://github.com/gargmehul10/MyChatAppp/blob/master/Screenshot_2.png" height="400" alt="Screenshot"/>
<img src="https://github.com/gargmehul10/MyChatAppp/blob/master/Screenshot_3.png" height="400" alt="Screenshot"/> 
