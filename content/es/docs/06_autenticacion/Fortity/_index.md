---
title: "Fortity"
date: 2023-04-08T18:21:47+02:00
draft: false
weight: 60
icon: fa-solid fa-sitemap
---
# Introducción y concepto del paquete
* Referencia en la web https://laravel.com/docs/master/fortify

{{% pageinfo%}}
#### 
****
Fortity es un paquete que podemos instalar en nuestras aplicaciones de laravel para gestionar la autenticación.
   
Este paquete o librería se centra en la parte del **back**, dejando al desarrollador libertad a la hora de implementar la parte del front (vistas) que no instala por defecto.
Entre sus funcionalidades:
* Registro de usuarios.
* Inicio de sesión.
* Restablecimiento de contraseñas.
* Verificación de correo electrónico.
* **Verificación de dos factores (2FA)** *(No en breeze)*.
* **Administración de sesiones** *(No en breeze)*.
* **Bloqueo de usuarios** *(No en breeze)*.
{{% /pageinfo%}}

## Su funcionamiento
* Instalación
{{< highlight bash "linenos=table, hl_lines=1" >}}
  composer require laravel/fortify # Instalar el paquete
  php artisan fortify:install # publicar los recursos de fortity
  php artisan migrate # ejecutar las migraciones
* {{< / highlight >}}
## Personalizando

### Enlazando el front

### Actuando en el registro

### Actuando en el logout

### Redirigir (next login or logout)

### Personalizando perfiles

### Los teams

### Subiendo imágenes
