Nox | Crosses

```
~Lv2~{"Name":"Zeromus","Group":"Abyssal Fracture Extreme","ZoneLockH":[1169],"ElementsL":[{"Name":"Nox","type":3,"refY":35.0,"radius":5.0,"color":1677721855,"refActorDataID":2013519,"refActorPlaceholder":[],"refActorComparisonAnd":true,"refActorComparisonType":8,"includeRotation":true,"onlyUnTargetable":true,"refActorObjectEffectData1":1,"refActorObjectEffectData2":2,"refActorObjectEffectMax":5000},{"Name":"Miasmic Blast 1","type":3,"refY":-35.0,"offY":35.0,"radius":5.0,"color":1677721855,"refActorNPCNameID":12586,"refActorRequireCast":true,"refActorCastId":[35657],"refActorComparisonType":6,"includeRotation":true,"onlyUnTargetable":true},{"Name":"Miasmic Blast 2","type":3,"refY":-35.0,"offY":35.0,"radius":5.0,"color":1677721855,"refActorNPCNameID":12586,"refActorRequireCast":true,"refActorCastId":[35657],"refActorComparisonType":6,"includeRotation":true,"onlyUnTargetable":true,"AdditionalRotation":1.5707964}]}
```
Abyssal Echo (From Gabein Discord, I adjusted timings to avoid moving before the mechanic even starts)

1
```
~Lv2~{"Name":"Abyssal Nox AOE 1","Group":"Abyssal Fracture Extreme","ZoneLockH":[1169],"ElementsL":[{"Name":"Abyssal Echo","type":1,"radius":12.0,"color":1258291455,"refActorDataID":9020,"refActorRequireCast":true,"refActorCastId":[35578,35650],"refActorUseCastTime":true,"refActorCastTimeMax":3.0,"refActorComparisonType":3,"onlyUnTargetable":true,"Filled":true}],"Freezing":true,"FreezeFor":11.0,"FreezeDisplayDelay":9.5}
```
2
```
~Lv2~{"Name":"Abyssal Nox AOE 2","Group":"Abyssal Fracture Extreme","ZoneLockH":[1169],"ElementsL":[{"Name":"Abyssal Echo","type":1,"radius":12.0,"color":1258291455,"refActorDataID":9020,"refActorRequireCast":true,"refActorCastId":[35578,35650],"refActorUseCastTime":true,"refActorCastTimeMin":10.0,"refActorCastTimeMax":13.0,"refActorUseOvercast":true,"refActorComparisonType":3,"onlyUnTargetable":true,"Filled":true}],"Freezing":true,"FreezeFor":6.0,"IntervalBetweenFreezes":3.0,"FreezeDisplayDelay":1.0}
```