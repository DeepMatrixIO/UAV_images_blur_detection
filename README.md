blur_scan will detect in a set of UAV images the ones that could be blurry. Those images are usually taken when the UAV is changing direction and with a low speed. 
blur_scan scan a directory with a regex filter and create a list of potentially blurry images.
<img src="https://github.com/IPGP/UAV_images_blur_detection/blob/main/map_exemple.png" width="800px" height="auto">


# Requirements
`python3 -m venv ~/.venv/rasterqa`
`source ~/.venv/rasterqa/bin/activate`
`pip install -r requirements.txt`
# Install on mac
`brew install openblas`
`export OPENBLAS="$(brew --prefix openblas)"`
# usage
`blur_scan.py -d /directory/images -r "IMG.*JPG" -o output.csv`
`./blur_scan.py -i /Users/kaustubh/code/deepmatrix/UAV_images_blur_detection/input.csv -o tmp"`
