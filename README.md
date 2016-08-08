# iBrew White Tealeaf Edition

[iKettle 2.0](http://smarter.am/ikettle) and [Smarter Coffee](http://smarter.am/coffee) Interface

## Introduction

iBrew is a (python) interface to iKettle 2.0 and Smarter Coffee devices. It includes a console, monitor, and command line interface. iKettle 2.0 tested only

### Requirements 

* python 2.7

### Installation

#### Download

```
git clone https://github.com/Tristan79/iBrew.git
```

Download [source](https://github.com/Tristan79/iBrew/archive/master.zip) unpack and run iBrew

#### Run

tba.

### Versions

 * v0.0 Bean Grinder Edition
 * v0.1 White Tealeaf Edition

### Donate

Please donate (for) a (working) Smarter Coffee (interface), can not test without one!

### Contact

[Bugs, issues](https://github.com/Tristan79/iBrew/issues)

Donations & other questions <tristan@monkeycat.nl>

### Links

  *    http://smarter.am/
  *    https://www.hackster.io/lahorde/from-a-14-kettle-to-an-ikettle-d2b3f7

## iKettle 2.0 & Smarter Protocol

This interface was built using this [protocol](https://github.com/Tristan79/iBrew/blob/master/protocol.txt) description

### References

  *    https://github.com/Jamstah/libsmarteram2/
  *    https://github.com/ian-kent/ikettle2/
  *    https://github.com/athombv/am.smarter/
  *    https://github.com/nanab/smartercoffee/
  *    https://github.com/AdenForshaw/smarter-coffee-api
  *    https://domoticz.com/forum/viewtopic.php?f=23&t=12837
  *    https://www.pentestpartners.com/blog/hacking-a-wi-fi-coffee-machine-part-1/

## Console

Console options of v0.1
```

  iKettle 2.0 & Smarter Coffee Commands
  info                   Device info
  status                 Show status
  [data]                 Send raw data to device

  iKettle 2.0 Commands
  off                    Turn off
  on                     Turn on
  base                   Show watersensor base value
  calibrate              Calibrates watersensor

  Smarter Coffee Commands
  cups [number]          Set number of cups [1..12]
  grinder                Toggle grinder
  hotplate off           Turn hotplate off
  hotplate on            Turn hotplate on
  strength [strength]    Set strength coffee [weak, medium or strong]

  WiFi Commands
  connect                Connect to wireless network
  firmware               Show firmware WiFi
  name [name]            Set wireless network name to access
  password [password]    Set password of wireless network to access
  reset                  Reset WiFi
  scan                   Scan wireless networks
  setup                  Select and connect wireless network

  Help Commands
  examples               Show examples of commands
  messages               Show all known protocol messages
  message [id]           Show protocol message detail
  protocol               Show protocol structure

  Console Commands
  dump                   Toggle 'dump raw messages'
  joke                   Show joke
  quit                   Quit console
```