# **🕷️ La Arañita del Laberinto \- Arcade Edition 🏁**

¡Bienvenido a **Arañita Arcade**, un juego web de acción y rompecabezas retro desarrollado íntegramente en JavaScript del lado del cliente\! Guía a una carismática arañita a través de complicados laberintos procedimentales, recolecta llaves para abrir compuertas de seguridad y usa habilidades explosivas antes de que se agote el tiempo.

Este juego combina la nostalgia de los clásicos de consola con físicas fluidas de deslizamiento de píxeles y un algoritmo inteligente que garantiza la resolución segura de cada mapa sin posibilidad de bloqueos indeseados (*softlocks*).

## **🚀 Características Principales**

* **20 Niveles de Dificultad Progresiva:** El tamaño y la complejidad del laberinto aumentan dinámicamente. El Nivel 1 comienza con una cómoda rejilla de ![][image1], mientras que el Nivel 20 te desafiará con un laberinto colosal de ![][image2] pasadizos.  
* **Estética Neón Retro:** Cada uno de los 20 niveles cuenta con su propio esquema de colores de luces neón para dar una sensación arcade única.  
* **Movimiento Ultra Fluido:** La araña no se mueve rígidamente cuadro por cuadro; se desliza pixel a pixel de forma continua y se apoya suavemente en los bordes de los muros.  
* **Habilidad de Bomba:** Cada jugador dispone de **una bomba por nivel** para destruir muros en un radio circular de 50 píxeles, permitiendo crear atajos estratégicos. (¡Los límites externos del laberinto son indestructibles\!).  
* **Efectos de Sonido Integrados:** El juego genera música y sonidos de forma sintetizada (pasos, recolección de llaves, explosiones y alertas) directamente usando la API de audio nativa de tu navegador, sin necesidad de descargas externas.  
* **Modos de Juego Adaptativos:** Soporte completo para partidas en solitario o duelos versus de forma local.

## **🎮 Modos de Juego y Reglas**

Al iniciar el juego, se te presentará un menú interactivo para elegir el modo que prefieras:

### **1️⃣ Modo 1 Jugador (Aventura)**

* **Tu Objetivo:** Debes explorar el laberinto para encontrar las **2 llaves doradas (🔑)** que abren las **2 compuertas cerradas (🔒)**. Una vez abiertas, ábrete paso hasta la bandera de meta (**🏁**) en la esquina inferior derecha.  
* **Límite de Tiempo:** Tienes **2 minutos (120 segundos)** por nivel. Si el tiempo expira, el nivel se reiniciará con una distribución de laberinto totalmente diferente pero con la misma dificultad.

### **2️⃣ Modo 2 Jugadores (Versus Local)**

* **Tu Objetivo:** Una auténtica carrera de velocidad y reflejos. Ambos jugadores aparecen al inicio y deben competir para ver quién llega primero a la meta (**🏁**).  
* **Mecánica de Llaves Cooperativa/Competitiva:** El mapa genera **1 sola puerta** bloqueando la bandera final y **2 llaves** en rincones lejanos. Cualquiera de los dos jugadores puede recoger las llaves. En cuanto el marcador colectivo sume 2 llaves, la compuerta se abrirá para ambos y comenzará el sprint final hacia la victoria.  
* **Puntuación:** Quien toque la meta primero se lleva el punto del nivel. Al terminar los 20 niveles, se coronará al gran campeón de la partida.

## **⌨️ Esquema de Controles**

### **🟣 Jugador 1 (Arañita Morada)**

* **Moverse:** Flechas de dirección (![][image3]) del teclado. *(Nota: En modo de 1 jugador, también se puede usar WASD de forma indiferente).*  
* **Soltar Bomba:** Barra Espaciadora (Space).

### **🟢 Jugador 2 (Arañita Verde \- Solo en modo Versus)**

* **Moverse:** Teclas **W** (Arriba), **S** (Abajo), **A** (Izquierda) y **D** (Derecha).  
* **Soltar Bomba:** Tecla **Q**.

## **💡 Consejos de Supervivencia Aracnofílica**

1. **Usa la bomba estratégicamente:** Solo tienes una oportunidad de demolición por nivel. Guárdala para cuando estés realmente perdido, para abrir un atajo directo a una llave lejana o para ganarle el paso a tu oponente en los últimos segundos.  
2. **Deslízate por las esquinas:** Al mantener presionadas dos direcciones en diagonal, la araña se deslizará fluidamente por el contorno de las paredes. Esto es vital en los niveles más densos para no perder valiosos segundos.  
3. **No temas al reinicio:** Si el tiempo se agota, el nuevo laberinto generado de forma procedimental podría ofrecerte una ruta más óptima que la anterior. ¡Mantén la calma y concéntrate\!

[image1]: <data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAAEIAAAAZCAYAAACFHfjcAAABc0lEQVR4Xu2WO0oEYRCEJ/AIRgPzwtwDiIEaGAkGioE3UFEUvMGm3sPAS6ihiKCRgkYqIoKBgoHJWj3+A00x7DzYnqg/aHanuv+a2t4HG0WO4zgdyLLsOM/zHdaJGcz9sjg0U8+KwVMZRo1D7fKMAP1ezYy5PwSDZZ1kXoH+Vy/zKWOa1cq8KIp51jRN96zDKmuJlTnmH1ALrAvQz/FdX2e9CausJZbmOPOIF7yktTRNL6BvaK0tllkr8z3WNb3No/LsE2pZnmMpl1jEFs+0xTSrHEK4fdY1vc0DYRnXqG3udcE0azA/YF3T2zyAszeyDPyArnKvC6ZZ5RA+soesa3qbR/9LQPhNeY773OF6hWfaYpo1mB+xrulrrpdQIcvgH9C2mGWN43hWDqFOuKdB/6erOQJfYQlrrAvwukVvkfVJmGTF4BnqA/WCeg6P7xn9R8f1N+otzEi9oj6TJJnTc3U0vevwGbFWxxBZHcdxHMdxuvAH3Ya95+Y7ik4AAAAASUVORK5CYII=>

[image2]: <data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAAEIAAAAZCAYAAACFHfjcAAACBElEQVR4Xu2Wv0tcQRDHTwyks7O9dycHSor8ARJCksJKsFAsrK1S5QciIUKKmMbSRqxEsdFCwc5C8Ecn4cSQJpBAqsQURxq5EFHPzxzzZJnbe+8U12o/MOzud747N8x7PC0UIpFIJIdSqfSaWCsWi4/0PJAkySrrK493nVyD+I9/2uZDE7RXjLN6wY0jj69RqVR63DNx5npCE7RXpvUB0zwTXGadQeq2nnK5/FSL7aQa+7+iket3vSEJ2qsUJJ5b3fBAi8+lAvu6aO7k20EDj63mQp2XVvMRtFcM7zso3oL+WMPqPvB9IwatLqDv8oRHrO4jaK808Q7TJzHy6i3JirZofQ4y8a/EJfsum2wH/u/UfeZq/N4e+qirZRG0V0xvKLpttAbx0dVUn8C7wPqHBrZsPg/u/Uj0iXJ/n1rj1pPFffbaRItnvkrkT9STPWmDDuOzNGpzt+Eue21Jcumig+JvtYnfNpcF/qoMgw/okM11QLhe1VDzaNfF2a8Q566H1+6J9eWBt8q9Mdnzun7h/MJ6sgjaqxqmPJpbvHl2P3acJ1X/lWpZJM4QUmQY9gOaRdBeSdb5+9qbnqWAXHL/+eC8SRykZ9VOxcfdh67ug5qHDGHY6gI1juWJWd1H8F4x1cSYBo31eTwbmv+p67/cwkreU088X/12hO41EolEIpFI5CZcAZlnBnaAvI3MAAAAAElFTkSuQmCC>

[image3]: <data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAAGAAAAAZCAYAAADOtSsxAAACUElEQVR4Xu2YvWsUQRjG4xcWCvGD44z3sXfH+dFfQBDUPoX+AYGIvVqKKLHRQoiK6YQUQUxhZyfY2ATT2VgIVtYiCCGJVRL9LezI+nA3O3tzuUwxP3jZ2+ede+bdeXf2lpuYiEQikXBot9tV1Tw5qELEQpIkf1TzAb8nqkUGwGK10wbUarXTmhuWVqv1VLXIAFj83bQBo9wFeC2oFhHq9XrXLHr+yN175v+R5cHnmWq+UNf9Ue7SUVGtVo9xvfOqW8kWejF/bj43m807vruB7z9XzRffmvYS79q8DQT8XqjmAzfLNTxvqx4K1PaAuKy6MyE3oNFonKUBX1QPDa7519Cv86E2AJ8V4jdNmB4m1M8V9XENat3kEb6sfoUE3ICPWQOuDxPq54r6uAa1btCAD+pXSKgNSOHxcxG/NdVDgxo/8WZ5TnUnbA1IX0uJm6rbKGoAd8kj1Www/42yNfSDee9xOKy6L/jOcc0zqjtja0Cay/KHNGcgv8ACvc6d/2sAxXU438rl3mWe743mgq1GF6jjbjbvhuZ88a3NakDuIfGVBb6luTy9Xu8I437wJnDBNIDjKt97mR/HNj2F/tM2Zz8YP88inlS9DHh8J7ZV96HT6Uzi+Vj1UhQtBvkZFvKS6v1g7BoL9ZZ4RTOuat7AuHXVxkHRte4LRUWR/6aajdSP+Ky6gbvmPPlZ1feabrd7lHmXVN93bA3g9epKUvK/Dsa/YcecUN1Afle1ccC8O6oFAY+KRDUDRU+p5sDAH+yMAyqMg0qlcly1SCQSiUTGyV/tNaFMZ38M5wAAAABJRU5ErkJggg==>