#INSTALAR GIT
>GitHub le ofrece a los clientes de computadoras de escritorio que
incluye una interfaz gráfica de usuario para las acciones de reposito-
rio más comunes y una edición de línea de comando de actualización
automática de Git para escenarios avanzados.

###GitHub para Windows
https://windows.github.com
###GitHub para Mac
https://mac.github.com

#CONFIGURAR HERRAMIENTA
| Sintaxis                                               | Descripcion                                                                         |
|--------------------------------------------------------|-------------------------------------------------------------------------------------|
| `$ git config --global user.name "[name]"`             | Establece el nombre que desea esté anexado a sus transacciones de commit            |
| `$ git config --global user.email "[email address]"`   | Establece el e-mail que desea esté anexado a sus transacciones de commit            |
| `$ git config --global user.name "[name]"`             | Habilita la útil colorización del producto de la línea de comando                   |

#CREAR REPOSITORIOS
| Sintaxis                            | Descripcion                                                  |
|-------------------------------------|--------------------------------------------------------------|
| `$ git init [project-name]`         | Crea un nuevo repositorio local con el nombre especificado   |
| `$ git clone [url]`                 | Descarga un proyecto y toda su historia de versión           |

#EFECTUAR CAMBIOS
| Sintaxis                                  | Descripcion                                                                                 |
|-------------------------------------------|---------------------------------------------------------------------------------------------|
| `$ git status`                            | Enumera todos los archivos nuevos o modificados que se deben confirmar                      |
| `$ git diff`                              | Muestra las diferencias de archivos que no se han enviado aún al área de espera             |
| `$ git add [file]`                        | Toma una instantánea del archivo para preparar la versión                                   |
| `$ git diff --staged`                     | Muestra las diferencias del archivo entre el área de espera y la última versión del archivo |
| `$ git reset [file]`                      | Mueve el archivo del área de espera, pero preserva su contenido                             |
| `$ git commit -m "[descriptive message]"` | Registra las instantáneas del archivo permanentemente en el historial de versión            |

#CAMBIOS GRUPALES
| Sintaxis                        | Descripcion                                                     |
|---------------------------------|-----------------------------------------------------------------|
| `$ git branch`                  | Enumera todas las ramas en el repositorio actual                |
| `$ git branch [branch-name]`    | Crea una nueva rama                                             |
| `$ git checkout [branch-name]`  | Cambia a la rama especificada y actualiza el directorio activo  |
| `$ git merge [branch]`          | Combina el historial de la rama especificada con la rama actual |
| `$ git branch -d [branch-name]` | Borra la rama especificada                                      |

