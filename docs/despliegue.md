# Despliegue

Pasos para pasar del código fuente a tener la API funcionando:

1. **Acceder al directorio:** `cd api-productos-a14`
2. **Instalar dependencias:** `npm install`
3. **Iniciar la aplicación:** `npm start`

* Comprobando el funcionamiento:
curl http://localhost:3000/api/productos

## Checklist
- [ ] No se han incluido contraseñas ni secretos en el repositorio
- [ ] Los posibles ficheros con secretos están incluidos en .gitignore
- [ ] En producción debería utilizarse HTTPS
- [ ] Solo deberían exponerse los puertos necesarios