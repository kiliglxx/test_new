### EGTabNet
#### 1. Abstract
This dataset is divided into three parts, the first part is a generative dataset that does not contain semantic relations. It is a dataset generated using the steps of construction, filling, screenshotting, and saving in order for the model to learn richer structural relationships. This part of the code will be disclosed later. There are a total of 20,000 images and annotations of tables with different structures, colors, and sizes. The second part is generated based on the first part using existing relationships for filling. The third part is manually labeled after collecting the images.
These Chinese engineering tables, generated through multi
level nested entity interactions in disciplines such as petroleum and geology,
 comprise 2,000 tables. The annotations encompass the HTML framework, cell
 contents, and bounding box information. There are 415 of these long tables (num
ber of structure tokens greater than 300), including 125 table images with more
 than 500 structure tokens. 
#### 2. Format
The dataset format is presented in a ppocrlable labeled format. If training is required, the format can be converted and used.
More data will be put up gradually afterwards.
#### 3. Contact
If you have any questions or communication, please contact us:

kiligLi: kiligl_xx@163.com

##### Note:
Now this part is not perfect, we will continue to modify and improve, so stay tuned.