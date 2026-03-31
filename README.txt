
# CRM Prospectos Sync

Esta app ya está conectada a tu Supabase y está pensada para PC y celular con la misma URL.

## Qué hace
- Login con email + contraseña
- Usuarios separados
- Leads / Prospectos sincronizados
- Agenda inteligente
- Tareas manuales y por gestión
- Coach diario que se reinicia cada día
- Consejos que rotan cada 30 minutos
- Importar / exportar Excel
- Vista responsive para escritorio y móvil

## Cómo probarla localmente
Abrí `index.html` con doble clic.
Para login, primero registrate con tu email.

## Cómo publicarla gratis
1. Creá un repositorio en GitHub
2. Subí estos archivos
3. En Vercel elegí "Add New Project"
4. Importá el repo
5. Deploy

## Importante
- Usa tu Supabase real:
  https://yvvhsvajvkyxqkbowedp.supabase.co
- La publishable key ya está cargada en `app.js`
- La `service_role` NO va en el frontend

## Nota sobre Auth
Si al registrarte te pide confirmar email y no querés eso para probar:
Supabase → Authentication → Providers → Email → desactivar "Confirm email"


Correcciones:
- Crear/editar/borrar leads y tareas refresca al instante.
- Las tareas muestran vencimiento.
- Recordatorios por notificación para tareas que vencen hoy o están vencidas.
