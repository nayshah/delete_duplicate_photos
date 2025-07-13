A Python script that detects and deletes exact duplicate photos based on file content (using SHA256 hash). 
This ensures that even if the filenames are different but the images are identical, they will be flagged as duplicates.

Features
- Detects duplicate images by comparing actual file content (not just filenames)
- Supports JPG, PNG, GIF, BMP, TIFF, and JPEG formats
- Works recursively through folders
- Option to review and confirm deletion before files are removed

How to Use
- Copy or download this script.
- Set your folder path in the script:
    folder_to_scan = r'YOUR\FOLDER\PATH\HERE'
