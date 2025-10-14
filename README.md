# supermarket-detection

Simple example project that uses YOLOv8 to identify and locate products on store shelves, and CLIP-based feature matching to associate detected items with reference images.

The following additional resources will be downloaded from my personal drive.
- Yolov8 model trained with the following dataset: [https://www.kaggle.com/datasets/thedatasith/sku110k-annotations](https://www.kaggle.com/datasets/thedatasith/sku110k-annotations)
- Test image 1 (smaller shelf) [source here](https://huggingface.co/datasets/bharadwajkg/planogram-sample-sd-data3/viewer/default/train?row=10&views%5B%5D=train)
- Target set 1 (set of product images that match the products from Test 1) [source: Google Images]
- Test image 2 (bigger shelf) [source here](https://www.dreamstime.com/rome-italy-december-several-packs-chips-snack-inside-ma-supermarket-italy-rome-shelves-full-tidy-shelves-image142747547)
- Target set 2 (set of product images that match the products from Test 2) [source: Google Images]

---

## Example Shelf 1 (Small simple case)

### Object detection with YOLO
![YOLO detection example](res/object_detection_example.jpeg)

### Some matches with target products
**Example 1:**  
![Product match 1](res/object_matching_example1.png)

**Example 2:**  
![Product match 2](res/object_matching_example1.png)

**Example 3:**  
![Product match 3](res/object_matching_example1.png)

## Example Shelf 2 (Bigger and more complex)

### Object detection with YOLO
![YOLO detection example](res/object_detection_example2.jpeg)

### Some matches with target products
**Example 1:**  
![Product match 1](res/object_matching_example4.png)
Imperfect match. Found a similar object, but not the exact one.

**Example 2:**  
![Product match 2](res/object_matching_example5.png)
Good match.

**Example 3:**  
![Product match 3](res/object_matching_example6.png)
Incorrect match.

