# Full Stack Rust Template

Ok, so you're crazy enough to want to build a whole ass web application in Rust. But you have no idea how to build a full stack application with a Frontend and a Backend connected to a Postgres instance. This is a template that will help you quickly write full stack Rust applications without bothering with the boilerplate code.

## Stack

- Rust (of course)
- WASM (to run Rust in the browser)
- Yew (Frontend Rust framework)
- Trunk (WASM Bundler)
- Tailwind
- Rocket (Backend Rust framework)
- Postgres
- Docker

## How to use

- Clone the repository and cd into it
- `docker compose up`
- cd into the backend folder, make necessary changes and run `cargo run` to test the backend. This should start a local server on port 8000
- cd into the frontend folder, make necessary changes, run 'cargo build --target wasm32-unknown-unknown' to build the frontend and then run 'trunk serve' to serve the frontend on port 8080
- Write more code, test it, and repeat
