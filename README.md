# Bulk Image Downloader

This script downloads images for a list of boxers using the Google Custom Search API, and then processes the images by cropping them to a square format.

## License

This project is licensed under the Zero-Clause BSD license.

## Requirements

- Python 3.x
- requests
- Pillow

## Setup

### Using a Virtual Environment

It is recommended to use a virtual environment to manage dependencies. Follow these steps to set up the project:

1. **Create a virtual environment:**
   ```bash
   python -m venv venv
   source venv/bin/activate
   pip install requests pillow
   export YOUTUBE_API_KEY=your_api_key_here
   export SEARCH_ENGINE_ID=your_search_engine_id_here
   python image_downloader.py
