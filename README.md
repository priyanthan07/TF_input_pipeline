# TF_input_pipeline
Creating a TensorFlow input pipeline to process the dataset
------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------
For the training of the machine learning algorithm. The TensorFlow libraries play a vital role in that. Large amounts of data will be converted into batches, and those batches will be fed into the algorithm. 
 Data Extraction:      tf. data.Dataset (from_tensor_slices() |  list_files())
- Filter         :      filter(filter_func) gets required data only.
- Mapping        :      Map(func), This is used to apply the same changes to the entire dataset
- lambda         :      used to define the function simply.
- scalling       :      Bring values to the required range.
- shuffel(n)     :      shuffle the dataset. Here, n is the buffer value. 

as_numpy_iterator and numpy() can be used to convert tensor to numpy.

- take () and skip()   functions are used to create separate datasets for training and testing purposes.
- get_label()     : This function can be used to retrieve the label from each data.
- process_image() : This function can be used to decode and resize the images.  tf has decode_jpeg functions.
- scale()         : Scale function used to convert all the values between 0 to 1.

