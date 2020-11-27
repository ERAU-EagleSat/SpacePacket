# Basic Design

## Primary Header
### Fields
* Binary of header
* Packet Version Number
* Packet Identification (own class)
* Packet Sequence Control (own class)
* Packet Data Length
### Methods
#### Public
* Unpack from binary
* Pack to binary
#### Private

## Packet Identification
### Fields
* Binary of Identification (13 bits)
* Packet Type (Boolean)
* Secondary Header Flag (Boolean)
* APID (Application Process ID)
### Methods
#### Public
* Unpack from binary
* Pack to binary
#### Private

## Packet Sequence Control
### Fields
* Binary of sequence Control (16 bits)
* Sequence Flags 
* Sequence Count
### Methods
#### Public
* Unpack from binary
* Pack to binary
#### Private

## Packet Data
This will contain the data of the packet.