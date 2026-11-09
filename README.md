# Laboratorio: Código Seguro y Modelo OWASP

## 1. Datos generales

- **Nombre completo:** Fabio Alexander Leiva Thez
- **Carné:** na
- **Correo institucional:**  (personal) fabioyalethez@gmail.com
- **Asignatura:** Programación con Aspectos de Seguridad
- **Fecha:** 08/11/2026

## 2. Descripción

Este laboratorio consiste en desarrollar una aplicación web utilizando Python, implementando controles básicos de seguridad basados en buenas prácticas y el modelo OWASP. Se aplican mecanismos de validación de entradas, consultas parametrizadas, protección de contraseñas, registro de eventos de autenticación y detección de incidentes, incluyendo el cálculo de las métricas MTTD y MTTR.

## 3. Estructura del proyecto

```text
laboratorio-las/
├── templates/
│   ├── registro.html
│   └── login.html
├── app.py
├── detector.py
├── eventos.log
├── respuesta.log
├── usuarios.db
├── .gitignore
├── requirements.txt
└── README.md
```

## 4. Ejecución del proyecto

**Paso 1.** Clonar el repositorio.

```bash
git clone https://github.com/drumsplease-fab/Laboratorio1-ESIT.git
```

**Paso 2.** Ingresar al proyecto.

```bash
cd laboratorio-las
```

**Paso 3.** Instalar las dependencias.

```bash
pip install -r requirements.txt
```

**Paso 4.** Ejecutar la aplicación.

```bash
python app.py
```
