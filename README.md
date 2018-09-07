# Js normalizer

This is a simple implementation of audio level normalization in Javascript.
Such normalization is useful if you are listening to recordings with hugely different loudness levels
and want to have them all keep the same level.

It bases partially on the ReplayGain algorithm, but doesn't implement it fully.

Useful links:

* http://replaygain.hydrogenaud.io/proposal/calculating_rg.html
* http://wiki.hydrogenaud.io/index.php?title=ReplayGain_specification

## License

This is licensed under the terms of the MIT license and the Apache License (Version 2.0), at your option.

The audio files were obtained from the [Mozilla Common Voice project](https://voice.mozilla.org/) and stand under CC-0.
