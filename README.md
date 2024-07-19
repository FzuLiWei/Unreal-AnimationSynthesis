Unreal-AnimationSynthesis

(1) Animation Splitting

Description

<img src="https://github.com/FzuLiWei/Unreal-AnimationSynthesis/blob/master/1.png"/>

Drag the source animation to be split into the "Source Animation" field, then click the "DETACH" button to perform the split. After splitting, by default, only the "Lower Body" contains pelvis bone data, while other parts do not.

(2) Animation Blending

Description

<img src="https://github.com/FzuLiWei/Unreal-AnimationSynthesis/blob/master/2.png"/>

Drag the animations of different body parts to their respective slots (you can directly drag the entire animation), then click the "BLEND" button to merge them. Currently, "Lower Body" is used as the default layer (with pelvis bone data), and only the pelvis bone data from "Lower Body" is taken as the target animation's pelvis bone data.
Final animation and cached animation storage location (Cache directory can be deleted):

<img src="https://github.com/FzuLiWei/Unreal-AnimationSynthesis/blob/master/3.png"/>

Note: The prerequisite for merging is to use animations with a consistent frame rate (you can modify the Custom FrameRate when importing animations, Unreal does not support non-multiples modification after import).

1.Custom Frame Count: The plugin supports customizing the frame count for the final generated animation. You can choose the minimum frame count, maximum frame count, or specify a specific frame count to control the duration of the animation based on the scene or requirements.

<img src="https://github.com/FzuLiWei/Unreal-AnimationSynthesis/blob/master/4.png"/>

2.Linear Interpolation: The plugin provides linear interpolation functionality, allowing you to smoothly transition animations. By specifying the number of frames in the input field, you can perform linear interpolation starting from the last frame of the animation, resulting in a smooth transition effect when the animation is played. This is useful for creating transition animations or making animations more fluid.

<img src="https://github.com/FzuLiWei/Unreal-AnimationSynthesis/blob/master/5.png"/>

Note: Set to 0 to disable interpolation for the final generated animation;

<img src="https://github.com/FzuLiWei/Unreal-AnimationSynthesis/blob/master/6.png"/>

3.Frame Addition: The plugin also offers frame addition functionality, allowing you to add extra frames to a specified animation using linear interpolation. This allows you to extend the duration of the animation or add details to achieve a richer and more accurate animation effect.

<img src="https://github.com/FzuLiWei/Unreal-AnimationSynthesis/blob/master/7.png"/>

4.Metahuman Support: The plugin is designed specifically for Metahuman character skeletal animations, making it fully compatible with Metahuman characters and Standard skeleton compatible with unreal4 and unreal5.


Youtube URL:  ( Click Image )

<a href="https://youtu.be/ksSYVi3xyiQ" title="Unreal 5 : Animation Splitting And Blending"><img src="https://github.com/FzuLiWei/Unreal-AnimationSynthesis/blob/master/THUMBNAIL.png" /></a>

v1.0.2 NEW FEATURE : Preview Animation ( Click Image )

<a href="https://youtu.be/DNUZxwqkm_E" title="Unreal 5 : Animation Splitting And Blending"><img src="https://github.com/FzuLiWei/Unreal-AnimationSynthesis/blob/master/THUMBNAIL.png" /></a>

v1.0.3 NEW FEATURE : Blending On Sequencer  ( Click Image )

<a href="https://youtu.be/4CblOU60K7g" title="Unreal 5 : Animation Splitting And Blending"><img src="https://github.com/FzuLiWei/Unreal-AnimationSynthesis/blob/master/THUMBNAIL.png" /></a>

v1.0.4 NEW FEATURE : Batch Blending  ( Click Image )

<a href="https://youtu.be/jbjeYupzrO4" title="Unreal 5 : Animation Splitting And Blending"><img src="https://github.com/FzuLiWei/Unreal-AnimationSynthesis/blob/master/THUMBNAIL.png" /></a>

v1.0.5 NEW FEATURE : Lock Foot Position, solve the foot sliding  ( Click Image )

<a href="https://youtu.be/9hku8yniA34" title="Unreal 5 : Animation Splitting And Blending"><img src="https://github.com/FzuLiWei/Unreal-AnimationSynthesis/blob/master/THUMBNAIL.png" /></a>

