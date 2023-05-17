# Sennheiser Wireless Systems Manager

The in- and exclusion data are exclusively nation wide. To fine-tune the exclusion data to your specific region, you will need to add the TV channels that are active on your location. And because of this, regionally there are some allowed and safe frequencies you could add to inclusion data if you need to maximise your possibilities in a difficult location. Please visit RDI's website for this information.

## `nation-wide-exclusion-data-NL.csv`

Contains nation-wide occupied frequencies. To import these, open `Frequency Manager > Professional Setup > Frequencies/Bands > Import list...`.

## `regional-grid-allowed-nation-wide-frequencies-NL.xml`

This file makes use of the _Regional Grid_ functionality of WSM. It contains _only_ the safe and allowed opertating frequency ranges as declared by the government. They are assigned a priority of _Low_, so WSM will try to plot all devices within these frequency ranges, but leaves you free to defeat them with higher priorities.

An important note: if you have too many devices in a certain range, WSM will venture outside the safe and allowed frequency ranges. Always check the coordination results!

To import this file, you need to be in the following window: `Frequency Manager > Professional Setup > Frequencies/Bands` then just above the frequency/noise graph, you can open a context menu to add or change regional grid.

## `all-UHF-tv-exclusion-data-EU.csv`

WSM does not have a convenient TV channel selection tool. To make things a little easier, I made an exclusion list that contains **ALL** TV channels. **What you need to do (!)** is import this list, find out which TV channels hinder you on your location, keep those TV channel exclusions and delete the rest. If you fail to execute this last directive, you will find you cannot coordinate any device to a frequency!