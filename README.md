# quasikb
yet another split 36key keyboard


I am a huge fan of pashutk's chocofi as it is the first split ergo keyboard I've got to use and fall in love with. After a year of use I found myself wanting to tweak some of its design characteristics to better fit my hands. Although I love its compact design I felt the need to spread out the keys a little and give an heavier pinky stagger, ring and pinky slant. The thumb cluster is also spaced out more to help with a more comfortable reach. The keys are a little spaced between each other as to have a more comfortable relax position of my fingers. To achieve all of this I've used ergogen and designed my keyboard from scratch, that said a huge portion of its look and inspiration goes to the chocofi as I still use it daily and wanted my custom keyboard to be ready to use, and not have to adapt once more to a new keyboard layout. For this reason I've opted for this not to be a direct fork, but rather used pashutk's work as an inspiration to create quasikb.

Aesthetics and ergonomy aside, as per the hardware I also decided to go a slightly different route. The whole ethos of the project was to be as minimal as possible, anything that [i] didn't need it's not included, only the bare minimum to make a functional keyboard for myself. For this reason you will see that this keyboard lacks a lot of the flexibily or features that other keyboard have, that is by design. I daily drive a fully bluetooth chocofi, equipped with nice nanos and nice views. For my keyboard I preferred not to have nice views, as albeit useful at times, I didn't felt the absolute need for them especially considering the added cost. Gone also are the diodes, I definitely didn't want to hand solder those, and opted for an easier solder job with just direct to GPIOs connections. As said, since I've designed this for myself I didn't opt to add anything more than the absolute needful, this means that this keyborad design, as it currently stands, doesn't support TRSS jacks and wired builds, doesn't support nice views, LEDs and it's intended to be used with nice nanos and fully bluetooth with zmk.

few notes for future, as I type this on it, I have a few things I might keep improving, ergonomy is great, but might try to space the fingers less? the controller to big thumb line isn't perfectly straight, will have to address that. And the biggest gripe, since I decided to use the extra gpios found in the nice nanos to connect the thumb cluster the standard battery recoomended with nice nanos sticks out a bit, I would like to find a battery that is shorter so it tucks in nicely under the controller. If I find one I will update here my findings.


in this repo you can find submodules pointing to my ergogen and zmk-config repo, in those you can find anything you need for the pcb design and firmware to flash the keyboard once built. Read the ergogen readme for info on where the files for quasikb are, same goes for zmk config.


BOMu:

+ you need to print your pcbs, it is currently set up for JLCPCB.
+ 36x kailh choc switches sockets I've bought them directly from Kailh official [aliexpress shop][https://a.aliexpress.com/_mNf3t1d]
+ 2x C&K Tactile Switches model PTS636 SL43 LFS ( for reset )
+ 2x Alps Alpine Slide Switches model SSSS811101 ( for on/off )
+ 2x 301230 batteries as advised for nice nanos, ( i will be experimenting with this )
+ 2x nice nanos
+ your choice of 36x choc v1 switches, I am using a combination of [nocturnals][https://lowprokb.ca/products/ambients-silent-choc-switches?variant=44873446391972] for most keys and [sunsets][https://lowprokb.ca/collections/switches/products/sunset-tactile-choc-switches] for big thumb 
+ your choice of 36x choc keycaps, I am using [LDSA][https://lowprokb.ca/collections/keycaps/products/ldsa-low-profile-blank-keycaps]
+ optional tenting feet, I am using these from [typeractive][https://typeractive.xyz/products/tenting-feet?_pos=1&_sid=341f7f11b&_ss=r]
