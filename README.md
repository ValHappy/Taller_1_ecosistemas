# Ecosistemas Taller_1

# UML Taller 1: Servidor en eclipse

## Main
+ **Main(String[]):** Ejecuta la aplicación
+ **Setup() : void :** Establece las variables al iniciar el codigo
+ **Settings() :** void : Configura del lienzo
+ **Draw() : void :** Pinta los graficos del juego

## Logica
+ **Logica(PApplet app):** Constructor de la Logica
+ **Pintar() : void:** Pintar los graficos del juego
+ **Mover() : void:** Movimiento del personajes
+ **Getters and Setters

## Jugador
+ **Jugador(int x, int y, String rutaImagen):** Constructor del personaje, con parametros X, Y e imagen
+ **Pintar() : void:** Pinta el personaje en cada vista
+ **Mover() : void:** Movimiento del jugador
+ **Getters and Setters

## Bala
+ **Bala(int x, int y, String rutaImagen):** Constructor de la bala del personaje, con parametros X, Y e imagen
+ **Pintar() : void:** Pinta la bala al activarla
+ **Getters and Setters

## Recuerdo
+ **Recuerdo(PApplet app):** Constructor del objeto a recoger
+ **pintar() : void:** Pinta el objeto recuerdo

## Tiempo
+ **Tiempo(PApplet app):** Constructor del contador de tiempo
+ **Getters and Setters

## Enemigo
+ **Enemigo(int x, int y, String rutaImagen):** Constructor del enemigo, con parametros X, Y e imagen
+ **Pintar() : void:** Pinta el enemigo en cada vista
+ **Getters and Setters

## Servidor
+ **Servidor(PApplet app):** Constructor del servidor
+ **Run() : void:** Inicia el Hilo
+ **Enviar() : void:** Envia informacion al cliente en Android

## Receptor
+ **Receptor(Socket s):** Constructor del receptor con parametro socket
+ **Run() : void:** Inicia al hilo

# UML Taller 1: Cliente en Android

## ActivityMain
+ **onCreate(Bundle):** Ejecuta la aplicación
+ **atacar() : void:** Botones del movimiento del personaje

## Cliente
+ **Cliente (MainActivity activity):** Constructor del cliente, parametro activity
+ **Run () : Void:** Inicia el hilo del receptor
+ **Enviar () : Void:** Envia la información 

## Receptor
+ **Receptor(Socket socket):** Constructor del receptor, parametro socket
+ **Run() : void:** Inicia el hilo del receptor

