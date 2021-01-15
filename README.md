# BOSS-IonPump-Interface
The BOSS CCD dewars use a Modion C-1765V 2l/s ion pump with a custom vacuum fitting. This model number is not on the current modionvacuum.com website but the C-1765M looks similar.
The power supply is a Modion C-1766Q, which supplies the high voltage and also presents an analog signal indicating internal current that can be used as a vacuum pressure measurement. This power supply has an unusual 5-pin connector with a wall plug-in supply to supply power and also break out the signals.
To distribute the signals to the BOSS motion controller system (specMech) we use an interface box that supplies isolated 15 V to the two ion pumps (one on each of the two dewars) and conditions the analog signal for transmission to the control system.
[Link to the interface board description](https://docs.google.com/document/d/1ESppHA3kPF6aFfvCehlsRecCQ0mpgMWIIbT9OZ6ddFA/edit#)
