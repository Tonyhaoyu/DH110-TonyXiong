# DH 110 Assignment 07 - Interface Design
Tony Xiong | DH 110 | Fall 2021

## Summary
This interactive prototype is for the feature "Smart Trip", which provides travellers popular tourist site and event suggestions. This feature is placed under Hawaii's state website's visitor section. Upon entering, the users would be asked a few questions regarding their trip plans. Then, the system would provide the user with a list of suggestions that match their answers. The users can Smart Trip helps users to plan their trip better. The purpose of a high-fidelity interactive prototype is to emmulate the real feature and to improve the accuracy of feedback in user testing. The addition of details also helps me to identify elements that should be changed or removed.

## List of Tasks
### User Survey
In order to provide the users trip suggestions that fit their need, we need to understand what the users want from their trip. This user survey asks the users the duration of their travel, their budget, and what they want from an ideal trip to Hawaii. The duration of travel would determine how many suggestions to give the users, as a longer trip would mean more places visited. The budget would decide the price range of the tourist sites and resorts suggested. The words the user chooses to describe their trip would be directly connected to the suggestions: a chill trip would lean towards resorts and spas and an adenturous trip would lean towards volcanoes and scuba diving. I used scrolling animation for duration and budget, and multiple choice for mood using component variants.

### Suggestion Alternatives
After Smart Trip provides suggestions to the user, the user has the choice to pick an alternative to each suggestions made. For instance, if the user does not like 
visiting Volcanoes National Park, they could click on the switch icon for a similar alternative, for instance, Haleakala National Park. This task offers great flexibility to the users, as they have some degree of control over their preferences without compromising the goal of the Smart Trip feature itself. I used both scrolling and component variants to closely emulate the working product.

## Wireflow
Link to the Figma file: https://www.figma.com/file/uzeYiSpDX02PF1GrtYV0P5/Interactive-Prototype?node-id=0%3A1

Link to the prototype: https://www.figma.com/proto/uzeYiSpDX02PF1GrtYV0P5/Interactive-Prototype?node-id=4%3A2&scaling=scale-down&page-id=0%3A1&starting-point-node-id=2%3A2

Image of the graphical interface:
<img src="./4.png">

Image of the prototype with wireflows:
<img src="./5.png">

The components I used for the "click to switch" animation:
<img src="./3.png">

## Cognitive Walkthrough
I conducted a cognitive walkthrough of my interactive prototype during class time and received three written feedback from my peers and one oral feedback from Professor Sookie. In terms of the purpose of this Smart Trip feature, participants said that they might use it make better plans for a trip to Hawaii or to find more travelling information on Hawaii. They also enjoyed the overall feel of the prototype, saying that it looks very "clean". In terms of places for imporvement, here are some feedbacks that stood out to me and the changes I made in response to them:

1. "There was 2 different kinds of next buttons on different pages. This lack of consistency could be an issue."

Initially, I used the icon for "next" on the suggestion page instead of the text + icon I used across the other pages. This incoherence in style might cause some confusion. Therefore, I adopted the text + icon format in all the pages.

2. "Last result page - missing continue button"

This was a comment made by a different person pointing out the same issue as above, except this time, the person couldn't even find the continue button. Having two different input saying the same thing, I had to make the change to not only make the continue button as visible as possible, but also to stay consistent. As a result, I pushed up the boundary for the frame on the suggestion page to leave the continue button at the bottom, so that users can easily identify it.

3. "You don't know where you are in the process"

This was a comment made by Professor Sookie in regards to my initial design's failure in tracking user progress. In an effort to fix this, I added a progress tracker on top to clearly show which step the user is on, and they can also go back to previous steps by clicking on the progress tracker.

4. "The user selections on the "mood" page look like the continue button"

When a user selection resembles the system's default styles, it might confuse the users and make them less certain about their actions. It also makes it harder for users to identify which selections are made by them and which are default commands by the system. To fix this, I simply changed the color of user selections to a lighter shade of blue compared to the system's default button color, white.

After these feedback and the respective changes I made, I conducted a last cognitive walkthrough and short usability testing session with my friend, Alan Nguyen. I walked him through the prototype in order to achieve what the feature set out to do. And here is the link to the recording: https://drive.google.com/file/d/1N_hsL32SxP_nfa4qpS9G_4QtKRHAZw1x/view?usp=sharing

Alan said he enjoyed the flow of the feature and that since it was a linear process, little could go wrong on the user's end. He also liked the alternatives the feature provides on the suggestions page, so that users can see other options that they might be interested in.
