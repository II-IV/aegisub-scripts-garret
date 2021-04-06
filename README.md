# garret's shitty aegisub scripts

Aegisub automation scripts I've written.
Probably only useful to me.

----

## Script List

### A-B

Makes checking pre-timing possible by putting some text in the lines (the actor name, and `a` or `b` (hence the name))

**Caution: Overwrites every selected line!**

### Audio Clipper

Extracts audio from the selected line(s), like the create audio clip button.
Unlike the create audio clip button, it can copy the audio stream.

Also, if you select multiple lines, it'll make separate clips for each, not one long one.

**Needs ffmpeg. Can be slow.**

### Blur Fade

Makes fade with blur.

Blurs out lines with the effect `blurout`, and blurs in lines with the effect `blurin`.

For fancy fade effects. (i.e, when the whole scene blurs out until it's invisible, as a transition)

### Dupe and Comment

Duplicates a line and comments out the original.

I like seeing the original line while editing, and being able to go back to it easily if my edit was crap.

### Em-dash

Appends an Em-dash (`—`) to the selected line(s).
Replaces `--` with `—`.

I do not have an em-dash key on my keyboard.