22.06.
The kick-off meeting was for 30 mins. A couple of project topics were discussed, and the feasibility was discussed.
We agreed that I would survey the topics for a short while and get back within evening with a topic for dissertation. 
By evening I confirmed the dissertation topic to the professor. Other general advice regarding running the project was given out. 
The next meeting was agreed to be on next week where the task is to do background reading on the dissertation

29.06
The progress from the last week and the short summary of the survey was presented. Professor was happy with both. 
The plan for next week and the overall project plan was presented. Advice was given to focus on text defining the project scope. 
Guidelines on building the dataset was given. 
Advice to write the intro chapter of dissertation and design proposal was given. 
Task to look into variations in a chart. Start building the dataset. 
Getting hands dirty with development techniques. 
Think about the degree to which the software is to be automatic. 

06.07
This was a group meeting lasting about 1.5 hrs. Valuable ideas were shared between group mates reagrding their projects. 
For my part, I explained the work done in the last week which includes survey of CNN classifiers, building the dataset, writing the 
introduction part of dissertation and the hand-on experience with the limitations of the opensource tool tesseract (python) for text extraction and opencv for object
detection. Due to the limitations and inaccuracy of opensource tools, advice was given to first focus on classification of chart images and to work
on data extraction if time permits. Plan for this week is to work on:
- building the initial classifier 
- expanding the dataset to include more chart types
- work on introduction and background chapters of dissertation
- find possible classification techniques

13.07
This is was an individual meeting lasting 30 mins. Professor was happy with the progress made from last week. The configuration of baseline model was explained and intention to use transfer learning for image classification was proposed. Professor was happy for me to continue with transfer learning, while giving advice on experimenting with pre-trained model weights. Advice was given to think about localization, chart image generation, synthetic documents with randomized chart images, working with distorted chart images and predicting the parts of charts as many options to move ahead in the project. This week's task is to:
- Survey the above mentioned options to implement
- Start draft of background chapter
- Investigate and implement transfer learning approach for image classification
- Work on labelling the dataset (if necessary)

21.07
This was a group meeting lasting 1.5 hrs. I presented my progress from last week and explained the challenges I faced and how I overcame them. Advice was given to experiment on data augmentation and varying the learning rate & weights decay for transfer learning image classification. In terms of object detection, the professor agreed with my choice of labels to detect (title, axis label, legend). Experiment on autoencoders for chart image denoising was proposed. We were informed that we wont have a meeting next week. Therefore, the task for the next 2 weeks include:
- Finalize the dataset
- Labelling the images
- Experiment and fine tune transfer learning
- Perform object detection using detecto package
- Continue working on autoencoders
- Explore localization using mask rcnn
- Explore color space augmentation for images

03.08
This was an individual meeting after 2 weeks. I presented my progress which included learning rate scheduling for baseline cnn, fine tuning mobilenetv2 and vgg16 transfer learning, object detection results, autoencoder performance, thoughts about color spaces based on experimentation and discussion about ablation study. The professor was happy with the progress and suggested to work on vgg16 transfer learning as it provided the best performance. The performance of autoencoders was discussed and decsision was taken to not further proceed with the implementation as it has very little impact on the overall project and does not provide good performance. The plan for this week includes:
- fine tune vgg16 further
- Confidence score cut off threshold for object detection
- Introduce noise in classification and object detection to make it similar to real world data 
- Increase epochs to 200/300 to test the learning rate decay in baseline cnn
- Experiment with lab color space (if possible)

10.08
This was a group meeting lasting 1.5 hrs. I presented my progress from last week which includes injection of gaussian noise in the dataset, ablation study, effect of increasing the epochs to 300 in baseline model and optimizing the classification models. Suggestion was made to analyse the class-wise understanding of these models to better analyse the strengths and weaknesses and to improve the ablation study. The task for this week includes:
- Class-wise analysis of the model performance
- Improve ablation study according the class-wise analysis
- Set confidence score threshold for object detection
- Explain the model performance in terms of its effect on dataset
- Continue writing the dissertation report

24.08
This was an individual meeting. The user demo of the project was presented. Class-wise model performance, abalation study, setting confidence score threshold and changes & updates to improve the dataset diversity was presented. The professor was happy with the progress made. Suggestion was made to work on the image cropping and paddding for the classifcation's input for the demo to preserve features. The task for this week:
- Work on evaludation plan for object detection
- Implement eval metric : per class avg.precision and mean avg precision
- Code clean up and find bugs

31.08
This was a group meeting. Progress made from the last week and challenges faced while making the progress was explained to the professor. The results from object detection was discussed and compared to the state-of-the-art software to put it in perspective. The professor was happy with the progress and agreed with the reasoning for the results. Suggestion was made to use scaled images to cambat the cropping issue for larger images to the target size. The plan for this week includes:
- Produce a draft of the dissertation report
- Work on the image resizing
- Code cleanup and finalization

07.09
This was an individual meeting. I presented my progress from last week which included writing the draft of the dissertation report. I wrote the draft of the analysis chapter, the design chapter and the results chapter. Feedback was given to work on:
- background survey of the project
- The implementation details
- Summarize the methodologies 
- Improve evidence/reasoning for thr descisions
