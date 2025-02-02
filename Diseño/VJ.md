<Div align="center">
    <img src="https://i.postimg.cc/3Rbr23nJ/UTN-Logo.png" alt="Texto alternativo" style="width: auto; height: 100%;"/>
</div>


<p align="center"><span style="color:White; font-size: 40px;">Diseño de Videojuegos</span></p>


---
###### [Ver Arte 2D](../Arte/2D.md)
###### [Ver Diseño de Videojuegos](../Diseño/VJ.md)
###### [Ver Probabilidad](../Probabilidad/Probabilidad.md)
###### [Ver Documentación](../Documentacion/Arquitectura.md)
###### [Ver Programación](../Programacion/Programacion.md)


### Tabla de Contenidos

---

- [Conceptos Básicos de Arquitectura](#conceptos-básicos-de-arquitectura)
- [Arquitectura Monolítica](#arquitectura-monolítica)
  - [MVC (Modelo-Vista-Controlador):](#mvc-modelo-vista-controlador)
  - [Aplicación de Escritorio WPF o Windows Forms:](#aplicación-de-escritorio-wpf-o-windows-forms)
  - [Servicios Web ASP.NET clásicos:](#servicios-web-aspnet-clásicos)
  - [Ventajas y Desventajas](#ventajas-y-desventajas)
  - [Grafico](#grafico)
- [Arquitectura en Capas](#arquitectura-en-capas)
    - [Capa de Presentación (UI)](#capa-de-presentación-ui)
    - [Capa de Lógica de Negocio (BLL)](#capa-de-lógica-de-negocio-bll)
    - [Capa de Acceso a Datos (DAL)](#capa-de-acceso-a-datos-dal)
    - [Ventajas y Desventajas](#ventajas-y-desventajas-1)
  - [Grafico](#grafico-1)
- [Arquitectura de Microservicios](#arquitectura-de-microservicios)
  - [Componentes Clave](#componentes-clave)
    - [APIs y Comunicación](#apis-y-comunicación)
    - [Gestión de Configuración](#gestión-de-configuración)
    - [Monitoreo y Registro](#monitoreo-y-registro)
  - [Grafico](#grafico-2)
- [Arquitectura Orientada a Servicios (SOA)](#arquitectura-orientada-a-servicios-soa)
  - [Componentes Clave](#componentes-clave-1)
    - [Servicios](#servicios)
    - [Registro de Servicios](#registro-de-servicios)
    - [Seguridad y Gobernanza](#seguridad-y-gobernanza)
  - [Grafico](#grafico-3)
- [Arquitectura de Aplicaciones Distribuidas](#arquitectura-de-aplicaciones-distribuidas)
  - [Componentes Clave](#componentes-clave-2)
    - [Servidores de Aplicaciones:](#servidores-de-aplicaciones)
    - [Servidores de Bases de Datos:](#servidores-de-bases-de-datos)
    - [Servicios Web y APIs:](#servicios-web-y-apis)
    - [Balanceadores de Carga:](#balanceadores-de-carga)
    - [Caché Distribuida:](#caché-distribuida)
    - [Herramientas de Monitoreo y Gestión:](#herramientas-de-monitoreo-y-gestión)
  - [Grafico](#grafico-4)
- [Arquitectura de Cliente-Servidor](#arquitectura-de-cliente-servidor)
  - [Componentes Clave](#componentes-clave-3)
    - [Cliente (Frontend)](#cliente-frontend)
    - [Servidor (Backend):](#servidor-backend)
    - [Base de Datos:](#base-de-datos)
  - [Grafico](#grafico-5)
- [Arquitectura Limpia (Clean Architecture)](#arquitectura-limpia-clean-architecture)
  - [1. Capa de Presentación (Presentation Layer)](#1-capa-de-presentación-presentation-layer)
  - [2. Capa de Aplicación (Application Layer)](#2-capa-de-aplicación-application-layer)
  - [3. Capa de Dominio (Domain Layer)](#3-capa-de-dominio-domain-layer)
  - [4. Capa de Infraestructura (Infrastructure Layer)](#4-capa-de-infraestructura-infrastructure-layer)
  - [Grafico](#grafico-6)
- [Arquitectura Event-Driven (Orientada a Eventos)](#arquitectura-event-driven-orientada-a-eventos)
  - [Componentes Clave](#componentes-clave-4)
  - [Grafico](#grafico-7)
- [Arquitectura Hexagonal (Ports and Adapters)](#arquitectura-hexagonal-ports-and-adapters)
  - [Componentes Clave](#componentes-clave-5)
  - [Grafico](#grafico-8)
- [Arquitectura de Microkernel (Plugin-Based Architecture)](#arquitectura-de-microkernel-plugin-based-architecture)
  - [Componentes Clave](#componentes-clave-6)
  - [Grafico](#grafico-9)
- [Arquitectura de Espacio de Trabajo (Workspace Architecture)](#arquitectura-de-espacio-de-trabajo-workspace-architecture)
  - [Componentes Clave](#componentes-clave-7)
  - [Grafico](#grafico-10)
- [Historial de Versiones](#historial-de-versiones)
---

## Conceptos Básicos 

[Inicio](#tabla-de-contenidos)


## Historial de Versiones

[Inicio](#tabla-de-contenidos)

Fecha       | Versión | Autor                 | Organización | Descripción
------------|---------|-----------------------|--------------|------------
10/08/2024  | 01      | Dario Cano Valdegaray | Uso Personal | Diseño VJ