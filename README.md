# AzureDevOpsLabs
Resolución de dos laboratorios de Azure DevOps Labs

## Prerrequisitos
Navegar en https://azuredevopsdemogenerator.azurewebsites.net. Este sitio de utilidad automatizará el proceso de creación de un nuevo proyecto de Azure DevOps dentro de su cuenta que está prepoblado con el contenido (elementos de trabajo, repos, etc.) requerido para el laboratorio.
   Es necesario crear una organización para generar el proyecto.
   ![image](https://github.com/bricenojuliana/AzureDevOpsLabs/assets/124324787/1be958b4-5034-40fb-b7a5-09c64949a5ed)
   Damos Click en **Create Project** y esperamos a que se cree el proyecto


## Ejercicio 1: Gestión de Planes de Entrega con Azure DevOps
### Tarea 1: Creación de un plan de entrega

Vamos a Boards / Delivery Plans y damos click en New Plan
  
![image](https://github.com/bricenojuliana/AzureDevOpsLabs/assets/124324787/d30309b2-ddaf-4cb5-b806-f57d93095c84)

Creamos un nuevo **Field criteria** en **Settings**
  
![image](https://github.com/bricenojuliana/AzureDevOpsLabs/assets/124324787/8df19bf3-0553-47e4-8d81-5c45d0b4aed1)

Añadimos un marcador en **Markers** en **Settings**

![image](https://github.com/bricenojuliana/AzureDevOpsLabs/assets/124324787/c43e13c8-3625-43e6-aa54-9a5aa901564d)

![image](https://github.com/bricenojuliana/AzureDevOpsLabs/assets/124324787/ac14768f-8940-4a7a-ae77-beeb18092baa)

Tambien podemos hacer zoom in y zoom out de los Sprint

![image](https://github.com/bricenojuliana/AzureDevOpsLabs/assets/124324787/1c509d85-67f2-405d-b18b-d64f965d11c8)

### Tarea 2: Añadiendo un equipo externo al proyecto

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

### Tarea 3: Tomar decisiones de entrega

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

### Tarea 4: Realizar un seguimiento de las dependencias mediante el uso de planes de entrega (Delivery Plans)

Movemos brandig feature al Sprint 1

![image](https://github.com/bricenojuliana/AzureDevOpsLabs/assets/124324787/60da1fd7-a521-4333-916e-740ddee58bbe)

![image](https://github.com/bricenojuliana/AzureDevOpsLabs/assets/124324787/ffc6dab9-ad7b-4b23-8fa5-ee068ce1c4bc)

Damos click en la pantalla de enlaces y añadimos como Sucesores las tareas que creamos

![image](https://github.com/bricenojuliana/AzureDevOpsLabs/assets/124324787/8f09e943-f00e-437c-a32f-81f09b283e73)

Guardamos y ahora podemos ver lo que está enlazado dando click en las dependencias de cada tarea

![image](https://github.com/bricenojuliana/AzureDevOpsLabs/assets/124324787/dbc2d70d-9249-4bc2-963b-24f18c2644b6)
