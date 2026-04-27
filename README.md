# **Cat Prime Detector \- Pixel Art Edition 🐱🎮**

¡Bienvenido a **Cat Prime Detector**\! Esta es una aplicación web retro inspirada en la estética de los videojuegos de 8 bits (NES/GameBoy). Su función principal es determinar si un número ingresado por el usuario es **primo** o no, utilizando un algoritmo optimizado y feedback visual mediante un simpático gatito negro en pixel art.

## **✨ Características**

* **Estética Pixel Art:** Diseño visual consistente utilizando la fuente "Press Start 2P" y gráficos generados puramente con CSS (box-shadow), sin necesidad de imágenes externas.  
* **Feedback Emocional:** \- Si el número es **primo**, aparece un gatito feliz que salta con alegría.  
  * Si el número **no es primo**, el gatito aparece triste y con lágrimas.  
* **Sonido 8-bit:** Generación de audio en tiempo real mediante la *Web Audio API* para emitir sonidos retro de "victoria" o "error".  
* **Algoritmo Eficiente:** Implementa una verificación de primalidad optimizada (![][image1]) que permite procesar números grandes rápidamente.  
* **Diseño Responsivo:** Adaptado para funcionar en navegadores de escritorio y dispositivos móviles.

## **🛠️ Tecnologías Utilizadas**

* **HTML5:** Estructura semántica del aplicativo.  
* **Tailwind CSS:** Para el diseño base y utilidades de espaciado.  
* **CSS3 (Custom):** \- Técnicas de box-shadow para dibujar los sprites del gato.  
  * Animaciones de 8 bits (@keyframes).  
* **JavaScript (Vanilla):** \- Lógica matemática de primalidad.  
  * Manipulación del DOM.  
  * **Web Audio API** para la síntesis de sonidos retro.

## **🚀 Instalación y Uso**

Al ser un proyecto de un solo archivo, no requiere dependencias externas pesadas.

1. Descarga el archivo verificador\_primos.html.  
2. Ábrelo en cualquier navegador moderno (Chrome, Firefox, Edge, Safari).  
3. Ingresa un número en el campo de texto y presiona el botón **VERIFICAR** o la tecla **Enter**.

## **🧠 ¿Cómo funciona la lógica?**

El detector utiliza una optimización matemática que descarta rápidamente múltiplos de 2 y 3, y luego solo verifica posibles divisores hasta la raíz cuadrada del número ingresado (![][image2]), reduciendo drásticamente el tiempo de procesamiento.

*Desarrollado con ❤️ para los amantes de los gatos y el código retro.*

[image1]: <data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAADYAAAAkCAYAAADCW8lNAAADW0lEQVR4Xu2W2U8TURTG+5+UAmEtsoQlRKSyliVAU5YAskmoqFEWQYgQhSjVishiFBVBKoVKLCZiXACXsCiYmBhf9M0HjWs0Gvfl5dhzcMZ2bgpUaOI08/BrMt+998z9puece2WjC7/AHZEJBXdBMiY2JGNiQzJmy8jcN+iffM3o/xOMsaPmh1BR3wlNXeMwNP3RbuzM9RegDA4HuVwOPr4BYL77gwnoDM3dlxnNWXrHn0C9YZTReWOmmc8Ql5oH2uIaaOubhpKdelBrypgFSFBIJCRmbGJ0Z4lPz2e0lXBs7DHtL1qVSh9ZrSll5vDGNEVVkF1axw+gSbmHB5y98dZuwemrzyjYloZuJpizxKXkMtpKaDfdh136EegYeQCeXt6OjdUeGKLN4pfgBlqOT1BKChc0tFtorsG4wIw5y0Z1DqM5y5LG0rIrwNdfScLgzXdLNgb8V728fWB49gs9Y50dGpxfco0jXG5sXWgUhEfHQVm1gVIyWpUCsUkaa7N4ySwIiYiB+LTF2sBGk5RZDDll9RAVk8TMXQ6XGsPNY2p5KBRQ22Yi8fz8T0jL0UHk+kS7znfqylOaiymKqVi4dR8Mz32FwKAwCLUaFgbnwHpIz6tk8FeGMBqyueYwE8MRDo11X3hEm8UJ5jvf+YHq/UbSW05M8hpXX7nlDdaXt9MH4OZiIQuDc5hmPkH/xCsGzAqhhhhvvWdiOAL3nZxVwugyDISbDYtS2Q1wJvJ1TbyGKadQeIJfQBClrG2z+RfWKhWxHIS6DFMND1thjTQeGSNjeeWNvBYWGQsJ6QV05mlLasHHLxDwHxcGXSkuNYY/Gfnb6NC1HeCOgD2dl+i579pzetb9Ob+wceBzY8dFSkk0Kgy+HGtmLKOI0cmYfmCODmM8+LiBrMIdEJOQydcRGkQjBuM9eu6xLNamvn+Wbiq63V1M8OVYrTFsXApPL1Cps+n+ajvG3zy2N5+kzoYdSZWspcLusfytIdTxnmgbINnajTYkZkGKthzO3f7AvJijqnWATAjBs1OoIQWVe5kYtrT2TlFZKIMjqIwQ7MzYJ/Acxjl2l2C85NYdNNNC7p/iwI0PTL1hXoJXrNVehl0Bc7t3FyRjYkMyJjYkY2JDMiY2JGNiQzImNtzW2G97M8n9VUthnwAAAABJRU5ErkJggg==>

[image2]: <data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAABwAAAAkCAYAAACaJFpUAAACkUlEQVR4XmNYcfzXf3piBnQBWuNRC6mOh5aF0zbe/Z9Y0EESpshCr5DU//kN8/83zthHNCbbwklrb/y3dvLFECeEybYwLLnif/v84xjihDBZFs7c+vi/i18shjgxmCwLY7Ia/jfN3I8hTgwm2cJ5u1//t7T3+r/82E8U8bZ5R//3rbgE509df/t/w7Rd/+fveYOijmQLk4u7/1f2b0QRSyub+D8wJv+/vILC/+K2Zf/DUyr/R6bV/M+onPJfRU3jf8usA+RZuOjAx//OPtEovgOJgbIHiK2jb/JfWUX1f8cCRGKycvD67xueAeeTZGF27cz/VX0bUMS6Fp/+Xz1hEzAhPfovLy8PDIEeFHkdfdP/fpFZcD7cwsUHP/33AbokvWIyhkUgDPKVnWsghjgMl3evAVvYs/QcXGzi6qtgsYKmhagWztjy8L+tiz8wONT+65tYYxgGwiVty/8XNC7AEIfhkISS/+qaOv+XHfkOFwP5VkFR8f/s7c9QLayfsgMY7if+R2c2gF1U1LoUxTCQ7xw8wjBSJjI2MrP77x6QgCJmauUMjPMoMDsyvfb/nJ0vUONw2sZ7/+Xk5P5b2LmjaKzq3/Q/t34uhiUwPGvbE7BDs2pmwMVA2QEsVj0dnEW8Q9PA4hiJxj86F6ywZc5hMB/kK/SUiY4bp+8BJ//J626iiHsEJgKjKuC/vXswOFFhtbB32QWwhe5AxSB+NdB3mVVTMSxBxksPfwMHF7o4CIPSx5LDX+F8DAtB2NEzHGzp1A13/9u7BYPzGroacjFWC+uBRRLIQhNLx/8ppX0Y8pRgrBaCsJmN638NLT1g5L/FkKME47SwesJmcBmJLk4pxmkhrfCohVTHoxZSHY9aSHUMANLM0kB9d46XAAAAAElFTkSuQmCC>