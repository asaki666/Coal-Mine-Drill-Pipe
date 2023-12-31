# Coal-Mine-Drill-Pipe
Due to the limitations of the downhole environmental conditions, surveillance videos of downhole coal mines have the following characteristics:

(1)Inadequate lighting and insufficient illumination. Despite the installation of fixed light sources, the brightness is notably lower than that of the surrounding environment. The grayscale of the images is predominantly concentrated in a lower range, leading to inadequate contrast.

(2)Dramatical brightness variation. When the headlamp is positioned directly in front of the lens, it produces localized glare as a result of its significantly higher brightness compared the surrounding areas.
(3)Absence of color information. The primary hues of the target objects are black, white, and gray. The colors closely resmble the background, and the environment is complex.

In terms of computational efficiency, the YOLOX model employs a series of optimization strategies, such as feature reuse, adjustable network depth, and convolutional layer fusion, to improve computational efficiency, and compared to general network models, YOLOX has a faster inference speed while maintaining higher detection accuracy.

Firstly, image enhancement and annotation are performed on the unloading rod image data. Secondly, the model introduces an attention mechanism between the Backbone and Neck structure of the YOLOX model to enhance the feature extraction capability; The feature pyramid is used in the neck part to reduce feature loss for better multi-scale feature fusion; the loss function is optimized to enhance the localization ability of the prediction box. The accuracy of the improved model reaches 91.3%, which is 4.4% higher than before the improvement, and the positioning is more accurate. The center points of the prediction box of the power head and the front of the machine are used to calculate and generate the distance change graph to obtain the motion information of the drill pipe. By counting the number of effective wave peaks, the number of unloading rods is obtained, and validate the statistical results.

You can find the video footage of removing drill pipes from a coal mine underground here. 
