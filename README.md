# Batch to EXE Converter with IExpress

This script allows you to easily convert batch files (`.bat`) into executable files (`.exe`) using the built-in IExpress tool in Windows.

## Features

- Drag and drop functionality for quick conversion.
- Automatically cleans up temporary files after creating the executable.
- Simple and efficient, leveraging IExpress.

## How to Use

1. Place your batch file in the same directory as this script, or ensure you can easily locate the script.
2. Drag and drop the `.bat` file onto this script (`bat2exe.bat`).
3. Wait for the conversion to complete. The resulting `.exe` file will be in the same directory as the batch file.

### Example

1. You have a batch file named `example.bat`.
2. Drag `example.bat` onto `bat2exe.bat`.
3. The script creates `example.exe` in the same folder as `example.bat`.

## Notes

- The script creates a temporary `.sed` file to handle IExpress configuration, which is deleted after execution.
- Based on an original script from [CxrveWTF](https://github.com/CxrveWTF/Batch-To-EXE/blob/main/battoexe.bat).

## Requirements

- Windows OS with IExpress installed (most Windows installations include IExpress by default).

## License

This script is provided under an open license. Feel free to use, modify, and distribute it as needed, but attribution to the original author is appreciated.
