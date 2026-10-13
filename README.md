# rod
npx @angular/cli@22.2.2 new ea7753u202420031 --directory . --skip-git --routing --style css --ssr=false
pwd                    # Ver en qué carpeta estás
ls                     # Ver archivos y carpetas
cd .\nombre-carpeta     # Entrar a una carpeta
cd ..                  # Subir una carpeta
gh auth login          # Iniciar sesión
gh auth logout
gh auth status         # Comprobar la sesión
git config --global user.name "Tu nombre"
git config --global user.email "Tu correo de GitHub"
git clone https://github.com/usuario/repositorio.git
cd .\repositorio
git status                                  # Ver cambios
git diff                                    # Revisar cambios sin preparar
git add .                                   # Preparar todos los cambios
git diff --staged                            # Revisar lo preparado
git commit -m "feat(fleet): add overview"     # Guardar un commit local
git push                                    # Subir los commits a GitHub
npm install              # Instalar dependencias
npm start                # Iniciar Angular
npm run build            # Compilar y generar dist
npm test                 # Ejecutar las pruebas configuradas
npx ng version           # Ver la versión de Angular
npx ng generate component fleet/presentation/views/fleet-overview
npx ng generate service fleet/infrastructure/fleet-api
