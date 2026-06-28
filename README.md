# Gestor de Citas

Sistema de gestión de citas médicas con Spring Boot.

## Configuración

Antes de ejecutar la aplicación, configura las siguientes variables de entorno:

| Variable | Descripción | Valor por defecto |
|---|---|---|
| `MYSQL_URL` | URL de conexión a MySQL | `jdbc:mysql://localhost:3306/clinica?allowPublicKeyRetrieval=true&useSSL=false` |
| `MYSQL_USERNAME` | Usuario de MySQL | `root` |
| `MYSQL_PASSWORD` | Contraseña de MySQL | `admin` |
| `GROQ_API_KEY` | API Key de Groq para el chatbot | *(obligatorio)* |

### Ejemplo con archivo `.env`

Crea un archivo `.env` en la raíz del proyecto:

```env
MYSQL_URL=jdbc:mysql://localhost:3306/clinica?allowPublicKeyRetrieval=true&useSSL=false
MYSQL_USERNAME=root
MYSQL_PASSWORD=admin
GROQ_API_KEY=tu_api_key_aqui
```

## Ejecución

```bash
./mvnw spring-boot:run
```
