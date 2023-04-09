# Resume Wizard Backend API

## Current Routes
127.0.0.1:8080/api/greet/Carson

Prints hello to the name given in path

127.0.0.1:8080/api/AItest

Prints a test poem about a resume wizard demonstrating the AI completion request works

### Build / Deploy instructions
Make sure to have a .env file set with an openAI API key. Check the discord to find the key if you don't have one on hand

The .env file should live in backend/.env with contents

```
export OPENAI_API_KEY="sk-xxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxx"
```

To deploy the api, navigate to the backend directory

```
cd backend/
```

And build / start with the cargo run command

```
cargo run
```

Cargo is a Rust all in one tool for managing projects. Running the backend requires the Rust programming language to be installed on your computer. For instructions on installing Rust and Cargo, checkout the Rust homepage and run their install script.

[Rust Install](https://www.rust-lang.org/tools/install)

```
curl --proto '=https' --tlsv1.2 -sSf https://sh.rustup.rs | sh
```
