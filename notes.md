## BI-RADS

BI-RADS, which stands for Breast Imaging Reporting and Data System. BI-RADS is a standardized system used in the interpretation and reporting of mammography and other breast imaging studies. It was developed by the American College of Radiology (ACR) to provide a common language for radiologists, clinicians, and other healthcare professionals to communicate about breast imaging findings. The system helps standardize reporting, improve communication, and ensure appropriate follow-up for patients.

- BI-RADS categorizes findings into several assessment categories to convey the level of suspicion for breast cancer. The categories are numbered from 0 to 6.
- Categories include 0 (incomplete), 1 (negative), 2 (benign finding), 3 (probably benign), 4 (suspicious abnormality), 5 (highly suggestive of malignancy), and 6 (known biopsy-proven malignancy).


## Test-Train Split
![Sample Image](https://media.springernature.com/full/springer-static/image/art%3A10.1038%2Fsdata.2017.177/MediaObjects/41597_2017_Article_BFsdata2017177_Fig3_HTML.jpg?as=webp)


## Dataset Description

- The dataset contains 2857 full_mammogram_images, 3567 cropped images, 3247 masks.
- We have mass train, mass test, calcination train, calcination test dataframes. 



## Model Performance

### Ultrasound
1. CNN 3 layers
    - Validation Accuracy - 83.72%
    - Testing Accuracy - 78.46%


###  Mammography