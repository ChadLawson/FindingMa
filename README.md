FindingMa
=========

The Prequel to an ARG using Pay Phones: Mapping Them.

DESCRIPTION

A while ago I had an idea for an Augmented Reality Game (ARG) that used pay phones for cold war style "agents" to receive missions and enter solutions.

The problem was: finding enough existing pay phones. I needed their locations in terms of the network (inbound phone number) and the real world (GPS coordinates) in a database.

I've already created a Twilio/PHP/MySQL system where an "agent" can generate a code on their mobile device which submits the GPS coordinates to a database. From there they can call a number from the pay phone and enter the code, mapping the GPS coordinate to the incoming call number.

When I talked about this to some people at DEF CON, a local 2600 member suggested finding a way to make it more anonymous/open and not dependent on cell phones.

That inspired me to think back to my youth. When I was young my dad (a then engineer for "Ma" Bell) taught me about the world of phones including DTMF and MODEM technologies.

DETAILS

The device I'm working on would contain a GPS module, display, and keypad. When an "agent" arrives at a pay phone, the device would be held up to the handset and dial the "headquarters." From there it would transmit the GPS coordinates either using DTMF or FSK mapping the phone in the real world.
