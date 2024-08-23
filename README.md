# bfv-ereg-fix
Battlefield: Vietnam 1.21 ereg registry fix

Beginning with newer versions of Windows 10, the ereg CD key registration executable started to write into a different registry key than the game read it from, resulting in the game running in unregistered mode. This batch file temporarily fixes this issue by copying the registry key so that the game can read it.

After you put your CD key in the registration program, run the batch file as administrator and the game should start in registered mode.
