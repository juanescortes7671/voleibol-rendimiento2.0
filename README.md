# RendimientoVoleibolWinForms

Aplicacion Windows Forms (.NET Framework 4.8) para consultar, buscar, crear y editar registros de la tabla `dbo.RendimientoVoleibol` en SQL Server Express.

## Funciones del frontend

- Inicio redisenado como centro de mando visual con resumen vivo, pulso del equipo, insight automatico y accesos rapidos.
- Navegacion por pestanas: Inicio, Usuario, Listado, Dashboard y Registro.
- Dashboard analitico con KPIs, clasificacion de riesgo, tendencia temporal, ranking inteligente e insights automaticos.
- Asistente IA interactivo mejorado llamado `Volley`, fijo en todos los menus, con informe ejecutivo, prediccion, alertas, plan de entrenamiento y recomendaciones tacticas.
- Busqueda por nombre de jugador o posicion.
- Botones funcionales: Guardar, Cancelar, Limpiar campos, Buscar, Nuevo y Recargar.
- Validacion de campos obligatorios, nombre completo, fecha no futura y rangos numericos.
- Manejo de errores SQL con mensajes mas claros para el usuario.
- Diseno consistente con paleta azul, verde y gris.
- Ventana adaptable con controles acoplados, scroll y reacomodo del formulario en modo compacto.

## Conexion usada

La cadena de conexion esta en:

`RendimientoVoleibolWinForms/App.config`

```xml
Data Source=.\SQLEXPRESS;Initial Catalog=master;Integrated Security=True;TrustServerCertificate=True
```

## Abrir en Visual Studio

1. Abre `RendimientoVoleibolWinForms.sln`.
2. Ejecuta el proyecto con `F5`.
3. La pantalla carga los registros de `dbo.RendimientoVoleibol`.
4. Usa `Listado` para buscar y doble clic sobre una fila para editar.
5. Usa `Dashboard` para revisar KPIs, riesgo, tendencia por fecha, ranking e insights automaticos.
6. Usa el panel fijo `Volley` para pedir informe ejecutivo, prediccion, alertas, ranking, comparacion por posiciones y plan de entrenamiento desde cualquier pantalla.
7. Usa `Registro` para guardar nuevos registros o actualizar uno seleccionado.

## Documentacion adicional

- `docs/TECHNICAL.md`: arquitectura, validaciones, manejo de errores y estructura.
- `docs/DEPLOYMENT.md`: pasos de instalacion, ejecucion y despliegue.
- `docs/AUDITORIA_ETAPA_1.md`: evidencia del avance frente a los criterios de revision.
- `docs/SQL_SCHEMA.sql`: script de referencia para crear la tabla si se necesita recrear.
- `docs/CODIGO_IMPLEMENTADO.md`: resumen del codigo agregado para inicio, usuario, dashboard analitico y Volley.

## Subir a GitHub desde Visual Studio

1. En Visual Studio abre la solucion.
2. Ve a `Git > Create Git Repository`.
3. Inicia sesion en GitHub si Visual Studio lo solicita.
4. Elige el nombre del repositorio.
5. Marca `Private` o `Public`.
6. Presiona `Create and Push`.
