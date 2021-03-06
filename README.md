# xb

*LFE/Erlang library for the XBee API*

<img src="docs/source/images/just-xb.png" />

## Table of Contents

* [Introduction](#introduction-)
* [Installation](#installation-)
* [Usage](#usage-)
* [Resources](#resources-)

## Introduction [&#x219F;](#table-of-contents)

Add content to me here!


## Installation [&#x219F;](#table-of-contents)

Just add it to your ``rebar.config`` deps:

```erlang
  {deps, [
    ...
    {xb, ".*",
      {git, "git@github.com:oubiwann/xb.git", "master"}}
      ]}.
```

And then do the usual:

```bash
    $ make compile
```


## Usage [&#x219F;](#table-of-contents)

Currently under development. See the [docs](http://oubiwann.github.com/xb) for
current progress.

## Resources [&#x219F;](#table-of-contents)

 * [Building WSN with MQTT, RPi & Arduino](https://www.erlang-factory.com/upload/presentations/807/ZviMQTTS_for_EUC2013.pdf) (Erlang)
 * [XBee - XBee / XBee-PRO - RF Modules - 802.15.4 Protocol](http://ftp1.digi.com/support/documentation/90000982_S.pdf) - API Operation for the XBee/XBee-PRO RF Module, starts at page 89 (series 1)
 * [XBee / XBee-PRO - ZigBee RF Modules - XBEE2, XBEEPRO2, PRO S2B](http://ftp1.digi.com/support/documentation/90000976_W.pdf) - API Operation, starts at page 112 (series 2)
 * [XBee API Packet Generator](http://ftp1.digi.com/support/utilities/digi_apiframes2.htm)
 * [Python XBee library](https://github.com/markfickett/python-xbee)
 * [Node.js XBee library](https://www.npmjs.com/package/xbee-api)
