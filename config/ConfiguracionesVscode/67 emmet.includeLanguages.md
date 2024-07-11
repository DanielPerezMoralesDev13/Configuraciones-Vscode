<!-- Autor: Daniel Benjamin Perez Morales -->
<!-- GitHub: https://github.com/DanielPerezMoralesDev13 -->
<!-- Correo electrónico: danielperezdev@proton.me -->

# ***emmet.includeLanguages***

```json
{
  "emmet.includeLanguages": {}
}
```

**Descripción:** *Configura los idiomas en los que Emmet debe estar activo para la expansión de abreviaturas. Al agregar entradas específicas a `"emmet.includeLanguages"`, puedes definir en qué tipos de archivos Emmet debería funcionar. Por ejemplo, en aplicaciones React que utilizan JavaScript, puedes configurar `"javascriptreact"` como un valor para activar Emmet. Esto permite que Emmet reconozca y expanda abreviaturas en archivos JavaScript React.*

**Ejemplo de configuración con valores específicos:**

```json
{
  "emmet.includeLanguages": {
    "javascript": "javascriptreact"
  }
}
```

> [!NOTE]
> *Para habilitar Emmet en archivos JavaScript React, se utiliza `"javascriptreact"` como valor dentro de `"emmet.includeLanguages"`.*
