# CrewAI Project Initialization Boilerplate (Crewai Starter Template)

This repository provides a boilerplate for initializing a new CrewAI project with custom configurations.

**_Note:_**
Running pip install 'crewai[tools]' may sometimes raise unnecessary errors, preventing you from executing the command crewai project project_name, which is intended to create a boilerplate for your project.

This repository is designed to simplify the process of downloading the CrewAI project template and getting started quickly.

To use this template, simply clone this repository and run the initialize.py file. This script will personalize several files according to your project name.

## Getting Started

Follow these instructions to clone the repository and initialize your project.

### Clone the Repository:

```bash
   git clone git@github.com:moe1047/Crewai-Biolerplate.git
```

### Navigate to the cloned directory:

```bash
cd crewai-boilerplate
```

### Run the initialization script:

```python
   python3 initialize.py
```

You will be prompted to enter the CrewAI project name. Provide a suitable name and press Enter.

## What the Script Does

**Step 1**: Running initialize.py Prompts you to enter the project name.

**Step 2**: Formats the project name into `class_name` and `folder_name` variables.

- `class_name`: Capitalizes each word and removes spaces and hyphens.
- `folder_name`: Converts the name to lowercase, replacing spaces and hyphens with underscores.

**Step 3**: Replaces placeholders in all files within the current directory:

- `{{crew_name}}` is replaced with the formatted `class_name`.
- `{{name}}` is replaced with the original project name.
- `{{folder_name}}` is replaced with the formatted `folder_name`.

**Step 4**: Renames the current directory to match the `folder_name`.
