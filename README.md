# secure-text-to-image-encryption-using-ASCII-value-encoding
a text to image technique to do the hiding of text inside the image. 
This method involves the storing the value of ASCII in the image's X, Y coordinate. 
The Ascii value is stored in one of the three Red, Green, or Blue channels, where the other two channels correspond to the message's next coordinate. To generate the random keys , the system involves picking up of the random images of size 256*256.The decryption process involves production of the decrypted text file which has the message.
The system is secure and could be combined with the other encryption standard algorithms to make it even more secure

. WORKFLOW

      STEP 1: Get a message from the user and save it in text file.
      STEP 2: The ASCII value of the text is stored in the image to create the message image.
      STEP 3: The block is replaced with 3 color codes R, G, B for each pixel within the block.
      STEP 4: The entire known pixel contain 3 components like Red, Green and Blue. The algorithm has 3 components range between 0 to 255 simultaneously ASCII table also contain 0 to 255.
      STEP 5:  Load the public key and private key images and combine them with the message image.
      STEP 6: The combination of public key image, private key image and message image creates an encrypted image.
      STEP 7: Decode the encrypted image using RGB values.
       
CONCLUSION

The data or the information could be securely sent from sender to the receiver via the usage of the image as the object to hide the message. The proposed method is secure and the receiver could get the text sent by the sender safely .With this implementation, one problem we have is the safe transfer of the private image to the other person. It needs to be done through a secure channel like physical media at the moment. It would be ideal in a future analysis to introduce some mathematical operations to send and deliver this data. The proposed method is very useful for securely transmitting the message between sender and receiver.


