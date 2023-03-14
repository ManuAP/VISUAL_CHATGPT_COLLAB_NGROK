<!DOCTYPE html>
<html>
<body>
  <h1>Visual ChatGPT en Google Colab con Ngrok</h1>

<p>Este repositorio contiene un ejemplo de cómo implementar Visual ChatGPT con Google Colab y ngrok. Visual ChatGPT es un modelo de generación de texto de lenguaje natural que utiliza tanto imágenes como texto como entrada para producir una respuesta coherente y relevante.</p>

<h2>Requisitos</h2>

<p>Para ejecutar el código de Visual ChatGPT en Google Colab, se necesitan los siguientes requisitos:</p>

<ul>
	<li>Un entorno de Google Colab (disponible de forma gratuita)</li>
	<li>Una cuenta de ngrok (disponible de forma gratuita)</li>
</ul>

<h2>Uso</h2>

<ol>
	<li>Clonar este repositorio en su entorno de Google Colab. Para ello, abra Google Colab y cree un nuevo cuaderno. Luego, ejecute la siguiente celda para clonar el repositorio:</li>
</ol>

<code>!git clone https://github.com/ManuAP/VISUAL_CHATGPT_COLLAB_NGROK.git</code>

<ol start="2">
	<li>Instalar las dependencias necesarias. Ejecute la siguiente celda para instalar las dependencias:</li>
</ol>

<code>LA PRIMERA INSTRUCCIÓN DEL CUADERNO INSTALARÁ LAS DEPENDENCIAS NECESARIAS</code>

<ol start="3">
	<li>Ejecutar el código de Visual ChatGPT. Abra el archivo Visual_ChatGPT.ipynb y ejecute cada celda secuencialmente. La última celda iniciará el servidor local de Visual ChatGPT.</li>
	<li>Ejecutar ngrok. Para exponer el servidor local de Visual ChatGPT a Internet, ejecutaremos la siguiente celda:</li>
</ol>

<code>!ngrok http 7868</code>

<ol start="5">
	<li>Para acceder a la interfaz de usuario. Una vez que se ejecute la celda anterior, copie la dirección generada en Ngrok y péguela en su navegador web. Se abrirá la interfaz de usuario de Visual ChatGPT y podrá comenzar a interactuar con el modelo.</li>
</ol>

<h2>Contribución</h2>

<p>Si desea contribuir a este repositorio, no dude en enviar una solicitud de extracción o informar cualquier problema a través de la sección de problemas.</p>
</body>
</html>
