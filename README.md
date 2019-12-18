# FairCoinPaperwallet
JavaScript Client-Side Faircoin Wallet Generator ( forked from https://github.com/pointbiz/bitaddress.org )

Please send DONATIONS for this project to Bitcoin Address:
1NiNja1bUmhSoTXozBRBEtR8LeF9TGbZBN ( origin project bitaddress.org )

END USER NOTES:

 1) For Bulk Wallet I recommended using Google Chrome, it's the fastest.

 2) Requires IE9+, Firefox, Chrome or sufficient JavaScript support.

 3) Mobile Safari only works with iPhone4 or newer devices.
    Older devices timeout while executing JavaScript.

 4) DO NOT use Opera Mini it renders JavaScript output server side, therefore
    they might record the private key you generated.

 5) BIP38 most likely will not work on mobile devices due to hardware limitations.


Notice of Copyrights and Licenses:
---------------------------------------
Project is forked from https://github.com/pointbiz/bitaddress.org

Portions of the all-in-one HTML document contain JavaScript codes that
are the copyrights of others. The individual copyrights are included
throughout the document along with their licenses. Included JavaScript
libraries are separated with HTML script tags.

Summary of JavaScript functions with a redistributable license:

JavaScript function	|	License
-------------------	|	--------------
Array.prototype.map	|	Public Domain
window.Crypto | BSD License
window.SecureRandom	| BSD License
window.EllipticCurve	|	BSD License
window.BigInteger |	BSD License
window.QRCode | MIT License
window.Bitcoin | MIT License

The bitaddress.org software is available under The MIT License (MIT)
Copyright (c) 2011-2013 bitaddress.org

Permission is hereby granted, free of charge, to any person obtaining
a copy of this software and associated documentation files (the
"Software"), to deal in the Software without restriction, including
without limitation the rights to use, copy, modify, merge, publish,
distribute, sublicense, and/or sell copies of the Software, and to
permit persons to whom the Software is furnished to do so, subject to
the following conditions:

The above copyright notice and this permission notice shall be
included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND,
EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF
MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND
NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE
LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION
OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION
WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.

## Usage

### Create Paper Wallet

##### 1. Download and extract
https://github.com/fairchainsx/faircoinpaperwallet/archive/master.zip

##### 2. Disconnect all networks ( world wide web )

##### 3. Reopen the webbrowser -> index.HTML

##### 4. Click tab "Paper Wallet"

##### 5. If you want encrypt your paperwallet then enable "BIP38 encrypt" checkbox -> enter passphrase -> click "Generate" ( optional )

It is recommend to encrypt your paperwallet because in the case that anybody would find your paperwallet then he or she would have full access to your wallet.

If you encrypt the wallet then the private key of your paperwallet will encrypted by this passphrase. Without the passphrase a full access is not possible.

Notice that the passphrase should be secure!

##### 6. Print out your paperwallet
Now you can store the paper offline.

### Restore Paper Wallet

To send FairCoin from your paperwallet you need to restore it in your desktop/mobile wallet ( electrumfair wallet )

Step 1 - 7 is only required when your paperwallet is encrypted. Skip this steps if you have an unencrypted paperwallet.

##### 1. Download and extract
https://github.com/fairchainsx/faircoinpaperwallet/archive/master.zip

##### 2. Disconnect all networks ( world wide web )

##### 3. Reopen the webbrowser -> index.HTML

##### 4. Click tab "Wallet Details"

##### 5. Enter private key into the textfield or scan the QR code ( click scan QR )

##### 6. Click "View Details"

##### 7. enter BIP38 passphrase and click "Decrypt BIP38"

##### 8. Import the decrypted private key in your desktop/mobile wallet
