# React + Vite

This template provides a minimal setup to get React working in Vite with HMR and some ESLint rules.

Currently, two official plugins are available:

- [@vitejs/plugin-react](https://github.com/vitejs/vite-plugin-react/blob/main/packages/plugin-react) uses [Babel](https://babeljs.io/) (or [oxc](https://oxc.rs) when used in [rolldown-vite](https://vite.dev/guide/rolldown)) for Fast Refresh
- [@vitejs/plugin-react-swc](https://github.com/vitejs/vite-plugin-react/blob/main/packages/plugin-react-swc) uses [SWC](https://swc.rs/) for Fast Refresh

## React Compiler

The React Compiler is not enabled on this template because of its impact on dev & build performances. To add it, see [this documentation](https://react.dev/learn/react-compiler/installation).

## Expanding the ESLint configuration

If you are developing a production application, we recommend using TypeScript with type-aware lint rules enabled. Check out the [TS template](https://github.com/vitejs/vite/tree/main/packages/create-vite/template-react-ts) for information on how to integrate TypeScript and [`typescript-eslint`](https://typescript-eslint.io) in your project.
## Ejecutar el portafolio (desarrollo)

Instrucciones rápidas para ejecutar el portafolio localmente:

1. Instala dependencias:

```powershell
npm install
```

2. Ejecuta el servidor de desarrollo:

```powershell
npm run dev
```

Nota para usuarios de Windows PowerShell: si al ejecutar `npm` obtienes un error sobre la política de ejecución (por ejemplo: "No se puede cargar el archivo ... npm.ps1 porque la ejecución de scripts está deshabilitada"), puedes:

- Ejecutar PowerShell como Administrador y ejecutar:

```powershell
Set-ExecutionPolicy RemoteSigned
```

- O ejecutar el comando en una terminal diferente (Git Bash, CMD).

Después de iniciar el servidor abre http://localhost:5173 (u otra URL que muestre Vite) para ver el portafolio.

Si quieres, puedo ajustar estilos, añadir tus datos reales (nombre, bio, proyectos) o convertir esto a una app React completa. Dime qué prefieres.
