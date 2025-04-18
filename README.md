# HTTPrune

A modular, extensible HTTP server and client built using **modern C++**.


## Installation

### 1. Install CMake (if not already installed)

```bash
# macOS
brew install cmake

# Ubuntu/Debian
sudo apt install cmake
```

### 2. Build the Project

Switch to the root of the project and run:

```bash
./scripts/build.sh
```

This will create a `build/` directory and compile the project using CMake.


### 3. Run the Server

```bash
./scripts/run_server.sh    # Starts the server (default: port 4221)
```

### 4. Test in Browser

Once the server is running, open your browser and navigate to:

```bash
http://localhost:4221/
```

You should see:

```bash
Hello, world!
```

That means your server is accepting HTTP connections and serving responses successfully!
