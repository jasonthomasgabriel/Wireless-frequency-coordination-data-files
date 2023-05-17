# Shure Wireless Workbench

The in- and exclusion data are exclusively nation wide. To fine-tune the exclusion data to your specific region, you will need to select the TV channels that are active on your location. And because of this, regionally there are some allowed and safe frequencies you could add to inclusion data if you need to maximise your possibilities in a difficult location. Please visit RDI's website for this information.

## `nation-wide-exclusion-data-NL.fxl`

Adding these exclusion to Wireless Workbench is pretty straight-forward. `Frequency Coordination (tab) > Spectrum (tab) > Additional Exclusions > Import`.

## `nation-wide-inclusion-data-NL.fxl`

This file contains the safe and allowed opertating frequency ranges as declared by the government. To make Wirless Workbench snap _only_ to these inclusions, you will need to import this file in a specific way: `Frequency Coordination (tab) > Spectrum (tab) > Inclusions > Account for user groups (...) [enable] > Manage > Custom` once you have selected custom, find the settings icon under the `Groups` column and click on it to select `Import Groups`. Select this inclusion file and then hit save.

**You are not done yet!** Back in the `User Groups` dialog (that was still open underneath) select from dropdown menu `List` the value _Custom_ and from dropdown menu `User Group` _Nation-wide allowed frequencies_.

Now you're done ;). Is this a little more finicky than it should be? Absolutely! But I don't make the user interfaces. I just work with them.
