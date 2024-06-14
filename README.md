# Automatic File Sorter

Automatic File Sorter is a Python script designed to organize your files into respective folders based on their file types. This script moves files with specified extensions into pre-defined directories, making your file system more organized and easier to navigate.

## Features

- Automatically creates folders for different file types.
- Moves files into respective folders based on their extensions.
- Supports sorting of Excel files, image files, and text files.
- Simple and easy-to-use script with minimal configuration.

## Requirements

- Python 3.x
- `os` and `shutil` libraries (standard in Python)

## Setup

1. Clone the repository to your local machine:
    ```sh
    git clone https://github.com/your-username/automatic-file-sorter.git
    ```
2. Navigate to the project directory:
    ```sh
    cd automatic-file-sorter
    ```
3. Update the `path` variable in the script to the directory you want to organize:
    ```python
    path = r"E:/Downloads/file sorter//"
    ```

## Usage

1. Run the script:
    ```sh
    python automatic_file_sorter.py
    ```

The script will:
- Create directories for Excel files, image files, and text files if they do not already exist.
- Move `.xlsx` files to the `excel files` folder.
- Move `.png` files to the `image files` folder.
- Move `.txt` files to the `text files` folder.
- Notify if there are files that do not match the specified extensions.

## Contributing

Contributions are welcome! Please fork the repository and submit a pull request.

1. Fork the repository.
2. Create a new branch:
    ```sh
    git checkout -b feature-branch
    ```
3. Commit your changes:
    ```sh
    git commit -m 'Add some feature'
    ```
4. Push to the branch:
    ```sh
    git push origin feature-branch
    ```
5. Open a pull request.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

## Contact

For any questions or feedback, feel free to reach out to [tanmoy.tanvir001@gmail.com].
