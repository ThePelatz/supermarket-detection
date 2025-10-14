# supermarket-detection

Simple example project that uses YOLOv8 to identify and locate products on store shelves, and CLIP-based feature matching to associate detected items with reference images.


- Yolov8 model trained with the following dataset: [https://www.kaggle.com/datasets/thedatasith/sku110k-annotations](https://www.kaggle.com/datasets/thedatasith/sku110k-annotations)
- Test image 1 (smaller shelf) [source here](https://huggingface.co/datasets/bharadwajkg/planogram-sample-sd-data3/viewer/default/train?row=10&views%5B%5D=train)
- Target set 1 (set of product images that match the products from Test 1) [source: Google Images]
- Test image 2 (bigger shelf) [source here](https://www.dreamstime.com/rome-italy-december-several-packs-chips-snack-inside-ma-supermarket-italy-rome-shelves-full-tidy-shelves-image142747547)
- Target set 2 (set of product images that match the products from Test 2) [source: Google Images]

