# PeerCoin-PPC-CKPool-Fork
CKPool to solo mine PeerCoin (PPC)<br><br>
I could not find a fork of CKPool that has the option to solo mine PPC, so I downloaded the original BTC version from BitBucket, modified some of the files in the src directory and made it work. You can download the original version from BitBucket, replace the src directory with this one, compile, configure and solo mine PPC.<br><br>
The mining difficulty setting via stratum password field is also enabled in this fork. You can use for example: d=5000 that will be your mindiff and startdiff, or you can use md=5000 that will be your fixed difficulty level overwriting everything else.<br><br>
Make sure to edit credentials in ckpool.conf file:<br><br>
For the:<br><br>
"blocksignkey" : "YOUR_GENERATED_PRIVATE_KEY_GOES_HERE"<br><br>
In your Linux Terminal:<br>
```bash
openssl rand -hex 32
```
Copy and paste the output text (64 characters) between the quotation marks in blocksignkey value in the ckpool.conf file.
<br><br>
I am open to feedback and future requests to enhance the capability of this application. Please do not hesitate to write up an issue if you notice anything not working properly. Alternatively, you can reach out via Reddit: https://www.reddit.com/r/Options4Good/<br>
<h4>Donations are highly appreciated and can be made via crypto:</h4>
<b>DGB</b> wallet address:&nbsp;&nbsp;DEkZrJo1BHdiqnQq1XQSWGymEcDWGAWwZs<br>
<b>DOGE</b> wallet address:&nbsp;&nbsp;DKZ9sv4VoTiQQdwi7VY25573UfpQqZJfYf<br>
<b>LTC</b> wallet address:&nbsp;&nbsp;MJw3XHpR65Ec8rKEBthK5Dnvcy1CixYGTa<br>
<b>BCH</b> wallet address:&nbsp;&nbsp;bitcoincash:qq66dg3vhczrqf4zy4kxje3c45vz47khsufsludxcc<br><br>
Thank you.
<br><br>
