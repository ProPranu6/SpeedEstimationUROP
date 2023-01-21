# SpeedEstimationUROP
 > ![Tux, the Linux mascot](/assets/images/tux.png)
 >
 >
> ## Our Objective
> **“Our research objective is to estimate the speed of the car in real-time from the video stream from our car’s dashboard using the convolution neural network of long short term memory networks architecture with CNN resulting in the sequential prediction of the speed of our car. “**
>
> ## Review of Literature That Align With our Research
>> ### Convolutional, Long Short-Term Memory, fully connected Deep Neural Networks (published in IEEE Journal)
>> **Authored By** : 	*T.N. Sainath, O. Vinyals, A. Senior and H. Sak*
>
>> ### FlowNet: Learning Optical Flow with Convolutional Networks. 
>> **Authored By** : 	*Fischer, Philipp & Dosovitskivy, Alexey & Ilg, Eddy&Hausser, Philip&Hazirbas, Caner&Golkov*
>
>> ### FlowNet 2.0: Evolution of Optical Flow Estimation with Deep Networks.
>> **Authored By** : 	*Ilg, Eddy&Mayer, Nikoulas&Saikia, Tonmoy&Keuper, Margret&Dosovitskivy, Alexey&Brox*
>
>> ### Long Short-Term Memory, Neural Computer
>> **Authored By** : 	*Hochreiter S & Schmidhuber*
>
> ## How our Research Is Different
> - Use of ConvLSTM, which performs convolutional operations on the image feature maps is used to estimate the speed of the vehicles in the first person perspective.
> - Deep Convolutional Neural Network is used to extract the best features which constantly change over the timestamps and which help to calculate the speed of the vehicle.
> - As a result, the suggested model can be used as an alternative to existing piecewise neural network models for predicting speeds. The suggested technique eliminates the need to construct optical flow diagrams from a series before forecasting speeds, instead allowing the neural network model to extract the best properties from the sequence without the need for human involvement.
>
> ## Our Proposed Model Architecture
> ![Tux, the Linux mascot](/assets/images/tux.png)
>
> ## Flow Chart Of The Proposed Model Workings
> ![Tux, the Linux mascot](/assets/images/tux.png)
>
> ## Plausibility of our Idea
> Theoretically the research idea yields optimal results  because:
> - The proposed model makes use of sequentially changing data to calculate the speed of an object which is intuitive from how human brain works. 
> - The Proposed model extracts the features from sequence of frames using deep convolutional layers in accordance to reach the goal state, rather than pre-computing it manually like in optical flow procedures which isn’t goal oriented.
>
> ## Stats of our Model
> ![Tux, the Linux mascot](/assets/images/tux.png)
> 
> The first image is the result of locally trained model. The model due to small sequence length uses the locally trained function to map to the global function as well although it’s not the case hence resulting in a poor prediction. 
> To increase the model performance it’s important that we capture more of global variation in every sequence we pass as input which means to either increase the input sequence length or sample farly spaced inputs in the initial sequence. 
> But the more spacing we give to inputs the more overfits the model but less spacing leads to underfitting so it is also important that the spacing is just right

> ## Conclusion and Future Scope
> - The proposed model performs an end-to-end speed estimation from sequential data using a single deep ConvLSTM convolutional neural network.
> - The proposed CNN LSTM architecture model can be improved using state of the art CNN architecture like VGG-19 
> - The dataset can be further expanded under diverse environments and driving conditions to avoid the overfitting of the data also adding more dashboard types and angles in which the video footage will be shot can help in generating a more diverse and generalized dataset 
> - To increase the model performance it’s important that we capture more of global variation in every sequence we pass as input which means to either increase the input sequence length or sample farly spaced inputs in the initial sequence.

 
