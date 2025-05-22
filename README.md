Paso a paso genérico para subir un proyecto a GitHub usando la terminal de Visual Studio Code:
1. Abre la terminal en Visual Studio Code
Ve a "Ver" > "Terminal" o presiona Ctrl + ñ (o `Ctrl + ``).
2. Ubícate en la carpeta raíz de tu proyecto
Usa el comando cd para navegar a la carpeta donde está tu proyecto.
  cd ruta\de\tu\proyecto
3. Inicializa un repositorio Git (si aún no lo hiciste)
  git init
4. Agrega los archivos al área de preparación (staging)
Para agregar todos los archivos:
  git add .
O para agregar un archivo específico:
git add nombre_del_archivo
5. Haz un commit con un mensaje descriptivo
Ejemplo:
  git commit -m "Primer commit"
6. Vincula tu repositorio local con el de GitHub
Copia la URL de tu repositorio (por ejemplo, https://github.com/usuario/repositorio.git) y ejecuta:
git remote add origin https://github.com/usuario/repositorio.git
7. Sube los archivos a GitHub
Si tu rama principal se llama main:
  git push -u origin main
Si se llama master:
  git push -u origin master
