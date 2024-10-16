# 🐍 PyExecGo Project

**PyExecGo** is a small, simple and lightweight solution for running Python scripts on any system **without requiring Python** to be installed. It packages a portable Python version and open-source Go executable to run your Python scripts on the target machine.

This project avoids the common issues with converting or compiling Python scripts into executables, such as **triggering antivirus software**, which can cause users to be wary and potentially lead to losing customers. By keeping the Python script intact and using a minimal Go executable, PyExecGo minimizes these risks and provides a safer, more user-friendly solution.

Another important point is that the original code from developers remains open-source when using PyExecGo. This transparency ensures that you can trust the code, as there’s no risk of tampering. In contrast, using tools like Py2Exe, which "compiles" the code, makes it impossible for you to verify what’s been changed or added.

## 🚀 Features
- **No Python installation required**: PyExecGo includes a portable version of Python.
- **Avoid antivirus flags**: Compiling Python scripts often triggers antivirus alerts, making users hesitant to run your software. PyExecGo helps you bypass this issue.
- **Small and open-source Go executable**: The Go executable is lightweight and open-source, making it easy to audit and trust.
- **Easy to use**: A Go executable handles the execution of your Python script.
- **Retain your code**: No need to compile or convert—your Python code stays as-is.

## 🛠️ How It Works
1. **Portable Python**: A minimal, portable Python version is bundled with the project.
2. **Go Executable**: A small, open-source Go-based executable runs your Python script by leveraging this portable Python environment.
3. **Run Anywhere**: Simply distribute the Go executable along with the portable Python files and the scripts that need to be executed in a folder, allowing hassle-free execution on any machine.

## 📝 Build Your Own Project

### Automatic Builder

We provide an [automatic builder](https://github.com/PyExecGo-Project/PyExecGo-Builder) designed to simplify the setup process. No experience with Go? No problem—you don’t even need to have Go installed! Check out our [Latest Release](https://github.com/PyExecGo-Project/PyExecGo-Builder/releases). We highly recommend using the builder or downloading one of our pre-built Python scripts/programs for a seamless experience.

### Template Repository
We provide a [template repository](https://github.com/PyExecGo-Project/Template-Windows) that includes a detailed README to guide you through the setup process. The steps are clearly outlined, making it easy for you to get started.

## 📦 Pre-built Scripts/Programs
Take a look at our available repositories for pre-built scripts/programs: [PyExecGo Project Repositories](https://github.com/orgs/PyExecGo-Project/repositories) (COMING SOON!)

## 🤝 Contributing
We welcome contributions! Feel free to open issues or submit pull requests to enhance PyExecGo.

## 📄 License
This project is licensed under the MIT License. Check out the [LICENSE](https://github.com/PyExecGo-Project/.github/blob/main/LICENSE) file for details.
