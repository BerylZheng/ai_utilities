# ai_utilities

Is a set of script useful in deep learning and AI purposes.

## image_download.py
Download any number of images from Google image search.

Usage:  `python image_download.py query num_images

Example:`python image_download.py 'dog' 200`

## filter-img.sh
Use 'file' to determine the type of picture then filter (keep) only pictures of a specified type.

Images are filtered in place, i.e., non-IMG files are deleted.

Usage:  `filter-img image_directory`
Example:`filter-image pictures`

# make-train-valid.sh
Set up `valid` and `train` directories for use in deep learning models.

Usage:   make-train-valid.sh dir_containing_labels number_of_valids
- dir_containing_labels contains subdirectories lable1, label2..., each containing files of the corresponding label.
- number_of_valids is the number of validations to use for each label

Example: make-train-valid.sh catsdogs 100

These should be used for educational purposes only. Copyright is owned by the respective websites.
