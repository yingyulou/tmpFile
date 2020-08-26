# tmpFile

A module for creating temporary files and folders.

## tmpFile

### Description

Create a tmp file.

### Usage

``` Python
from tmpFile import tmpFile

with tmpFile() as tmpFileName:
    with open(tmpFileName, 'w') as fo:
        ...

# File: "tmpFileName" will be deleted automatically (if exist)
```

### Argument

#### 1. ext = '', str

The extension of the tempfile.

#### 2. path = './', str

The path of the tempfile.

## tmpFolder

### Description

Create a tmp folder.

### Usage

``` Python
from tmpFile import tmpFolder

with tmpFolder() as tmpFolderPath:
    ...

# Folder: "tmpFolderPath" will be deleted automatically (if exist)
```

### Argument

#### 1. path = './', str

The path of the tmp folder.
