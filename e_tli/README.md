# Mario Extended Tactic level Information (E-TLI) Play Log
## Play log definition:
```python
['BlockCoinDestroy', 'BlockCoinDestroyBulletBill', 'BlockPowerDestroy',
'BlockPowerDestroyBulletBill', 'CollectCoin', 'CollectCoinBulletBill',
'DeathByBulletBill', 'DeathByGap', 'DeathByShell', 'DieByGoomba',
'DieByGreenKoopa', 'DuckEnd', 'DuckStart', 'FireKillGoomba',
'FireKillGreenKoopa', 'FireStateEnd', 'FireStateStart', 'JumpEnd',
'JumpStart', 'LargeStateEnd', 'LargeStateStart', 'LeftMoveEnd',
'LeftMoveStart', 'LittleStateEnd', 'LittleStateStart', 'LostLevel',
'RightMoveEnd', 'RightMoveStart', 'RunStateEnd', 'RunStateStart',
'ShellKillBulletBill', 'ShellKillGoomba', 'ShellKillGreenKoopa',
'StartLevel', 'StompKillBulletBill', 'StompKillGoomba',
'StompKillGreenKoopa', 'UnleashShell', 'WonLevel', 'CorpusIndex']
```

## Overview
Each row represents an episode, where the line is terminated by a `#0,0,0#`.
Each step within the episode is separated with a `|`. The above play log definition
defines what each entry within the play log represents.
