1. Install Python 3.11

2. Install dependencies:
   py -m pip install playwright openpyxl
   py -m playwright install

3. Run test:
   py image_preview_test.py --url "https://www.pixelssuite.com/convert-to-png" --slow-mo-ms 2000
