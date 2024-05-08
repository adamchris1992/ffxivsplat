# E8N

# Scythe Kick
```
~Lv2~{"Name":"Scythe Kick","Group":"E8N","ZoneLockH":[905],"ElementsL":[{"Name":"In","type":1,"radius":4.0,"Donut":20.0,"color":4278190335,"fillIntensity":0.13333334,"originFillColor":436207871,"endFillColor":436207871,"refActorName":"*","refActorRequireCast":true,"refActorCastId":[19939],"includeRotation":true,"mechanicType":1}]}
```

# Axe Kick
```
~Lv2~{"Name":"Axe Kick","Group":"E8N","ZoneLockH":[905],"ElementsL":[{"Name":"Out","type":1,"radius":16.0,"refActorName":"*","refActorRequireCast":true,"refActorCastId":[19938],"mechanicType":1}]}
```

# Biting Frost
```
~Lv2~{"Name":"Biting Frost","Group":"E8N","ZoneLockH":[905],"ElementsL":[{"Name":"270 Frontal","type":4,"radius":30.0,"coneAngleMin":-135,"coneAngleMax":135,"color":4278190335,"fillIntensity":0.325,"originFillColor":1308623103,"endFillColor":1308623103,"refActorName":"*","refActorRequireCast":true,"refActorCastId":[19931],"includeRotation":true,"mechanicType":1}]}
```

# Driving Frost
```
~Lv2~{"Name":"Driving Frost","Group":"E8N","ZoneLockH":[905],"ElementsL":[{"Name":"90 Rear","type":4,"radius":40.0,"coneAngleMin":-45,"coneAngleMax":45,"color":4278190335,"fillIntensity":0.325,"originFillColor":1308623103,"endFillColor":1308623103,"refActorName":"*","refActorRequireCast":true,"refActorCastId":[19932],"includeRotation":true,"AdditionalRotation":3.1415927,"mechanicType":1}]}
```

# Mirrors Reflect
TODO: Additional reflects
```
~Lv2~{"Name":"Mirrors Reflect","Group":"E8N","ZoneLockH":[905],"ElementsL":[{"Name":"Reflected Driving Frost","type":4,"radius":40.0,"coneAngleMin":-45,"coneAngleMax":45,"refActorName":"*","refActorRequireCast":true,"refActorCastId":[19967],"includeRotation":true,"mechanicType":1},{"Name":"Reflected Biting Frost","type":4,"radius":30.0,"coneAngleMin":-135,"coneAngleMax":135,"refActorName":"*","refActorRequireCast":true,"refActorCastId":[19966],"includeRotation":true,"mechanicType":1}]}
```

# Holy
Singly central proximity AoE
```
~Lv2~{"Name":"Holy Proximity (Out)","Group":"E8N","ZoneLockH":[905],"DCond":5,"ElementsL":[{"Name":"Middle AoE","refX":100.0,"refY":100.0,"radius":16.0,"mechanicType":1}],"UseTriggers":true,"Triggers":[{"Type":2,"Duration":8.0,"Match":"(9353>19948)"}]}
```

Multiple proximity AoEs around the outer edge
```
~Lv2~{"Name":"Holy Proximity (In)","Group":"E8N","ZoneLockH":[905],"DCond":5,"ElementsL":[{"Name":"1","refX":100.0,"refY":84.0,"radius":8.0,"mechanicType":1},{"Name":"2","refX":111.30602,"refY":88.70169,"radius":8.0,"mechanicType":1},{"Name":"3","refX":115.995155,"refY":100.0329,"refZ":-1.9073486E-06,"radius":8.0,"mechanicType":1},{"Name":"4","refX":111.25724,"refY":111.26984,"radius":8.0,"mechanicType":1},{"Name":"5","refX":100.0,"refY":116.0,"refZ":1.9073486E-06,"radius":8.0,"mechanicType":1},{"Name":"6","refX":88.6786,"refY":111.273605,"radius":8.0,"mechanicType":1},{"Name":"7","refX":84.0,"refY":100.0,"radius":8.0,"mechanicType":1},{"Name":"8","refX":88.698,"refY":88.688065,"refZ":-3.8146973E-06,"radius":8.0,"refActorComparisonType":8,"mechanicType":1}],"UseTriggers":true,"Triggers":[{"Type":2,"Duration":8.0,"Match":"(9353>19949)"}]}
```
