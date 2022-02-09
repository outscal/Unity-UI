## Slider

-   The Slider UI element is commonly used where a certain value should be set between a minimum and      maximum value pair.
-   One of the most common usages of this is for audio volume, screen brightness, or for doing zoom.
-   To create a slider UI, right-click on the scene hierarchy and select Game Object -> UI -> Slider. A new slider element will display on your scene.

    <br>
    
    ![UI_Slider.png](https://github.com/outscal/Unity-UI/blob/main/Images/UI_Slider.png?raw=true)
    
-   Once the slider has been added we can set a direction for our slider to work in.
    
    <br>
    
    ![Slider_1.png](https://github.com/outscal/Unity-UI/blob/main/Images/Slider_1.png?raw=true)
    
-   Once you have decided what direction should the slider work in we can proceed by setting the maximum and minimum value for our slider.
-   In this case as I am using my slider for volume control I will set the min value to 0 and max to 1.

    <br>
    
    ![Slider_2.png](https://github.com/outscal/Unity-UI/blob/main/Images/Slider_2.png?raw=true)
    
-   Great! We are almost done with trying to make our slider work. For the final step we need to allocate an audio source component which will be playing our game sound to the slider.
-   In my game I have created a standalone script that takes care of the whole UI of our game which goes by the name "game manager".
-   As my game manager is handling the UI for my complete game(also the sound of the game included), I will allocate the audio source(audiosource.volume) of the game manager.

    <br>
    
    ![Slider_3.png](https://github.com/outscal/Unity-UI/blob/main/Images/Slider_3.png)
