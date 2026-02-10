# Local-network-reliability-testtool
python test tool for logging issues with a local (home) network designed to run 24/7/365 logging issues with wifi networks. 
System requirements:
- A client running the python3 test script. The script has been tested to work on linux and termux/android.
- A iperf2 and/or iperf3 server, preferably inside the local (home) network, e.g. on the internet router.

The reason I started this script:
In a small apartment with to many to count wifi networks I experienced occasional (monthly - weeky - daily) issues. Such an issue starts with wifi still being connected but very poor performance. Then wifi becomes unusable. Some time later wifi starts to work again but the huge amount of visible wifi networks dropped to only a handful. I bought two small access points and both became so hot they both died. 
