# smsgate
## Your own local SMS gateway

smsgate is a fork of [gosms](https://github.com/haxpax/gosms)

What's the use ?
----------------
Can be used to send SMS,
where you don't have access to internet or cannot use Web SMS gateways
or want to save some money per SMS,
or have minimal requirements for personal / internal use and such

- deploy in less than 1 minute
- supports Windows, GNU\Linux, Mac OS
- works with GSM modems
- provides API over HTTP to push messages to gateway, just like the internet based gateways do
- takes care of queuing, throttling and retrying
- supports multiple devices at once.


planned features
-------
- Allowing multiple mobile numbers with a single message.
- go modules
- Single executabe file using embed.
- CRUD support for messages, possibly support cancellation of message
- Support bulk messages from file.
- Support huawei mifi router.
- Auto configuration (no ini file).
---------------------

