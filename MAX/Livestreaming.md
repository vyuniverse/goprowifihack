### Livestreaming for MAX

First, HTTP Get this URL: http://10.5.5.9/gp/gpControl/execute?p1=gpStream&c1=restart and then you can get a UDP stream by using this URL: udp://10.5.5.9:8554 (you might have a hard time using this in your work...)

**NOTE**: If using ffplay (ffMPEG), try using the `nobuffer` flag, for a low latency stream.
More info can be found here: https://www.reddit.com/r/gopro/comments/2md8hm/how_to_livestream_from_a_gopro_hero4/cr1b193
