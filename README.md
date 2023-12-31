# Curso NodeJs y Express

Created: July 10, 2023 4:43 PM

<details>
<summary><b>Introducción a NodeJs</b></summary>
    
Node.js es un entorno de ejecución de código JavaScript del lado del servidor. A diferencia     de otros entornos de ejecución de JavaScript, como los navegadores web, Node.js permite         ejecutar código JavaScript fuera del contexto del navegador, lo que lo convierte en una         herramienta poderosa para desarrollar aplicaciones web y servicios de backend.

Node.js utiliza el motor de JavaScript de Google Chrome, llamado V8, para interpretar y         ejecutar el código JavaScript. Esto proporciona a Node.js un rendimiento rápido y               eficiente. Además, Node.js adopta un enfoque basado en eventos y no bloqueante, lo que          significa que puede manejar un gran número de conexiones simultáneas sin bloquear el hilo       principal de ejecución.

Una de las características más destacadas de Node.js es su capacidad para realizar operaciones de entrada y salida de manera asíncrona. Esto permite que las aplicaciones Node.js sean escalables y puedan manejar múltiples solicitudes simultáneas sin bloquearse. Además, Node.js cuenta con un sistema de módulos incorporado que facilita la modularidad y reutilización de código.

Node.js se utiliza comúnmente para desarrollar aplicaciones web y servicios de backend. Proporciona una gran cantidad de bibliotecas y frameworks que simplifican tareas comunes, como el manejo de solicitudes HTTP, la interacción con bases de datos y la creación de APIs RESTful.

</details>

<details>
<summary><b>Características de Node Js:</b></summary>
    
1. **JavaScript en el servidor**: Node.js permite ejecutar código JavaScript en el servidor, lo que proporciona coherencia en el lenguaje de programación tanto en el frontend como en el backend. Esto permite a los desarrolladores utilizar las mismas habilidades y bibliotecas para desarrollar aplicaciones tanto en el cliente como en el servidor.
2. **Arquitectura orientada a eventos**: Node.js utiliza un modelo de programación basado en eventos y devoluciones de llamada (callbacks), lo que significa que las operaciones no bloqueantes son manejadas mediante eventos. Esto permite un manejo eficiente de múltiples solicitudes simultáneas y un rendimiento escalable.
3. **Operaciones de entrada/salida no bloqueantes**: Node.js se basa en una arquitectura no bloqueante que permite que las operaciones de entrada/salida (E/S) se realicen de manera asíncrona. Esto significa que, en lugar de esperar a que se complete una operación E/S antes de pasar a la siguiente, Node.js puede continuar ejecutando otras tareas y notificar cuando la operación E/S haya finalizado. Esto es especialmente útil para aplicaciones con alta concurrencia y tiempos de respuesta rápidos.
4. **Módulos y paquetes**: Node.js cuenta con un sistema de módulos incorporado que permite la modularidad y reutilización de código. Los módulos de Node.js pueden ser compartidos y reutilizados a través del gestor de paquetes npm, que es uno de los mayores repositorios de paquetes de código abierto disponibles. Esto facilita la integración de bibliotecas y el desarrollo rápido de aplicaciones.
5. **Escalabilidad**: Node.js se ha diseñado para ser escalable. Gracias a su arquitectura no bloqueante y a su capacidad para manejar múltiples solicitudes simultáneas, Node.js es capaz de manejar una gran cantidad de conexiones concurrentes con un uso eficiente de los recursos del sistema.
6. **Amplio ecosistema**: Node.js cuenta con un amplio ecosistema de bibliotecas y frameworks que facilitan el desarrollo de aplicaciones. Desde frameworks web como Express.js hasta bibliotecas para el acceso a bases de datos como Mongoose, hay muchas opciones disponibles para simplificar y acelerar el desarrollo de aplicaciones con Node.js.

</details>

<details>
<summary><b>Conceptos importantes para trabajar con NodeJs y desarrollo backend</b></summary>

<details>
<summary><b>Conceptos Básicos</b></summary>

1. **Arquitectura cliente-servidor**: Es un modelo de diseño común en el desarrollo de aplicaciones y sistemas distribuidos. En esta arquitectura, hay dos componentes principales: el cliente y el servidor. El cliente es el dispositivo o aplicación que realiza solicitudes de servicios, y el servidor es el dispositivo o aplicación que responde a esas solicitudes proporcionando los servicios o recursos solicitados. La comunicación entre el cliente y el servidor se realiza a través de una red, como Internet. Por ejemplo, al acceder a un sitio web, el navegador actúa como el cliente y solicita los recursos al servidor web, que los entrega en respuesta.
2. **Desarrollo frontend y backend**: El desarrollo frontend se refiere a la creación de la interfaz de usuario y la interacción del usuario en una aplicación o sitio web. Implica el uso de tecnologías como HTML, CSS y JavaScript para construir la parte visual y funcional que los usuarios ven y con la que interactúan directamente en el navegador. Por otro lado, el desarrollo backend se enfoca en la implementación de la lógica de negocios y el procesamiento de datos detrás de escena. Involucra la creación de servidores, APIs y la gestión de bases de datos para manejar la lógica y el almacenamiento de los datos. El desarrollo frontend y backend trabajan juntos para crear una aplicación web completa.
3. **Protocolo**: En el contexto de las redes de computadoras, un protocolo es un conjunto de reglas y normas que define cómo se deben comunicar los dispositivos y sistemas. Establece la sintaxis, la semántica y los procedimientos de intercambio de datos entre las partes. Un protocolo puede incluir especificaciones sobre el formato de los mensajes, el control de flujo, la autenticación, la seguridad, la entrega de datos, entre otros aspectos. Algunos ejemplos de protocolos son HTTP, TCP, IP y SMTP, que se utilizan para diferentes propósitos de comunicación en Internet.
4. **Base de datos**: Una base de datos es un sistema organizado para almacenar, gestionar y recuperar información de manera estructurada. Proporciona un medio para almacenar datos de manera persistente, lo que significa que los datos se mantienen incluso cuando la aplicación o el sistema se detiene. Las bases de datos se utilizan para almacenar y gestionar grandes cantidades de datos de manera eficiente. Pueden ser de diferentes tipos, como bases de datos relacionales (como MySQL, PostgreSQL) o bases de datos NoSQL (como MongoDB, Redis), y se accede a ellas utilizando lenguajes de consulta, como SQL (Structured Query Language) en el caso de las bases de datos relacionales.
5. **Página web estática y dinámica**: Una página web estática es una página cuyo contenido no cambia dinámicamente, es decir, se muestra de la misma manera para todos los usuarios. La página se crea previamente y se entrega tal cual cuando se solicita. Estas páginas generalmente están escritas en HTML y CSS, y pueden contener imágenes y otros recursos estáticos. Por otro lado, una página web dinámica se genera en tiempo real en función de diferentes parámetros y condiciones. El contenido puede variar según la interacción del usuario, la base de datos o información externa. Estas páginas a menudo utilizan tecnologías del lado del servidor, como PHP, Python o Node.js, para generar contenido dinámico y responder a las solicitudes del usuario de manera personalizada.
</details>

<details>
<summary><b>Otros Conceptos importantes</b></summary>

1. **Módulos y paquetes**: Node.js utiliza un sistema de módulos incorporado para organizar y reutilizar código. Los módulos son archivos JavaScript que encapsulan funcionalidades específicas y se pueden importar/exportar en otros archivos. Además, puedes utilizar el gestor de paquetes npm (Node Package Manager) para instalar, administrar y compartir paquetes de código de terceros, lo que facilita la incorporación de funcionalidades adicionales en tu aplicación.
2. **Asincronía y devoluciones de llamada (callbacks)**: La asincronía es una característica clave de Node.js. Las operaciones de entrada/salida (E/S), como las solicitudes de red o las operaciones de archivo, se realizan de forma asíncrona mediante devoluciones de llamada (callbacks) o promesas. Esto significa que el código no se bloquea mientras se espera a que se complete una operación, lo que permite una mayor concurrencia y rendimiento. Es importante comprender cómo manejar las devoluciones de llamada y trabajar con la asincronía en Node.js.
3. **Eventos y emisores de eventos**: Node.js utiliza un sistema de eventos para manejar las interacciones asíncronas. Los objetos que emiten eventos son llamados "emisores de eventos" y se pueden registrar para escuchar eventos específicos. Esto es especialmente útil para manejar eventos relacionados con la red, como solicitudes HTTP o conexiones de sockets.
4. **APIs y módulos principales de Node.js**: Node.js proporciona una serie de módulos principales (core modules) que son parte de la instalación estándar y ofrecen funcionalidades esenciales. Algunos ejemplos incluyen **`http`** para crear servidores web, **`fs`** para trabajar con el sistema de archivos, **`path`** para manejar rutas de archivos y **`util`** para funciones de utilidad. Familiarizarse con estos módulos principales te permitirá aprovechar al máximo las capacidades de Node.js.
5. **Express.js y frameworks web**: Express.js es uno de los frameworks web más populares para Node.js. Proporciona una capa de abstracción sobre las funcionalidades básicas de Node.js, lo que facilita la creación de aplicaciones web y APIs RESTful. Aprender a trabajar con Express.js, entender sus conceptos y middleware te permitirá desarrollar aplicaciones web backend de manera más eficiente.
6. **Bases de datos**: Node.js es compatible con una amplia gama de bases de datos, tanto SQL como NoSQL. Algunas bases de datos populares son MongoDB, MySQL, PostgreSQL y Redis. Es importante entender cómo interactuar con estas bases de datos utilizando bibliotecas y módulos específicos, como Mongoose para MongoDB o Sequelize para bases de datos SQL.
7. **Seguridad**: Al desarrollar aplicaciones backend, es fundamental tener en cuenta la seguridad. Node.js tiene sus propias prácticas y recomendaciones de seguridad, como proteger contra ataques de inyección de código o manejar correctamente las contraseñas y la autenticación de usuarios. Es importante familiarizarse con las buenas prácticas de seguridad y aplicar medidas adecuadas en tu aplicación.
    </details>
</details>

<details>
<summary><b>Aplicaciones de NodeJs, es usado para?</b></summary>

1. **Desarrollo web y APIs**: Node.js es ampliamente utilizado para el desarrollo de aplicaciones web y la creación de APIs (Application Programming Interfaces) RESTful. Su enfoque no bloqueante y basado en eventos lo hace ideal para manejar una gran cantidad de solicitudes simultáneas y construir aplicaciones web escalables y de alto rendimiento. Frameworks populares como Express.js, Koa.js y Nest.js se basan en Node.js para facilitar el desarrollo web.
2. **Aplicaciones en tiempo real**: Node.js es una excelente opción para construir aplicaciones en tiempo real que requieren una comunicación bidireccional entre el cliente y el servidor. Esto incluye aplicaciones de chat en tiempo real, juegos multijugador, sistemas de colaboración en tiempo real, monitoreo en tiempo real, entre otros. Bibliotecas como Socket.IO y SockJS se utilizan con Node.js para habilitar la comunicación en tiempo real.
3. **Microservicios y arquitecturas orientadas a servicios**: Node.js es adecuado para implementar microservicios y sistemas basados en arquitecturas orientadas a servicios. Permite construir servicios pequeños e independientes que se pueden escalar y desplegar fácilmente. Además, su enfoque modular y su capacidad para manejar solicitudes simultáneas lo convierten en una buena opción para sistemas distribuidos y escalables.
4. **Automatización y scripting**: Node.js es una herramienta popular para la automatización de tareas y scripting en el lado del servidor. Puede utilizarse para crear scripts y herramientas personalizadas que automatizan tareas repetitivas, procesamiento de archivos, generación de informes, entre otros. Además, Node.js cuenta con una amplia gama de paquetes y módulos disponibles a través de npm que facilitan la automatización de diversas tareas.
5. **Internet de las cosas (IoT)**: Node.js también se utiliza en aplicaciones de Internet de las cosas (IoT). Su ligereza y eficiencia lo hacen adecuado para ejecutarse en dispositivos con recursos limitados, como sensores, controladores y gateways. Node.js puede utilizarse para recopilar datos de sensores, controlar dispositivos y coordinar la comunicación entre ellos en una red IoT.
</details>
    
<details>
<summary><b>Descargar e instalar NodeJs*</b></summary>

1. **Ir al sitio oficial**: Accede al sitio oficial de Node.js en **[https://nodejs.org/](https://nodejs.org/)**. Esto te llevará a la página de descargas.
2. **Seleccionar la versión**: En la página de descargas, verás las diferentes versiones de Node.js disponibles. Se recomienda elegir la versión LTS (Long-Term Support) para obtener la versión más estable y con soporte a largo plazo. Sin embargo, también puedes optar por la última versión si deseas acceder a las características más recientes.
3. **Seleccionar el sistema operativo**: A continuación, debes seleccionar tu sistema operativo. Node.js está disponible para Windows, macOS y Linux. Haz clic en el botón de descarga correspondiente a tu sistema operativo.
4. **Descargar el instalador**: Después de hacer clic en el botón de descarga, se descargará un archivo de instalación en tu computadora.
5. **Ejecutar el instalador**: Una vez que se haya completado la descarga, ejecuta el archivo de instalación haciendo doble clic en él. Esto iniciará el asistente de instalación de Node.js.
6. **Aceptar los términos de uso**: En el asistente de instalación, lee y acepta los términos de uso y licencia de Node.js.
7. **Seleccionar la ubicación de instalación**: A continuación, elige la ubicación donde deseas instalar Node.js. La ubicación predeterminada generalmente es adecuada para la mayoría de los usuarios, pero puedes cambiarla si lo deseas.
8. **Seleccionar componentes adicionales**: Durante el proceso de instalación, puedes seleccionar componentes adicionales, como la herramienta npm (Node Package Manager), que se instala junto con Node.js. Se recomienda mantener las opciones predeterminadas seleccionadas.
9. **Iniciar la instalación**: Una vez que hayas seleccionado los componentes adicionales, haz clic en el botón "Install" o "Next" para iniciar la instalación de Node.js.
10. **Esperar a que se complete la instalación**: El instalador copiará los archivos necesarios y configurará Node.js en tu sistema. Esto puede llevar unos minutos.
11. **Verificar la instalación**: Una vez que la instalación se haya completado con éxito, puedes verificar si Node.js se ha instalado correctamente abriendo una ventana de terminal (o símbolo del sistema) y escribiendo el comando **`node -v`**. Esto mostrará la versión de Node.js instalada. También puedes ejecutar **`npm -v`** para verificar la versión de npm.

¡Y eso es todo! Ahora tienes Node.js instalado en tu sistema y estás listo para comenzar a desarrollar aplicaciones con él.
</details>

<details>
<summary><b>El REPL de Node</b></summary>

El REPL (Read-Eval-Print Loop) de Node.js es una herramienta interactiva que permite probar y ejecutar código JavaScript de forma interactiva en tiempo real. Proporciona una forma rápida y conveniente de experimentar con el código y explorar las características del lenguaje.

Para iniciar el REPL de Node.js, sigue estos pasos:

1. Abre una ventana de terminal (o símbolo del sistema) en tu sistema operativo.
2. Escribe el comando **`node`** y presiona Enter. Esto iniciará el REPL de Node.js y verás el indicador **`>`** que indica que estás en el modo de entrada del REPL.
3. A partir de ahora, puedes escribir y ejecutar código JavaScript directamente en el REPL. Cada vez que presiones Enter, el código ingresado se evaluará y el resultado se imprimirá en la siguiente línea.

Por ejemplo, puedes probar operaciones matemáticas simples:

```
> 2 + 3
5
> Math.sqrt(16)
4
```

También puedes definir variables y realizar operaciones más complejas:

```
> let x = 5
undefined
> let y = 3
undefined
> x * y
15
> x > y
true
```

El REPL también es útil para probar funciones y módulos. Puedes definir funciones y llamarlas en el mismo entorno:
```jsx
> function greet(name) {
    console.log('Hello, ' + name + '!')
    }
undefined
> greet('John')
Hello, John!
undefined

```

Para salir del REPL, puedes presionar las teclas **`Ctrl + C`** dos veces o escribir **`.exit`** y presionar Enter.

![Untitled](./images/Untitled.png)

El REPL de Node.js es una herramienta muy útil para probar ideas rápidamente, depurar código o explorar características del lenguaje. Te permite interactuar con el código de forma inmediata sin necesidad de crear archivos o ejecutar un programa completo.
</details>

<details>
<summary><b>Primer programa con Node.js</b></summary>

En Visual Studio Code (VSCode), puedes ejecutar un archivo de JavaScript con Node.js utilizando la terminal integrada. Sigue estos pasos:

1. Abre Visual Studio Code.
2. Abre la carpeta que contiene el archivo de JavaScript que deseas ejecutar. Puedes hacerlo seleccionando "File" en la barra de menú superior y luego seleccionando "Open Folder". O bien, puedes arrastrar y soltar la carpeta en la ventana de VSCode.
3. En la barra de menú superior, selecciona "View" y luego "Terminal" (o usa el atajo de teclado **`Ctrl +`** ).
4. Aparecerá una terminal en la parte inferior de la ventana de VSCode. Asegúrate de que la terminal esté en el directorio correcto donde se encuentra el archivo de JavaScript que deseas ejecutar. Puedes utilizar el comando **`cd`** para cambiar al directorio adecuado.
5. Una vez que te encuentres en el directorio correcto, puedes ejecutar el archivo de JavaScript con el comando **`node`** seguido del nombre del archivo. Por ejemplo:

```
node archivo.js
```

Asegúrate de reemplazar "archivo.js" con el nombre real de tu archivo de JavaScript.

1. Presiona Enter para ejecutar el comando. Node.js ejecutará el archivo de JavaScript y mostrará cualquier salida o resultado en la terminal de VSCode.

Recuerda guardar los cambios en el archivo de JavaScript antes de ejecutarlo para asegurarte de que estás ejecutando la versión más reciente del código.

Utilizando la terminal integrada en Visual Studio Code, puedes ejecutar archivos de JavaScript con Node.js sin tener que salir del editor. Esto te permite depurar y probar tu código directamente en el entorno de desarrollo.

![Untitled](./images/Untitled%201.png)
</details>

<details>
<summary><b>Módulos en Node.js</b></summary>
<details>
<summary><b>Qué son?</b></summary>
En Node.js, los módulos son unidades independientes de código que encapsulan funcionalidades específicas y se pueden reutilizar en diferentes partes de una aplicación. Los módulos permiten organizar y modularizar el código, lo que facilita el mantenimiento, la reutilización y la colaboración en proyectos de Node.js.
</details>
<details>
<summary><b>Ventajas</b></summary>

Los módulos en Node.js proporcionan varias ventajas que mejoran la organización, reutilización y mantenibilidad del código. Algunas de las ventajas de utilizar módulos en Node.js son:

1. **Modularidad**: Los módulos permiten organizar el código en unidades independientes y autónomas. Esto facilita la comprensión y el mantenimiento del código, ya que cada módulo se enfoca en una funcionalidad específica. Los módulos también promueven la separación de responsabilidades y el principio de una sola responsabilidad (SRP), lo que facilita la evolución y escalabilidad de la aplicación.
2. **Reutilización**: Los módulos permiten encapsular funcionalidades específicas y reutilizarlas en diferentes partes de una aplicación. Esto evita la duplicación de código y mejora la eficiencia en el desarrollo, ya que no es necesario escribir el mismo código una y otra vez. Además, los módulos externos disponibles a través de npm proporcionan una amplia gama de funcionalidades predefinidas que se pueden utilizar en proyectos.
3. **Colaboración y compartición**: Los módulos facilitan la colaboración entre desarrolladores. Cada desarrollador puede trabajar en un módulo específico sin interferir con el trabajo de los demás. Además, los módulos externos pueden compartirse y distribuirse fácilmente a través del registro público de npm. Esto fomenta la comunidad y el intercambio de código entre desarrolladores, lo que acelera el desarrollo de aplicaciones.
4. **Abstracción y ocultamiento de información**: Los módulos permiten definir interfaces claras y abstraer detalles internos de implementación. Esto significa que los módulos pueden exponer solo las funciones y propiedades necesarias para utilizarlos, ocultando los detalles internos de implementación. Esto mejora la seguridad y reduce la complejidad al interactuar con los módulos.
5. **Facilidad de prueba**: Los módulos independientes son más fáciles de probar de forma aislada. Al encapsular la funcionalidad en módulos, se puede realizar pruebas unitarias más específicas y centradas en cada módulo. Esto mejora la calidad del código y facilita la detección y corrección de errores.
6. **Mejora el rendimiento**: Los módulos en Node.js se cargan de forma diferida, lo que significa que solo se cargan cuando se requieren. Esto permite una mejor gestión de los recursos y un mejor rendimiento de la aplicación, ya que solo se cargan los módulos necesarios en un momento dado.
</details>

<details>
<summary><b>Crear un módulo</b></summary>
Para crear un módulo en Node.js, debes seguir los siguientes pasos:

1. Crea un nuevo archivo JavaScript con la extensión **`.js`**. Por ejemplo, puedes llamarlo **`miModulo.js`**.
2. Abre el archivo **`miModulo.js`** en tu editor de código preferido.
3. Define las funcionalidades que deseas incluir en el módulo. Por ejemplo, puedes declarar variables, funciones u objetos. Aquí hay un ejemplo básico de cómo podrías definir un módulo con una función de saludo:

```jsx
// miModulo.js

function saludar(nombre) {
    console.log('¡Hola, ' + nombre + '!');
}

// Exporta la función para que esté disponible para otros archivos
module.exports = {
    saludar: saludar
};

```

En este ejemplo, el módulo **`miModulo`** tiene una función llamada **`saludar`** que toma un nombre como argumento y muestra un saludo por consola.

1. Guarda el archivo **`miModulo.js`**.
2. Ahora puedes utilizar el módulo en otro archivo de JavaScript. Por ejemplo, crea un nuevo archivo llamado **`index.js`** y requiere el módulo **`miModulo`** utilizando la función **`require`**:

```jsx
// index.js

const miModulo = require('./miModulo');

miModulo.saludar('Juan');

```

En este ejemplo, estamos requiriendo el módulo **`miModulo`** y utilizando la función **`saludar`** que exportamos desde ese módulo.

1. Guarda el archivo **`index.js`**.
2. Abre una terminal en la ubicación donde se encuentran los archivos **`miModulo.js`** y **`index.js`**.
3. Ejecuta el archivo **`index.js`** utilizando Node.js con el siguiente comando:

```
Copy code
node index.js

```

Verás el saludo impreso en la consola.

¡Y eso es todo! Has creado y utilizado un módulo en Node.js. Puedes seguir expandiendo tu módulo agregando más funcionalidades y exportándolas según sea necesario. Recuerda que puedes exportar variables, funciones o cualquier objeto que desees hacer disponible para otros archivos de JavaScript.
</details>

<details>
<summary><b>Exportar Varios Elementos</b></summary>
Para exportar varios elementos desde un módulo en Node.js, puedes utilizar la asignación al objeto **`module.exports`** para agregar propiedades individuales o asignar un objeto que contenga los elementos que deseas exportar. Aquí tienes un ejemplo de cómo puedes exportar varios elementos:

En el archivo **`greetings.js`**, se definen dos funciones: **`greeting`** y **`greetingHelloWorld`**. La función **`greeting`** toma un parámetro **`name`** y devuelve un saludo personalizado. La función **`greetingHelloWorld`** no toma parámetros y devuelve un saludo genérico "Hello World!".

Luego, se utiliza la asignación directa a **`module.exports`** para exportar un objeto que contiene las funciones **`greeting`** y **`greetingHelloWorld`**.

```jsx
function greeting(name) {
    return `Hi ${name}`
}

function greetingHelloWorld(){
    return 'Hello World!'
}

module.exports = {
    greeting: greeting,
    greetingHelloWorld: greetingHelloWorld
}
```

En este caso, **`module.exports`** se establece como un objeto que tiene dos propiedades: **`greeting`** y **`greetingHelloWorld`**. Estas propiedades hacen referencia a las funciones definidas anteriormente.

En el archivo **`app.js`**, se requiere el módulo **`greetings.js`** utilizando **`require`**:

Esto carga el módulo **`greetings.js`** y asigna su contenido al objeto **`greetings`**.

Finalmente, se utilizan las funciones exportadas **`greeting`** y **`greetingHelloWorld`** desde el módulo **`greetings.js`**:

```jsx
function greeting(name) {
    return `Hi ${name}`
}

function greetingHelloWorld(){
    return 'Hello World!'
}

module.exports = {
    greeting: greeting,
    greetingHelloWorld: greetingHelloWorld
}
```

Aquí, **`greetings.greeting('Samantha')`** llama a la función **`greeting`** exportada desde el módulo **`greetings.js`** y pasa el argumento **`'Samantha'`**. El resultado se imprime en la consola.

De manera similar, **`greetings.greetingHelloWorld()`** llama a la función **`greetingHelloWorld`** exportada desde el módulo **`greetings.js`**. Como esta función no toma ningún argumento, simplemente devuelve el saludo "Hello World!". Nuevamente, el resultado se imprime en la consola.

![Untitled](./images/Untitled%202.png)
</details>

<details>
<summary><b>Sintaxis de desestructuración y require()</b></summary>

**Require y Exportación de Módulos**:
En Node.js, puedes utilizar **`require`** para cargar módulos y la exportación e importación de módulos se realiza a través de **`module.exports`** y **`require`**.

1. **Exportación de módulos**:

```jsx
// módulo.js
const greeting = 'Hello';

function sayHello(name) {
    console.log(`${greeting}, ${name}!`);
}

module.exports = { sayHello };

```

En este ejemplo, estamos exportando la función **`sayHello`** desde el módulo **`módulo.js`** utilizando **`module.exports`**.

1. **Importación de módulos**:

```jsx
const { sayHello } = require('./módulo.js');

sayHello('John'); // Output: Hello, John!

```

Aquí, estamos importando la función **`sayHello`** desde el módulo **`módulo.js`** utilizando la sintaxis de desestructuración. Luego, podemos llamar a la función **`sayHello`** y pasar un argumento para obtener el saludo correspondiente.

Es importante tener en cuenta que la ruta **`./módulo.js`** en el ejemplo es un ejemplo de ruta relativa al archivo actual. Asegúrate de proporcionar la ruta correcta al módulo que deseas importar.

Estos ejemplos te muestran cómo utilizar la desestructuración, **`require`** y la exportación e importación de módulos en JavaScript. Utilizando estas sintaxis, puedes estructurar y modularizar tu código de manera efectiva y reutilizable en diferentes partes de tu aplicación.
</details>

</details>

<details>
<summary><b>Módulos principales de Node.js:</b></summary>
<details>
<summary><b>Módulos integrados (built-in modules)</b></summary>
<summary><b>Concepto</b></summary>
Node.js incluye varios módulos integrados (built-in modules) que están disponibles de forma predeterminada sin necesidad de instalar nada adicional. Estos módulos proporcionan funcionalidades esenciales para el desarrollo de aplicaciones en Node.js.
</details>
<details>
<summary><b>Más utilizados:</b></summary>

1. **fs**: El módulo **`fs`** (File System) proporciona funciones para interactuar con el sistema de archivos, permitiendo leer, escribir, modificar, borrar archivos y directorios, entre otras operaciones relacionadas con el sistema de archivos.
2. **http**: El módulo **`http`** permite crear y manejar servidores HTTP. Proporciona funciones y clases para crear servidores web, realizar solicitudes y respuestas HTTP, manipular cabeceras, rutas, entre otros.
3. **path**: El módulo **`path`** proporciona utilidades para trabajar con rutas de archivos y directorios. Ayuda a manejar rutas de forma segura y portátil, uniendo, normalizando o resolviendo rutas, entre otras operaciones.
4. **os**: El módulo **`os`** proporciona funciones para interactuar con el sistema operativo. Permite obtener información sobre el sistema operativo, como el nombre del sistema operativo, la arquitectura, la memoria, la información del usuario, entre otros.
5. **util**: El módulo **`util`** contiene funciones y utilidades diversas que son útiles para el desarrollo de aplicaciones en Node.js. Proporciona funciones para la herencia de objetos, la promisificación de funciones, la manipulación de objetos, la gestión de errores, entre otras funcionalidades.
6. **events**: El módulo **`events`** permite la implementación y el manejo de eventos en Node.js. Permite la comunicación asíncrona entre diferentes partes de una aplicación a través de la emisión y escucha de eventos.

Estos son solo algunos ejemplos de los módulos integrados que están disponibles en Node.js. Existen otros módulos incorporados como **`crypto`** para funcionalidades criptográficas, **`stream`** para trabajar con flujos de datos, **`child_process`** para la ejecución de procesos secundarios, entre otros. Puedes explorar la documentación oficial de Node.js para obtener más información sobre estos módulos y sus funcionalidades específicas: **[https://nodejs.org/api/](https://nodejs.org/api/)**.
</details>
<details>
<summary><b>Módulo Console:</b></summary>

El módulo **`console`** es un módulo integrado en Node.js que proporciona funciones para imprimir mensajes y depurar en la consola. Permite mostrar información, mensajes de depuración, advertencias y errores en la salida de la consola.

Aquí hay algunos métodos comunes proporcionados por el módulo **`console`**:

1. **console.log()**: Imprime un mensaje en la consola. Puede aceptar varios argumentos y los muestra como una cadena formateada.

```jsx
console.log('Hola, mundo!');
// Output: Hola, mundo!

const nombre = 'Juan';
console.log('Hola,', nombre);
// Output: Hola, Juan
```

1. **console.error()**: Imprime un mensaje de error en la consola. Al igual que **`console.log()`**, puede aceptar varios argumentos.

```jsx
console.error('Ocurrió un error');
// Output: Ocurrió un error

const errorCode = 404;
console.error('Error', errorCode, ': Página no encontrada');
// Output: Error 404: Página no encontrada
```

1. **console.warn()**: Imprime un mensaje de advertencia en la consola. Similar a **`console.log()`** y **`console.error()`**, puede aceptar varios argumentos.

```jsx
console.warn('Advertencia: Esta acción es irreversible');
// Output: Advertencia: Esta acción es irreversible

const warningMessage = 'Falta información';
console.warn('Advertencia:', warningMessage);
// Output: Advertencia: Falta información
```

1. **console.info()**: Imprime un mensaje informativo en la consola. Funciona de manera similar a **`console.log()`** y **`console.error()`**.

```jsx
console.info('Información importante');
// Output: Información importante

const infoMessage = '¡La sesión ha iniciado correctamente!';
console.info('Información:', infoMessage);
// Output: Información: ¡La sesión ha iniciado correctamente!
```

Estos son solo algunos de los métodos proporcionados por el módulo **`console`**. También existen otros métodos, como **`console.debug()`**, **`console.trace()`**, entre otros. Puedes utilizarlos para imprimir mensajes y realizar tareas de depuración en tu aplicación Node.js.
</details>

<details>
<summary><b>Módulo Process</b></summary>

El módulo **`process`** es un módulo integrado en Node.js que proporciona información y control sobre el proceso en ejecución. Contiene propiedades y métodos que permiten acceder a los argumentos de línea de comandos, entorno, flujo de entrada y salida, entre otros aspectos del proceso en Node.js.

Aquí hay algunos aspectos clave del módulo **`process`**:

1. **process.argv**: Es un array que contiene los argumentos de línea de comandos pasados al script. El primer elemento (**`process.argv[0]`**) representa la ruta al ejecutable de Node.js y el segundo elemento (**`process.argv[1]`**) representa la ruta al archivo de script ejecutado. Los argumentos adicionales se encuentran en las posiciones siguientes.

```jsx
// node script.js arg1 arg2 arg3
console.log(process.argv);

// Output: ['node', '/ruta/al/script.js', 'arg1', 'arg2', 'arg3']
```

1. **process.env**: Es un objeto que contiene las variables de entorno del sistema operativo. Puedes acceder a las variables de entorno utilizando las claves del objeto **`process.env`**.

```jsx
console.log(process.env.HOME); 
// Output: '/home/user'

console.log(process.env.PATH); 
// Output: '/usr/local/bin:/usr/bin:/bin'
```

1. **process.stdin**: Es un stream que representa el flujo de entrada estándar (stdin). Puedes utilizarlo para leer la entrada del usuario desde la consola.

```jsx
process.stdin.setEncoding('utf8');

process.stdin.on('data', (data) => {
    console.log('Entrada recibida:', data);
});

console.log('Ingrese algo:');
```

En este ejemplo, estamos configurando un controlador de eventos para el evento **`'data'`** en **`process.stdin`**. Cada vez que se ingresa algo en la consola, el controlador se activa y muestra la entrada recibida.

1. **process.stdout** y **process.stderr**: Representan los flujos de salida estándar (stdout) y error estándar (stderr), respectivamente. Puedes utilizarlos para mostrar mensajes y resultados en la consola.

```jsx
process.stdout.write('Esto es un mensaje en stdout\n');
// Output: Esto es un mensaje en stdout

process.stderr.write('Esto es un mensaje de error en stderr\n');
// Output: Esto es un mensaje de error en stderr

```

Estos son solo algunos ejemplos de las funcionalidades que proporciona el módulo **`process`**. También puedes utilizar **`process.exit()`** para terminar la ejecución del proceso, **`process.cwd()`** para obtener el directorio de trabajo actual, **`process.pid`** para obtener el ID del proceso, entre otros.

El módulo **`process`** es una parte integral de Node.js y proporciona información y control sobre el proceso en ejecución, permitiéndote interactuar con el entorno, la entrada/salida y otros aspectos del proceso. Puedes consultar la documentación oficial de Node.js para obtener más información sobre el módulo **`process`** y sus funcionalidades específicas: **[https://nodejs.org/api/process.html](https://nodejs.org/api/process.html)**.
            
</details>

<details>
<summary><b>Módulo OS:</b></summary>

El módulo **`os`** es un módulo integrado en Node.js que proporciona funciones y utilidades para interactuar con el sistema operativo. Permite acceder a información relacionada con el sistema operativo, como la arquitectura de la CPU, el nombre del sistema operativo, la información de red, la memoria, entre otros.

Aquí tienes algunos aspectos clave del módulo **`os`**:

1. **os.platform()**: Devuelve el nombre de la plataforma del sistema operativo en la que se está ejecutando Node.js, como **`"darwin"`** para macOS, **`"win32"`** para Windows, o **`"linux"`** para Linux.

```jsx
console.log(os.platform()); // Output: 'darwin'

```

1. **os.arch()**: Devuelve la arquitectura de la CPU del sistema, como **`"x64"`**, **`"arm"`**, **`"ia32"`**, etc.

```jsx
console.log(os.arch()); // Output: 'x64'

```

1. **os.hostname()**: Devuelve el nombre del host del sistema.

```jsx
console.log(os.hostname()); // Output: 'mi-pc'

```

1. **os.totalmem()** y **os.freemem()**: Devuelven la cantidad total de memoria del sistema y la cantidad de memoria libre, respectivamente, en bytes.

```jsx
console.log(os.totalmem()); // Output: 8589934592 (8 GB)
console.log(os.freemem()); // Output: 4294967296 (4 GB)

```

1. **os.cpus()**: Devuelve un arreglo de objetos que representan la información de cada núcleo de la CPU del sistema.

```jsx
console.log(os.cpus());
// Output:
// [
//   { model: 'Intel(R) Core(TM) i7-7700HQ CPU @ 2.80GHz', speed: 2800 },
//   { model: 'Intel(R) Core(TM) i7-7700HQ CPU @ 2.80GHz', speed: 2800 },
//   ...
// ]

```

Estos son solo algunos ejemplos de las funcionalidades que proporciona el módulo **`os`**. También puedes utilizar **`os.networkInterfaces()`** para obtener información sobre las interfaces de red del sistema, **`os.uptime()`** para obtener el tiempo de actividad del sistema, **`os.tmpdir()`** para obtener el directorio temporal predeterminado del sistema, entre otros.

El módulo **`os`** es muy útil para obtener información del sistema operativo y realizar operaciones relacionadas con el entorno en el que se está ejecutando tu aplicación Node.js. Puedes consultar la documentación oficial de Node.js para obtener más información sobre el módulo **`os`** y sus funcionalidades específicas: **[https://nodejs.org/api/os.html](https://nodejs.org/api/os.html)**.
</details>

<details>
<summary><b>Módulo Timers:</b></summary>

El módulo **`timers`** es un módulo integrado en Node.js que proporciona funciones y utilidades para trabajar con temporizadores. Permite programar la ejecución de funciones en un momento futuro o repetir la ejecución de funciones a intervalos regulares.

Aquí tienes algunos aspectos clave del módulo **`timers`**:

1. **setTimeout()**: La función **`setTimeout()`** se utiliza para programar la ejecución de una función después de un cierto período de tiempo, expresado en milisegundos.

```jsx
setTimeout(() => {
console.log('¡Han pasado 2 segundos!');
}, 2000);

```

En este ejemplo, la función **`console.log()`** se ejecutará después de 2 segundos.

1. **setInterval()**: La función **`setInterval()`** se utiliza para repetir la ejecución de una función a intervalos regulares, expresados en milisegundos.

```jsx
let counter = 0;

const intervalId = setInterval(() => {
console.log('Contador:', counter);
counter++;

if (counter === 5) {
clearInterval(intervalId);
console.log('Intervalo finalizado');
}
}, 1000);

```

En este ejemplo, la función **`console.log()`** se ejecutará cada segundo. Después de que el contador alcance el valor 5, se cancela el intervalo utilizando **`clearInterval()`**.

1. **setImmediate()**: La función **`setImmediate()`** se utiliza para programar la ejecución de una función en la siguiente iteración del bucle de eventos, después de que se hayan procesado los eventos actuales.

```jsx
setImmediate(() => {
console.log('¡Esto se ejecuta inmediatamente!');
});

```

En este ejemplo, la función se ejecutará en la siguiente iteración del bucle de eventos.

Estas son solo algunas de las funcionalidades proporcionadas por el módulo **`timers`**. También puedes utilizar **`clearTimeout()`** para cancelar un temporizador creado con **`setTimeout()`**, **`clearInterval()`** para cancelar un intervalo creado con **`setInterval()`**, entre otros.

El módulo **`timers`** es útil cuando necesitas programar la ejecución de funciones en un momento futuro o realizar tareas repetitivas en intervalos regulares en tu aplicación Node.js.
</details>

<details>
<summary><b>Módulo fs</b></summary>
    
El módulo **`fs`** (File System) es un módulo integrado en Node.js que proporciona funcionalidades para interactuar con el sistema de archivos. Permite leer, escribir, modificar, borrar archivos y directorios, obtener información sobre archivos y directorios, entre otras operaciones relacionadas con el sistema de archivos.

Aquí tienes algunos aspectos clave del módulo **`fs`**:
1. **Lectura de archivos**:
- **`fs.readFile()`**: Lee el contenido de un archivo de forma asíncrona.

```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Node.js</title>
</head>
<body>
    <h1>Curso Node.js</h1> 
        <p>Estoy aprendiendo Node.js</p>
</body>
</html>
```

```jsx
const fs = require('fs')

fs.readFile('./index.html', 'utf-8', (err, contenido)=>{
if(err) {
throw err;
}else{
console.log(contenido);
}
});
```

![Untitled](./images/Untitled%203.png)

- **`fs.readFileSync()`**: Lee el contenido de un archivo de forma sincrónica.

```jsx

// Lectura de archivo de forma asíncrona
fs.readFile('archivo.txt', 'utf8', (error, data) => {
if (error) {
console.error('Error al leer el archivo:', error);
} else {
console.log('Contenido del archivo:', data);
}
});

// Lectura de archivo de forma sincrónica
try {
const data = fs.readFileSync('archivo.txt', 'utf8');
console.log('Contenido del archivo:', data);
} catch (error) {
console.error('Error al leer el archivo:', error);
}

```

2. **Escritura de archivos**:
- **`fs.writeFile()`**: Escribe datos en un archivo de forma asíncrona.
- **`fs.writeFileSync()`**: Escribe datos en un archivo de forma sincrónica.

```jsx
javascriptCopy code
// Escritura de archivo de forma asíncrona
const data = 'Este es el contenido a escribir en el archivo';
fs.writeFile('archivo.txt', data, 'utf8', (error) => {
if (error) {
console.error('Error al escribir en el archivo:', error);
} else {
console.log('Archivo escrito correctamente');
}
});

// Escritura de archivo de forma sincrónica
const data = 'Este es el contenido a escribir en el archivo';
try {
fs.writeFileSync('archivo.txt', data, 'utf8');
console.log('Archivo escrito correctamente');
} catch (error) {
console.error('Error al escribir en el archivo:', error);
}
```

3. **Manipulación de archivos y directorios**:
- **`fs.rename()`**: Cambia el nombre de un archivo o mueve un archivo a otra ubicación.
- **`fs.unlink()`**: Elimina un archivo.
- **`fs.mkdir()`**: Crea un directorio.
- **`fs.readdir()`**: Lee los contenidos de un directorio.

```jsx
// Renombrar un archivo
fs.rename('antiguo.txt', 'nuevo.txt', (error) => {
if (error) {
console.error('Error al renombrar el archivo:', error);
} else {
console.log('Archivo renombrado correctamente');
}
});

// Eliminar un archivo
fs.unlink('archivo.txt', (error) => {
if (error) {
console.error('Error al eliminar el archivo:', error);
} else {
console.log('Archivo eliminado correctamente');
}
});

// Crear un directorio
fs.mkdir('directorio', (error) => {
if (error) {
console.error('Error al crear el directorio:', error);
} else {
console.log('Directorio creado correctamente');
}
});

// Leer los contenidos de un directorio
fs.readdir('directorio', (error, files) => {
if (error) {
console.error('Error al leer el directorio:', error);
} else {
console.log('Contenidos del directorio:', files);
}
});

```

Estos son solo algunos ejemplos de las funcionalidades proporcionadas por el módulo **`fs`**. También puedes utilizar **`fs.stat()`** para obtener información sobre un archivo o directorio, **`fs.rmdir()`** para eliminar un directorio, **`fs.copyFile()`** para copiar un archivo, entre otras operaciones relacionadas con el sistema de archivos.

El módulo **`fs`** es una parte esencial de Node.js para trabajar con el sistema de archivos.
</details>

</details>
<details>
<summary><b>Módulos externos (third-party modules)</b></summary>

```jsx
const express = require('express');
```

Además de los módulos integrados, Node.js permite utilizar módulos externos desarrollados por la comunidad de desarrolladores. Estos módulos se encuentran disponibles a través del gestor de paquetes npm (Node Package Manager). npm es una herramienta que facilita la instalación, gestión y compartición de paquetes de código de terceros. Puedes explorar y buscar módulos en el registro público de npm en **[https://www.npmjs.com/](https://www.npmjs.com/)**. Para utilizar un módulo externo, primero debes instalarlo en tu proyecto utilizando el comando **`npm install`**. Luego, puedes requerirlo en tu código de la misma manera que con los módulos integrados. Por ejemplo:

Además de requerir módulos, Node.js también permite exportar código desde un módulo para que pueda ser utilizado en otros archivos. Esto se hace utilizando la variable **`module.exports`** o la función **`exports`**. Por ejemplo, en un archivo **`myModule.js`**:

```jsx
// Exportar una función
exports.saludar = function(nombre) {
console.log('Hola, ' + nombre + '!');
};

// Exportar una variable
exports.numero = 42;
```

Luego, en otro archivo, puedes requerir y utilizar el módulo:

```jsx
const myModule = require('./myModule');

myModule.saludar('Juan'); // Imprime: Hola, Juan!
console.log(myModule.numero); // Imprime: 42
```
</details>
</details>

<details>
<summary><b>NPM</b></summary>

<details>
<summary><b>Qué es: </b></summary>

**npm** es el administrador de paquetes predeterminado para Node.js. Se instala automáticamente junto con Node.js. npm es una herramienta que te permite descargar, instalar, actualizar y gestionar las dependencias de tu proyecto. Un paquete en npm es un módulo o biblioteca de JavaScript reutilizable que puedes utilizar en tu aplicación.

Con npm, puedes buscar paquetes, instalar paquetes desde el registro de npm (un repositorio en línea que alberga miles de paquetes de código abierto), administrar las versiones de los paquetes, y más. Además, puedes crear y publicar tus propios paquetes para que otros desarrolladores puedan utilizarlos.

El uso de npm te permite aprovechar la amplia variedad de paquetes y herramientas disponibles en el ecosistema de Node.js, lo que agiliza y simplifica el desarrollo de aplicaciones.

</details>

<details>
<summary><b>node_modules</b></summary>
La carpeta **`node_modules`** es un directorio creado automáticamente por npm al instalar paquetes en un proyecto de Node.js. Cuando utilizas npm para instalar paquetes en tu proyecto, npm descarga esos paquetes y los guarda en la carpeta **`node_modules`** de tu directorio de proyecto.

Cada paquete instalado mediante npm tendrá su propia carpeta dentro de **`node_modules`**, con su nombre y versión específicos. Dentro de cada carpeta de paquete, se encuentran los archivos y dependencias necesarios para que ese paquete funcione correctamente.

La estructura de la carpeta **`node_modules`** puede ser bastante compleja, especialmente si tu proyecto tiene muchas dependencias. Sin embargo, no es necesario que te preocupes por su contenido o su estructura en la mayoría de los casos.

Cuando ejecutas tu aplicación Node.js, el entorno de ejecución busca automáticamente los módulos requeridos en la carpeta **`node_modules`**. No necesitas hacer referencia explícita a la carpeta **`node_modules`** en tu código, ya que Node.js sabe dónde buscar los módulos requeridos en función de la configuración del proyecto y los caminos de búsqueda establecidos.

La carpeta **`node_modules`** se excluye generalmente de los sistemas de control de versiones (como Git) al publicar tu código fuente, ya que los paquetes pueden ser instalados nuevamente utilizando el archivo **`package.json`** y el comando **`npm install`**. Esto evita que la carpeta **`node_modules`** ocupe espacio innecesario en el repositorio y simplifica la distribución y colaboración del proyecto.
</details>

<details>
<summary><b>Paquetes y dependencias</b></summary>
En el contexto de Node.js y npm, los términos "paquetes" y "dependencias" están estrechamente relacionados y se refieren a los módulos o bibliotecas de código que se utilizan en una aplicación.

**Paquetes**: En el ecosistema de Node.js, un paquete se refiere a un módulo o biblioteca de JavaScript reutilizable que se distribuye a través del registro de npm. Un paquete puede contener funcionalidades específicas, como funciones, clases, métodos y utilidades, que pueden ser utilizadas por otros desarrolladores en sus proyectos. Un paquete generalmente se publica con un nombre único y una versión específica.

**Dependencias**: Las dependencias son paquetes o módulos externos en los que se basa una aplicación para funcionar correctamente. Cuando desarrollas una aplicación con Node.js, puedes utilizar diferentes paquetes de código abierto para agregar funcionalidades adicionales o simplificar ciertas tareas. Estos paquetes se especifican en el archivo **`package.json`** de tu proyecto y se instalan en la carpeta **`node_modules`** mediante el administrador de paquetes npm.
</details>
</details>

<details>
<summary><b>Crear paquete con NPM</b></summary>

<details>
<summary><b>npm init</b></summary>

Aquí tienes una guía paso a paso para utilizar el comando **`npm init`** y crear un archivo **`package.json`** en tu proyecto:

1. Abre tu línea de comandos o terminal y navega hasta la carpeta raíz de tu proyecto donde deseas crear el archivo **`package.json`**.
2. Ejecuta el siguiente comando:

```bash
npm init

```

1. A continuación, se te guiará a través de un asistente interactivo que te solicitará información sobre tu proyecto. A continuación se muestra una lista de los campos comunes que se te pedirá que completes:
- **name**: Ingresa el nombre de tu proyecto. El nombre debe ser único y no debe contener caracteres especiales ni espacios.
- **version**: Ingresa la versión inicial de tu proyecto. Puedes usar el formato de versión semántica, como "1.0.0".
- **description**: Proporciona una breve descripción de tu proyecto.
- **entry point**: Especifica el archivo principal de tu proyecto, generalmente llamado **`index.js`**. Si estás creando una biblioteca o un módulo, puedes dejar este campo vacío.
- **test command**: Si tienes configurado algún comando de prueba, puedes ingresarlo aquí. De lo contrario, puedes dejarlo en blanco.
- **git repository**: Si tu proyecto está vinculado a un repositorio Git, puedes ingresar la URL de tu repositorio aquí. De lo contrario, puedes dejarlo en blanco.
- **keywords**: Proporciona palabras clave que describan tu proyecto, separadas por espacios.
- **author**: Ingresa tu nombre o el nombre del autor principal del proyecto.
- **license**: Elige la licencia bajo la cual deseas distribuir tu proyecto. Puedes elegir entre las opciones comunes como "MIT", "ISC", "Apache-2.0", etc.
- **Yes/No questions**: Se te harán preguntas adicionales, como si deseas incluir un archivo **`README.md`**, si deseas que tu proyecto esté configurado como privado, etc. Responde "Yes" o "No" según tus necesidades.
2. Después de responder todas las preguntas, se generará el archivo **`package.json`** con la información proporcionada. Revisa cuidadosamente la información en el archivo y asegúrate de que sea correcta.

¡Y eso es todo! Ahora tienes un archivo **`package.json`** generado en tu proyecto, el cual contiene la configuración básica de tu proyecto y puede ser utilizado para administrar las dependencias, scripts y otra información relevante.

Recuerda que siempre puedes editar manualmente el archivo **`package.json`** si necesitas realizar cambios en la configuración de tu proyecto más adelante.
</details>

<details>
<summary><b>JSON</b></summary>
JSON (JavaScript Object Notation) es un formato de intercambio de datos ligero y legible por humanos. Se utiliza para transmitir y almacenar datos estructurados en una forma que es fácilmente comprensible tanto para los humanos como para las máquinas. JSON se basa en la sintaxis de los objetos literales de JavaScript, pero es un formato independiente del lenguaje.

Aquí hay algunas características clave de JSON:

1. **Estructura de datos**: JSON permite representar datos estructurados utilizando una combinación de objetos y arreglos. Los datos se organizan en pares clave-valor, donde las claves son cadenas y los valores pueden ser de diferentes tipos, como cadenas de texto, números, booleanos, objetos, arreglos o valores nulos.
2. **Sintaxis sencilla**: La sintaxis de JSON es sencilla y fácil de leer y escribir. Los objetos se delimitan con llaves **`{}`**, los arreglos se delimitan con corchetes **`[]`**, y los pares clave-valor se separan con dos puntos **`:`**. Los elementos en un arreglo o en un objeto se separan con comas **`,`**.
3. **Tipos de datos compatibles**: JSON admite varios tipos de datos comunes, incluyendo cadenas de texto, números, booleanos, objetos, arreglos y valores nulos. Los objetos JSON pueden contener propiedades con nombres únicos, mientras que los arreglos JSON contienen una secuencia ordenada de valores.
4. **Compatibilidad con varios lenguajes**: JSON se ha convertido en un formato de datos ampliamente aceptado y es compatible con la mayoría de los lenguajes de programación. Esto significa que puedes generar, leer y analizar JSON en diferentes lenguajes sin problemas.
5. **Interoperabilidad**: JSON es utilizado ampliamente en aplicaciones web y servicios web como un formato de intercambio de datos. Puedes enviar datos en formato JSON desde un servidor a un cliente, y viceversa, lo que permite una comunicación eficiente y consistente entre diferentes sistemas.

Aquí tienes un ejemplo de cómo se ve un objeto JSON:

```json

{
  "nombre": "Juan",
  "edad": 30,
  "ciudad": "México",
  "hobbies": ["correr", "leer", "viajar"],
  "activo": true,
  "amigos": [
    { "nombre": "María", "edad": 28 },
    { "nombre": "Carlos", "edad": 32 }
  ]
}

```

En este ejemplo, tenemos un objeto JSON que representa información de una persona. El objeto tiene propiedades como "nombre", "edad", "ciudad", "hobbies" y "activo". Algunas propiedades contienen valores simples, como cadenas de texto y números, mientras que otras contienen arreglos y objetos anidados.

JSON se utiliza ampliamente en el desarrollo de aplicaciones web y servicios web para el intercambio de datos entre diferentes sistemas. La mayoría de los lenguajes de programación proporcionan funciones y bibliotecas para trabajar con JSON, lo que facilita su manipulación y análisis.
</details>

<details>
<summary><b>JSON.parse</b></summary>

**`JSON.parse()`** es una función incorporada en JavaScript que se utiliza para analizar una cadena JSON y convertirla en un objeto JavaScript. Toma una cadena JSON válida como argumento y devuelve un objeto JavaScript que representa los datos contenidos en esa cadena.

La sintaxis básica de **`JSON.parse()`** es la siguiente:

```jsx
JSON.parse(jsonString)

```

Donde **`jsonString`** es la cadena JSON que se desea analizar y convertir en un objeto JavaScript.

Aquí hay un ejemplo de cómo utilizar **`JSON.parse()`**:

```jsx
const jsonString = '{"nombre": "Juan", "edad": 30, "ciudad": "México"}';
const obj = JSON.parse(jsonString);
console.log(obj.nombre); // Output: "Juan"
console.log(obj.edad); // Output: 30
console.log(obj.ciudad); // Output: "México"

```

En este ejemplo, **`jsonString`** es una cadena JSON que representa un objeto con propiedades como "nombre", "edad" y "ciudad". Al llamar a **`JSON.parse(jsonString)`**, se analiza la cadena JSON y se convierte en un objeto JavaScript. Luego, podemos acceder a las propiedades del objeto utilizando la notación de punto.

Es importante tener en cuenta que la cadena JSON debe ser válida para que **`JSON.parse()`** funcione correctamente. Debe seguir la sintaxis y el formato adecuados de JSON. Si la cadena JSON no es válida, **`JSON.parse()`** lanzará una excepción de error.

**`JSON.parse()`** también puede manejar cadenas JSON que contienen arreglos, objetos anidados y otros tipos de datos compatibles con JSON. Si la cadena JSON contiene arreglos, se convertirán en arreglos JavaScript correspondientes. Si contiene objetos anidados, se convertirán en objetos JavaScript anidados.

</details>

<details>
<summary><b>JSON.stringify</b></summary>

**`JSON.stringify()`** es una función incorporada en JavaScript que se utiliza para convertir un objeto JavaScript en una cadena JSON. Toma un objeto JavaScript como argumento y devuelve una representación JSON de ese objeto.

La sintaxis básica de **`JSON.stringify()`** es la siguiente:

```jsx
JSON.stringify(objeto[, propiedades[, espaciado]])

```

Donde:

- **`objeto`**: El objeto JavaScript que se desea convertir en una cadena JSON.
- **`propiedades`** (opcional): Un array o una función que se utiliza para filtrar y seleccionar las propiedades que se incluirán en la cadena JSON resultante.
- **`espaciado`** (opcional): Un valor numérico o una cadena que se utiliza para dar formato a la cadena JSON resultante con espacios y saltos de línea para hacerla más legible. Por ejemplo, puedes utilizar un valor numérico para especificar la cantidad de espacios en blanco que se deben usar para la indentación, o puedes utilizar una cadena como "\t" para usar tabulaciones en lugar de espacios.

Aquí hay un ejemplo de cómo utilizar **`JSON.stringify()`**:

```jsx
const objeto = {
  nombre: "Juan",
  edad: 30,
  ciudad: "México"
};

const jsonString = JSON.stringify(objeto);
console.log(jsonString);
// Output: '{"nombre":"Juan","edad":30,"ciudad":"México"}'

```

En este ejemplo, **`objeto`** es un objeto JavaScript que representa información de una persona. Al llamar a **`JSON.stringify(objeto)`**, el objeto se convierte en una cadena JSON válida. La cadena JSON resultante se imprime en la consola.

Además de convertir objetos JavaScript en cadenas JSON, **`JSON.stringify()`** también puede manejar opciones adicionales como:

- El uso del segundo argumento **`propiedades`** para filtrar las propiedades del objeto que se incluirán en la cadena JSON resultante. Esto permite una mayor flexibilidad en la selección de propiedades específicas para incluir o excluir.
- El uso del tercer argumento **`espaciado`** para dar formato a la cadena JSON resultante con espacios y saltos de línea. Esto hace que la cadena JSON sea más legible para los humanos.
</details>
</details>


<details>
<summary><b>Instalar y Desinstalar paquetes con npm</b></summary>

Para instalar y desinstalar paquetes con npm, sigue estos pasos:

**Instalar paquetes:**

1. Abre tu línea de comandos o terminal.
2. Navega hasta la carpeta raíz de tu proyecto o al directorio donde deseas instalar el paquete.
3. Ejecuta el siguiente comando para instalar un paquete específico:

```bash
npm install nombre-del-paquete

```

Reemplaza "nombre-del-paquete" por el nombre del paquete que deseas instalar. Por ejemplo, para instalar el paquete "lodash", usarías **`npm install lodash`**. También puedes especificar una versión específica agregando **`@`** seguido del número de versión, como **`npm install lodash@4.17.21`**.

1. npm descargará e instalará el paquete junto con sus dependencias en la carpeta **`node_modules`** de tu proyecto. Puedes consultar el archivo **`package.json`** para ver la lista de dependencias instaladas y sus versiones.

**Desinstalar paquetes:**

1. Abre tu línea de comandos o terminal.
2. Navega hasta la carpeta raíz de tu proyecto o al directorio donde se encuentra el paquete que deseas desinstalar.
3. Ejecuta el siguiente comando para desinstalar un paquete específico:

```bash
npm uninstall nombre-del-paquete

```

Reemplaza "nombre-del-paquete" por el nombre del paquete que deseas desinstalar. Por ejemplo, para desinstalar el paquete "lodash", usarías **`npm uninstall lodash`**.

1. npm eliminará el paquete y sus dependencias de la carpeta **`node_modules`** de tu proyecto.

Es importante tener en cuenta que, al desinstalar un paquete, se eliminará solo la versión específica del paquete que estás desinstalando. Si otros paquetes en tu proyecto dependen de la misma versión, seguirán estando presentes en la carpeta **`node_modules`**.

Además, es posible que desees agregar el flag **`--save`** o **`--save-dev`** al ejecutar **`npm install`** para guardar las dependencias en el archivo **`package.json`**. Por ejemplo:

```bash
npm install nombre-del-paquete --save

```

Esto agregará el paquete como una dependencia en la sección **`"dependencies"`** del archivo **`package.json`**. Si el paquete es una dependencia de desarrollo, puedes usar **`--save-dev`** en su lugar para agregarlo a la sección **`"devDependencies"`**.

Recuerda que debes tener npm instalado en tu sistema para poder utilizar estos comandos. npm se instala automáticamente junto con Node.js.
</details>

<details>
<summary><b>Package-lock.json</b></summary>
El archivo **`package-lock.json`** es un archivo generado automáticamente por npm cuando se instalan paquetes en un proyecto. Este archivo almacena información detallada sobre las dependencias y las versiones específicas de los paquetes instalados en el proyecto.

El propósito principal del archivo **`package-lock.json`** es garantizar la reproducibilidad de las instalaciones de paquetes. Contiene un registro de las versiones exactas de los paquetes que se han instalado, incluidas las versiones de sus dependencias directas e indirectas. Esto significa que cuando otro desarrollador o equipo trabaje en el proyecto y ejecute el comando **`npm install`**, npm utilizará la información del archivo **`package-lock.json`** para asegurarse de que las mismas versiones exactas de los paquetes se instalen en sus máquinas.

El archivo **`package-lock.json`** también incluye información adicional, como los enlaces a los repositorios de los paquetes y los hashes de integridad para verificar la integridad de los paquetes descargados.

Es importante incluir el archivo **`package-lock.json`** en el control de versiones de tu proyecto para garantizar la consistencia en el entorno de desarrollo. Esto significa que cuando compartas el proyecto con otros desarrolladores o lo implementes en diferentes entornos, se utilizarán las mismas versiones de paquetes.

Además, cuando ejecutas el comando **`npm install`**, npm verifica si existe el archivo **`package-lock.json`** y lo utiliza para realizar instalaciones más rápidas y consistentes. Si no se encuentra el archivo **`package-lock.json`**, npm generará uno nuevo basado en las dependencias declaradas en el archivo **`package.json`**.
</details>


<details>
<summary><b>Eventos en Node.js</b></summary>

En Node.js, los eventos son una parte fundamental de su arquitectura basada en el modelo de programación asíncrona y orientada a eventos. El módulo principal que permite trabajar con eventos en Node.js es el módulo **`events`**, que proporciona una forma de emitir, escuchar y manejar eventos.

Aquí hay una descripción general de cómo funcionan los eventos en Node.js:

<details>
<summary><b>Creación del objeto EventEmitter:</b></summary>
El primer paso es crear una instancia de la clase **`EventEmitter`** del módulo **`events`**. Esta instancia actuará como el emisor de eventos.

![Untitled](./images/Untitled%204.png)

```jsx

const EventEmitter = require('events');
const miEmitter = new EventEmitter();

```
</details>

<details>
<summary><b>Registro de escuchadores de eventos: </b></summary>

A continuación, puedes registrar escuchadores de eventos en el objeto **`EventEmitter`**. Un escuchador de eventos es una función que se ejecuta cuando un evento en particular es emitido por el emisor.

```jsx
miEmitter.on('evento', () => {
  console.log('El evento fue emitido');
});

```

En este ejemplo, hemos registrado un escuchador de eventos para el evento llamado **`'evento'`**. Cuando este evento se emita, la función de escuchador se ejecutará.
</details>

<details>
<summary><b>Emisión de eventos: </b></summary>
Para emitir un evento, utilizas el método **`emit()`** en el objeto **`EventEmitter`**. Puedes pasar datos adicionales como argumentos al método **`emit()`** que serán pasados a los escuchadores de eventos.

```jsx
miEmitter.emit('evento');

```

Al ejecutar este código, el evento llamado **`'evento'`** se emitirá y el escuchador asociado a ese evento se ejecutará, imprimiendo **`"El evento fue emitido"`** en la consola.
</details>

<details>
<summary><b>Manejo de eventos con una vez: </b></summary>
Además de **`on()`**, puedes usar el método **`once()`** para registrar un escuchador de eventos que solo se ejecutará una vez.

```jsx
miEmitter.once('eventoUnico', () => {
  console.log('Este evento se ejecutará solo una vez');
});

```

En este caso, el escuchador de eventos asociado al evento **`'eventoUnico'`** solo se ejecutará la primera vez que se emita el evento. Si el evento se emite nuevamente, el escuchador no se ejecutará.
</details>

<details>
<summary><b>Pasando argumentos a los escuchadores de eventos: </b></summary>
Puedes pasar argumentos adicionales al emitir un evento y acceder a ellos en los escuchadores de eventos.

```jsx
miEmitter.on('mensaje', (mensaje) => {
  console.log('Mensaje recibido:', mensaje);
});

miEmitter.emit('mensaje', 'Hola, mundo!');

```

En este ejemplo, el evento **`'mensaje'`** se emite con el argumento **`'Hola, mundo!'`**. El escuchador de eventos asociado a ese evento imprimirá **`"Mensaje recibido: Hola, mundo!"`** en la consola.
</details>
</details>

<details>
<summary><b>Promesas en JavaScript</b></summary>
Las promesas en JavaScript son un concepto fundamental en programación asincrónica y se utilizan para manejar operaciones que toman tiempo, como llamadas a API, operaciones de red o lectura/escritura de archivos, de una manera más fácil y legible.

En términos sencillos, una promesa es un objeto que representa el resultado pendiente de una operación asincrónica. Puede tener uno de los siguientes estados:

1. **Pendiente**: La promesa está en espera de que se resuelva o se rechace.
2. **Cumplida**: La operación asincrónica se ha completado exitosamente y se ha obtenido un resultado.
3. **Rechazada**: La operación asincrónica ha fallado y se ha obtenido un motivo de rechazo (un error).

Aquí tienes un ejemplo básico de cómo se ve una promesa en JavaScript:

```jsx
const miPromesa = new Promise((resolve, reject) => {
  // Aquí se realiza la operación asincrónica

  // Si la operación es exitosa, llamamos a 'resolve' con el resultado
  resolve('¡La operación se completó correctamente!');

  // Si la operación falla, llamamos a 'reject' con el motivo del rechazo
  // reject('Ocurrió un error en la operación');
});

// Manejamos el resultado de la promesa usando 'then' y 'catch'
miPromesa.then((resultado) => {
  console.log(resultado); // Imprime el resultado si la promesa se cumple
}).catch((error) => {
  console.log(error); // Imprime el motivo del rechazo si la promesa es rechazada
});

```

En este ejemplo, creamos una promesa llamada **`miPromesa`** que representa una operación asincrónica. Dentro de la función que recibe como argumento, realizamos la operación y llamamos a la función **`resolve()`** si la operación es exitosa o a la función **`reject()`** si la operación falla.

Luego, utilizamos los métodos **`then()`** y **`catch()`** para manejar el resultado de la promesa. Si la promesa se cumple (es decir, se resuelve), el código dentro de **`then()`** se ejecutará y tendremos acceso al resultado. Si la promesa es rechazada, el código dentro de **`catch()`** se ejecutará y tendremos acceso al motivo del rechazo.

El uso de promesas permite estructurar de manera más clara y ordenada el código asincrónico, evitando el anidamiento excesivo de callbacks y mejorando la legibilidad del código. Además, las promesas proporcionan métodos adicionales, como **`finally()`** para ejecutar código independientemente del resultado de la promesa, y permiten encadenar múltiples operaciones asincrónicas utilizando **`then()`**.
</details>

<details>
<summary><b>async / await</b></summary>

**`async/await`** es una característica introducida en JavaScript ES2017 (también conocido como ES8) que proporciona una forma más concisa y legible de trabajar con promesas. Permite escribir código asincrónico como si fuera síncrono, sin anidamiento excesivo de callbacks o uso de métodos **`then()`** y **`catch()`**.

Aquí tienes un ejemplo básico de cómo se utiliza **`async/await`**:

```jsx
async function miFuncionAsincrona() {
  try {
    const resultado = await promesa; // La promesa se resuelve y se obtiene el resultado
    console.log(resultado); // Se trabaja con el resultado como si fuera síncrono
  } catch (error) {
    console.log(error); // Se maneja el error si la promesa es rechazada
  }
}

```

En este ejemplo, definimos una función **`miFuncionAsincrona`** con la palabra clave **`async`**. Dentro de la función, utilizamos la palabra clave **`await`** seguida de una promesa. Esto pausa la ejecución de la función hasta que la promesa se resuelva o se rechace. Una vez que la promesa se resuelve, el resultado se asigna a la variable **`resultado`** y se puede trabajar con él como si fuera un valor síncrono. Si la promesa es rechazada, el código dentro del bloque **`catch`** se ejecutará y se manejará el error.

Es importante tener en cuenta que **`await`** solo se puede usar dentro de una función **`async`**. Además, el uso de **`await`** solo está permitido en contextos asincrónicos, como dentro de funciones que devuelven promesas o dentro de otras funciones **`async`**. Esto permite un flujo de control más claro y legible en el código asincrónico.

La ventaja de utilizar **`async/await`** es que simplifica la escritura y comprensión de código asincrónico al eliminar la necesidad de encadenar múltiples llamadas de **`then()`** y manejar errores con **`catch()`**. En su lugar, puedes escribir código más secuencial y estructurado, similar a un código síncrono tradicional.

Recuerda que, aunque **`async/await`** facilita el manejo de promesas, aún estás trabajando con operaciones asincrónicas. Las funciones **`async`** siempre devuelven una promesa, y si una promesa dentro de un bloque **`async`** es rechazada sin ser manejada, la promesa devuelta por la función **`async`** también será rechazada.

En resumen, **`async/await`** es una característica de JavaScript que proporciona una forma más concisa y legible de trabajar con promesas. Permite escribir código asincrónico como si fuera síncrono, utilizando la palabra clave **`await`** para pausar la ejecución y esperar la resolución de una promesa. Esto simplifica el flujo de control y mejora la legibilidad del código asincrónico.
</details>


<details>
<summary><b>Modelo Cliente-Servidor</b></summary>
El modelo Cliente-Servidor es una arquitectura de red y un paradigma de comunicación entre sistemas en el cual hay dos roles principales: el cliente y el servidor.

En este modelo, el cliente y el servidor son entidades independientes que se comunican entre sí a través de una red, como Internet. Cada uno tiene responsabilidades y roles específicos:

1. **Cliente**: El cliente es el software o la aplicación que solicita y consume recursos o servicios proporcionados por el servidor. Puede ser una aplicación de escritorio, una aplicación móvil o incluso un navegador web. El cliente envía solicitudes al servidor y espera recibir las respuestas correspondientes.
2. **Servidor**: El servidor es el software o la aplicación que proporciona recursos o servicios al cliente. Tiene la capacidad de recibir solicitudes del cliente, procesarlas y enviar las respuestas correspondientes. El servidor puede ser una computadora física dedicada, un servidor en la nube o cualquier dispositivo capaz de manejar solicitudes y ofrecer servicios.

La comunicación entre el cliente y el servidor se basa en un protocolo de red, como HTTP (Protocolo de Transferencia de Hipertexto), que define cómo se intercambian los datos entre el cliente y el servidor.

En un escenario típico, el flujo de comunicación puede ser el siguiente:

1. El cliente envía una solicitud al servidor a través de una conexión de red. La solicitud puede contener información como la URL, los parámetros, los datos del formulario o cualquier otro dato relevante para la operación deseada.
2. El servidor recibe la solicitud del cliente y procesa la solicitud según el tipo de servicio solicitado. Esto puede incluir realizar operaciones en una base de datos, ejecutar una lógica de negocio o acceder a otros recursos.
3. Una vez que el servidor ha procesado la solicitud, genera una respuesta que contiene los datos solicitados o el resultado de la operación solicitada.
4. El servidor envía la respuesta de vuelta al cliente a través de la conexión de red establecida previamente.
5. El cliente recibe la respuesta del servidor y puede procesarla según sea necesario. Esto puede incluir mostrar la información en una interfaz de usuario, almacenar los datos recibidos o realizar acciones adicionales en función de la respuesta.

Este flujo de comunicación se repite cada vez que el cliente envía una solicitud al servidor y espera una respuesta correspondiente.

El modelo Cliente-Servidor se utiliza ampliamente en aplicaciones y sistemas distribuidos en Internet. Permite una distribución eficiente de la carga de trabajo y una separación clara de responsabilidades entre el cliente y el servidor, lo que facilita el desarrollo, el mantenimiento y la escalabilidad de los sistemas.
</details>

<details>
<summary><b>Solicitudes HTTP</b></summary>

Las solicitudes HTTP (Hypertext Transfer Protocol) son un componente fundamental en la comunicación cliente-servidor en la web. Con HTTP, los clientes pueden enviar solicitudes al servidor y recibir respuestas que contienen datos, recursos o información solicitada.

Las solicitudes HTTP están compuestas por varios elementos importantes:

1. **Verbo HTTP**: Especifica el tipo de acción que se desea realizar en el servidor. Algunos de los verbos más comunes son:
    - GET: Solicita un recurso específico del servidor.
    - POST: Envía datos al servidor para ser procesados (como enviar un formulario en línea).
    - PUT: Actualiza un recurso existente en el servidor.
    - DELETE: Elimina un recurso existente en el servidor.
    - PATCH: Realiza una modificación parcial de un recurso existente en el servidor.
2. **URL (Uniform Resource Locator)**: Es la dirección del recurso que se desea obtener, modificar o eliminar en el servidor. La URL consta de varios componentes, como el protocolo (HTTP), el dominio (nombre del servidor) y la ruta específica del recurso en el servidor.
3. **Encabezados (Headers)**: Son metadatos adicionales que se incluyen en la solicitud para proporcionar información adicional al servidor o al cliente. Los encabezados pueden contener información sobre el tipo de contenido que se envía, las preferencias del cliente, la autenticación, el idioma, la codificación, etc.
4. **Cuerpo de la solicitud (Request body)**: Opcionalmente, algunas solicitudes pueden incluir un cuerpo que contiene datos adicionales que se envían al servidor. Esto se utiliza principalmente en solicitudes POST, PUT o PATCH, donde se envían datos para ser procesados por el servidor.

Una vez que se envía la solicitud HTTP al servidor, este la procesa y devuelve una respuesta correspondiente. Las respuestas HTTP contienen información sobre el estado de la solicitud, así como los datos o recursos solicitados.

Las respuestas HTTP también están compuestas por varios elementos importantes, como el código de estado HTTP (como 200 OK para una respuesta exitosa), los encabezados de respuesta y el cuerpo de la respuesta (que puede contener datos o recursos solicitados).

En resumen, las solicitudes HTTP son la base de la comunicación entre clientes y servidores en la web. Los clientes envían solicitudes al servidor especificando el verbo HTTP, la URL, los encabezados y, opcionalmente, el cuerpo de la solicitud. El servidor procesa la solicitud y devuelve una respuesta que contiene el código de estado, los encabezados y el cuerpo de la respuesta. Esto permite la transferencia de datos, recursos y la interacción entre los clientes y los servidores en la web.
</details>

<details>
<summary><b>Métodos HTTP</b></summary>

Los métodos HTTP (Hypertext Transfer Protocol) son verbos o acciones que se utilizan en las solicitudes para indicar el tipo de operación que se debe realizar en un recurso específico. Estos métodos definen la intención del cliente al interactuar con el servidor y son parte integral del protocolo HTTP. Aquí tienes una descripción de los métodos HTTP más comunes:

1. **GET**: El método GET se utiliza para solicitar y obtener un recurso específico del servidor. Esta solicitud no modifica ningún dato en el servidor y solo recupera información.
2. **POST**: El método POST se utiliza para enviar datos al servidor y crear un nuevo recurso en el servidor. Por ejemplo, se utiliza para enviar datos de formularios o cargar archivos al servidor.
3. **PUT**: El método PUT se utiliza para actualizar o reemplazar completamente un recurso existente en el servidor. Se envía el recurso completo al servidor para su actualización.
4. **PATCH**: El método PATCH se utiliza para realizar una modificación parcial de un recurso existente en el servidor. En lugar de enviar el recurso completo, solo se envían los cambios o actualizaciones necesarios.
5. **DELETE**: El método DELETE se utiliza para eliminar un recurso específico del servidor.
6. **HEAD**: El método HEAD es similar a GET, pero solicita solo los encabezados de respuesta, sin recuperar el cuerpo del recurso. Se utiliza para obtener información sobre un recurso sin descargar todo el contenido.
7. **OPTIONS**: El método OPTIONS se utiliza para obtener información sobre las opciones y capacidades de comunicación disponibles para un recurso específico en el servidor. Esto puede incluir los métodos HTTP admitidos, los encabezados permitidos, etc.

Estos son algunos de los métodos HTTP más utilizados, pero existen otros menos comunes, como TRACE, CONNECT, etc., que tienen usos más especializados.

Es importante tener en cuenta que cada método HTTP tiene un propósito específico y está diseñado para realizar operaciones particulares en los recursos del servidor. Al enviar una solicitud HTTP, debes elegir el método adecuado según la intención y el resultado esperado de la operación en el servidor.
</details>

<details>
<summary><b>Respuestas HTTP</b></summary>

Las respuestas HTTP (Hypertext Transfer Protocol) son enviadas por el servidor en respuesta a una solicitud realizada por el cliente. Las respuestas contienen información sobre el estado de la solicitud, así como los datos o recursos solicitados. Aquí tienes una descripción de los componentes principales de una respuesta HTTP:

1. **Código de estado HTTP**: Es un número de tres dígitos que indica el estado de la solicitud. Los códigos de estado más comunes incluyen:
    - 200 OK: Indica que la solicitud fue exitosa y se envía el contenido solicitado en el cuerpo de la respuesta.
    - 404 Not Found: Indica que el recurso solicitado no se encontró en el servidor.
    - 500 Internal Server Error: Indica un error interno del servidor al procesar la solicitud.
    - 301 Moved Permanently: Indica que el recurso solicitado se ha movido permanentemente a una nueva ubicación.
2. **Encabezados de respuesta**: Son metadatos adicionales que se envían junto con la respuesta para proporcionar información adicional al cliente o al servidor. Los encabezados pueden incluir información sobre el tipo de contenido, la codificación, la fecha y hora de la respuesta, entre otros datos.
3. **Cuerpo de la respuesta**: Es el contenido de la respuesta, que puede ser el recurso solicitado, datos adicionales o información relevante. El cuerpo de la respuesta puede contener HTML, texto plano, JSON, imágenes u otros formatos, dependiendo del tipo de contenido solicitado y proporcionado por el servidor.

La respuesta HTTP se envía desde el servidor al cliente a través de la conexión de red establecida previamente. El cliente recibe la respuesta y puede procesarla según sea necesario. Esto puede incluir mostrar el contenido en una interfaz de usuario, extraer datos del cuerpo de la respuesta o tomar acciones adicionales basadas en los encabezados y el código de estado recibidos.

Es importante tener en cuenta que una solicitud puede tener diferentes tipos de respuestas dependiendo de diversos factores, como la validez de la solicitud, la disponibilidad del recurso y las configuraciones del servidor. Las respuestas HTTP proporcionan información crucial para el cliente y permiten una comunicación efectiva entre el cliente y el servidor en la web.
</details>

<details>
<summary><b>Códigos de estado HTTP</b></summary>

Los códigos de estado HTTP (Hypertext Transfer Protocol) son números de tres dígitos que indican el resultado de una solicitud HTTP realizada por el cliente. Estos códigos proporcionan información sobre el estado de la solicitud y ayudan a identificar cualquier problema o éxito en la comunicación entre el cliente y el servidor. Aquí tienes algunos ejemplos de códigos de estado HTTP comunes:

1. **1xx: Respuestas informativas**
    - 100 Continue: Indica que el servidor ha recibido los encabezados iniciales de la solicitud y está esperando que el cliente envíe el resto de la solicitud.
    - 101 Switching Protocols: Indica que el servidor está cambiando el protocolo utilizado en la conexión.
2. **2xx: Respuestas exitosas**
    - 200 OK: Indica que la solicitud ha sido exitosa y se devuelve el contenido solicitado.
    - 201 Created: Indica que la solicitud ha sido exitosa y se ha creado un nuevo recurso.
    - 204 No Content: Indica que la solicitud ha sido exitosa, pero no hay contenido para devolver en la respuesta.
3. **3xx: Redirecciones**
    - 301 Moved Permanently: Indica que el recurso solicitado se ha movido permanentemente a una nueva ubicación.
    - 302 Found: Indica que el recurso solicitado se ha encontrado, pero se ha movido temporalmente a una nueva ubicación.
    - 304 Not Modified: Indica que el recurso solicitado no ha sido modificado desde la última solicitud y se puede utilizar la copia en caché.
4. **4xx: Errores del cliente**
    - 400 Bad Request: Indica que la solicitud del cliente es incorrecta o no se puede procesar.
    - 404 Not Found: Indica que el recurso solicitado no se ha encontrado en el servidor.
    - 403 Forbidden: Indica que el servidor rechaza la solicitud del cliente debido a permisos insuficientes.
5. **5xx: Errores del servidor**
    - 500 Internal Server Error: Indica un error interno en el servidor al procesar la solicitud.
    - 502 Bad Gateway: Indica que el servidor actuando como puerta de enlace recibió una respuesta no válida del servidor ascendente.
    - 503 Service Unavailable: Indica que el servidor no está disponible actualmente para manejar la solicitud debido a una sobrecarga o mantenimiento.

Estos son solo algunos ejemplos de los códigos de estado HTTP más comunes. Hay muchos otros códigos de estado que se utilizan para diversos propósitos y situaciones. Los códigos de estado HTTP son útiles para diagnosticar y solucionar problemas en la comunicación entre clientes y servidores, ya que proporcionan información sobre el resultado de la solicitud.
</details>

<details>
<summary><b>Primer servidor HTTP</b></summary>

Aquí tienes un ejemplo básico de cómo crear un servidor HTTP utilizando el módulo **`http`** en Node.js:

```jsx
const http = require('http');

// Crear un servidor HTTP
const server = http.createServer((req, res) => {
  // Configurar encabezados de respuesta
  res.writeHead(200, { 'Content-Type': 'text/plain' });

  // Enviar la respuesta al cliente
  res.end('¡Hola, mundo!');
});

// Escuchar en un puerto específico
const port = 3000;
server.listen(port, () => {
  console.log(`El servidor está escuchando en el puerto ${port}`);
});

```

En este ejemplo, creamos un servidor HTTP utilizando la función **`http.createServer()`**. Dentro del callback, configuramos los encabezados de respuesta utilizando **`res.writeHead()`** y enviamos la respuesta al cliente utilizando **`res.end()`**. En este caso, simplemente enviamos el texto "¡Hola, mundo!" como respuesta.

Luego, especificamos el puerto en el que queremos que el servidor escuche llamando al método **`listen()`** en el objeto del servidor. En este ejemplo, el servidor está configurado para escuchar en el puerto 3000.

Una vez que hayas guardado el código en un archivo, como **`server.js`**, puedes ejecutarlo desde la línea de comandos utilizando el comando **`node server.js`**. Esto iniciará el servidor y podrás acceder a él en tu navegador ingresando **`http://localhost:3000`**.

Al acceder a **`http://localhost:3000`**, verás la respuesta "¡Hola, mundo!" que envía el servidor.
</details>

<details>
<summary><b>req / res</b></summary>

En un servidor HTTP, **`req`** y **`res`** son dos objetos que representan la solicitud entrante (request) y la respuesta saliente (response) respectivamente.

- **`req`** (Request): El objeto **`req`** representa la solicitud entrante del cliente al servidor. Contiene información sobre la solicitud, como la URL, los encabezados, los parámetros de consulta y cualquier cuerpo de solicitud enviado por el cliente. Permite acceder a estos datos y utilizarlos para procesar la solicitud.
- **`res`** (Response): El objeto **`res`** representa la respuesta saliente que el servidor enviará al cliente en respuesta a la solicitud. Permite configurar y enviar la respuesta al cliente. Puedes establecer los encabezados de respuesta, el código de estado HTTP y el cuerpo de la respuesta utilizando métodos y propiedades proporcionados por el objeto **`res`**.

Aquí tienes algunos ejemplos de cómo utilizar **`req`** y **`res`** en un servidor HTTP:

```jsx
const http = require('http');

const server = http.createServer((req, res) => {
  // Acceder a la URL de la solicitud
  console.log(req.url);

  // Acceder a los encabezados de la solicitud
  console.log(req.headers);

  // Acceder a los parámetros de consulta (query parameters)
  const queryParams = new URLSearchParams(req.url.slice(1));
  console.log(queryParams.get('id'));

  // Configurar encabezados de respuesta
  res.setHeader('Content-Type', 'text/plain');

  // Enviar una respuesta con código de estado 200 y un cuerpo de respuesta
  res.statusCode = 200;
  res.end('¡Respuesta enviada!');
});

server.listen(3000, () => {
  console.log('El servidor está escuchando en el puerto 3000');
});

```

En este ejemplo, estamos utilizando **`req`** y **`res`** en el callback que se pasa a **`createServer()`**. Accedemos a la URL de la solicitud a través de **`req.url`**, los encabezados de la solicitud a través de **`req.headers`** y los parámetros de consulta utilizando el módulo **`URLSearchParams`**.

Para la respuesta, configuramos los encabezados de respuesta utilizando **`res.setHeader()`**, establecemos el código de estado HTTP con **`res.statusCode`** y enviamos el cuerpo de respuesta utilizando **`res.end()`**.

Estos son solo algunos ejemplos de cómo se pueden utilizar **`req`** y **`res`** en un servidor HTTP. Ambos objetos proporcionan una serie de métodos y propiedades para interactuar con las solicitudes y respuestas, lo que te permite procesar y enviar datos entre el cliente y el servidor de manera eficiente.
</details>

<details>
<summary><b>Estructura de una URL</b></summary>

Una URL (Uniform Resource Locator) es una cadena de caracteres que se utiliza para identificar y localizar recursos en la web. La estructura de una URL consta de varios componentes que definen la ubicación y la forma de acceder al recurso deseado. Aquí está la estructura general de una URL:

```bash

protocolo://dominio:puerto/ruta?parámetros#fragmento

```

A continuación, se explica cada componente de una URL:

1. **Protocolo**: Especifica el protocolo de comunicación utilizado para acceder al recurso. Algunos ejemplos comunes son **`http://`** para el protocolo HTTP y **`https://`** para el protocolo HTTPS.
2. **Dominio**: Es el nombre de dominio del servidor que aloja el recurso. Puede ser una dirección IP o un nombre de dominio legible por humanos, como **`www.ejemplo.com`**.
3. **Puerto** (opcional): Especifica el puerto en el servidor al que se realizará la solicitud. Si no se especifica, se utiliza el puerto predeterminado para el protocolo, como el puerto 80 para HTTP y el puerto 443 para HTTPS.
4. **Ruta**: Es la ubicación específica del recurso dentro del servidor. Indica la ruta de acceso relativa al dominio donde se encuentra el recurso. Por ejemplo, **`/productos/televisor`** representa la ruta del recurso "televisor" dentro del directorio "productos" en el servidor.
5. **Parámetros** (opcional): Se utilizan para enviar datos adicionales en la URL. Los parámetros se agregan después de la ruta y se separan con el símbolo de interrogación **`?`**. Cada parámetro se compone de un nombre y un valor separados por el símbolo de igual **`=`**, y múltiples parámetros se separan con el símbolo de ampersand **`&`**. Por ejemplo, **`?id=123&nombre=producto`**.
6. **Fragmento** (opcional): Especifica una ubicación específica dentro del recurso. Se indica con el símbolo de numeral **`#`**. Los fragmentos son comúnmente utilizados en páginas web para navegar directamente a una sección específica de la página.

Aquí tienes un ejemplo de una URL completa:

```
bashCopy code
https://www.ejemplo.com:8080/productos/televisor?id=123&nombre=producto#seccion2

```

En este ejemplo, el protocolo es **`https://`**, el dominio es **`www.ejemplo.com`**, el puerto es **`8080`**, la ruta es **`/productos/televisor`**, los parámetros son **`id=123&nombre=producto`** y el fragmento es **`seccion2`**.

La estructura de una URL puede variar dependiendo del contexto y el tipo de recurso que se esté accediendo. Es importante comprender la estructura para poder trabajar con URLs de manera efectiva en el desarrollo web.
</details>

<details>
<summary><b>Módulo url</b></summary>

El módulo **`url`** en Node.js es un módulo incorporado que proporciona utilidades para trabajar con URLs. Permite analizar y manipular componentes individuales de una URL, así como construir y formatear URLs.

Para utilizar el módulo **`url`**, primero debes importarlo en tu archivo de JavaScript:

```jsx

const url = require('url');

```

A continuación, puedes utilizar las funciones y propiedades proporcionadas por el módulo **`url`**. Aquí tienes algunos ejemplos de cómo puedes utilizarlo:

1. **Analizar una URL**:
Puedes utilizar la función **`url.parse()`** para analizar una URL y obtener sus componentes individuales, como el protocolo, el dominio, la ruta, los parámetros, etc. Por ejemplo:
    
    ```jsx
    
    const parsedUrl = url.parse('https://www.example.com/products?category=electronics', true);
    console.log(parsedUrl.protocol); // 'https:'
    console.log(parsedUrl.hostname); // 'www.example.com'
    console.log(parsedUrl.pathname); // '/products'
    console.log(parsedUrl.searchParams); // { category: 'electronics' }
    
    ```
    
2. **Construir una URL**:
Puedes utilizar la función **`url.format()`** para construir una URL a partir de sus componentes individuales. Por ejemplo:
    
    ```jsx
    
    const constructedUrl = url.format({
      protocol: 'https:',
      hostname: 'www.example.com',
      pathname: '/products',
      query: { category: 'electronics' },
    });
    console.log(constructedUrl); // 'https://www.example.com/products?category=electronics'
    
    ```
    
3. **Normalizar una URL**:
Puedes utilizar la función **`url.resolve()`** para normalizar una URL resolviendo cualquier relativo que pueda contener. Por ejemplo:
    
    ```jsx
    
    const baseUrl = 'https://www.example.com';
    const relativePath = '/products/123';
    const resolvedUrl = url.resolve(baseUrl, relativePath);
    console.log(resolvedUrl); // 'https://www.example.com/products/123'
    
    ```
    

Estos son solo algunos ejemplos de cómo puedes utilizar el módulo **`url`** en Node.js. El módulo **`url`** proporciona varias otras funciones y propiedades útiles para trabajar con URLs, como **`url.parse()`** y **`url.format()`**. Consulta la documentación oficial de Node.js para obtener más información sobre el módulo **`url`** y sus funcionalidades.
</details>

<details>
<summary><b>Routing en Node.js</b></summary>

El enrutamiento (routing) en Node.js se refiere al proceso de determinar cómo responder a una solicitud HTTP en función de la ruta y el método de la solicitud. Es una parte fundamental de la creación de aplicaciones web en Node.js, ya que permite definir diferentes acciones o controladores según la URL y el verbo HTTP utilizados.

Existen varias bibliotecas y marcos de trabajo en Node.js que facilitan el enrutamiento, como Express.js, Koa.js, Hapi.js, entre otros. Estas bibliotecas proporcionan funcionalidades para definir rutas y manejar solicitudes HTTP de manera fácil y eficiente.

Aquí tienes un ejemplo básico de enrutamiento utilizando el marco de trabajo Express.js:

```jsx

const express = require('express');
const app = express();

// Definir una ruta GET
app.get('/', (req, res) => {
  res.send('¡Hola, mundo!');
});

// Definir una ruta POST
app.post('/productos', (req, res) => {
  res.send('Producto creado');
});

// Definir una ruta dinámica
app.get('/usuarios/:id', (req, res) => {
  const userId = req.params.id;
  res.send(`Usuario ${userId}`);
});

// Escuchar en un puerto específico
app.listen(3000, () => {
  console.log('El servidor está escuchando en el puerto 3000');
});

```

En este ejemplo, estamos utilizando Express.js para definir diferentes rutas y manejar las solicitudes correspondientes. Utilizamos **`app.get()`** para definir una ruta GET para la URL raíz ("/"), **`app.post()`** para definir una ruta POST para "/productos" y **`app.get()`** para definir una ruta dinámica para "/usuarios/:id", donde ":id" es un parámetro dinámico.

Dentro de las funciones de controlador, utilizamos **`req`** y **`res`** para acceder a la solicitud entrante y enviar la respuesta correspondiente. Por ejemplo, **`req.params`** nos permite acceder a los parámetros dinámicos en una ruta.

El enrutamiento permite definir una lógica específica para diferentes rutas y métodos HTTP en una aplicación web. Puedes manejar la autenticación, la validación de datos, el acceso a bases de datos y otras operaciones según las necesidades de tu aplicación.

Recuerda que el enrutamiento puede ser mucho más complejo dependiendo de la aplicación y los requisitos específicos. Las bibliotecas y marcos de trabajo como Express.js brindan una amplia gama de funcionalidades adicionales para facilitar la gestión de rutas y solicitudes HTTP en Node.js.
</details>

<details>
<summary><b>Nodemon</b></summary>
    
Nodemon es una herramienta muy útil en el desarrollo de aplicaciones Node.js. Es un paquete de Node.js que supervisa los cambios en los archivos de tu proyecto y automáticamente reinicia el servidor cuando se detectan cambios, lo que te permite ahorrar tiempo y mejorar tu flujo de desarrollo.

Cuando estás desarrollando una aplicación Node.js, normalmente tienes que reiniciar manualmente el servidor cada vez que realizas cambios en tus archivos de código. Esto puede ser tedioso y consumir tiempo, especialmente cuando tienes que reiniciar el servidor con frecuencia durante el desarrollo.

Nodemon soluciona este problema al supervisar los archivos de tu proyecto y reiniciar automáticamente el servidor cuando detecta cambios. Esto te permite ahorrar tiempo y evitar la necesidad de reiniciar manualmente el servidor después de cada cambio.

Para utilizar Nodemon, primero debes instalarlo globalmente o como una dependencia de desarrollo en tu proyecto. Puedes instalar Nodemon ejecutando el siguiente comando en tu línea de comandos:

```bash
npm install -g nodemon

```

Una vez que Nodemon está instalado, puedes utilizarlo para ejecutar tu archivo de entrada (por ejemplo, **`app.js`**) en lugar de usar el comando **`node`**. En lugar de ejecutar **`node app.js`**, ejecuta:

```bash
nodemon app.js

```

Cuando Nodemon esté en ejecución, supervisará los archivos de tu proyecto y, si se detectan cambios, reiniciará automáticamente el servidor. Esto te permite realizar cambios en tu código y ver los resultados sin tener que reiniciar manualmente el servidor.

Nodemon también proporciona opciones adicionales que puedes utilizar, como ignorar ciertos archivos o directorios, retrasar la reiniciación del servidor después de los cambios y más. Puedes consultar la documentación oficial de Nodemon para obtener más información sobre cómo utilizar estas opciones.

</details>
