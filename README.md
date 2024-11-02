# onion-xmc3-explorer
 
onion:version 
commit f91c8b0cc537bc509844281c0e62e3c67914b5a7 (HEAD -> master, origin/master, origin/HEAD)
Author: moneroexamples <moneroexamples@tuta.io>
Date:   Sun Sep 3 09:03:52 2023 +0800

   /api/networkinfo iso fix
    
   https://github.com/moneroexamples/onion-monero-blockchain-explorer/issues/292#issuecomment-1702988652



monero:version 
commit d9b765a3af16d2f16184b6b0876e42d3f2976971 (HEAD -> release-v0.18, origin/release-v0.18)
Merge: 72d2a610c 09a88cc00
Author: luigi1111 <luigi1111w@gmail.com>
Date:   Wed Oct 25 21:41:27 2023 -0400

   Merge pull request #9027
    
   09a88cc Update RandomX to 1.2.1 (tevador)


The released bin file was compiled on ubuntu 20.04 and cpu of e3-1230v2, so the bin file should be run on ubuntu 20.04 and x86 cpu which is released later than e3-1230v2 .


    git clone  https://github.com/monero-classic-lab/onion-xmc3-explorer.git
    chmod 775 onion-xmc3-explorer
    cd onion-xmc3-explorer
    ./xmrblock -b ~/.bitmoneroclassic/lmdb -p 8081
    curl 127.0.0.1:8081

    
