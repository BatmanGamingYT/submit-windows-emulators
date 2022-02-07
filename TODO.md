# create a site for EVERY windows version complete with a config settings for users to change the hardware.

* add a network "router" for the windows emulator.

* attempt to add windows 11 into a emulator

* add file moving system (not like anyone's going to import a game into the emulator but who knows :P)

* dont know if anyone would want to do this but who cares: [ADD BONZI BUDDY]

* add steam fully installed

* add minecraft launcher (complete with fabric, TLauncher, Badlion client, Lunar client and Technic.)

* prepackage windows 10 with cortana aka BONZI BUDDY 2.0

* add windows vista, xp, me, 7 and basicly all the windows versions

* optimize the windows 7, 10 and 11 emulator to have average fps when gaming

* add the windows apps like minesweeper and pinball

* add a setup for windows when the user first go on the site

* make a create user setup

* add virtualbox (if users want to use minecraft vm computers mod :p)

* add replit to the emulator (for windows 7, 10 and 11)

# ![](images/icons/shutdown-32x32.png)

* Add more libraries to CREDITS.txt, and possibly include (or at least mention) licenses

* *Properly* link to the repo from within the app, not just with a URL in a virtual text file

* Start Menu

	* Aria attributes

	* "Legitimate content"

* File save and open dialogs

* Integrate Paint better

	* Windows that pop out; will need to display graphics via data URIs or canvases, and rely only on inline styles (or `<style scoped>`?) and the shared styles

		* Could *maybe* use [`<base>`](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/base) for `<img>`s, but all styles (that aren't shared) would have to be inline, and I think it would be better just to try to make everything canvases

* Integrate Blue Screen of Death similar to http://fakebsod.com/generic

	* Press <kbd>~</kbd> or something to bluescreen

	* Prankily wait for next user input before fullscreening and bluescreening

* Try integrating arbitrary applications by emulating Windows 98 on the webpage [with v86](https://github.com/copy/v86/blob/master/docs/api.md),
with an X server installed in the VM, and acting as an X client externally??
And integrating a virtual filesystem??
That would be undoubtedly cool, but idk how hard it might be,
and especially what data channels are available between the VM and the host.
Partially [inspired by OS.js](https://www.youtube.com/watch?v=c0safRR0ldM&index=16&list=PL74DE0E481419C259).
