# tmpFile
A module for creating temporary files and folders.

* tmpFile

DESCRIPTION

    Create a tmp file.

USAGE

    from tmpFile import tmpFile

    with tmpFile() as tmpFileName, open(tmpFileName, 'w') as fo:
        ...

    # File: "tmpFileName" will be deleted automatically (if exist)

ARGUMENT

    * ext = '', str
        The extension of the tempfile.

    * path = './', str
        The path of the tempfile.


* tmpFolder

DESCRIPTION

    Create a tmp folder.

USAGE

    from tmpFile import tmpFolder

    with tmpFolder() as tmpFolderPath:
        ...

    # Folder: "tmpFolderPath" will be deleted automatically (if exist)

ARGUMENT

    * path = './', str
        The path of the tmp folder.