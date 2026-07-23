# PROCESO DE CREACIÓN REPOSITORIO REMOTO
A continuación se enlista una serie de paso a paso con los cuales podras generar un repositorio remoto

## Paso 1
Lo primero que debes realizar es cerciorarte si tu usuario e email estan vinculados mediante los comandos  
 - **Git config --list**: El cual te desplegara una serie de información donde veras que usuario y email estan vinculados.

  ### EN CASO DE QUE NO ESTE VINCULADA TU CUENTA:
 - **Git config --global user.name "INSERTE USUARIO"** Con este comando cambiaras el usuario
 - **Git config --global user.email "INSERTE CORREO"** Con este comando cambiaras el email.

 ## Paso 2 
 Considerando de que ya tengas una cuenta en github, ingresaras a ella y desde el *dashboard* crearas un nuevo repositorio (idealmente con el mismo nombre del repositorio local).    
 Lo configuras y luego ingresas en tu consola de git bash para realizar los siguientes comandos en ella:  
 1.  **git remote add origin "INSERTE LINK DE VINCULACIÓN"**: Mediante este comando vincularas ambos repositorios, *recuerda que el link de vinculación lo puedes encontrar en la pagina de tu repositorio.*

### ¡NOTA IMPORTANTE!

Recuerda tener tus commits al dia para realizar el siguiente paso.

### Paso 3
Ahora vamos a subir nuestros archivos al repositorio remoto de la siguiente manera ya que es la primera vez que lo hacemos:  
- **git push -u origin main** Este comando se usa cuando vamos a subir archivos por primera vez.  

**Felicidades, ya vinculaste tu cuenta por primera vez**

## Recuerda para tu flujo diario

Cuando te encuentres trabajando local y quieras exportar tus avances, usa el siguiente comando **git push**  
Cuando vayas a iniciar a trabajar en tu espacio locar, recuerda usar el comando **Git pull** para sincronizarte con tus cambios previos en caso tal.  

<img width="667" height="306" alt="image" src="https://github.com/user-attachments/assets/9248894f-f6e4-4268-a2cb-72fea8bd2a31" />
