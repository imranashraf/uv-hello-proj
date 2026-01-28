# install uv
curl -LsSf https://astral.sh/uv/install.sh | sh

Exit and open a new tab/window

# setup a project
mkdir myproj
cd myproj
uv init .




# RUFF
A nice tool to be used for code formatting

## Check for errors and code smells
uv run ruff check .

## Automatically fix what can be fixed (like unused imports)
uv run ruff check --fix .

## Format your code (like Black)
uv run ruff format .
