Landslide (Cardinal Leap)
```
~Lv2~{"Name":"Landslide","Group":"E4S","ZoneLockH":[856],"ElementsL":[{"Name":"Vertical","type":3,"refY":10.0,"offY":30.0,"radius":10.0,"color":1677787391,"thicc":5.0,"refActorNPCID":8350,"refActorRequireCast":true,"refActorCastId":[16667],"refActorComparisonType":4,"includeRotation":true,"onlyUnTargetable":true},{"Name":"Horizontal","type":3,"refY":-10.0,"offY":10.0,"radius":20.0,"color":1677721855,"refActorNPCID":8350,"refActorRequireCast":true,"refActorCastId":[16667],"refActorComparisonType":4,"includeRotation":true,"onlyUnTargetable":true}]}
```
Tankbuster
```
~Lv2~{"Name":"Tankbuster","Group":"E4S","ZoneLockH":[856],"DCond":5,"ElementsL":[{"Name":"Tankbuster","type":1,"radius":5.0,"color":1677721855,"refActorPlaceholder":["<t1>"],"refActorComparisonType":5,"Filled":true}],"UseTriggers":true,"Triggers":[{"Type":2,"Duration":12.0,"Match":"(8350>16662)"}]}
```
Rightward/Leftward Landslide
```
~Lv2~{"Name":"Rightward/Leftward Landslide","Group":"E4S","ZoneLockH":[856],"ElementsL":[{"Name":"Rightward - First","type":3,"refX":-5.0,"refY":-10.0,"offX":-5.0,"offY":30.0,"radius":5.0,"color":1677721855,"refActorNameIntl":{"En":"Titan"},"refActorRequireCast":true,"refActorCastId":[16669],"refActorUseCastTime":true,"refActorCastTimeMin":2.5,"refActorCastTimeMax":5.0,"refActorUseOvercast":true,"FillStep":0.3,"includeRotation":true,"onlyTargetable":true,"onlyVisible":true},{"Name":"Rightward - Second","type":3,"refX":-15.0,"refY":-10.0,"offX":-15.0,"offY":30.0,"radius":5.0,"color":1677721855,"refActorNameIntl":{"En":"Titan"},"refActorRequireCast":true,"refActorCastId":[16669],"refActorUseCastTime":true,"refActorCastTimeMin":6.0,"refActorCastTimeMax":7.0,"refActorUseOvercast":true,"FillStep":0.3,"includeRotation":true,"onlyTargetable":true,"onlyVisible":true},{"Name":"Lefward - First","type":3,"refX":5.0,"refY":-10.0,"offX":5.0,"offY":30.0,"radius":5.0,"color":1677721855,"refActorNameIntl":{"En":"Titan"},"refActorRequireCast":true,"refActorCastId":[16668],"refActorUseCastTime":true,"refActorCastTimeMin":2.5,"refActorCastTimeMax":5.0,"refActorUseOvercast":true,"FillStep":0.3,"includeRotation":true,"onlyTargetable":true,"onlyVisible":true},{"Name":"Leftward - Second","type":3,"refX":15.0,"refY":-10.0,"offX":15.0,"offY":30.0,"radius":5.0,"color":1677721855,"refActorNameIntl":{"En":"Titan"},"refActorRequireCast":true,"refActorCastId":[16668],"refActorUseCastTime":true,"refActorCastTimeMin":6.0,"refActorCastTimeMax":7.0,"refActorUseOvercast":true,"FillStep":0.3,"includeRotation":true,"onlyTargetable":true,"onlyVisible":true}],"Freezing":true,"FreezeFor":3.5,"IntervalBetweenFreezes":2.5}
```
Human Form - Outside
```
~Lv2~{"Name":"Human Form - Outside","Group":"E4S","ZoneLockH":[856],"DCond":5,"ElementsL":[{"Name":"Outside - Left","type":3,"refX":-15.0,"refY":-5.0,"offX":-15.0,"offY":35.0,"radius":10.0,"color":1677721855,"refActorNameIntl":{"En":"Titan"},"FillStep":0.3,"includeRotation":true,"onlyTargetable":true,"onlyVisible":true,"Filled":true},{"Name":"Outside - Right","type":3,"refX":15.0,"refY":-5.0,"offX":15.0,"offY":35.0,"radius":10.0,"color":1677721855,"refActorNameIntl":{"En":"Titan"},"FillStep":0.3,"includeRotation":true,"onlyTargetable":true,"onlyVisible":true,"Filled":true}],"UseTriggers":true,"Triggers":[{"Type":2,"Duration":6.0,"Match":"Titan uses Earthen Gauntlets."}]}
```
Human Form - Inside
```
~Lv2~{"Name":"Human Form - Inside","Group":"E4S","ZoneLockH":[856],"DCond":5,"ElementsL":[{"Name":"Inside","type":3,"refY":-5.0,"offY":35.0,"radius":5.0,"color":1677721855,"refActorNameIntl":{"En":"Titan"},"FillStep":0.3,"includeRotation":true,"onlyTargetable":true,"onlyVisible":true}],"UseTriggers":true,"Triggers":[{"Type":2,"Duration":2.52,"Match":"Titan uses Earthen Gauntlets.","MatchDelay":6.0}]}
```
Bomb Boulders
```
~Lv2~{"Name":"Bomb Boulders","Group":"E4S","ZoneLockH":[856],"ElementsL":[{"Name":"Explosion","type":1,"radius":10.0,"color":1677721855,"refActorNameIntl":{"En":"bomb boulder"},"refActorRequireCast":true,"refActorCastId":[16650],"refActorUseCastTime":true,"refActorCastTimeMin":2.0,"refActorCastTimeMax":5.0,"onlyVisible":true,"Filled":true}]}
```
Truck Form - Inside
```
~Lv2~{"Name":"Earthen Wheels - Inside","Group":"E4S","ZoneLockH":[856],"DCond":5,"ElementsL":[{"Name":"Inside","type":3,"refY":-5.0,"offY":35.0,"radius":5.0,"color":1677721855,"refActorNameIntl":{"En":"Titan"},"FillStep":0.3,"includeRotation":true,"onlyTargetable":true,"onlyVisible":true}],"UseTriggers":true,"Triggers":[{"Type":2,"Duration":5.0,"Match":"Titan uses Earthen Wheels."}],"Freezing":true,"FreezeFor":5.0}
```
Truck Form - Outside 

(These will most certainly break when the boss spams the dash over and over if running the fight synced, and I will be unable to fix it until BLU patch releases)

(Aoe will hit the far lane after this hit, but the boss spins to face someone and throws it off without time to freeze)
```
~Lv2~{"Name":"Earthen Wheels - Outside 1","Group":"E4S","ZoneLockH":[856],"DCond":5,"ElementsL":[{"Name":"Left","type":3,"refX":-10.0,"refY":30.0,"offX":-10.0,"offY":-40.0,"radius":5.0,"color":1677721855,"refActorNameIntl":{"En":"Titan"},"FillStep":0.3,"includeRotation":true,"onlyTargetable":true,"onlyVisible":true},{"Name":"Right","type":3,"refX":10.0,"refY":30.0,"offX":10.0,"offY":-40.0,"radius":5.0,"color":1677721855,"refActorNameIntl":{"En":"Titan"},"FillStep":0.3,"includeRotation":true,"onlyTargetable":true,"onlyVisible":true}],"UseTriggers":true,"Triggers":[{"Type":2,"TimeBegin":6.0,"Duration":4.0,"Match":"Titan uses Earthen Wheels.","MatchDelay":5.0}],"Freezing":true,"FreezeFor":2.5}
```
Magnitude 5.0
```
~Lv2~{"Name":"Magnitude 5.0","Group":"E4S","ZoneLockH":[856],"ElementsL":[{"Name":"Donut","type":1,"radius":0.0,"Donut":30.0,"color":1677721855,"thicc":3.0,"refActorNameIntl":{"En":"Titan"},"refActorRequireCast":true,"refActorCastId":[16673],"FillStep":1.0,"includeHitbox":true,"onlyTargetable":true,"onlyVisible":true}]}
```