# .rel File Debugger
Tool for parsing the .rel file format and displaying the data in a human readable format.

Usage: `py rel_reader.py <rel file> [--options]`

Extra options:
* `--hideops`: will hide the assumed opcode mnemonics in the code output section, instead displaying the raw hex value
* `--ws`: shows whitespace lines where there is no code in the code output section. Inserts an empty line instead of skipping lines.
* `--header`: will display only the header information for the `.rel` file

## Requirements: 
* Python 3.6 or higher

If you are having issues with `py` opening up the Windows Store, make sure to turn off the python app execution alias in `Settings > Apps > Apps & Features > App Execution Aliases`.
