# AlgUI

Algorithm visualization service built with Go, Rust, and SvelteKit.

## Project Structure

```
AlgUI/
├── api/                    # Protocol Buffers definitions
├── services/
│   ├── storage/           # Rust storage service
│   ├── visualizer/        # Go visualization service
│   └── web/              # SvelteKit frontend
├── deployments/           # Deployment configurations
└── build.zig             # Zig build system
```

## Development

1. Install required tools:
   ```bash
   make setup
   ```

2. Build all services:
   ```bash
   zig build
   ```

3. Run development environment:
   ```bash
   zig build dev
   ```
