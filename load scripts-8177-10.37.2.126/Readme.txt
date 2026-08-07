set up a user in voice with Vocera phone 4532
set up call forwarding all to 5571234540
DID information for the site :
prefix 557123	 range 4532 to 4535


Run 2 command prompts one for placing a call and another for receiving the call:
Call initiator command:
cygwin64\Sipp_3.2>sipp 10.37.2.112:5060 -sf uac-Load.xml -i 10.37.2.126 -s 557123
34532 -r 6 -rp 1000 -l 95


Call acceptor command:
64\Sipp_3.2>sipp 10.37.2.112:5060 -sf options-invite-PRACK-200-load.xml -i 10 -p 5060

Looks good