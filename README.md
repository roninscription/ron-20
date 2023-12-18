# RON-20 Protocol
RON-20 Protocol base on Ronin blockchain writing the string into the memo field of the transaction to achieve this.
## Method
 - Deploy:
   ```
   data:,{"p":"ron-20","op":"deploy","tick":"roni","max":"21000000000","lim":"1000"}
   ```
 - Mint:
   ```
   data:,{"p":"ron-20","op":"mint","tick":"roni","amt":"1000"}
   ```
 - Transfer:
   ```
   data:,{"p":"ron-20","op":"transfer","tick":"roni","detail":[{"to":"Ronin Address","amt":"1000"}]}
   ```

## Deploy RONI - The first inscription on the Ronin chain

### Token Economic Information
- Token: RONI
- Supply: 21,000,000,000
- Limit: 1000

### Deploy transaction Details
- Transaction ID (TxID): [Deploy TxID](https://www.oklink.com/vi/ronin/tx/0x01b02eaeacb50285b1bb005b00c279e57f9726af2323d223966969c829610053)
- Block Number: 30292785
- Hex:
  ```
  0x646174613a2c7b2270223a22726f6e2d3230222c226f70223a226465706c6f79222c227469636b223a22726f6e69222c226d6178223a223231303030303030303030222c226c696d223a2231303030227d
  ```
- UTF-8:
  ```
  data:,{"p":"ron-20","op":"deploy","tick":"roni","max":"21000000000","lim":"1000"}
  ```

## Minting RONI Tokens Guide

This guide provides step-by-step instructions on minting RONI tokens using Pocket Wallet.

### Add a Ronin Chain to Pocket Wallet

#### Chain Specifications:

- Chain ID (Network ID): 2020
- RPC Endpoint: https://api.roninchain.com/rpc
- Explorer: https://app.roninchain.com

#### Instructions:

1. **Open the Pocket wallet application on your device.**

2. **Within the app, select "Add custom Network" or similar.**

3. **Enter the following details:**
   - Network Name: Ronin
   - RPC: https://api.roninchain.com/rpc
   - ChainID: 2020
   - Default token: RON
   - Browser: https://app.roninchain.com

4. **Confirm and complete the network addition process.**

5. **Return to the main screen and select the newly added network to use.**

6. **Congratulations! You have successfully added a custom chain to your Pocket wallet.**


### Steps to Mint RONI Tokens:

1. **Open your wallet application.**

2. **Navigate to the "Send" section.**

3. **Enter the Receiver Address: Your address.**

4. **Set the Amount: 0 RON.**

5. **Click on "Advanced".**

6. **For Text Input Method:**
   - Fill in the following text in the provided field:
     ```
     data:,{"p":"ron-20","op":"mint","tick":"roni","amt":"1000"}
     ```

7. **Alternatively, for Hexadecimal Input Method:**
   - Fill in the following hexadecimal string in the designated field:
     ```
     0x646174613a2c7b2270223a22726f6e2d3230222c226f70223a226d696e74222c227469636b223a22726f6e69222c22616d74223a2231303030227d
     ```

8. **Double-check all details for accuracy.**

9. **Initiate the transaction by clicking "Send" or the relevant confirmation button.**

10. **Wait for the transaction to confirm on the network.**

### Important Note:

- Gas fees for transactions may be adjustable based on the current state of the chain. Please consider adjusting the gas fees according to the network conditions for timely transaction processing.

- This process involves minting RONI tokens using specific encoded data. Ensure accurate entry of the provided text or hexadecimal string to successfully mint the tokens.
