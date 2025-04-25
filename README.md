
```markdown
# VERCEL, UNA GUÍA PARA CONFIGURAR EL ENTORNO EN LA NUBE

Este documento proporciona una guía detallada para crear una cuenta en la nube pública **Vercel**, así como las diferentes formas de autenticación disponibles y la configuración inicial para desplegar aplicaciones como PokeDex.

---

## 1. Crear una Cuenta en Vercel
Para crear una cuenta en Vercel tiene 6 formas distintas que aparecen en la pagina web: GitHub, GitLab, Bitbucket, SAML SSO, Passkey y con Email.

Para este caso, y recomendado usaremos GitHub:
1. Accede a https://vercel.com
2. Haga clic en "Continue with GitHub"
3. Conecta tu cuenta de GitHub si no lo has hecho aún
4. Autoriza a Vercel a acceder a tus repositorios 
5. Se creará tu cuenta de Vercel con acceso directo a tus proyectos de GitHub

---

## 2. Configurando el Proyecto
Una vez creada la cuenta, podemos empezar a desplegar la aplicación:

### 2.1. Crea un Proyecto
- Desde la ventana de Vercel, navegamos hasta el menú de "Add New.." y luego en "Project"
- Se desplegara la lista de repositorios que tenemos asociados a Github
- Elegimos el repositorio que contiene el proyecto

### 2.2. Configuración de Framework y Comandos
- **Framework Preset**: selecciona el que usas (React, Angular, Next.js, etc.)
- **Build Command**: por lo general es `npm run build`
- **Output Directory**: puede ser `build/`, `dist/` o `out/` según el framework

### 2.3. Desplegar
- Haz clic en **"Deploy"** para iniciar el proceso de construcción y publicación. Puede tomar entre 5 a 10 minutos la primera publicación.

---

## 3. Recomendaciones 
- Usar variables de entorno cuando la aplicación se comunica con APIs externas (`Settings > Environment Variables`)
- Mantener actualizado el repositorio de Git, ya que Vercel hace **despliegue continuo** con cada `git push`
- Considera usar un dominio personalizado si deseas posicionar la URL como marca

¡Con esta guía, tu cuenta en Vercel estará lista!
```

