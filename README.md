# Lab10-desk-object-sorter-ai
WC ITAI-1370 Lab10-desk-object-sorter-ai

## Project Description
This project consisted of teaching an AI model to recognize various desk items. A total of 5 different objects were chosen that varied from what I considered "well known" to possibly unknown with respect to familiarity. The expectation, i.e., hypothesis, was that the more familiar objects would have a higher recognition accuracy-confidence score than the unfamiliar one. The letter opener is the "red-herring" of the lab and with the expectation of having a low accuracy-confidence score since this type of object is more generational in use and unique in shape. I considered the other 4 items to be more common and well known.

## Classes Identified
Class 1 - Pen/Pencil Holder
Class 2 - Blue Screen Glasses
Class 3 - Stapler
Class 4 - Letter Opener
Class 5 - Green Highlighter

## Discussion and Reflection
1. Model Performance & Iteration
   a) Surprisingly the accuracy was more than expected and the confidence variation between objects was minimal with the exception of the        letter opener. My expectation was met with the letter opener having the lowest accuracy, but at the same time I was surprised at the       upper range of confidence it had.
   b) To improve the accuracy of the letter opener I did more training with a closer view and a simpler/basic background.
   c) The enhanced training of the letter opener significantly improved the model's accuracy and confidence to 100% from a variation range       of the 60-80 percentiles.

2) Challenges & Observations
   a) The more familiar objects, Classes 1,2,3, and 5, were the easiest for the model to learn and distinguish. I believe that the better        accuracy and confidence was due to being more well known, e.g., uploaded and trained before and possibly multiple times, versus the        letter opener. As a 60's Boomer I do not see letter openers shaped like a knife very much anymore. Growing up they were very common        and these days you normally see a plastic opener with a pointed plastic tip and a recessed blade, and some are imprinted with a            business logo. 
    b)The letter opener was the most challenging. I think that the reason being is that its shape is unique in design and that the               model's feature training most likely does not have a large training database to draw from. I could see where if I labeled it as a          knife the accuracy/confidence would be far greater.
   c) When an object the model was not trained on, e.g., notepad, the confidence score was low. The is significant because of poor               training. The model was not given and feature labeling to assist in identification.

   3) Bias in AI
      a) The pen/pencil holder was shaped as a "mug" though minus the handle. The overall shape was simple and easily recognized in                 various positions. The color would not make a difference, but shape could, e.g., had a Starbucks Barista Bear shape, rather than           a "mug" shape. I think it would easily recognize other students’ "mugs" do its simplicity. The bias introduced in the training             data is straight forward due to its simplicity in shape. A more complex shape, as mentioned, would most likely result in lower             accuracy.
      b) If all the images were taken in a publication type of setting, i.e., bright lights on a white non-textured background, the                 accuracy would be fantastic when shown again under similar to closer environments. If the environment was dimly lit with                   background textures, shadows, and surrounding visual noise then the accuracy would decrease. This shows that the AI models of              yesteryear have grown significantly but still have a long way to go with respect to improving accuracy and confidence with                 minimal bias.

     4) 
