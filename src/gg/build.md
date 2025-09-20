# Build

This page provides brief tutorials on how to build an app directly on your device.

## Rust Programming Language

To build a Rust project on your device:

1. **Install Rust**  
   Make sure Rust is installed on your system. You can follow the official guide here: [Rust Installation](https://www.rust-lang.org/tools/install)

2. **Navigate to the project directory**  
   Open your terminal and move to the folder containing the project:

    ```cd path/to/the/project```

3. **Build the project**
   Run the following command to compile the project:

    ```cargo build```

   This will build the project in **debug mode**. The compiled executable will be located at:

   ```
   target/debug/[APPLICATION_NAME]
   ```

### Optional: Build in Release Mode

For a fully optimized build suitable for production, use:

```
cargo build --release
```

The release build will be placed in:

```
target/release/[APPLICATION_NAME]
```

### Notes

* The debug build is faster to compile and useful during development.
* The release build is optimized for performance and smaller binary size.
* Make sure to replace `[APPLICATION_NAME]` with the actual name of the Rust project.