# Contrato-Inteligente-Blockchain-Hello-World

Paso 1: Crear el Contrato Inteligente
Primero, escribe un contrato inteligente básico. Aquí está el código para un contrato "Hello World":

solidity
// SPDX-License-Identifier: MIT
pragma solidity ^0.8.0;

contract HelloWorld {
    string public message;

    constructor() {
        message = "Hello, World!";
    }

    function setMessage(string memory newMessage) public {
        message = newMessage;
    }

    function getMessage() public view returns (string memory) {
        return message;
    }
}

Paso 2: Crear el Repositorio en GitHub
Inicia sesión en GitHub o regístrate si aún no tienes una cuenta.
Haz clic en el signo '+' en la esquina superior derecha y selecciona "New repository".
Nombre del repositorio: Escribe algo como HelloWorldSmartContract.
Descripción: Añade una breve descripción, por ejemplo, "Contrato inteligente básico en Solidity para aprender Ethereum".
Elige si será público o privado: Para este ejercicio, elige "Public".
Inicializa con un README: Marca esta opción para que GitHub cree un archivo README.md automáticamente.
Elige una licencia: Puedes seleccionar "MIT License" para ser consistente con el comentario de licencia en el código.
Crear repositorio.

Paso 3: Subir el Contrato al Repositorio
Clona el repositorio en tu máquina local usando Git. Desde la línea de comandos, ejecuta:
bash
git clone https://github.com/tu-usuario/HelloWorldSmartContract.git
Navega al directorio del repositorio:
bash
cd HelloWorldSmartContract
Crea un nuevo archivo con el contrato inteligente:
bash
touch HelloWorld.sol
Abre HelloWorld.sol con tu editor de texto favorito y pega el código de Solidity que has escrito.
Añade y confirma tus cambios:
bash
git add HelloWorld.sol
git commit -m "Añadido contrato inteligente Hello World en Solidity"
Sube los cambios a GitHub:
bash
git push origin main

Paso 4: Documentación y Mantenimiento
Edita el README.md para proporcionar instrucciones sobre cómo usar o probar el contrato, herramientas necesarias (como Remix para desarrollo de Solidity), y cualquier otra información relevante.
Asegúrate de actualizar o añadir archivos de configuración si decides expandir el proyecto (por ejemplo, .gitignore para ignorar archivos de entorno de desarrollo).

Este repositorio ahora contiene un contrato inteligente básico "Hello World" y puede servir como punto de partida para más experimentación o aprendizaje en el desarrollo de contratos inteligentes.
