# AI-Generated-Video-Detection #
A parallel/branched input structure that attempts to distinguish between AI Generated and non-AI-Generated videos

The folder arrangement might be a bit confounding, so I will be doing my best to explain the function of some of the files and some folders:


-Code-

-- 1PI_TDCNN_ConvLSTM.ipynb - Single input code

-- 2PI_TDCNN_ConvLSTM.ipynb - 2 branched input code

-- 3PI_TDCNN_ConvLSTM.ipynb - 3 branched input code


-Report- Contains images of graphs and diagrams I used in the paper


-Results- Contains the training and validation results for each network variant trained by me

-Saved Models- I was conducting this experiment on the free version of Google Collab and since the resources are limited by internet and available compute time, I saved for each epoch. It is not possible to upload all of them so I uploaded the last 3 for each variant being trained on 8 batches and the variant of 3 input for both 8 and 16 batches.

--X0 - Single input

--X0X1 - 2 branched input

--X0X1X2 - 3 branched input

--X0X1X2X3 - Only a concept where each rotational orientation of the input could be used as well as a version of the video mathematically transformed by wavelets. So that there would be 4 inputs.




