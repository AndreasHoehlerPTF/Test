
# TODO list for this project

## Tests to do after library updates
* [ ] Sleep / ESTop
* [ ] Reset PUC Message reset 2x
* [ ] Fuse Control tests



## Refactoring for Deformation integration


### Detection (StarPosDetect/MarkCam)
- (option) vorgelagerter StartDetection Sensor
- [ ] Refactor `iStartPosDetectExt` better to an interface to MASTER Module


### PrintModule
- MASTER / SLAVE Module
- Be a `I_PrintSubSystem`





### FB_WorkerDefGrid
- *FB_ParamMediator* try to make it more generic (no pointer to specific Worker)
- 



### Counting
We try to do this the same way like on a DMAX.
A Verification worker checks the arriving Containers (for validity) and counts at the end of the machine.
(ImageEnd Isr) can be a fallback option if the Verification is not possible.
