# ASS to SRT Converter

This Colab Notebook provides a simple Python script to convert subtitles from the ASS format to the SRT format using the [pysubs2](https://pysubs2.readthedocs.io/en/latest/) library.
<br>

## Features

- Converts subtitle files from `.ass` format to `.srt` format.
- Simple and efficient implementation.
- Automatically handles encoding as `utf-8` for accurate processing.
<br>

## Usage

1. **Upload your `.ass` file** to the Colab environment.
2. **Edit the paths** in the script:
   - Replace `subtitle.ass` with the path to your `.ass` file.
   - Replace `subtitle.srt` with your desired output `.srt` file name.
3. **Run the Notebook** to perform the conversion.
<br>

## Function Details

### `convert_ass_to_srt(input_file, output_file)`

Converts an ASS subtitle file to SRT format.

#### Parameters:
- `input_file` (str): Path to the input `.ass` file.
- `output_file` (str): Path to save the converted `.srt` file.

#### Example Output:
```plaintext
Conversion successful! File saved as: subtitle.srt
```

## Error Handling

If an error occurs during conversion, it will display a message in the following format:

```plaintext
An error occurred during conversion: [Error details]
```
