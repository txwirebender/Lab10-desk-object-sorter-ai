# Lab10-desk-object-sorter-ai
WC ITAI-1370 Lab10-desk-object-sorter-ai

## Project Description
This project consisted of teaching an AI model to recognize various desk items. A total of 5 different objects were chosen that varied from what I considered "well known" to possibly unknown with respect to familiarity. The expectation, i.e., hypothesis, was that the more familiar objects would have a higher recognition accuracy-confidence score than the unfamiliar one. The letter opener is the "red-herring" of the lab and with the expectation of having a low accuracy-confidence score since this type of object is more generational in use and unique in shape. I considered the other 4 items to be more common and well known.

## Classes Identified
* Class 1 - Pen/Pencil Holder
* Class 2 - Blue Screen Glasses
* Class 3 - Stapler
* Class 4 - Letter Opener
* Class 5 - Green Highlighter

## Discussion and Reflection
1. Model Performance & Iteration
   * a) Surprisingly the accuracy was more than expected and the confidence variation between objects was minimal with the exception of the letter opener. My expectation was met with the letter opener having the lowest accuracy, but at the same time I was surprised at the upper range of confidence it had.
     
   * b) To improve the accuracy of the letter opener I did more training with a closer view and a simpler/basic background.
     
   * c) The enhanced training of the letter opener significantly improved the model's accuracy and confidence to 100% from a variation range of the 60-80 percentiles.

2) Challenges & Observations
   * a) The more familiar objects, Classes 1,2,3, and 5, were the easiest for the model to learn and distinguish. I believe that the better accuracy and confidence was due to being more well known, e.g., uploaded and trained before and possibly multiple times, versus the letter opener. As a 60's Boomer I do not see letter openers shaped like a knife very much anymore. Growing up they were very common and these days you normally see a plastic opener with a pointed plastic tip and a recessed blade, and some are imprinted with a business logo.
      
    * b)The letter opener was the most challenging. I think that the reason being is that its shape is unique in design and that the       model's feature training most likely does not have a large training database to draw from. I could see where if I labeled it as a        knife the accuracy/confidence would be far greater.
      
   * c) When an object the model was not trained on, e.g., notepad, the confidence score was low. The is significant because of poor       training. The model was not given and feature labeling to assist in identification.

3) Bias in AI
   * a) The pen/pencil holder was shaped as a "mug" though minus the handle. The overall shape was simple and easily recognized in                 various positions. The color would not make a difference, but shape could, e.g., had a Starbucks Barista Bear shape, rather than           a "mug" shape. I think it would easily recognize other students’ "mugs" do its simplicity. The bias introduced in the training             data is straight forward due to its simplicity in shape. A more complex shape, as mentioned, would most likely result in lower             accuracy.
     
   * b) If all the images were taken in a publication type of setting, i.e., bright lights on a white non-textured background, the                 accuracy would be fantastic when shown again under similar to closer environments. If the environment was dimly lit with                   background textures, shadows, and surrounding visual noise then the accuracy would decrease. This shows that the AI models of              yesteryear have grown significantly but still have a long way to go with respect to improving accuracy and confidence with                 minimal bias.

4) Model Limitations & Usefulness
   * a) Some key limitations are the ability to recognize more complex/unique objects with greater accuracy-confidence that may or may not         be well known until the training database is enhanced over time.
     
   * b) The usefulness of downloading my trained data model bedsides fulfilling the lab requirements and affecting my grade is the ability         to share it. For example, if I wanted to manufacture and sell letter openers I could continue to train the model, enhance its              ability to recognize the object and its perfection then I could put it into an AI model library and share/sell it. The ACME company        that purchased it then could use it on their production line to reject any with a defect. 

5) Real-World Applications & Ethics
   * a) As mentioned in 4b the model could be used to bring back good 'ol solid letter openers. The ACME company would purchase it from the        AI model library and tweak it to their specific needs and design prior to beginning a manufacturing process. This after the ACME           Board of Directors completed their feasibility study and realized that there is a shortage of letter openers and the market demand         is growing.

   * b) Ethics is a concern I have had throughout this course especially since I have been involved in healthcare ethics for over 4 decades.
      We have already seen the lack of AI ethics with the 3-D printing of ghost guns and other weapons along with using AI to create coded       and now non-coded malware. The misuse of AI for propaganda by various countries and even by country leaders who should be showing          more professional and ethical behavior. Even Grok, when first being developed, showed racial bias. Axis countries have also been           using it to deceive, steal, and interfere with various companies. AI needs to have better guardrails and ethical parameters that can       be enforced before it gets out of control, or a country achieves their goal to harness its unlimited power.
   
      Ethical human oversight is strongly needed with the use of AI to ensure intellectual rights, copyrights, and trademarks are not            infringed upon nor stolen. The models created should always have credit due when used, even those that are open sourced. Best              example is Kali-Linux. That is open-sourced, and many cybersecurity companies will use it as a platform for their AI models. At the        Secure World meeting in Dallas this past October the number of vendors using AI models for their product was amazing and only a few        would admit that they were using models designed by others and that they were morphing it to their product architecture.

      When developers build and deploy their recognition images into the real world, they need to be sure of the wholeness of their              product in accuracy, consistency, and usefulness for the user within its intended purpose. Out of bounds use should somehow be             unavailable of impossible to do.
    
      With respect to ethics, I can be very verbose and passionate. There is an increasing lack of it in our world. I will now step off my       soapbox for this assignment, lol.

## Optional
   Each assignment has been an eyeopener on the power of AI and an amazing technology I look forward to seeing its future potential.
   

   
