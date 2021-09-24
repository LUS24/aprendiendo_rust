# Aprendiendo Rust

[Libro](https://doc.rust-lang.org/book/title-page.html)

## Comandos útiles

Muestra la versión de rust

```bash
rustc --version
```

Actualiza rust

```bash
rustup update
```

Muestra la documentación de rust

```bash
rustup doc
```

Compila el program a un .exe

```bash
rustc <nombre_archivo.rc>
```

Crea un nuevo proyecto con cargo

```bash
cargo new <nombre_proyecto>
```

Compila el proyecto en modo debug

El archivo .exe generado se encuentra en `/targets/debug/`

```bash
cargo build
```

Compila el proyecto y mostrar el resultado

```bash
cargo run
```

Verifica que el proyecto compile, es mucho más rápido que compilar el proyecto. 
Es útil correr checks perioricamente para verificar que no haya bugs que impidan
la compilación.

```bash
cargo check
```

Cuando se quiere una versión final se usa

```bash
cargo build --release
```