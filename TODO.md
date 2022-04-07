# TODO list for this project

[TOC]

## PLC Configuration

#### Waveform

* [x] New waveform form Steinemann "20200930_Oli_triple and single.xlsm"  

#### StartUp

* [ ] Excel sheet creation (not used yet, StartUp is defined direct in TC3)


## PLC Code

### Tests
* [x] BlockId saving with new fb
* [x] Mask file donwload
* [x] Waveform file download
* [x] Remote HIB updater
* [ ] 

### SystemCmd
* [ ] Sleep, EStop must be handled by library
* [ ] Link FB_PC[iL_I].sI_SystemCmd
* [ ] PRG_Macine signals `IbEStop` and `IbMachineActive` (sleep) must be used

### PRG_INK
* [ ] PurgeEnable signals from BAIER must be used with the command from BAIER

### PRG_PRINT
* [ ] OnNumberPassJob: must be set by job
* [ ] OfYOffsetPass: must be set by job
* [ ] If no printhead is enabled and the print is activated the state machine hangs...

### PRG_Machine
* [ ] Purge allowed: link signal when it comes from BAIER
* [ ] (optional) IbMessageReset from BAIER can be used to reset messages

### Pinning unit
* [ ] Implementation and test


## PUC

### ADS interface

* [ ] `ST_ADS_PU`: ImageDepth and ImageWidth are not correct


## Print

* [ ] Some lines are not printing correctly when two passes with full mask and no stitching are printed
* [ ] Stitching test with generated masks
* [ ] Printing with generated YOffset


## Release

* [ ] Add Security DB again
* [ ] Review File Security settings for all files (lot of new files)
* [ ] Review Licenses
* [ ] Install compiled libraries

