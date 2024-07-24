# Integracion de Redes

## Descripción del Proyecto

Este proyecto presenta el diseño y la configuración de la infraestructura de red para la fusión de dos microempresas de 30 y 20 empleados respectivamente, unidas por un enlace WAN. El repositorio incluye el archivo de simulación de Cisco Packet Tracer (.pkt) y los archivos de texto con la configuración de los routers y switches.

## Contenido del Repositorio

- `network_design.pkt`: Archivo de simulación de Cisco Packet Tracer que contiene el diseño lógico de la red.
- `A-router_config.txt`: Archivo de texto con la configuración del Router A (Microempresa A).
- `router_B_config.txt`: Archivo de texto con la configuración del Router B (Microempresa B).
- `switch_A1_config.txt`: Archivo de texto con la configuración del Switch 1 de la Microempresa A.
- `switch_A2_config.txt`: Archivo de texto con la configuración del Switch 2 de la Microempresa A.
- `switch_A3_config.txt`: Archivo de texto con la configuración del Switch 3 de la Microempresa A.
- `switch_B1_config.txt`: Archivo de texto con la configuración del Switch 1 de la Microempresa B.
- `switch_B2_config.txt`: Archivo de texto con la configuración del Switch 2 de la Microempresa B.
- `switch_B3_config.txt`: Archivo de texto con la configuración del Switch 3 de la Microempresa B.

## Solución de Incorporación

- **Enlace WAN:** Conexión VPN sobre Internet utilizando routers ISR4331.
- **Protocolo de Enrutamiento:** RIP para la comunicación entre las microempresas.
- **Segmentación de la Red:** Uso de VLANs para segmentar el tráfico de PCs, servidores e impresoras.

## Soluciones de Direccionamiento

- **Microempresa A:** Red 192.168.1.0/24
- **Microempresa B:** Red 192.168.2.0/24
- **Red WAN:** 10.0.0.0/30 para la conexión punto a punto entre los routers.

## Diseño Físico y Lógico

- **Diseño Físico:** Ubicación de los equipos de red en cada microempresa y diagrama de cableado.
- **Diseño Lógico:** Segmentación de la red en VLANs y configuración de las VLANs en los switches.

## Propuesta Económica

- **Costos de Equipos:** Detalle de los costos de routers, switches, cables y otros equipos necesarios.
- **Costos de Implementación:** Mano de obra para la instalación y configuración, y capacitación para el personal.
- **Costos de Mantenimiento:** Soporte técnico y actualizaciones de software.

## Conclusión

Este proyecto proporciona una solución integral para la fusión de dos microempresas, mejorando la conectividad, seguridad y eficiencia de la red. La implementación de esta infraestructura permitirá una integración fluida y un rendimiento óptimo de la red.

## Contacto

Para más información, puedes contactarme en paul83511@gmail.com.

---

¡Gracias por revisar este proyecto!
