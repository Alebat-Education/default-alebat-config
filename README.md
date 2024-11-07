# Default Alebat Config

Este paquete proporciona configuraciones estándar de linters y formateadores de código para proyectos JavaScript/TypeScript. Su objetivo es facilitar la configuración de herramientas de calidad de código en proyectos nuevos y asegurar consistencia en el estilo y en las prácticas de codificación.

## Instalación

Instala el paquete desde NPM ejecutando el siguiente comando:

```bash
npm install --save-dev @alebat/default-alebat-config
```

## Configuración Incluida

Este paquete incluye configuraciones para las siguientes herramientas:

- **ESLint**: Linter para JavaScript y TypeScript.
- **Prettier**: Formateador de código.
- **Stylelint**: Linter para CSS, SCSS, y otros archivos de estilos.
- **Commitlint**: Enforcea convenciones de mensajes de commit.
- **EditorConfig**: Configuración estándar para editores de texto.

### Archivos de Configuración

<!-- - `.eslintrc.js`: Configuración para ESLint.
- `.prettierrc`: Configuración para Prettier.
- `.stylelintrc.js`: Configuración para Stylelint. -->

- `commitlint.config.ts`: Configuración para Commitlint.
<!-- - `.editorconfig`: Configuración para asegurar consistencia en los editores de texto. -->

## Uso

<!-- 1. **ESLint**

   Para ejecutar ESLint en tu proyecto, añade un script en tu `package.json`:

   ```json
   "scripts": {
     "lint:js": "eslint 'src/**/*.{js,ts}'"
   }
   ```

   Luego ejecuta:

   ```bash
   npm run lint:js
   ```

2. **Prettier**

   Para formatear tu código con Prettier, añade el siguiente script:

   ```json
   "scripts": {
     "format": "prettier --write 'src/**/*.{js,ts,css,scss,md}'"
   }
   ```

   Luego ejecuta:

   ```bash
   npm run format
   ```

3. **Stylelint**

   Si estás usando CSS o SCSS, ejecuta Stylelint con el siguiente script:

   ```json
   "scripts": {
     "lint:css": "stylelint 'src/**/*.{css,scss}'"
   }
   ```

   Luego ejecuta:

   ```bash
   npm run lint:css
   ``` -->

## Integración con VS Code

Para que estas configuraciones funcionen automáticamente en Visual Studio Code, se recomienda instalar las siguientes extensiones:

- **ESLint**: Para ejecutar ESLint en tus archivos mientras editas.
- **Prettier - Code formatter**: Para formateo automático al guardar.
- **Stylelint**: Para detectar errores de estilo en archivos CSS y SCSS.

Puedes añadir las configuraciones en `.vscode/settings.json` para aplicar formateo al guardar:

```json
{
  "editor.formatOnSave": true,
  "editor.codeActionsOnSave": {
    "source.fixAll.eslint": true,
    "source.fixAll.stylelint": true
  },
  "prettier.requireConfig": true
}
```

## Contribuidores

<table>
<tr>
    <td align="center" style="word-wrap: break-word; width: 150.0; height: 150.0">
        <a href=https://github.com/RodriAsime>
            <img src=https://avatars.githubusercontent.com/u/131388988?v=4 width="100;"  style="border-radius:50%;align-items:center;justify-content:center;overflow:hidden;padding-top:10px" alt=Miguel Ángel Durán/>
            <br />
            <sub style="font-size:14px"><b>Rodrigo Herranz</b></sub>
        </a>
    </td>
    <td align="center" style="word-wrap: break-word; width: 150.0; height: 150.0">
        <a href=https://github.com/BorjaCuerva>
            <img src=https://avatars.githubusercontent.com/u/77273470?v=4 width="100;"  style="border-radius:50%;align-items:center;justify-content:center;overflow:hidden;padding-top:10px" alt=Luciano Fernández/>
            <br />
            <sub style="font-size:14px"><b>Borja Cuerva</b></sub>
        </a>
    </td>
</tr>
</table>
