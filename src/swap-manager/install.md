# Installation

To install **Swap Manager**, follow these steps:

## Building the application

1. **Clone the Project**  
   The project is hosted at [https://github.com/eypozax/swap-manager](https://github.com/eypozax/swap-manager). The core files are located in the `swap_core` directory.

    ```
    git clone https://github.com/eypozax/swap-manager.git
    cd swap-manager/swap_core
        ```

For a full guide on cloning repositories, see the [Cloning tutorial](../gg/clone.md).

2. **Build the Project**
   Swap Manager is written in Rust. To build it on your device, follow the [Rust building tutorial](../gg/build.md#rust-programming-language).

   Example:

   ```
   cargo build
   ```

   After building, the executable will be in `target/debug/` (or `target/release/` for a release build).

3. **Run Swap Manager**
   Once built, you can run the application:

   ```
   ./target/debug/swap-manager
   ```

### Notes

* Ensure Rust is installed before attempting to build.
* For a fully optimized version, use the release build:

    ```
    cargo build --release
    ./target/release/swap-manager
    ```


## Installing

After building your Rust application, you can install it system-wide by moving the compiled executable to `/usr/local/bin/`. This allows you to run the app from anywhere in your terminal.

```
# Replace 'path/to/app' with the actual path to your compiled executable
# Requires sudo privileges
sudo cp path/to/app /usr/local/bin/
```

### Notes

* Make sure the executable has proper permissions to run:

    ```
    sudo chmod +x /usr/local/bin/app
    ```

* Once installed, you can run the application from any location by simply typing its name in the terminal:

    ```
    app
    ```