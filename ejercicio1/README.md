cd (Me ubico en el directorio qeu quiero)
mkdir ejercicios (crear carpeta)
cd ejercicios (ubicación de la carpeta creada)
code . (Abrir VSCode)
Dentro del VSCode se crea la carpeta ejercicio1
type nul>README.md (crear el archivo README.md)
git config --global user.name "Yanira Bautista" (Configurar nombre globalmente)
git config --global user.email nybautistas@unal.edu.co (Configurar email globalmente)
git config --list (verifica la configuración de usuario y email)
cd ..(me devuelvo a la carpeta ejercicios)
git init (para inicializar el git)
git add .(agrega los archivos a la carpeta ejercicios)
git commit -m "Version Inicial"
Modifiqué algo en el archivo y nuevamente realicé la línea de comando pero con otro nombre
git commit -m "Agrega solución primer ejercicio"
git log --oneline (Lista los commit realizados)
