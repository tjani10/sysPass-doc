.. container:: logo

  .. image:: _static/logo.png
      :width: 500px
      :alt: Logo sysPass
      :align: left

Introducción
============

sysPass es un gestor de claves web escrito en PHP que permite la gestión centralizada de claves en un entorno multiusuario.

Características
---------------

* Interfaz con Material Design Lite en HTML5 y Ajax
* Claves encriptadas con AES-256 CBC
* Multiusuario con gestión de usuarios, grupos y perfiles
* Gestión avanzada de perfiles con 29 niveles de acceso
* Autentificación con MySQL/MariaDB, OpenLDAP y Active Directory
* Notificaciones por email e in-app de actividad
* Enlaces públicos a cuentas sin necesidad de login
* Historial de cambios en cuentas
* Gestión de archivos asociados a cuentas con previsualización de imágenes
* Multilenguaje, con traducciones en Inglés, Catalán, Alemán, Polaco, Ruso, Francés y Holandés
* Enlace a Wiki externa e integración con API de DokuWiki
* Backup en formato portable y exportación en XML encriptado
* Registro de acciones y eventos con posibilidad de enviar a Syslog remoto en formato CEF
* Configurable y extensible mediante temas y plugins
* API para integración con otras aplicaciones
* Importación desde KeePass, KeePassX y CSV
* Instalación en un solo paso

.. toctree::
    :maxdepth: 2
    :name: mastertoc
    :caption: Índice

    installing/index
    configuration/index
    application/index
    updating
    faq