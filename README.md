Este proyecto usa [Tailwind CSS](https://tailwindcss.com/) 

## Instalación


1.  **Instala Tailwind CSS**
    ``` bash
    npm install -D tailwindcss
    ```

2.  **Genera el archivo de configuración**

    ``` bash
    npx tailwindcss init
    ```

3.  **Crea el archivo CSS de entrada** ( `input.css`)

 @import "tailwindcss";


4.  **Compila Tailwind con CLI**

    ``` bash 
    npx tailwindcss -i ./dist/input.css -o ./public/assets/css/output.css --watch
    ```

5.  **direccion `output.css`** :

    ``` html
    <link href="assets/css/output.css" rel="stylesheet">
    ```

