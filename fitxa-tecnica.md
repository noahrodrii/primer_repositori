## CONFIGURARÓ D'UNA XARXA LOCAL PETITA
<img src="/Imatges/Imatge xarxa petita.png" alt="Esquema de la xarxa" width="500">

## Objectiu
Configurar una xarxa local entre dos ordinadors, assignant una adreça IP a cada equip i comprovant que es poden comunicar correctament.

## Materials
- 2 ordinadors.
- 2 cables de xarxa Ethernet.
- Un switch.
- Sistema operatiu Windows.
- Comanda ipconfig i ping.

## Esquema de la xarxa
<img src="/Imatges/Imatge xarxa dos equips.png" alt="Esquema de la xarxa" width="500">

## Procediment

1. Connectar els dos ordinadors al switch mitjançant cables Ethernet.
2. Obrir la configuració de xarxa de cada ordinador.
3. Configurar el primer ordinador amb l’adreça IP 192.168.1.10 i màscara 255.255.255.0.
4. Configurar el segon ordinador amb l’adreça IP 192.168.1.20 i la mateixa màscara.
5. Obrir el terminal de Windows.
6. Utilitzar la comanda ipconfig per comprovar que les adreces IP s’han configurat correctament.
7. Des del primer ordinador, executar ping 192.168.1.20.
8. Comprovar que es reben les respostes del segon ordinador.

## Comprovacions

- [ ] Els dos ordinadors estan connectats al switch.
- [ ] El primer ordinador té la IP 192.168.1.10.
- [ ] El segon ordinador té la IP 192.168.1.20.
- [ ] La màscara és 255.255.255.0 als dos equips.
- [ ] El ping rep resposta correctame

## Comanda
```bash
ipconfig
```

## Incidències i solucions

| Incidència                   | Solució                                                            |
| ---------------------------- | ------------------------------------------------------------------ |
| El `ping` no respon          | Comprovar que els dos ordinadors tenen una IP de la mateixa xarxa. |
| No apareix connexió Ethernet | Comprovar que el cable està ben connectat.                         |
| La IP no és correcta         | Revisar la configuració IPv4 de l’ordinador.                       |
| El switch no mostra connexió | Comprovar el cable i el port utilitzat.                            |


## Recursos

- [Documentació ipconfig microsoft](https://learn.microsoft.com/ca-es/windows-server/administration/windows-commands/ipconfig?utm_source)
- [Documentació ping microsoft](https://learn.microsoft.com/ca-es/windows-server/administration/windows-commands/ping?utm_source)
