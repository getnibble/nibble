Nibble
 
Specs:

Ascending reward system to stave off insta-mining, pre-mining, unfair rewards for early adopters.

Block 1 - 2016 @ 1 NIB
Block 2017 - 4032 @ 2 NIB's
Block 4033 - 6047 @ 4 NIB's
Block 6048 - 8063 @ 8 NIB's
Block 8064 - 10079 @ 16 NIB's
Block 10080 - 12095 @ 32 NIB's *** Difficulty SHOULD reach 1+ at this point.  Total NIB's mined = 127,004
Block 12096 - 219555 @ 50 NIB's
Block 219556 - 639555 @ 25 NIB's

21,000,004 total NIB's (4 more than Bitcoin)
639,555 total blocks
2 1/2 minute blocks (4 times faster than Bitcoin)
2016 Block Difficulty Retarget

Why is this system better?

Litecoin's 1st 12,096 blocks produced 604,800 LTC - though GPU mining wasn't released to the general public (but that's not it wasn't used)
Feathercoin's 1st 12,096 blocks produced 2,419,200 FTC
Nibble's 1st 12,096 blocks will produce 127,054 NIB

Ports:
8550 Connect
8551 JSON RPC

Solo Mining:

1) Download the client or daemon for your OS
2) Launch the or daemon.
3) Create a nibble.conf file in the correct location for yoru OS:

Windows: %appdata%\nibble\nibble.conf
Linux: ~/.nibble/nibble.conf

***nibble.conf***

rpcuser=[replace with username]
rpcpassword=[replace with password]
rpcport=[replace with any port you wish]
rpcallowip=[* for all, or IP of a remote system]
daemon=1
server=1

4) start your daemon or client with the -server option.

For example: >nibble-qt.exe -server

5) Point your favorite miner to the IP of the machine running the server.  Use the port and username/password as specified in the above nibble.conf file.



Development process
===================

Developers work in their own trees, then submit pull requests when
they think their feature or bug fix is ready.

The patch will be accepted if there is broad consensus that it is a
good thing.  Developers should expect to rework and resubmit patches
if they don't match the project's coding conventions (see coding.txt)
or are controversial.

The master branch is regularly built and tested, but is not guaranteed
to be completely stable. Tags are regularly created to indicate new
official, stable release versions of Litecoin.

Feature branches are created when there are major new features being
worked on by several people.

From time to time a pull request will become outdated. If this occurs, and
the pull is no longer automatically mergeable; a comment on the pull will
be used to issue a warning of closure. The pull will be closed 15 days
after the warning if action is not taken by the author. Pull requests closed
in this manner will have their corresponding issue labeled 'stagnant'.

Issues with no commits will be given a similar warning, and closed after
15 days from their last activity. Issues closed in this manner will be 
labeled 'stale'. 

Check out http://getnibble.org for more info about the development.