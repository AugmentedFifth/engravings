# engravings

These are (mostly [Musescore](https://musescore.org/)) engravings of pieces
originally written in another format (i.e. non-digitally or in a digital format
that isn&rsquo;t Musescore or [Lilypond](http://lilypond.org/)).

## Musescore in particular

Any scores that are in Musescore format here are **not** expected to sound good
or even sound accurate in any way when played using Musescore&rsquo;s playback
feature. Nor are any of the Musescore scores expected to make good use of
Musescore-specific metadata (that is, data not reflected in the score itself,
e.g. pitch ranges for instruments).

Musescore&rsquo;s layout/engraving system works well enough for some things,
but is unfortunately far inferior to a dedicated engraving program like
Lilypond. Because of this, rendering Musescore scores to a visual format (SVG,
PDF, &amp;c.) is expected to produce reasonable and fully readable results, but
don&rsquo;t expect them to look like the most beautiful sheets that
you&rsquo;ve ever seen. One way to get better results &mdash; if you
don&rsquo;t care about unpitched percussion parts, or have a way of working
around them (like setting them yourself in Lilypond) &mdash; is the following:

1. Use Musescore to export the score as
   [MusicXML](https://en.wikipedia.org/wiki/MusicXML) (uncompressed of course).
2. Use Lilypond&rsquo;s built-in `musicxml2ly` command to automatically convert
   the MusicXML to Lilypond format.
3. Use Lilypond to render to the desired visual format (after possibly making
   your own tweaks to the Lilypond file).

Naturally, this is a bit lossy, so not every bit of detail will transfer over,
most notably unpitched percussion parts (which will be destroyed).

## Legal

All contents of this repository (including this document, but not including the
[LICENSE](./LICENSE) text itself) are licensed to anyone under the terms of the
[Creative Commons Attribution-ShareAlike license, version
4.0](https://creativecommons.org/licenses/by-sa/4.0/) (or any higher version,
at your option).

[![CC BY-SA 4.0+](https://i.creativecommons.org/l/by-sa/4.0/88x31.png "CC BY-SA 4.0+")](https://creativecommons.org/licenses/by-sa/4.0/)
