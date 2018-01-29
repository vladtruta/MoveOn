# MoveOn
This is the Web-App we coded at HackSociety.

It can detect whether a room is full or empty, using motion sensors, as well as distance sensors.

Each room would have one Raspberry Pi, which has sensors connected to it. There is a central server, that gathers information from all connected Pi boards, processes the information, and sends it to a website, which displays the output in a user-friendly format (that is, there's a color which changes from red to green, depending on whether each room is empty or full).

The status will update every few seconds.
