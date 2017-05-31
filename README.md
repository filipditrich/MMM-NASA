## MMM-NASA
Stunning imagery and information about your universe.

Brought to you by NASA's Hubble, Spitzer and Galaxy Evolution Explorer Telescopes. (And others)

## To Infinity And Beyond!

![](pix/1.JPG), ![](pix/6.JPG), ![](pix/3.JPG)

![](pix/4.JPG),![](pix/5.JPG), ![](pix/2.JPG), ![](pix/7.JPG)

## Installation

* `git clone https://github.com/mykle1/MMM-NASA` into the `~/MagicMirror/modules` directory.

* No API needed!

* Annotated .css file included for sizing and coloring, text or no text.

## Config.js entry and options

    {
        module: 'MMM-NASA',
        position: 'top_left',
        config: {
            search: "nebula",              // See search: "parameters" list. 
		    rotateInterval: 5 * 60 * 1000, // New Image Appears
		    useHeader: false,
            header: "",
		    maxWidth: "300px",             // For description text. Image size using css file.
		    animationSpeed: 3000,          // Image fades in and out
            initialLoadDelay: 4250,
            retryDelay: 2500,
		    updateInterval: 60 * 60 * 1000, // NASA Limits 50 calls a day. Every 30 minutes = 48. 
        }
    },
	

## Config entries for search: "Galaxy",  <-- Example

* The search field is somewhat flexible. You can enter either "Galaxy" or "Galaxies".
* There is no set list, per se. Try any astronomical term. These work.

* Galaxy
* Galaxies
* Nebula
* Orion nebula
* Crab nebula
* Supernova
* Asterism
* Asteroid
* Black hole
* Comet
* Any planet name (e.g. Saturn, Jupiter, etc..)
* Constellation
* Culmination
* Binary Star
* Earthshine
* Eclipse
* Equinox
* Gibbous
* Meteor
* Milky Way
* Occultation
* Parallax
* Retrograde
* Solstice
* Terminator
* Transit

## Try your own. Name something in the sky and see what you get.

## Special thanks to NASA and SpaceCowboysDude
