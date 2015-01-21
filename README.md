# Inevio-Texts-File
Description of the file format for Inevio Texts

## Structure of the file
The file is a JSON object splited in 3 parts:

### Info
Indicates the file is an Inevio Text File name and the format version. **Important:** the attribute `description` must be declared with the value `"Inevio Texts File"` to build a valid file.

Example:
```json
"info": {
  "description": "Inevio Texts File",
  "generator": "Inevio Texts",
  "unrecognised" : true,
  "version": "1.1"
}
```

Mandatory attributes:
* `description`: musts be declared with the value `"Inevio Texts File"` to build a valid file.
* `version`: the current version is `"1.1"`.

Optional attributes:
* `generator`:
* `unrecognised`:
