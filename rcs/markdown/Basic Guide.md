# 📝 Guía rápida de Markdown

Markdown es un lenguaje de marcado ligero que se utiliza para **formatear texto** en GitHub, README, wikis y documentación interna.

Esta guía está pensada para **nuevos usuarios** que quieran aprender lo básico de Markdown y cómo usar enlaces, listas, imágenes y código.

---

## 1️⃣ Encabezados

Usa `#` para los títulos:

```markdown
# Título 1
## Título 2
### Título 3
```

Se verán así:

# Título 1
## Título 2
### Título 3



# 2️⃣ Texto básico

```markdown
**Negrita**
*Itálica*
~~Tachado~~
```

Se verán así:

**Negrita**

*Itálica*

~~Tachado~~

# 3️⃣ Listas
Listas con viñetas

```markdown
- Item 1
- Item 2
  - Subitem 2.1
    - Subsubitem 2.1.1
```
Se verán así:

- Item 1
- Item 2
  - Subitem 2.1
    - Subsubitem 2.1.1



Listas numeradas


```markdown
1. Paso uno
2. Paso dos
3. Paso tres
```






# 4️⃣ Enlaces
## Enlaces simples

```markdown
[Texto del enlace](https://www.ejemplo.com)
```
Resultado:

[Texto del enlace](https://www.ejemplo.com)


## Texto del enlace


```markdown
Enlaces a archivos en el repositorio
[Manual PDF](docs/manual.pdf)
```
Resultado:
[Manual PDF](docs/manual.pdf)


**Notas:** Se debe usar la ruta relativa al archivo en el repositorio.




## Enlaces con imágenes

```markdown
![Texto alternativo](ruta/a/la-imagen.png)
```
Resultado:
![All](https://images.pexels.com/photos/1303835/pexels-photo-1303835.jpeg)

Se puede centrar usando HTML:
```
<p align="center">
  <img src="ruta/a/la-imagen.png" height="200">
</p>
```

<p align="center">
  <img src="https://images.pexels.com/photos/34075960/pexels-photo-34075960.jpeg" height="200">
</p>

## 5️⃣ Código

En línea: `código` → código

Bloques de código:


```markdown
    ```python
    print("Hola mundo")
    ```

```

 ```python
    print("Hola mundo")
```

## 6️⃣ Consejos para nuevos usuarios

Siempre previsualiza tu README en GitHub antes de subir cambios.

Usa rutas relativas para archivos y enlaces internos.

Para imágenes grandes, sube a un repo de recursos interno o a un hosting confiable.

Markdown es sencillo: empieza con lo básico y ve agregando tablas, listas y enlaces conforme necesites.

Si quieres, puedo hacer una versión aún más resumida y visual, lista para pegar en tu repositorio como “Guía rápida para nuevos colaboradores”, con ejemplos prácticos de enlaces, imágenes y listas que ellos puedan copiar directamente.

[Generador de Tablas](https://www.tablesgenerator.com/markdown_tables)

| Heramienta | Version |   |   |   |
|------------|---------|---|---|---|
|            |         |   |   |   |
|            |         |   |   |   |
|            |         |   |   |   |
