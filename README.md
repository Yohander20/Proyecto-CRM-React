# Proyecto CRM.

La finalidad de este proyecto consiste en crear una aplicación de registro de clientes facilitando la comunicación entre vendedor y cliente
mejor conocido como CRM.

Para este proyecto se uso la biblioteca de javascript React y para los servicios se utilizo una API con la herramienta de json server para simular el backend y hacer los
CRUD.

# Conceptos aprendidos en este proyecto:
 
 **React Router DOM:** es una librería que permite agregar enrutamiento a una aplicación web de React.
 
**-{Outlet}:** para cargar los otros enlaces.

**-Link** :para navegar a otras páginas.

**LinkNav:** con este me da la ubicación actual de la página con una funcion pero no obtenemos los resultados esperados)

**-Hooks Utilizados:**
    
     useLocation: para obtener la ubicación actual de la pagina con el objeto location.path

     useNavigate: para navegar hacia otra pagina.

**-loader:** una forma para agregar state a tu aplicicacion o consultar una API o de un objeto (similar a un state)

**-Action:** para procesar la entrada de datos en un FORM.

**-Request:** es una peticion que estas haciendo hacia un action en un formulario.

**-formData:** para capturar los datos y enviarlos al servidor.

**navigate** se usa cuando tenemos un boton

**redirect** cuando estemos en action y loader

# Cuando Utilizar:

**useLoaderData:** cuando quieres obtener el resultado de un loader.

**useActionData:** cuando quieres obtener el resultado de una acción.

# Conceptos sobre Rest API

**REST=** Representational State Transfer, puede ser diseñada en cualquier lenguaje.

**Debe responder a los Request HTTP:** GET, POST, PUT,PATCH, DELETE

Tiene una forma ordenada y estructurada de poner a disposicion los recursos

**Verbos HTTP:**

GET-Obtener

Post- Enviar Datos al servidor / Creación

PUT / PATCH - Actualizar

Delete - Eliminar

Endpoints de una Rest API

-Una REST API cuenta con endpoints o (Urls) para hacer operaciones CRUD.

-Listar todos los clientes  GET / clientes

-Obtener un solo cliente Get/clientes/10

-Crear un nuevo cliente Post/clientes

-Editar un cliente Put/cliente/3

-Eliminar un cliente Delete/cliente/3

# Control de Errores

**Error Boundaries:** es un componente de react que obtiene los errores en cualquier lugar del componente.

# NOTAS

-Todos los formularios con React Router DOM requieren de un action (función)
