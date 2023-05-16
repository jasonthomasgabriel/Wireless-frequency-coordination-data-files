# audio-technica Wireless Manager

Wireless Manager's frequency gamut runs from 150MHz to 2000MHz, in- and exclusion information outside of this range is therefore omitted.

**An important message before you get started:** Wireless Manager does not seem to prioritise (or snap to) inclusion data, so frequencies may end up being coordinated to a frequency that is neither included nor excluded. This may mean you will operate your wireless device on a frequency that is not allowed by the government.

To "solve" this issue, I have made an alternative exlusion data file (`WORKAROUND-nation-wide-exclusion-data.NL.json`) that blocks out the entire frequency spectrum except for the the allowed ranges by the governement. The major drawback of this solution is that it is much harder to add subtract your own region safe zone. Next to that, inputting and mainting this data is much more time-consuming, as the goverment provides a list of where you _can_ be.

## `nation-wide-exclusion-data.NL.json`

The exclusion data is exclusively nation wide. To fine-tune the exclusion data to your specific region, you will need to select the TV channels that are active on your location.

## `WORKAROUND-nation-wide-exclusion-data.NL.json`

Contains the same data is above mentioned file, but additionally all frequencies except for the nation-wide allowed frequencies ranges are blocked out. (I hope an update of Wireless Manager will make having to do this obsolete).

## `nation-wide-inclusion-data.NL.json`

The inclusion data is exclusively nation wide. Regionally there are some extra allowed and safe frequencies you could add to inclusion data if you need to maximise your possibilities in a difficult location. Please visit RDI's website for this information.

> **Note:** Again, know that inclusion data is merely a visual aid in Wireless Manager. Contrary to the user manual, inclusion data seems to function more like _zones_ for if you would want to seperate your devices across various stages into frenquency ranges. This is not implied behaviour in the manual nor expected by nomenclature.
