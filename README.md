# OE QDMR Codeplugs

A Repository for DMR-Codeplugs for Austria (and neighbouring countries / regions).  
Using YAML Format readible by qdmr (https://dm3mat.darc.de/qdmr/).

**WARNING: There may be some errors. Work in Progress**

The `rt3s_gps_buttons.yaml` could work with other radios as well, I only tested it with a RETEVIS RT3S GPS.  
The `rd5r.yaml` is modified for the Baofeng RD-5R (or similar radios) as they can only store 16 channels per zone.  
The `anytone_compatible.yaml` is currently **WORK IN PROGRESS** and tested on Anytone AT-D878UVII Plus but should also work with RETEVIS RT3S GPS.

## Use

Open the file you want to try in qdmr and in the **Settings** tab change `YOURCALL` and `YOURNAME` according to your needs.  
In the **Radio IDs** tab enter your DMR id, then check the codeplug and upload it to your radio using the functions qdmr provides.

## License: CC0 Public domain

## TODO:
- [ ] Add more analog repeaters
- [x] Change analog repeater names to callsigns
- [ ] Add simplex DMR Frequencies in additional Zone
- [ ] Add more description (user must change DMR-ID, may change welcome message)
- [ ] Test other DMR radios 
