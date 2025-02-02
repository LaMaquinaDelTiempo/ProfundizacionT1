## Para iniciar el proyecto
Instalación (npm install)
Ejecución (npm run dev)

### **`<Link>`**  
Componente para navegación **sin recargar la página** (client-side). Permite transiciones fluidas entre rutas manteniendo el estado de la aplicación.

---

### **`loader`**  
Función **del lado del servidor** que carga datos específicos para una ruta antes de renderizarla. Centraliza la lógica de fetching y asegura que los datos estén disponibles al cargar el componente.

---

### **Rutas Dinámicas**  
Definidas con parámetros variables (ej: `$id` o `$slug`). Permiten crear URLs adaptables que capturan valores de la ruta para personalizar contenido o consultas.

---

### **Rutas Anidadas**  
Estructura jerárquica donde rutas hijas heredan la interfaz de su padre (como layouts compartidos). Organiza rutas relacionadas bajo una misma URL base (`/padre/hija`).

---

### **`<Outlet/>`**  
Componente que **renderiza el contenido de las rutas hijas** en rutas anidadas. Actúa como marcador de posición dentro del componente padre para mostrar la UI específica de cada hijo.

---

**Relación Clave:**  
- Los `loaders` alimentan datos a las rutas.  
- Las rutas dinámicas y anidadas estructuran URLs complejas.  
- `<Link>` y `<Outlet/>` gestionan la navegación y composición de UI.  
