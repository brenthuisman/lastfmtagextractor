## lastfmtagupdater

This programm uses tag information obtained from LastFM to update your files tags. Mainly intended for filling the genre tag.

### Install

Simply run the following:

    $ python setup.py install

Or run directly with:

    $ python lastfmtagupdater

## Usage

After installation, run with `lastfmtagupdater`. Command line options may be enumerated by using the --help option.

The default configuration file is [lastfm_tagger.conf]. Assuming that the configuration file points to your media directory, it's typically sufficient to simply run the above Python file without any options. 

### Dependencies:

 * Python3
 * Mutagen
 * pyLast
 * LastFM API Key (available at http://www.last.fm/api without any fuss)

### Changelog

 * 2018-07-20: v3.0.1. Updates to tag handling, more robust capitalization and duplicate checking. New configuration option: skipTags. Helps unclutter tags retrieved from LastFM.
 * 2016-03-21: Renamed to lastfmtagupdater, bumped version number to v3. Finish port to Python 3, added setup.py. Cleaned up code, removed Gui.
 * 2016-01-28: Update writing mp4.
 * 2014-11-30: Fix: correctly ignore writeUntaggedTag. Change: write ID3v2.3 tags instead of ID3v2.4.
 * 2014-11-30: Import of r17 lastfmtagextractor SVN repo @ http://code.google.com/p/lastfmtagextractor

~ Aaron McKee, May 2012
~ Brent Huisman, March 2016