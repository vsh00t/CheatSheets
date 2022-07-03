- [x] Revisar archivos en texto plano en shares a los que tenga acceso el usuario. 

- smbmap
- smbclient
- https://github.com/binaryAccess/highway_to_hell/blob/master/SearchUser.ps1

- [x] Revisar Kerberoast & ASREPRoast

- BloodHound
- Rubeus

- [x] En el caso de haber obtenido hashes de usuarios vulnerables a kerberoasting crackeralos.

- Hashcat
- John

- [x] Si obteiens la clave o el hash de un usuario administrador, prueba si es posible usar esas credenciales en otros equipos del dominio. 

- Crackmapexec

- [x] Revisar las delegaciones de kerberos que tienen los equipos y ver si es posible usarla con los usuarios/privilegios obtenidos. 

- Bloodhound
- Rubeus
- PrinterBug

- [x] Identificar los usuarios que tenga privilegio para realizar DCSync.

- Bloodhound

- [x] Ejecutar dcsync para extraer hashes de todo el dominio.   

- Mimikatz

- [x] Tomar control de la cuenta krbtgt para poder generar golden tickets. 
- [x] Reporting

- Ping Castle
- Bloodhound

