# PeerCoin-PPC-CKPool-Fork
CKPool to solo mine PeerCoin (PPC)<br><br>
I could not find a fork of CKPool that has the option to solo mine PPC, so I downloaded the original BTC version from BitBucket, modified some of the files in the src directory and made it work. You can download the original version from BitBucket, replace the src directory with this one, compile, configure and solo mine PPC.<br><br>
Make sure to edit credentials in ckpool.conf file:<br><br>
For the:<br><br>
"blocksignkey" : "YOUR_GENERATED_PRIVATE_KEY_GOES_HERE"<br><br>
In your Linux Terminal type:<br><br>
openssl rand -hex 32<br><br>
Copy and paste the output text (64 characters) between the quotation marks in blocksignkey value in the ckpool.conf file.
