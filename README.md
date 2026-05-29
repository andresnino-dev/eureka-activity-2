# Eureka Server

Servidor de descubrimiento **Netflix Eureka** para la arquitectura de microservicios de **UNIR BookStore**. Proyecto académico de la **Maestría en Ingeniería de Software y Sistemas Informáticos** de la **Universidad UNIR**.

**Autor:** Andrés Niño

## Descripción

Este servicio actúa como registro central donde todos los microservicios se publican y descubren entre sí. Se ejecuta en modo *standalone* (no se registra a sí mismo).

## Configuración

| Propiedad           | Valor   |
|---------------------|---------|
| Puerto              | `8761`  |
| Nombre Eureka       | `eureka-server` |
| `register-with-eureka` | `false` |
| `fetch-registry`    | `false` |

## Ejecución

```bash
./mvnw spring-boot:run
```

Una vez iniciado, la consola de Eureka está disponible en: [http://localhost:8761](http://localhost:8761)
