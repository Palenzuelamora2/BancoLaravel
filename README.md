# 💰 Aplicación de Gestión Financiera

Aplicación web desarrollada en **Laravel** para gestionar ingresos y retiradas de dinero, visualizar movimientos y crear cuentas de usuario.

---

## 🚀 Características principales

- ✅ Registro y creación de cuentas de usuario  
- 💸 Registrar ingresos  
- 🏧 Registrar retiradas de dinero  
- 📊 Visualizar el historial de movimientos  
- 🔒 Sistema básico de autenticación  
- ⚙️ Gestión sencilla e intuitiva

---

## 🛠️ Tecnologías usadas

![PHP](https://img.shields.io/badge/-PHP-777BB4?style=flat-square&logo=php&logoColor=white)  
![Laravel](https://img.shields.io/badge/-Laravel-F05340?style=flat-square&logo=laravel&logoColor=white)  
![MySQL](https://img.shields.io/badge/-MySQL-4479A1?style=flat-square&logo=mysql&logoColor=white)  
![HTML5](https://img.shields.io/badge/-HTML5-E34F26?style=flat-square&logo=html5&logoColor=white)  
![CSS3](https://img.shields.io/badge/-CSS3-1572B6?style=flat-square&logo=css3)  
![JavaScript](https://img.shields.io/badge/-JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black)

---

## ⚙️ Instalación y puesta en marcha

Sigue estos comandos para instalar y ejecutar la aplicación localmente:

```bash
git clone https://github.com/TU_USUARIO/nombre-del-repositorio.git
cd nombre-del-repositorio
composer install
cp .env.example .env
# Edita el archivo .env para configurar tu base de datos y otras variables
php artisan key:generate
php artisan migrate
# Opcional: php artisan db:seed
php artisan serve
