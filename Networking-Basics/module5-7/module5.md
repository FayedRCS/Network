## Protocols
Protocols are required for computers to properly communicate across the network. In both a wired and a wireless enviorment, a local network is defined as an area where all hosts must share a common protocol. 

Networking protocols define many aspects of communication over a the local network. The table below shows these aspects:

| Protocol Characteristic | Description |
|---|---|
| Message format | When a messsage is sent, it must use a specific format or structure. Message formats depend on the type of message and the channel that is used to deliver the message |
| Message size | The rules that govern the size of the pieces communicated across a network are strict. They can also be differend depending on the channel used. When a long message is sent from one host to another over a network, it may be necessary to break the message into smaller pieces in order to ensure the message can be delivered reliably. |
| Timing | Many network communication functions are dependant on timing. Timing determines the speed at which the bits are transmitted across the network. It also affects when an individual host can send data and the total amount of data that can be sent in any one transmission |
| Encoding | Messages sent across the network are first converted into bits by the sending host. Each bit is encoded into a pattern of sounds, light waves, or electircal impulses depending on the network media over which bits are transmitted. The desination host recieves and decodes the signals in order to interpret the message.  |
| Encapsulation | Each message transmitted on a network must include a header that contains adressing information that identifies the source and destination host, otherwise it cannot be delivered. Encapsulation is the process of adding this information to the pieces of data that make up the message. |
| Message pattern | Some messages require an acknowledgement before the next message can be sent. This type of request/response pattern is a common aspect of many networking protocols. However there are other types of messages that may simply be streamed across the network, without concern as to whether they reach their destination|












