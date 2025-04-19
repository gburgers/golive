# GoLive

GoLive is a lightweight, automated build and deployment tool designed to streamline your Go development workflow. It watches for changes in `.go` and `.templ` files, automatically rebuilding the app and restarting the server. With built-in templ generation and smooth server lifecycle management, GoLive ensures your Go application is always up-to-date and running.

### Features

- **Live reloading**: Automatically rebuilds and restarts your Go application when code changes are detected.
- **Automatic build**: Detects changes in Go and templ files, rebuilding the app on the fly.
- **Server management**: Gracefully starts, stops, and restarts the server.
- **Templ integration**: Automatically generates and builds templ files as part of the process, seamlessly compiling templates before rebuilding your Go code.
- **Process management**: Handles server termination and restart gracefully.
- **Minimal configuration**: Works out of the box with standard Go project structures.
- **File watching**: Continuously watches for file changes, keeping the development loop smooth and efficient.
- **Developer-friendly**: Simple interface with clear status messages about build success or failure.

### Perfect for:

Go developers looking to simplify and accelerate their development process, especially those working with the [templ](https://github.com/templ-lang/templ) templating engine. GoLive helps you automate building, running, and reloading your Go app, allowing you to focus more on coding and less on setup and maintenance.

---

### Installation

git clone https://github.com/gburgers/golive.git

cd golive  
chmod +x golive # Ensure it's executable  
sudo cp golive /usr/local/bin/ # Optional: install system-wide

### Usage

Make sure the golive binary is in your $PATH and run 'golive' in the root of your Go project.
