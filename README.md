# Catbackup API-NPP
- Per executar el programa s'a de tenir instal·lat python v3 o mes. I instal·lar el tesseract (ja hi ha el .exe a la carpeta) en la carpeta tesseract
- Requeriments a "requirements.txt".
- Configuració de la base de dades a `config/config.yaml`
- Logs de errors a `errorLogs/*txt`
- Executar amb opcio -h per veure mes opcions i funcionalitats.
- El fitxer compilar.bat transforma el .py en .pyc que es mes eficient i rapid.


## Estructura de la base de dades
```
"usuari" Usuari amb permisos d'administrador del CatBackup

"contrassenya" Contrassenya del usuari

"host" URL de la interfaç web + /Admin/Login.aspx Per exemple https://catbackup.net/Admin/Login.aspx

"clau" Clau de OPT de CatBackup
```


### Proximament:
2. Afegir support per altres bases de dades a part de mysql
