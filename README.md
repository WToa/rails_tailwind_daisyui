# README

This Rails starter template is pre-configured with [TailwindCSS](https://tailwindcss.com/) and [DaisyUI](https://daisyui.com/). It provides a foundation for UI development using utility-first CSS and a set of customizable components.

## Cloning and Setting Up Your Own Repository

To start a new project based on this repository:

```sh
git clone https://github.com/WToa/rails_tailwind_daisyui.git
# Optionally rename the folder
mv rails_tailwind_daisyui <your-project-folder>
cd <your-project-folder>
git remote remove origin
git remote add origin <your-own-repository-url>
```

Replace `<your-project-folder>` with your desired folder name and `<your-own-repository-url>` with the URL of your own GitHub repository.

After these steps, it's recommended to find and replace all occurrences of `rails_tailwind_daisyui` (the original project name) within the project files with your chosen application name (e.g., `<your-app-name>`). This typically involves searching in files like `config/application.rb` and others where the application name might be referenced. Many code editors have a "Find and Replace in Files" feature that can help with this.
