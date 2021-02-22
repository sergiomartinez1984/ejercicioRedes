# ejercicioRedes

Realizar utilizando Cisco Packet Tracer el siguiente ejercicio:
- Crear cinco redes:

    1. Crear tres subredes (VLSM), una que soporte 100 host (192.168.1.0/25),
    otra que soporte 30 (192.168.1.128/27)
    y por último una para 6 host(192.168.1.161/29).No pueden salir ninguno fuera

    2. 8 ordenadores con DHCP.(Se crea un servidor con ip fija(192.168.2.50/24) y el DHCP configurado para asignar las IPs apartir de la 192.168.2.50 con mascara 255.255.255.0, puerta de enlace 192.168.2.1 y servidor dns el 172.10.10.1)

    3. 4 ordenadores con DHCP.  (Se crea un servidor con ip fija(192.168.3.50/24) y el DHCP configurado para asignar IPs apartir de la 192.168.3.50 con mascara 255.255.255.0, puerta de enlace 192.168.3.1 y servidor dns el 172.10.10.1)

    4. 4 ordenadores con IP fija, un punto de acceso con 5 ordenadores con DHCP.
      (los cuatro PCs se configuran en la red 192.168.4.1/24 con IPs entre (192.168.4.3) y la (192.168.4.6) , 
       se crea un servidor con ip fija(192.168.4.50/24) y el DHCP configurado para asignar IPs apartir de la 192.168.4.5 con mascara 255.255.255.0,
       puerta de enlace 192.168.4.1 y servidor dns el 172.10.10.1, se añade un punto de acceso con 5 ordenadores conectados en DHCP)


    5. 5 ordenadores con IP fija. (Se crea la red 172.10.10.50/16 con 5 ordenadores conectados y configurados con puerta de enlace 172.10.10.50/16 y servidor DNS 172.10.10.1)

    - Todas las redes excepto las subredes estan conectadas mediante routers
    - he puesto tres servidores web:

    1. www.albacete.es :(Se crea un servidor con ip 172.10.10.4/16 configurado con el servicio web habilitado para que muestre una foto de Albacete)

    2. www.wagner.de :  (Se crea un servidor con ip 172.10.10.3/16 configurado con el servicio web habilitado para que muestre una foto de Wagner)

    3. www.dilar.com :  (Se crea un servidor con ip 172.10.10.2/16 configurado con el servicio web habilitado para que muestre una foto de Dilar)

    - He creado un servidor DNS para resolver los nombres anteriores.(Se crea un servidor con ip 172.10.10.1  configurado con el servicio DNS habilitado para que resuelva las IPs de los servidores web del punto anterior
