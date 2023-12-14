Object detection in densely packed, man-made scenes poses a significant challenge, especially when objects are numerous, identical, and closely positioned. The authors of the **SKU110K** dataset address this frontier with a novel deep-learning method designed explicitly for such challenging settings. They introduce an extensive annotated retail dataset consisting of more than 11K images and around 1M bounding boxes.

The authors mention densely packed scenes, such as retail shelf displays, traffic, and urban landscapes, where numerous objects, often similar or identical, are in close proximity. Despite the prevalence of such environments, they are underrepresented in existing object detection benchmarks, leading to challenges for state-of-the-art detectors. Identifying boundaries between identical objects and minimizing overlaps present significant difficulties, as demonstrated by the limitations of existing detectors.

To address the scarcity of datasets catering to densely packed scenes, the authors assembled SKU-110K, a labeled dataset centered around images of supermarket shelves. The choice of retail environments is motivated by the optimization of shelves for presenting many items in tightly packed arrangements. The dataset comprises extreme examples of dense environments, reflecting the authors' specific interest in such scenes.

## Data Acquisition

Associates from around the world captured images using personal cellphone cameras, resulting in images with varying quality and view settings. Annotations were performed by skilled annotators to ensure accuracy, and each image, along with its detection labels, underwent visual inspection to filter out localization errors.

## Dataset Characteristics

The dataset showcases the challenges of densely packed environments with variations in spatial transformations, image quality, and occlusion. Images from SKU-110K were collected globally from thousands of supermarket stores, introducing diverse scales, viewing angles, lighting conditions, and other sources of variability.

SKU-110K images were partitioned into *train*, *test*, and *val* splits, with 70%, 5%, and 25% of the images allocated, respectively. Random selection ensures that the same shelf display from the same shop does not appear in more than one subset.
