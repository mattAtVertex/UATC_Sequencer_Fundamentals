# Shooting from a Camera Rig Rail

<p>The<span>&nbsp;</span><strong>Camera Rig Rail</strong><span>&nbsp;</span>Actor can be used to produce fly-through, 360 degree, or any other moving shots by attaching a camera to a rail to move along. The path for the rail can be defined using a<span>&nbsp;</span><a id="content_link" href="https://docs.unrealengine.com/4.26/en-US/Basics/Components/Shapes"><span><strong>Spline Component</strong></span></a><span>&nbsp;</span>and in Sequencer, you can keyframe the position along the rail where the camera should be at any given time.</p>
<p>In this how-to we create a 360-degree rail where the attached camera stays focused on our character.</p>
<p>&nbsp;</p>
<p>1. <span>In your project on the&nbsp;</span><strong>Place Actors</strong><span>&nbsp;panel in the&nbsp;</span><strong>Cinematic</strong><span>&nbsp;tab, drag a&nbsp;</span><strong>Camera Rig Rail</strong><span>&nbsp;asset into the level.</span></p>
<p><img src="https://vertexschool.instructure.com/courses/314/files/20354/preview?verifier=50o0iK0JGmi2c9Wt5LYfG3JHAV3fv8TFBJczGLpe" alt="image.png" data-api-endpoint="https://vertexschool.instructure.com/api/v1/courses/314/files/20354" data-api-returntype="File"></p>
<p>&nbsp;</p>
<p><span>2. Also from the&nbsp;</span><strong>Place Actors</strong><span>&nbsp;panel in the&nbsp;</span><strong>Cinematic</strong><span>&nbsp;tab, drag in a&nbsp;</span><strong>Cine Camera Actor</strong><span>.</span></p>
<p><img src="https://vertexschool.instructure.com/courses/314/files/20355/preview?verifier=sX8OINkEohBGUG4KagdbGHlKtgHSKWOzTHRq2Cbs" alt="image.png" data-api-endpoint="https://vertexschool.instructure.com/api/v1/courses/314/files/20355" data-api-returntype="File"></p>
<p>&nbsp;</p>
<p>3. <span>In the&nbsp;</span><strong>World Outliner</strong><span>, drag-and-drop the&nbsp;</span><strong>CineCameraActor</strong><span>&nbsp;onto the&nbsp;</span><strong>CameraRig_Rail</strong><span>&nbsp;to attach it.</span></p>
<p><img src="https://vertexschool.instructure.com/courses/314/files/20356/preview?verifier=4GFcuco4UsIPd9kTmZCljIoNpyrEkT2dfn4pHUCd" alt="image.png" data-api-endpoint="https://vertexschool.instructure.com/api/v1/courses/314/files/20356" data-api-returntype="File"></p>
<p>&nbsp;</p>
<p>4. <span>In the&nbsp;</span><strong>Details</strong><span>&nbsp;panel for the&nbsp;</span><strong>CineCameraActor</strong><span>, set the&nbsp;</span><strong>XYZ</strong><span>&nbsp;for&nbsp;</span><strong>Location</strong><span>&nbsp;to&nbsp;</span><strong>0, 0, 60</strong><span>.</span></p>
<p><img src="https://vertexschool.instructure.com/courses/314/files/20357/preview?verifier=SvVRWHB3TPKcWbVkCto43aUxvOLYOlZ0becQEM9m" alt="image.png" data-api-endpoint="https://vertexschool.instructure.com/api/v1/courses/314/files/20357" data-api-returntype="File"></p>
<p>This will push the camera up slightly off the ground for our shot.</p>
<p>&nbsp;</p>
<p>5. <span>Select the&nbsp;</span><strong>CameraRigRail</strong><span>&nbsp;in the level, then select and move the end point so the rail moves to the left of the character.</span></p>
<p><img src="https://vertexschool.instructure.com/courses/314/files/20358/preview?verifier=ieSgoViHwZE9CbAxqxu7w2HTKsfc9JGZ2VaUPxhA" alt="image.png" data-api-endpoint="https://vertexschool.instructure.com/api/v1/courses/314/files/20358" data-api-returntype="File"></p>
<p>&nbsp;</p>
<p>6. <span>With the end point still selected, hold&nbsp;</span><strong>Alt</strong><span>&nbsp;then drag out another point as shown below.</span></p>
<p><img src="https://vertexschool.instructure.com/courses/314/files/20359/preview?verifier=pxxBsagjjIhLt3Pv2qCVIfahai5jx1IQGCpNr8S0" alt="image.png" data-api-endpoint="https://vertexschool.instructure.com/api/v1/courses/314/files/20359" data-api-returntype="File"></p>
<p>&nbsp;</p>
<p>7. <span>Select and move the red tangents to bend the rail to produce a curved shape.</span></p>
<p><img src="https://vertexschool.instructure.com/courses/314/files/20360/preview?verifier=nkn169dhjKQ0l6cPHBJpnlKHsSZ2LcYYAY4BFLrh" alt="image.png" data-api-endpoint="https://vertexschool.instructure.com/api/v1/courses/314/files/20360" data-api-returntype="File"></p>
<p>&nbsp;</p>
<p>8.<span>Hold&nbsp;</span><strong>Alt&nbsp;</strong><span>and drag out additional points, adjusting the&nbsp;tangents until you form a circle shape around the character.</span></p>
<p><img src="https://vertexschool.instructure.com/courses/314/files/20361/preview?verifier=2JOVlYtGFaBN6fTlgjsPWljBQSfR47r7Cfgv6tS9" alt="image.png" data-api-endpoint="https://vertexschool.instructure.com/api/v1/courses/314/files/20361" data-api-returntype="File"></p>
<p>&nbsp;</p>
<p>9. <span>From the Main Toolbar, click&nbsp;</span><strong>Cinematics</strong><span>&nbsp;then select&nbsp;</span><strong>Add Level Sequence</strong><span>.</span></p>
<p><img src="https://vertexschool.instructure.com/courses/314/files/20362/preview?verifier=94oRFi4qp49TOy312xLa5pM3otOxeBB55ZtCHp7K" alt="image.png" data-api-endpoint="https://vertexschool.instructure.com/api/v1/courses/314/files/20362" data-api-returntype="File"></p>
<p>&nbsp;</p>
<p>10. <span>Select the&nbsp;</span><strong>Camera Rig Rail</strong><span>&nbsp;and&nbsp;</span><strong>Cine Camera Actor</strong><span>&nbsp;in the Level,&nbsp;then click the&nbsp;</span><strong>Track</strong><span>&nbsp;button and&nbsp;add both to Sequencer.</span></p>
<p><img src="https://vertexschool.instructure.com/courses/314/files/20363/preview?verifier=p2jmoJKu5j2HkCnBmOHmpH0OM4xlsOWcWkuqlnX2" alt="image.png" data-api-endpoint="https://vertexschool.instructure.com/api/v1/courses/314/files/20363" data-api-returntype="File"></p>
<p>&nbsp;</p>
<p>11. <span>Add a key for the current&nbsp;</span><strong>Transform</strong><span>&nbsp;on the&nbsp;</span><strong>CineCameraActor</strong><span>.</span></p>
<p><img src="https://vertexschool.instructure.com/courses/314/files/20364/preview?verifier=0PQuIMCxlZ1LLD7g7coHFPRcTt4NZxhyF43VY5pK" alt="image.png" data-api-endpoint="https://vertexschool.instructure.com/api/v1/courses/314/files/20364" data-api-returntype="File"></p>
<p>&nbsp;</p>
<p>12. <span>On the&nbsp;</span><strong>CameraRig_Rail</strong><span>, click the&nbsp;</span><strong>+ Track</strong><span>&nbsp;button and add&nbsp;</span><strong>Current Position on Rail</strong><span>&nbsp;and a&nbsp;keyframe for the initial value.</span></p>
<p><img src="https://vertexschool.instructure.com/courses/314/files/20365/preview?verifier=taN5M8UYFhRgOYgJTCGiqMySrHOJtjCeRzDSvqwe" alt="image.png" data-api-endpoint="https://vertexschool.instructure.com/api/v1/courses/314/files/20365" data-api-returntype="File"></p>
<p><span>This value represents the position of the attached camera where&nbsp;</span><strong>0</strong><span>&nbsp;is at the start of the rail and&nbsp;</span><strong>1</strong><span>&nbsp;is the end of the rail.</span></p>
<p>&nbsp;</p>
<p>13.&nbsp;Move the Timeline marker to the end of the Sequence (frame&nbsp;<strong>150</strong>).</p>
<p>&nbsp;</p>
<p><span>14. With the&nbsp;</span><strong>Camera Rig Rail</strong><span>&nbsp;selected, in the&nbsp;</span><strong>Details</strong><span>&nbsp;panel set the&nbsp;</span><strong>Current Position on Rail</strong><span>&nbsp;to&nbsp;</span><strong>1.0</strong><span>&nbsp;then add a keyframe.</span></p>
<p><img src="https://vertexschool.instructure.com/courses/314/files/20366/preview?verifier=Dx0Jj7ylyPbSgZxKNXUUlNL23TtezztP21ZVEsmp" alt="image.png" data-api-endpoint="https://vertexschool.instructure.com/api/v1/courses/314/files/20366" data-api-returntype="File"></p>
<p>&nbsp;</p>
<p>15. <span>For the&nbsp;</span><strong>Cine Camera Actor</strong><span>, check&nbsp;</span><strong>Enable Look at Tracking</strong><span>&nbsp;for the&nbsp;</span><strong>ThirdPersonCharacter</strong><span>&nbsp;with a&nbsp;</span><strong>Z</strong><span>&nbsp;offset of&nbsp;</span><strong>45.0</strong><span>.</span></p>
<p><img src="https://vertexschool.instructure.com/courses/314/files/20367/preview?verifier=CED8iXWueiOMYHZMiwui2fEVW68N49U1fS3so5oB" alt="image.png" data-api-endpoint="https://vertexschool.instructure.com/api/v1/courses/314/files/20367" data-api-returntype="File"></p>
<p><span>Here we are setting our camera to always follow the location of the&nbsp;</span><strong>Actor to Track</strong><span>, in this case the&nbsp;</span><strong>ThirdPersonCharacter</strong><span>.</span></p>
<p>&nbsp;</p>
<p>16. Lock the viewport to the<span>&nbsp;</span><strong>Camera Cut Track</strong><span>&nbsp;</span>then click the preview play button.</p>
<p>&nbsp;</p>
<p>&nbsp;</p>
<p>&nbsp;</p>
<p>&nbsp;</p>
<p>&nbsp;</p>