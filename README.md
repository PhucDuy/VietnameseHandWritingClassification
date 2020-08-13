# VietnameseHandWritingClassification
This is my project in CoderSchool Hackathon with purpose to classify  the Vietnamese handwritting image OCR problem.

Things to improve for Hackathon:
- Copy files into train and test folder from sample folder 1 and 2.
- Handle labels with multiple json files.
- Resize image logics with multiple image sizes (maybe as following):
    + find min, max of height and width
    + resize to a fixed height you want
    + calculate the max width of all resized images
    + padding to all images to that max width
- Combine the logic of preprocessing of train set and test set together
- Convert them to tfdataset pipeline (note that it is challenging since OpenCV won't work with tensor)
- Rework/redesign new CRNN model to fit with your new processed images. 