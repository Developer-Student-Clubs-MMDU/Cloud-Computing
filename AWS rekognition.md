# Amazon Rekognition
Amazon Rekognition makes it easy to add image and video analysis to your applications. You just provide
an image or video to the Amazon Rekognition API, and the service can identify objects, people, text,
scenes, and activities. It can detect any inappropriate content as well. Amazon Rekognition also provides
highly accurate facial analysis, face comparison, and face search capabilities. You can detect, analyze, and
compare faces for a wide variety of use cases, including user verification, cataloging, people counting,
and public safety.

Amazon Rekognition is based on the same proven, highly scalable, deep learning technology developed
by Amazon’s computer vision scientists to analyze billions of images and videos daily. It requires no
machine learning expertise to use. Amazon Rekognition includes a simple, easy-to-use API that can
quickly analyze any image or video file that’s stored in Amazon S3. Amazon Rekognition is always
learning from new data, and we’re continually adding new labels and facial comparison features to the
service. 

## Common use cases for using Amazon Rekognition include the following:
• Searchable image and video libraries – Amazon Rekognition makes images and stored videos
searchable so you can discover objects and scenes that appear within them.
• Face-based user verification – Amazon Rekognition enables your applications to confirm user
identities by comparing their live image with a reference image.
• Detection of Personal Protective Equipment
Amazon Rekognition detects Personal Protective Equipment (PPE) such as face covers, head covers,
and hand covers on persons in images. You can use PPE detection where safety is the highest priority.
For example, industries such as construction, manufacturing, healthcare, food processing, logistics, and
retail. With PPE detection, you can automatically detect if a person is wearing a specific type of PPE.
You can use the detection results to send a notification or to identify places where safety warnings or
training practices can be improved.
• Sentiment and demographic analysis – Amazon Rekognition interprets emotional expressions such
as happy, sad, or surprise, and demographic information such as gender from facial images. Amazon
Rekognition can analyze images, and send the emotion and demographic attributes to Amazon
Redshift for periodic reporting on trends such as in store locations and similar scenarios. Note that a
prediction of an emotional expression is based on the physical appearance of a person's face only. It is
not indicative of a person’s internal emotional state, and Rekognition should not be used to make such
a determination.
• Facial Search – With Amazon Rekognition, you can search images, stored videos, and streaming videos
for faces that match those stored in a container known as a face collection. A face collection is an index
of faces that you own and manage. Searching for people based on their faces requires two major steps
in Amazon Rekognition:
1. Index the faces.
2. Search the faces.

## Amazon Rekognition Developer Guide
• Unsafe content detection – Amazon Rekognition can detect adult and violent content in images and
in stored videos. Developers can use the returned metadata to filter inappropriate content based on
their business needs. Beyond flagging an image based on the presence of unsafe content, the API also
returns a hierarchical list of labels with confidence scores. These labels indicate specific categories of
unsafe content, which enables granular filtering and management of large volumes of user-generated
content (UGC). Examples include social and dating sites, photo sharing platforms, blogs and forums,
apps for children, ecommerce sites, entertainment, and online advertising services.
• Celebrity recognition – Amazon Rekognition can recognize celebrities within supplied images and
in videos. Amazon Rekognition can recognize thousands of celebrities across a number of categories,
such as politics, sports, business, entertainment, and media.
• Text detection – Amazon Rekognition Text in Image enables you to recognize and extract textual
content from images. Text in Image supports most fonts, including highly stylized ones. It detects
text and numbers in different orientations, such as those commonly found in banners and posters. In
image sharing and social media applications, you can use it to enable visual search based on an index
of images that contain the same keywords. In media and entertainment applications, you can catalog
videos based on relevant text on screen, such as ads, news, sport scores, and captions. Finally, in public
safety applications, you can identify vehicles based on license plate numbers from images taken by
street cameras.
• Custom labels– With Amazon Rekognition Custom Labels, you can identify the objects and scenes in
images that are specific to your business needs. For example, you can find your logo in social media
posts, identify your products on store shelves, classify machine parts in an assembly line, distinguish
healthy and infected plants, or detect animated characters in videos. For more information, see What
is Amazon Rekognition Custom Labels? in the Amazon Rekognition Custom Labels Developer Guide.
Some of the benefits of using Amazon Rekognition include:
• Integrating powerful image and video analysis into your apps – You don’t need computer vision
or deep learning expertise to take advantage of the reliable image and video analysis in Amazon
Rekognition. With the API, you can easily and quickly build image and video analysis into any web,
mobile, or connected device application.
• Deep learning-based image and video analysis – Amazon Rekognition uses deep-learning technology
to accurately analyze images, find and compare faces in images, and detect objects and scenes within
your images and videos.
• Scalable image analysis – Amazon Rekognition enables you to analyze millions of images so you can
curate and organize massive amounts of visual data.
• Integration with other AWS services – Amazon Rekognition is designed to work seamlessly with other
AWS services like Amazon S3 and AWS Lambda. You can call the Amazon Rekognition API directly from
Lambda in response to Amazon S3 events. Because Amazon S3 and Lambda scale automatically in
response to your application’s demand, you can build scalable, affordable, and reliable image analysis
applications. For example, each time a person arrives at your residence, your door camera can upload a
photo of the visitor to Amazon S3. This triggers a Lambda function that uses Amazon Rekognition API
operations to identify your guest. You can run analysis directly on images that are stored in Amazon
S3 without having to load or move the data. Support for AWS Identity and Access Management (IAM)
makes it easy to securely control access to Amazon Rekognition API operations. Using IAM, you can
• Low cost – With Amazon Rekognition, you pay for the images and videos that you analyze, and the
face metadata that you store. There are no minimum fees or upfront commitments. You can get
started for free, and save more as you grow with the Amazon Rekognition tiered pricing model