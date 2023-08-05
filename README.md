# ANPR
### Number Plate Localization
The followed approach to number plate localization is a basic one involving pure morphological operations without the luxury of a dataset.

### Method Flow
![VNP_sys](https://github.com/Harshalshirote2002/ANPR/assets/75237728/b5e5d9ff-a371-4ccd-b01c-83860bc2bc34)


### Character Identification
The number plate recognition was done using `Tesseract` library.

# Instructions to use
run the driver.py file using a command sequence as such:  

`python ./driver.py -i path_to_image_directory`

The optional parameters `-c 1` can be used to clear possibilities of border lying plates.

The parameter `-d 1` can be used to output image after every operation.

# Demo
### Final Output Image
![finaloutput2](https://github.com/Harshalshirote2002/ANPR/assets/75237728/532e1483-bfc6-4f3e-997a-0e2210e855c5)

### Extracted Region of Interest
![roi2](https://github.com/Harshalshirote2002/ANPR/assets/75237728/f4f04b61-8e67-4e94-8bbf-5a061cd8317e)




