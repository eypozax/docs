# Installation

To install **PyPipPark**, follow these steps:

## Building

-  **Clone the Project**  
   The project is hosted at [https://github.com/eypozax/pypippark](https://github.com/eypozax/pypippark). The core files are located in the `q_generate` directory.  

    ```
    git clone https://github.com/eypozax/pypippark.git
    cd pypippark```

For a full guide on cloning repositories, see the [Cloning tutorial](../gg/clone.md).

-  **Build the Project**
   PyPipPark is written in Rust. To build it on your device, follow the [Rust building tutorial](../gg/build.md#rust-programming-language).

   Example:

   ```
   cargo build
   ```

   After building, the executable will be in `target/debug/` (or `target/release/` for a release build).

3. **Run PyPipPark**
   Once built, you can run the core application:

    ```
    ./target/debug/pypippark
    ```

### Notes

* Make sure you have Rust installed on your system before building.
* You can use the release build for optimized performance:

    ```
    cargo build --release
    ./target/release/pypippark
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