# cl_concevip

## Instalación
- Añade `esx_vehicleshop.sql` en tu base de datos
- Sustituye en el server, en el locale y en la explicacion de abajo tumoneda por el nombre que le quieras dar Ej: lococoin
- Añade esto a tu `server.cfg`:

```
ensure cl_viptienda
```
##
Busca en el config del es_extended:

Config.Accounts             = {'bank', 'black_money'}
Config.AccountLabels        = {bank = _U('bank'), black_money = _U('black_money')}

reemplaza por:

Config.Accounts             = {'bank', 'black_money', 'tumoneda'}
Config.AccountLabels        = {bank = _U('bank'), black_money = _U('black_money'), tumoneda = _U('tumoneda'),}
##
Ve a es_extended\locales
y añade

['tumoneda'] = 'Tumoneda',

CL_DEV LO MEJOR
CL_DEV LO MEJOR
