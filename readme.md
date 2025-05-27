# Práctica: Uso de Ramas y Clonado en Git

Esta práctica tiene como objetivo aprender a trabajar con ramas y clonar repositorios utilizando Git.

## Pasos a seguir

1. **Clonar el repositorio**
    ```bash
    git clone <URL-del-repositorio>
    cd <nombre-del-repositorio>
    ```

2. **Crear una nueva rama**
    ```bash
    git checkout -b nombre-de-tu-rama
    ```

3. **Realizar cambios y confirmarlos**
    ```bash
    git add .
    git commit -m "Descripción de los cambios"
    ```

4. **Subir la rama al repositorio remoto**
    ```bash
    git push origin nombre-de-tu-rama
    ```

## Recomendaciones

- Sustituye `<URL-del-repositorio>` y `nombre-de-tu-rama` por los valores correspondientes.
- No olvides hacer `pull` antes de empezar a trabajar para mantener tu copia actualizada.

## Recursos útiles

- [Documentación oficial de Git](https://git-scm.com/doc)
- [Guía de ramas en Git](https://www.atlassian.com/git/tutorials/using-branches)
