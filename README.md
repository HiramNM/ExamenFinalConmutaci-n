# ExamenFinalConmutacion
Examen final de conmutación 08/12/2025

# Instrucciones Generales
La compañía JuanMark le ha pedido hacer cambios en diferentes regiones de su red Nacional. Los cambios son en las siguientes áreas.

# Información de la Red

    Dominio: JuanMark.com
    Número de Red IPv4: 148.60.0.0/16
    Red IPv6 (Dual Stack - Región Noroeste): 2006:AFEA:B0CA::/48
    Topología: Ver diagrama JuanMark.drawio
Regiones de la Red:

    Noroeste (NW) - Noriega Melendres Hiram – 22170740 
    Noreste (NE)  - Calderon Esquivel Oliver Jahaziel – 22170590
    Sureste (SE)  -	Astorga Ramos Jorge Abel – 22170566
    Centro (CE)   -	Sarabia Sosa Cristofer – 22170825
Enlaces WAN:

    1 Mbps
    512 Kbps
    1.5 Mbps

# Segmentación de VLANs
Región Noroeste

    VLAN 5: Marketing
    VLAN 6: Ventas
    VLAN 7: Compras
    VLAN 9: Gestión de TI
Región Noreste

    VLAN 97: Gestión de TI
    VLAN 98: Ventas
    VLAN 99: Compras
    VLAN 100: Servicios
Región Centro

    VLAN 33: Gestión de TI
    VLAN 34: Gestión de WLAN
    VLAN 35: Ventas
    VLAN 36: Compras
    VLAN 37: Practicantes
Región Sureste

    VLAN 65: Ventas
    VLAN 66: Gestión TI
    VLAN 67: Compras
    VLAN 68: MKT

# Requerimientos por Región
# Región Noreste (NE)
Tareas específicas:

  Configure HSRP para que no se pierda conectividad con el resto de la red empresarial

    Implementar redundancia de gateway
Configure el Access Point autónomo

    WLAN operativa
Configure STP para que no queden enlaces desactivados

    Optimizar topología STP
    Minimizar enlaces bloqueados
Obtenga el árbol de expansión para cada VLAN

    Documentar topología STP por VLAN

# Región Noroeste (NW)
Tareas específicas:

  Implemente IPv4 e IPv6 (Dual Stack)

    Network ID IPv6: 2006:AFEA:B0CA::/48
    Configurar direccionamiento dual stack
Configure VTP Server

    Propagar VLANs a switches de la región
Configure DHCP

    En el router
Ruteo inter VLAN

    Router-on-a-stick

# Región Sureste
Tareas Específicas

  Configure HSRP para que no se pierda conectividad con el resto de la red empresarial

    Implementar redundancia de gateway
Configure VTP Server

    Propagar VLANs a switches de la región
Configure STP para que no queden enlaces desactivados

    Minimizar enlaces bloqueados
EtherChannel

    Configure la agregación de enlaces donde se indique
WLAN

    Los diferentes departamentos tienen acceso a la red por WiFi y por cable. Configure la controladora.

# Región Centro
Características:

    Punto central de interconexión
Tareas especificas
  
Controladora de WLAN

    a las WLAN en los dos edificios.
VTP

    Propagar las VLAN a todos los switches
Seguridad de puertos

    para prevenir ataques a la Tabla MAC
DAI para evitar un servidor DHCP no autorizado
