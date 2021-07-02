---
layout: default
---

# Control video playback speed with media keys

I remapped the **existing media control key paradigm** to work better for video. This maps the existing keyboard visual and expected functionality (forward and back arrows, start/stop ) and adds only one more element to remember.

![alt text](/assets/img/video-speed/keyboard-highlight.jpg 'mac keyboard with mapped keys highlighted')

Specifically, these keys now have these functions:

- `F6`: Rewind 10 seconds
- `F7`: Decrement speed 0.5 x
- `F8`: Play / Pause
- `F9`: Increment speed 0.5 x

I like this because I am doing more complex actions with intentional keyboard and mouse actions, such as switching to other videos. Traditionally, with music, it made more sense to be able to jump around the playlist.

I like the ability to jump back because if you miss something it's very quick and easy to hear it again; if the key is -15 sec it is trivial to do 15, 20, or 45 seconds and that's all that is needed for something one is paying attention to. This functionality is also difficult to get right with the mouse, as it takes a fair amount of attention to click at the expected spot and it's always too far or not far enough, and the act of clicking tends to move the cursor which is sensitive to exact input location. Essentially, it's almost not worth attempting to speed things up using the mouse interface.

With everything going remote, I am spending more time watching video lectures. Videos are useful because you can speed through parts you understand, and slow down or even repeat parts that are novel. I wanted to make this easier and require less focused attention.

## Installation

### Requirements

- Mac OS
- Google Chrome browser

### Video Speed Controller

Install the Chrome Browser extension [Video Speed Controller](https://chrome.google.com/webstore/detail/video-speed-controller/nffaoalbilbmmfgbnbgppjihopabppdk). This allows the setting of keystrokes to control video playback.

### Karabiner-Elements

Install [Karabiner-Elements](https://github.com/pqrs-org/Karabiner-Elements). This allows the mapping of physical keyboard keys to different key codes in software.

I used homebrew: `brew cask install karabiner-elements`

## Settings

### Go to Karabiner-Elements Preferences > Function keys...

... and map the following 'Physical key' to 'To key':

- `f6`: f6
- `f7`: f7
- `f9`: f9

When you are done it should look like this:

![alt text](/assets/img/video-speed/function-keys.png 'screenshot of function key screen after configuration')

_Leave "use [function keys] as standard function keys" unchecked, leave Target device as "For all devices"._

Also, make sure your keyboard is checked under Karabiner-Elements Preferences > Devices.

![alt text](/assets/img/video-speed/devices.png 'screenshot of devices screen after configuration')

Now the code sent when a key has pressed will be updated from this
![alt text](/assets/img/video-speed/events-before.png 'screenshot of key events before configuration')

to this
![alt text](/assets/img/video-speed/events-after.png 'screenshot of key events after configuration')

These new keys can be mapped in the Video Speed Controller settings.

### Go to Video Speed Controller > Settings > Shortcuts and set the following:

- Decrease speed: F7, 0.5
- Increase speed: F9, 0.5
- Rewind: F6, 10

When you are done it should look like this

![alt text](/assets/img/video-speed/controller.png 'screenshot of controller settings screen after configuration')

_Note: for image clarity I cleared keys that were not changed; these reset to default upon save._

The second parameter is the speed increment to change. I find that going beyond 2.5 makes the sound unusable and causes anxiety, and it takes too many clicks down to return to 1.0 is the increment is the default .25. Of course, you can tune these to your liking.

## Usage

Open a YouTube video, you should see the playback speed in the upper left
![alt text](/assets/img/video-speed/normal.png 'screenshot of youtube video with normal playback speed')

_If you don't see this, try pressing v for "Show/Hide controller"._

Now, press `F9` and you should see the playback speed advance to `1.50`
![alt text](/assets/img/video-speed/fast-highlight.png 'screenshot of youtube video with increased playback speed')

_Note that `F8` will work even when another screen is foremost, but the three we set up require the browser tab to be foremost to function._

## What else would be interesting:

- I'd like to make this easier to share and maintain by using the [Karabiner complex rules](https://karabiner-elements.pqrs.org/docs/manual/configuration/configure-complex-modifications/) mechanism; right now it is very manual to setup which makes it hard to share / limits the audience and takes time each time I switch machines.

- It would be nice to use the media key events directly without setting them in Karabiner. An advantage would be they would work no matter what window was foremost, the same way the play/pause button does (try it!). It's also closer to the system default, which means less setup and less chance of unintended secondary effects. It seems possible because there is a key event registered; if someone knows how to do this, please let me know!

## More background:

YouTube has a mechanism which can be controlled with the mouse. My method was to turn on closed captions, and start the video a bit fast (1.5x) and slow down when I needed to pay more attention. I prefer this to skipping ahead because it's easy to miss comments about how to think about problems or concepts and there is more guesswork. While I liked the method, I found there was a lot of clicking involved and user attention required for the control.

We know about the [jog wheel concept](https://9to5mac.com/2016/12/29/contour-shuttlexpress-review-mac/) from professional video editing, and so I wanted to mimic this - but I did not want to acquire new hardware that would take up space on my desk. I also thought the software mapping would be the most difficult part, and I wanted to make sure this worked before considering spending any money.

## Footnotes

- I also use Karabiner-Elements to map caps-lock to backspace which I discovered via the Colemak keyboard layout community. However, you don't need to switch to Colemak to try it: "...Even if you decide not to learn [Colemak], I recommend remapping the Caps Lock key to Backspace. That change alone results in a 15%-20% reduction of finger distance on QWERTY" [colemak.com](https://colemak.com/FAQ)
