# csgo-sharecode-decoder

A PHP class which decodes a CS:GO share code ID.

# Installation

There is not much to install. Copy the class to your Project and add your namespace.

# Usage

Just call the method `decode()` on your code and pass the share code.

``` php
    $initDecodeClass = new DecodeShareCode();
    $getInfo = $initDecodeClass->decode('CSGO-oPRbA-uTQuR-UFkiC-hYWMB-syBcO');
   /* This returns 
        [
            'matchId'       =>  3418217537907720662,
            'reservationId' =>  3418222754145501631,
            'tvPort'        =>  34897
        ]
    */
```