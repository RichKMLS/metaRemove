# metaRemove

This bash script monitors specified directories for file creation events. Upon the detection of a new file, it performs several operations to enhance the privacy and uniformity of file data.

<p align="center">
<img src="https://github.com/RichKMLS/metaRemove/assets/105183376/c7f0f890-860b-4b01-8eca-2d53d07daafd" />
</p>

## Features

- Monitors a specified directory for file creation events in real-time.
- Removes all metadata from the newly created file.
- Renames the original file with the new random filename of 12-20 characters.
- Displays the new metadata of the renamed file.

## Dependencies

This script depends on `inotifywait` for directory monitoring and `exiftool` for metadata manipulation.

## Feedback and support

If you have any issues, suggestions, or questions about this script, please feel free to open an issue.

## Disclaimer

metaRemove is provided "as is" without any warranty of any kind, either expressed or implied. The author is not responsible for any damages or losses that may result from using this script.
