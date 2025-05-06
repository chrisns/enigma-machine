# Enigma-E Project: From Kit to Custom Case and Beyond

This project was inspired by a wonderful family trip to [Bletchley Park](https://bletchleypark.org.uk/plan-a-visit/families/), the historic site of Britain's World War Two codebreakers. It's an awesome place for families, with hands-on exhibits and lots to explore. I definitely recommend planning a visit!

This repository documents my project of building an Enigma-E, an electronic replica of the famous Enigma cipher machine, from a kit purchased from [Crypto Museum](https://www.cryptomuseum.com/kits/enigma/index.htm).


![Finished Enigma-E box closed](./photos/IMG_8111.png)

## The Build

The Enigma-E kit was a fantastic project that I undertook with my two children, aged 8 and 6. It was a great learning experience for all of us, and they even got to practice their soldering skills on many of the components!

![My daughter Freya, 6 soldering the Enigma-E](./photos/IMG_8098.png)
*My daughter Freya, 6, soldering the Enigma-E*

## Custom Wooden Case

After successfully assembling the Enigma-E, I designed and built a custom wooden enclosure for it. I used [300x300x3mm basswood sheets](https://amzn.to/3Z7S3gv) for the construction, and after cutting, I glued the sheets together to achieve 9mm thick walls. This gives the box a really satisfying, solid feel. For the hardware, I used 65 x 15mm brass [furniture hinges](https://amzn.to/3GFS5WG) and a 60 x 40mm [brass buckle lock](https://amzn.to/4jYTOoq). If you're making this box, be sure to check that your hardware measurements work with the design before cutting, so you don't waste a load of wood! I also engraved some imagery and a reminder of what the jumper pins do on the base of the box. This repository primarily serves as a place to share the design files (e.g., `.svg`) for laser cutting a similar wooden box.

![Finished Enigma-E box open](./photos/IMG_8108.png)

## Future Plans

I have several exciting enhancements planned for this project, leveraging the Enigma-E's serial interface:

1.  **Microcontroller Integration:** I plan to use a microcontroller, such as an ESP32, ESP8266, or Arduino, to communicate with the Enigma-E.
2.  **Human Interface Device (HID) Emulation:** The microcontroller will be programmed to emulate a USB or Bluetooth HID. This will allow the Enigma-E to function as a unique keyboard or input device for a computer.
3.  **Web Interface:** I am also considering developing a web interface, potentially hosted on the microcontroller, to allow for remote interaction or configuration of the Enigma-E.
4. **Bombe**: I'd love to use a pair this with a [Bombe](https://en.wikipedia.org/wiki/Bombe) maybe an [online one](https://www.101computing.net/turing-welchman-bombe-simulator/) to demonstrate using a crib to reverse-engineer the Enigma settings.

## Files

### Base

- [base-side-filler.svg](./lasercuts/base-side-filler.svg) - small filler that sits inside the base of the box to keep the front panel from pressing against the front of the box
- [base-side.svg](./lasercuts/base-side.svg) - side of the base of the box
- [base-bottom.svg](./lasercuts/base-bottom.svg) - bottom of the base of the box
- [base-front-no-holes.svg](./lasercuts/base-front-no-holes.svg) - front of the base of the box without the holes for the hardware, this is the inside, so you'll just want one of these
- [base-front.svg](./lasercuts/base-front.svg) - front of the base of the box with the holes for the hardware, you'll want 2 of these
- [base-back.svg](./lasercuts/base-back.svg) - back of the base of the box


### Lid

- [lid-sides.svg](./lasercuts/lid-sides.svg) - side of the lid of the box, layout is 3 layers of the sides including two with holes to mount the plug board (Steckerbrett) patch cables
- [lid-top.svg](./lasercuts/lid-top.svg) - top of the lid of the box
- [lid-back.svg](./lasercuts/lid-back.svg) - back of the lid of the box

### Other
- [enigma_logo_bw.svg](./lasercuts/enigma_logo_bw.svg) - clean path svg of the Enigma logo (black and white) that was good for engraving with
- [box.snaplzr](./lasercuts/box.snaplzr) - [Snapmaker Luban](https://www.snapmaker.com/snapmaker-luban) project file 
- [photos](./photos/) - Directory containing photos of the finished Enigma-E and case

## Contributing

If you build a similar project or have suggestions, feel free to open an issue or submit a pull request! 