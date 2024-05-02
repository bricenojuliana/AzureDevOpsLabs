# AzureDevOpsLabs
Resolución de dos laboratorios de Azure DevOps Labs

## Building a roadmap and tracking dependencies across teams with Delivery Plans

### Prerrequisitos
Navegar en https://azuredevopsdemogenerator.azurewebsites.net. Este sitio de utilidad automatizará el proceso de creación de un nuevo proyecto de Azure DevOps dentro de su cuenta que está prepoblado con el contenido (elementos de trabajo, repos, etc.) requerido para el laboratorio.
   Es necesario crear una organización para generar el proyecto.
   ![image](https://github.com/bricenojuliana/AzureDevOpsLabs/assets/124324787/1be958b4-5034-40fb-b7a5-09c64949a5ed)
   Damos Click en **Create Project** y esperamos a que se cree el proyecto


### Ejercicio 1: Gestión de Planes de Entrega con Azure DevOps
#### Tarea 1: Creación de un plan de entrega

Vamos a Boards / Delivery Plans y damos click en New Plan
  
![image](https://github.com/bricenojuliana/AzureDevOpsLabs/assets/124324787/d30309b2-ddaf-4cb5-b806-f57d93095c84)

Creamos un nuevo **Field criteria** en **Settings**
  
![image](https://github.com/bricenojuliana/AzureDevOpsLabs/assets/124324787/8df19bf3-0553-47e4-8d81-5c45d0b4aed1)

Añadimos un marcador en **Markers** en **Settings**

![image](https://github.com/bricenojuliana/AzureDevOpsLabs/assets/124324787/c43e13c8-3625-43e6-aa54-9a5aa901564d)

![image](https://github.com/bricenojuliana/AzureDevOpsLabs/assets/124324787/ac14768f-8940-4a7a-ae77-beeb18092baa)

Tambien podemos hacer zoom in y zoom out de los Sprint

![image](https://github.com/bricenojuliana/AzureDevOpsLabs/assets/124324787/1c509d85-67f2-405d-b18b-d64f965d11c8)

#### Tarea 2: Añadiendo un equipo externo al proyecto

Vamos a **Project Settings** en **Teams**

![image](https://github.com/bricenojuliana/AzureDevOpsLabs/assets/124324787/f12530f1-2379-45a0-a0a5-36b8a94f569b)

Damos click en **New  Team** y creamos un nuevo equipo

![image](https://github.com/bricenojuliana/AzureDevOpsLabs/assets/124324787/581009e6-7bfb-46b8-a927-1a06894f7586)

Ahora vamos a **Boards/Project Configuration**, donde vamos a agregar dos nuevas iteraciones para el equipo de servicios externos que no se alinean exactamente con el cronograma del equipo principal.

![image](https://github.com/bricenojuliana/AzureDevOpsLabs/assets/124324787/5878be97-19ed-4448-8f16-0bd17f9a170e)

Damos click en **New child** con el nombre del proyecto seleccionado y creamos una nueva iteración

![image](https://github.com/bricenojuliana/AzureDevOpsLabs/assets/124324787/37b1bca8-bc60-4a0b-ba58-2cb8fe749ce5)

Hacemos el mismo proceso para crear una iteración 51 que empieza después de que iteración 50 acabe.

![image](https://github.com/bricenojuliana/AzureDevOpsLabs/assets/124324787/9875fd98-bcee-48c6-92f0-8a41e2ae33eb)

Ahora vamos a **Teams** y seleccionamos el nombre del equipo creado

![image](https://github.com/bricenojuliana/AzureDevOpsLabs/assets/124324787/2eed81c3-1e07-44e8-b302-a62267ecf54b)

![image](https://github.com/bricenojuliana/AzureDevOpsLabs/assets/124324787/8bc9db43-177f-4fbe-8e43-e13bbdca8afd)

Damos click en **Iterations and Area Paths** y damos click en la pestaña de iteraciones

![image](https://github.com/bricenojuliana/AzureDevOpsLabs/assets/124324787/b5eea5ff-84a6-410f-b8cd-6817460d4a57)

Le asignamos al equipo las iteraciones creadas con *Select iteration(s)*

![image](https://github.com/bricenojuliana/AzureDevOpsLabs/assets/124324787/549f7246-7a38-44bc-8cdb-a61bf3d1b220)

#### Tarea 3: Tomar decisiones de entrega

Vamos a **Boards/Delivery Plans**

![image](https://github.com/bricenojuliana/AzureDevOpsLabs/assets/124324787/1b2bc8b3-fd1c-4e62-9e08-e45b34ac9b5c)

Seleccionamos Web delivery plan y vamos a **Settings**

![image](https://github.com/bricenojuliana/AzureDevOpsLabs/assets/124324787/e09dd74e-39e3-47a5-b0e6-0dc9f7931c8a)

Vamos a **Teams** y añadimos un nuevo equipo

![image](https://github.com/bricenojuliana/AzureDevOpsLabs/assets/124324787/fc42a464-c6a3-4670-ba0a-290d67bb814e)

Sleccionamos el equipo externo de integración

![image](https://github.com/bricenojuliana/AzureDevOpsLabs/assets/124324787/c6ab1b9f-a692-422e-880f-e3e4565084bb)

Con zoom out podemos ver las iteraciones del equipo externo

![image](https://github.com/bricenojuliana/AzureDevOpsLabs/assets/124324787/8d6a499f-f14e-4bf7-9bab-e9b703111f35)

Como aún no tienen tareas asignadas, en la iteración 50 damos click en el **+** y ponemos el nombre de la tarea

![image](https://github.com/bricenojuliana/AzureDevOpsLabs/assets/124324787/e350741d-61b8-4e6d-9daf-bb899bf16b0c)

Ahora hacemos lo mismo con iteración 51

![image](https://github.com/bricenojuliana/AzureDevOpsLabs/assets/124324787/d11e21f3-2321-45e4-bf52-958acdf33fd0)

Podemos arrastrar y cambiar de Sprint / Iteración las tareas

![image](https://github.com/bricenojuliana/AzureDevOpsLabs/assets/124324787/46bb7a5d-5d1f-4136-9ba0-9e1c766ab5eb)

Podemos expandir o comprimir la vista de las tareas

![image](https://github.com/bricenojuliana/AzureDevOpsLabs/assets/124324787/200c0e96-2829-41f4-83ba-202013d71e86)

![image](https://github.com/bricenojuliana/AzureDevOpsLabs/assets/124324787/66c16a24-61ea-4d86-980f-ba66414d161d)

#### Tarea 4: Realizar un seguimiento de las dependencias mediante el uso de planes de entrega (Delivery Plans)

Movemos brandig feature al Sprint 1

![image](https://github.com/bricenojuliana/AzureDevOpsLabs/assets/124324787/60da1fd7-a521-4333-916e-740ddee58bbe)

![image](https://github.com/bricenojuliana/AzureDevOpsLabs/assets/124324787/ffc6dab9-ad7b-4b23-8fa5-ee068ce1c4bc)

Damos click en la pantalla de enlaces y añadimos como Sucesores las tareas que creamos

![image](https://github.com/bricenojuliana/AzureDevOpsLabs/assets/124324787/8f09e943-f00e-437c-a32f-81f09b283e73)

Guardamos y ahora podemos ver lo que está enlazado dando click en las dependencias de cada tarea

![image](https://github.com/bricenojuliana/AzureDevOpsLabs/assets/124324787/dbc2d70d-9249-4bc2-963b-24f18c2644b6)

## Version Controlling with Git in Visual Studio Code and Azure DevOps

### Prerrequisitos
- Visual Studio Code con la extensin de C# instalada.
  
  ![image](https://github.com/bricenojuliana/AzureDevOpsLabs/assets/124324787/f8542ae7-d49e-43cd-9535-fbfa22d0380c)

- Git para Windows 2.21.0 o superior.

  ![image](https://github.com/bricenojuliana/AzureDevOpsLabs/assets/124324787/6299d4f1-2d4c-4c96-b482-cac8655ec5ca)

- El proyecto que ya inicializamos en el anterior lab.

### Ejercicio 1: Configurando el entorno del laboratorio

#### Tarea 1: Configurando Visual Studio Code

Abrimos una terminal nueva en VS

![image](https://github.com/bricenojuliana/AzureDevOpsLabs/assets/124324787/f3dbff6b-1fb4-44db-aa79-092eeb4318a4)

Ejecutamos el comando 
```
git config --global credential.helper wincred
```
![image](https://github.com/bricenojuliana/AzureDevOpsLabs/assets/124324787/e851b93d-8d8e-4ec4-8e91-1587f93800ed)

Ahora configuramos las credenciales de github
```
git config --global user.name "Juliana Briceño"
git config --global user.email bricenojuliana@gmail.com
```
![image](https://github.com/bricenojuliana/AzureDevOpsLabs/assets/124324787/e1ffc3f4-b318-4864-a8b7-b80fa9d7c0e4)

### Ejercicio 2: Clonando un repositorio existente

#### Tarea 1: Clonando un repositorio existente

En un navegador buscamos nuestro proyecto en Azure DevOps
![image](https://github.com/bricenojuliana/AzureDevOpsLabs/assets/124324787/19474b2b-b8bf-4e50-9296-2401ee9277d4)

Vamos a **Repos/Clone** para clonar el repositorio
![image](https://github.com/bricenojuliana/AzureDevOpsLabs/assets/124324787/8a16b6c2-a067-4a52-91ce-f00166bbab57)

Copiamos la URL 
![image](https://github.com/bricenojuliana/AzureDevOpsLabs/assets/124324787/062fb595-1792-4667-a7fa-12698bfc217a)

En VS presionamos **Ctrl+Shift+P** para mostrar la **Command Palette**. Ejecutamos el comando **Git: Clone**
![image](https://github.com/bricenojuliana/AzureDevOpsLabs/assets/124324787/7eaf58f6-9129-4af6-b962-191a1f095d3a)

Pegamos la URL
![image](https://github.com/bricenojuliana/AzureDevOpsLabs/assets/124324787/ad71f84c-9eb9-4849-b016-2a17c60e1cf9)

Seleccionamos un directorio para guardar el proyecto localmente
![image](https://github.com/bricenojuliana/AzureDevOpsLabs/assets/124324787/b061c907-cc83-4b2b-89e8-39d46d2dcbec)

Nos logeamos con nuestra cuenta Azure DevOps
![image](https://github.com/bricenojuliana/AzureDevOpsLabs/assets/124324787/5a093827-abda-4d96-8862-565acaba0c9e)

Una vez que se haya clonado, damos click a *Open* para abrir el repositorio clonado.
![image](https://github.com/bricenojuliana/AzureDevOpsLabs/assets/124324787/459fe3e9-a5c8-43fb-8c90-912a31248fc7)

### Ejercicio 3: Guardando el trabajo con commits

#### Tarea 1: Committing changes

Desde el explorador de archivos de VS abrimos **PartsUnlimited-aspnet45\src\PartsUnlimitedWebsite\Models\CartItem.cs**
![image](https://github.com/bricenojuliana/AzureDevOpsLabs/assets/124324787/51ff327c-a5d7-44fb-a6db-a3e672329419)

Añadimos un comentario cualquiera en el archivo
![image](https://github.com/bricenojuliana/AzureDevOpsLabs/assets/124324787/154fb887-2e30-4f78-a8b0-cdf5bdc8bf91)

Abrimos la pestaña de **Source Control** para ver el cambio 
![image](https://github.com/bricenojuliana/AzureDevOpsLabs/assets/124324787/5cd8f7ff-80a7-4171-a6f1-718d252a3278)

Ponemos un mensaje en el commit y presionamos **Ctrl+Enter** para hacer commit localmente

![image](https://github.com/bricenojuliana/AzureDevOpsLabs/assets/124324787/9437d938-7bab-4928-b441-27d249c85f1b)

Le damos click a *Always* si nos aparece este mensaje

![image](https://github.com/bricenojuliana/AzureDevOpsLabs/assets/124324787/bbe59632-5066-4f3a-9740-598d1c5d8807)


Sincronizamos los cambios

![image](https://github.com/bricenojuliana/AzureDevOpsLabs/assets/124324787/fd400802-3ffa-42e3-b3ae-d3774ef39e09)

#### Tarea 2: Revisando commits

Vamos al navegador con el proyecto y vamos a **Repos/Commits** para ver los commits hechos, el commit más reciente está en la parte superior de el diagrama
![image](https://github.com/bricenojuliana/AzureDevOpsLabs/assets/124324787/5d1b9633-0ca3-4eac-8ddf-ee7496cf0269)

#### Tarea 3: Staging changes

Volvamos a VS. Vamos a modificar el comentario que habíamos hecho
![image](https://github.com/bricenojuliana/AzureDevOpsLabs/assets/124324787/dd5f44cc-05af-43f6-b76c-b1224fbf537f)

Abrimos **Category.cs** tambien
![image](https://github.com/bricenojuliana/AzureDevOpsLabs/assets/124324787/82fe6643-3c0c-4a69-b404-d3bdb0af6e35)

Añadimos un nuevo comentario, para que haya dos archivos con cambios
![image](https://github.com/bricenojuliana/AzureDevOpsLabs/assets/124324787/6d12fd8f-0664-469d-b91b-dfcb0fd659f2)

Desde **Source Control** damos click al **+** para hacer **Stage Changes** pero solo de **CartItem.cs.**
![image](https://github.com/bricenojuliana/AzureDevOpsLabs/assets/124324787/70abe17d-22e7-41d6-bee0-b8d3224bd93a)

Vamos a hacer commit sin **Category.cs**
![image](https://github.com/bricenojuliana/AzureDevOpsLabs/assets/124324787/256d0ecf-c8b0-4543-8590-b183db23bd0b)

Ponemos un comentario al commit y desde **More actions** seleccionamos **Commit Staged**
![image](https://github.com/bricenojuliana/AzureDevOpsLabs/assets/124324787/f1d96ce6-96a5-4009-ab7d-ba4ce31d3730)

Sincronizamos cambios

![image](https://github.com/bricenojuliana/AzureDevOpsLabs/assets/124324787/0a3315f8-d82f-4c77-94f9-597b248f931d)

### Ejercicio 4: Revisando historial

#### Tarea 1: Comparando archivos

Desde **Source control** seleccionamos **Category.cs** 

![image](https://github.com/bricenojuliana/AzureDevOpsLabs/assets/124324787/aa70d4c5-08c2-4dfb-93f9-b9b357de14db)

Se nos abre una vista de comparación para saber que cambios se han hecho localmente
![image](https://github.com/bricenojuliana/AzureDevOpsLabs/assets/124324787/c12ce080-4091-4dfb-93f0-c5e0007cf602)

Vamos a la vista de Commits en Azure DevOps para ubicar algunas de las ramas y fusiones de origen. Estos proporcionan una manera conveniente de visualizar cuándo y cómo se realizaron cambios en la fuente.
![image](https://github.com/bricenojuliana/AzureDevOpsLabs/assets/124324787/e218e356-6c68-465c-8b8e-f57c3402a0e8)

### Ejercicio 5: Trabajando con ramas

#### Tarea 1: Creando una nueva rama en el repositorio localmente

Volvemos a VS. Damos click en la rama master abajo a la izquierda

![image](https://github.com/bricenojuliana/AzureDevOpsLabs/assets/124324787/b852d7ec-dca8-4279-8298-044f17531dfb)

Seleccionamos **Create new branch from…**
![image](https://github.com/bricenojuliana/AzureDevOpsLabs/assets/124324787/3bf520cb-fa77-4b01-9549-c22190d2ad4f)

Ponemos el nombre **dev** para la nueva rama y presionamos **Enter**
![image](https://github.com/bricenojuliana/AzureDevOpsLabs/assets/124324787/8568597b-b58e-4e1f-bad2-654e8fa55dfd)

Seleccionamos **master** como la rama de referencia
![image](https://github.com/bricenojuliana/AzureDevOpsLabs/assets/124324787/90947c5b-5fbb-4ec6-85e1-9b44e1dd5213)

Ahora estamos trabajando en la nueva rama

![image](https://github.com/bricenojuliana/AzureDevOpsLabs/assets/124324787/23cc9039-1d04-49db-9767-42f211e90c10)

#### Tarea 2: Trabajando con ramas

Damos click sobre **Publish changes** a lado de la rama

![image](https://github.com/bricenojuliana/AzureDevOpsLabs/assets/124324787/1981a299-cfd9-4e64-bfe5-b78451057348)

Desde el navegador con Azure DevOps seleccionamos **Repos/Branches**. Vamos a ver la nueva rama **dev** 
![image](https://github.com/bricenojuliana/AzureDevOpsLabs/assets/124324787/a46c1758-11e7-421e-b0a6-5d556cda18f3)

Seleccionamos *more actions* y eliminamos la rama
![image](https://github.com/bricenojuliana/AzureDevOpsLabs/assets/124324787/25afdca2-3915-41f7-8a87-f5d3b1551d63)

Volvemos a VS. Damos click en la rama **dev**

![image](https://github.com/bricenojuliana/AzureDevOpsLabs/assets/124324787/d115dc0e-342d-45f4-9c65-70eacbf4b607)

Ahora hay dos ramas **dev**: localmente ya que no se elimina cuando la rama del servidor es eliminada, y la original ya que no ha sido eliminada.
![image](https://github.com/bricenojuliana/AzureDevOpsLabs/assets/124324787/ab436796-2b6d-486e-8d90-75159b037f31)

Seleccionamosla rama master

![image](https://github.com/bricenojuliana/AzureDevOpsLabs/assets/124324787/dda15226-5733-4517-9c2d-c74d477aaa9b)

Presionamos **Ctrl+Shift+P** para abrir **Command Palette**. Ponemos **Git: Delete** y seleccionamos **Git: Delete Branch**
![image](https://github.com/bricenojuliana/AzureDevOpsLabs/assets/124324787/0b9407f5-c451-4631-862e-8a5fb8a9a661)

Seleccionamos **dev**

![image](https://github.com/bricenojuliana/AzureDevOpsLabs/assets/124324787/a8692b82-cfb8-43dc-834d-28c5240af06d)

Damos click en la rama **master**. Vamos que ya no está localmente, pero aun aparece **origin/dev**

![image](https://github.com/bricenojuliana/AzureDevOpsLabs/assets/124324787/96d6764f-10f5-4a3a-8c56-47c92b96795d)

