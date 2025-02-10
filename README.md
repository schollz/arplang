# arplang

arps work in the context of chord changes

forms:

- u: up, goes straight up
- d: goes straight down

in both cases, there are a number of *steps*. for up - it goes up until it reaches that number of steps and then wraps around. for down - it starts that number of steps up and goes down and then loops back around when it gets to the root.

arpeggios can be *inverted* so that they start on something that is not the root.

"converging": up 1, down 1, up 1, down 1

syncopation (note on/note off):

0xAE00: 1010111000000000

movement (note iterating to the next):

0xA800: 1010100000000000

u3d3  -> c4 e4 g4 e4 c4 g3
u3 d3 -> c4 e4 g4 g4 e4 c4 

0x8888: 1000100010001000
