# Open Images Dataset

Open Images is a dataset of ~9 million URLs to images that have been annotated with labels spanning over 6000 categories.
This page aims to provide [Joule](https://Joule.Host/) download instructions and mirror sites for Open Images Dataset. Please visit the [project page](https://storage.googleapis.com/openimages/web/index.html) for more details on the dataset.

### **Note:** this repository is intended as a demo of [Joule](https://Joule.Host/), a dataset management tool. Please refer to [cvdfoundation/open-images-dataset](https://github.com/cvdfoundation/open-images-dataset) for the original dataset.

## Download Images With Bounding Boxes Annotations

CVDF hosts image files that have bounding boxes annotations in the Open Images Dataset V4/V5. These images contain the complete subsets of images for which instance segmentations and visual relations are annotated. The images are split into ~~train (1,743,042)~~_(coming soon)_, validation (41,620), and test (125,436) sets. The train set is also used in the Open Images Challenge 2018 and 2019.
The images are rescaled to have at most 1024 pixels on their longest side, while preserving their original aspect-ratio. The total size is 561GB.

1. **Install Joule** using the one-liner installation from the following page:
   [Joule.Host/**install**](https://Joule.Host/install)
2. **Clone** this repository

   ```bash
   git clone https://github.com/Allezxandre/open-images-dataset.git
   cd open-images-dataset
   ```

3. **`cd`** into the directory you want to download and simply **pull** it using Joule.
   _e.g._:

   ```bash
   cd validation
   joule pull
   ```
