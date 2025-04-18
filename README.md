![C#](https://img.shields.io/badge/Language-C%23-blue)

# Password Manager

A simple and secure password manager built using **C#** and **.NET Core**. This console-based application allows users to securely store, view, search, and delete passwords. The program stores the passwords locally in a text file.

## Features:
- **Add Password:** Store new passwords securely.
- **View Passwords:** View all stored passwords.
- **Search Password:** Find a specific password by name or login.
- **Delete Password:** Remove a password from storage.
- **Backup & Exit:** Automatically saves all passwords when exiting.

## Technologies Used:
- **Programming Language:** C#
- **Framework:** .NET Core
- **Storage:** Local text file

## Installation:

To use the Password Manager, follow these steps:

1. Clone this repository:
    ```bash
    git clone https://github.com/MiniExe1/Password-Manager.git
    ```

2. Open the solution file (`PasswordManager.sln`) in **Visual Studio** or use the **.NET CLI** to build and run the project:
    ```bash
    dotnet build
    dotnet run
    ```

3. Alternatively, you can build it using the IDE or directly using the `.csproj` file.

## How to Use:
- Launch the application, and you'll see the main menu with the following options:
    1. **Add Password:** Adds a new password to the storage.
    2. **View Passwords:** Displays all stored passwords.
    3. **Search Password:** Search for a password by its name or login.
    4. **Delete Password:** Deletes a password from the storage.
    5. **Exit:** Exits the program and saves all passwords.

When adding a password, the program asks for the **name**, **login**, and **password**. All data is stored in a local text file (`passwords.txt`).

## Contributing:
Feel free to contribute to this project. Fork it, create an issue, or submit a pull request.

### Steps for contributing:
1. Fork the repository.
2. Create a new branch for your feature or fix.
3. Commit your changes.
4. Push your branch to GitHub.
5. Submit a pull request.

## License:
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
