# Klipper-Motor-Testing-Results
Currently I have these motors for testing:
LDO [2804AH](https://northprint3d.ca/product/ldo-42sth48-2804-2-8a-super-power-stepper-motor/)
LDO [2504AH](https://www.3dlabtech.ca/product/ldo-nema17-motor-ldo-42sth48-2504ah/)
LDO [2004MAH](https://www.3dlabtech.ca/product/ldo-nema17-motor-ldo-42sth48-2004mah/)
OMC [17HE19-2004S](https://www.omc-stepperonline.com/e-series-nema-17-bipolar-55ncm-77-88oz-in-2a-42x48mm-4-wires-w-1m-cable-connector-17he19-2004s)
LEADSHINE [42CM06](https://www.leadshine.com/product-detail/42CM06.html)

Testing methodology:
I'll be running: https://github.com/MRX8024/chopper-resonance-tuner/blob/main/wiki/chopper_tuning_guide_english.md 
at 24v on tmc2209s.
Then 24v on tmc5160s.
Then 48v on tmc5160s.

Then testing for max speeds I can get out of them.
Then I'll run a VFA test at various speeds including motor resonance bands.

