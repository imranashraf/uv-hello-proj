# UV
An extremely fast Python package and project manager, written in Rust. `uv` is a recent answer to managing envrionments for python based developments. Claims to be fast and less space hungry.

    `uv` isn’t just another package manager, it’s a statement that Python packaging can actually work properly.


## Install uv
    curl -LsSf https://astral.sh/uv/install.sh | sh

Exit and open a new tab/window to have uv in path

## setup a project
    mkdir myproj
    cd myproj
    uv init .




# RUFF
An extremely fast Python linter and code formatter, written in Rust.

## Install Ruff globally.
    uv tool install ruff@latest

## Or add Ruff to your project.
    uv  add --dev ruff

## Check for errors and code smells
    uv run ruff check .

## Automatically fix what can be fixed (like unused imports)
    uv run ruff check --fix .

## Format your code (like Black)
   uv run ruff format .
