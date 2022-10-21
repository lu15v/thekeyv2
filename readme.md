# The Key V2 Custom Config

My custom configuration of the "The key" V2 (more info about what this is bellow).

This custom config allows you to modify the macropad without disabling the back lights (a problem that happens when you are following the official instructions website).

![The Key](https://massdrop-s3.imgix.net/product-images/stack-overflow-the-key-v2-macropad/FP/vSqOp9eUQNGXW4zl3EVQ_7528-copy-pdp.jpg?auto=format&fm=jpg&fit=fill&w=820&h=547&bg=f0f0f0&dpr=2&chromasub=444&q=35)


The Stack Overflow "The Key" V2 is a 3 button macropad based on atmega32u4 with Kailh Black Box switches.

> Some say a programmer’s best solution is a simple two-step process: copy and paste. On April 1st, 2021, Stack Overflow proved it. On that fateful day, each time users went to copy a piece of code, they were met with a pop-up for a fake product. It was called The Key: an ultra-compact macropad advertised as the new (and only) way to copy and paste on the platform. As it turns out, roughly one fourth of Stack Overflow’s 15 million users tries to copy and paste within five minutes of visiting the site. An even greater number saw the joke and loved it, with many demanding that The Key be developed in earnest. So, naturally, we teamed up with Stack Overflow to make it happen. What started as an April Fool’s gag is now a full-fledged macropad—designed by our very own community member Cassidy, with a portion of proceeds benefiting digitalundivided.

Keyboard Maintainer: [Drop / Massdrop](https://github.com/Massdrop/qmk_firmware) 

Hardware Supported: Massdrop, Inc. **The Key**

Hardware Availability: Limited Release - https://drop.com/buy/stack-overflow-the-key-macropad



## versions
1. **originalvial**  The original json from the forums (shoudout to monkiebacon in the drop.com questions for posting the original source)
2. **vial** the version with the light, Hue, and copy and paste for mac.

## Compile it with
``qmk compile -kb whatEverYourPathIs/thekeyv2 -km vial``

## Dev instructions
1. Connect the keyboard, and open the VIA app
2. VIA by default should open the installed keyboard, however sometimes it doesn't (at least that's my case) and you need to import it manually.
3. Remplace the current vial.json file with the new one
4. Compile the configuration with the command above.
5. The .hex should be in /Users/yourUser/qmk_firmware
6. Open the QMK Toolbox, flash the keyboard (click on the button under the keyboard).
7. Load the .hex, and click on flash.
