# Thaliak 

Not sure how to handle the triangles without it taking half my life, so may be skipping those


Left Bank | Right Bank

```
~Lv2~{"Name":"Thaliak","Group":"Thaleia","ZoneLockH":[1178],"ElementsL":[{"Name":"Left Bank","type":3,"refX":-15.0,"refY":-30.0,"offX":-15.0,"offY":30.0,"radius":15.0,"color":1677721855,"refActorNPCNameID":11298,"refActorRequireCast":true,"refActorCastId":[35026,35884],"refActorComparisonType":6,"includeRotation":true,"onlyTargetable":true,"onlyVisible":true},{"Name":"Right Bank","type":3,"refX":15.0,"refY":-30.0,"offX":15.0,"offY":30.0,"radius":15.0,"color":1677721855,"refActorNPCNameID":11298,"refActorRequireCast":true,"refActorCastId":[35027,35885],"refActorComparisonType":6,"includeRotation":true,"onlyTargetable":true,"onlyVisible":true}]}
```
Water Orbs (Probably missing a couple combinations)
```
~Lv2~{"Name":"Thaliak Orbs - Top - Left","Group":"Thaleia","ZoneLockH":[1178],"DCond":5,"ElementsL":[{"Name":"","type":2,"refX":-969.0,"refY":933.0,"refZ":-842.0,"offX":-921.0,"offY":933.0,"offZ":-842.0,"radius":12.0,"color":1677721855}],"UseTriggers":true,"Triggers":[{"Type":2,"Duration":5.0,"Match":"MapEffect: 0, 1, 512"}]}
```
```
~Lv2~{"Name":"Thaliak Orbs - Bottom - Left","Group":"Thaleia","ZoneLockH":[1178],"DCond":5,"ElementsL":[{"Name":"","type":2,"refX":-969.0,"refY":957.0,"refZ":-842.0,"offX":-921.0,"offY":957.0,"offZ":-842.0,"radius":12.0,"color":1677721855}],"UseTriggers":true,"Triggers":[{"Type":2,"Duration":5.0,"Match":"MapEffect: 0, 1, 256"}]}
```


# Llymlaen

Wind Rose | Right Strait | Left Strait | Tridents | Serpents

```
~Lv2~{"Name":"Llymlaen","Group":"Thaleia","ZoneLockH":[1178],"ElementsL":[{"Name":"Wind Rose","type":1,"radius":12.0,"color":1677721855,"refActorNPCNameID":11299,"refActorRequireCast":true,"refActorCastId":[34828],"refActorComparisonType":6,"Filled":true},{"Name":"Right Strait","type":3,"refY":30.0,"radius":25.0,"color":1677721855,"refActorNPCNameID":11299,"refActorRequireCast":true,"refActorCastId":[34898],"refActorComparisonType":6,"includeRotation":true,"onlyTargetable":true,"onlyVisible":true,"AdditionalRotation":1.5707964},{"Name":"Left Strait","type":3,"refY":30.0,"radius":25.0,"color":1677721855,"refActorNPCNameID":11299,"refActorRequireCast":true,"refActorCastId":[34897],"refActorComparisonType":6,"includeRotation":true,"onlyTargetable":true,"onlyVisible":true,"AdditionalRotation":4.712389},{"Name":"Trident","type":1,"radius":18.0,"color":1258291455,"refActorNPCNameID":12504,"refActorRequireCast":true,"refActorCastId":[19123,19185,20011,30288,34843,34844,35407],"refActorComparisonType":6,"onlyUnTargetable":true,"onlyVisible":true,"Filled":true},{"Name":"Serpents","type":3,"refY":60.0,"offY":-10.0,"radius":10.0,"color":1677721855,"refActorNameIntl":{"En":"Llymlaen"},"refActorRequireCast":true,"refActorCastId":[34853],"includeRotation":true,"onlyUnTargetable":true}]}
```

# Oschon

Trek Shot (Might be missing a couple directions if he does E/W as well) | Soaring Minuet | Piton Pull | Altitude
```
~Lv2~{"Name":"Oschon","Group":"Thaleia","ZoneLockH":[1178],"ElementsL":[{"Name":"Trek Shot","type":4,"radius":50.0,"coneAngleMin":-60,"coneAngleMax":60,"refActorNPCNameID":11300,"refActorRequireCast":true,"refActorCastId":[35908,35213,35214,35215,35908],"refActorComparisonType":6,"includeRotation":true,"onlyUnTargetable":true,"Filled":true},{"Name":"Soaring Minuet","type":4,"radius":40.0,"coneAngleMin":-135,"coneAngleMax":135,"refActorNPCNameID":11300,"refActorRequireCast":true,"refActorCastId":[35220,35433,36110],"refActorComparisonType":6,"includeRotation":true,"onlyTargetable":true,"onlyVisible":true,"Filled":true},{"Name":"Piton Pull","type":1,"radius":22.0,"color":1677721855,"refActorNPCNameID":11300,"refActorRequireCast":true,"refActorCastId":[35243],"refActorComparisonType":6,"onlyUnTargetable":true,"Filled":true},{"Name":"Altitude","type":1,"radius":6.0,"color":1677721855,"refActorNPCNameID":11300,"refActorRequireCast":true,"refActorCastId":[35249],"refActorComparisonType":6,"onlyUnTargetable":true,"Filled":true}]}
```
Wandering Shot - Front
```
~Lv2~{"Name":"Oschon Wandering Shot - Front","Group":"Thaleia","ZoneLockH":[1178],"DCond":5,"ElementsL":[{"Name":"","refY":740.0,"refZ":130.0,"radius":23.0,"color":1677721855,"Filled":true}],"UseTriggers":true,"Triggers":[{"Type":2,"Duration":8.0,"Match":"MapEffect: 72, 1, 2"}]}
```
Wandering Shot - Back
```
~Lv2~{"Name":"Oschon Wandering Shot - Back","Group":"Thaleia","ZoneLockH":[1178],"DCond":5,"ElementsL":[{"Name":"","refY":760.0,"refZ":130.0,"radius":23.0,"color":1677721855,"Filled":true}],"UseTriggers":true,"Triggers":[{"Type":2,"Duration":8.0,"Match":"MapEffect: 72, 16, 32"}]}
```

# Eulogia

Dont have a great way of dealing with the forms atm, but hopefully can come up with something later.

First Blush | Solar Fans | Hand of the Destroyer | Tridents | Thousandfold Thrust (missing left side) | Soaring Minuet
```
~Lv2~{"Name":"Eulogia","Group":"Thaleia","ZoneLockH":[1178],"ElementsL":[{"Name":"First Blush 1","type":3,"refY":70.0,"radius":12.18,"color":1677721855,"refActorNPCNameID":11301,"refActorRequireCast":true,"refActorCastId":[35379],"refActorCastTimeMin":3.6,"refActorCastTimeMax":30.0,"refActorComparisonType":6,"includeRotation":true},{"Name":"First Blush 2","type":3,"refY":70.0,"radius":12.18,"color":1677721855,"refActorNPCNameID":11301,"refActorRequireCast":true,"refActorCastId":[35380],"refActorUseCastTime":true,"refActorCastTimeMax":30.0,"refActorComparisonType":6,"includeRotation":true},{"Name":"First Blush 3","type":3,"refY":70.0,"radius":12.18,"color":1677721855,"refActorNPCNameID":11301,"refActorRequireCast":true,"refActorCastId":[35381],"refActorUseCastTime":true,"refActorCastTimeMin":7.0,"refActorCastTimeMax":30.0,"refActorComparisonType":6,"includeRotation":true},{"Name":"First Blush 4","type":3,"refY":70.0,"radius":12.18,"color":1677721855,"refActorNPCNameID":11301,"refActorRequireCast":true,"refActorCastId":[35382],"refActorUseCastTime":true,"refActorCastTimeMin":10.5,"refActorCastTimeMax":30.0,"refActorComparisonType":6,"includeRotation":true},{"Name":"Solar Fans","type":1,"radius":25.0,"color":1677721855,"refActorNPCNameID":11322,"refActorRequireCast":true,"refActorCastId":[35393],"refActorComparisonType":6,"Filled":true},{"Name":"Hand of the Destroyer","type":3,"refY":70.0,"radius":20.0,"color":1677721855,"refActorName":"*","refActorRequireCast":true,"refActorCastId":[28840,28841,28844,28847,28848,28849,28850,28853,29148,29151,35399,35400,35401,35402],"includeRotation":true,"onlyUnTargetable":true},{"Name":"Trident","type":1,"radius":18.0,"color":1677721855,"refActorNPCNameID":12504,"refActorRequireCast":true,"refActorCastId":[35408],"refActorComparisonType":6,"Filled":true},{"Name":"Thousandfold Thrust","type":3,"refY":40.0,"radius":40.0,"color":1677721855,"refActorNPCNameID":11301,"refActorRequireCast":true,"refActorCastId":[35415],"refActorComparisonType":6,"includeRotation":true,"onlyTargetable":true,"onlyVisible":true,"AdditionalRotation":1.5707964,"Filled":true},{"Name":"Soaring Minuet","type":4,"radius":40.0,"coneAngleMin":-135,"coneAngleMax":135,"refActorNPCNameID":11301,"refActorRequireCast":true,"refActorCastId":[35220,35433,36110],"refActorComparisonType":6,"includeRotation":true,"onlyTargetable":true,"onlyVisible":true,"Filled":true},{"Name":"Test","type":3,"refY":-30.0,"offY":30.0,"radius":6.0,"color":1677721855,"refActorNPCID":11301,"refActorRequireCast":true,"refActorCastId":[36097],"refActorComparisonType":4,"includeRotation":true,"Filled":true}]}
```
Climbing Shot - Red
```
~Lv2~{"Name":"Eulogia Climbing Shot - Red","Group":"Thaleia","ZoneLockH":[1178],"DCond":5,"ElementsL":[{"Name":"","type":3,"refY":-30.0,"offY":30.0,"radius":6.0,"color":1677721855,"refActorNPCID":11301,"refActorRequireCast":true,"refActorCastId":[29633,29637,29638,36094,36096,36098],"refActorComparisonType":4,"includeRotation":true,"Filled":true}],"UseTriggers":true,"Triggers":[{"Type":2,"Duration":10.0,"Match":"vfx/common/eff/m0857_cast04_c0t1.avfx"}]}
```
Climbing Shot - Blue
```
~Lv2~{"Name":"Eulogia Climbing Shot - Blue","Group":"Thaleia","ZoneLockH":[1178],"DCond":5,"ElementsL":[{"Name":"","type":3,"refY":-30.0,"offY":30.0,"radius":6.0,"color":1677721855,"refActorNPCID":11301,"refActorRequireCast":true,"refActorCastId":[29634,29635,29636,36095,36097,36099],"refActorComparisonType":4,"includeRotation":true,"Filled":true}],"UseTriggers":true,"Triggers":[{"Type":2,"Duration":10.0,"Match":"vfx/common/eff/m0857_cast03_c0t1.avfx"}]}
```
