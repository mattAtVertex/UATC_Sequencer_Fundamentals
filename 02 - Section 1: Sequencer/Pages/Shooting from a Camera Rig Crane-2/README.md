# Shooting from a Camera Rig Crane-2

<p>One of the methods real-world filmmakers use to produce smooth, sweeping shots, is by attaching a camera to a crane and controlling the shot with the crane's movement. You can create similar shots in Sequencer with the use of the<span>&nbsp;</span><strong>Camera Rig Crane</strong><span>&nbsp;</span>Actor and an attached<span>&nbsp;</span><strong>Camera</strong>. You can keyframe the crane's Pitch, Yaw, or the length of the Crane Arm, as well as Lock the Mounted Camera's Pitch or Yaw (which will follow the crane's movement).</p>
<p>In this guide, we will add a Camera Rig Crane, attach a Camera, and create a sample Crane Shot as indicated in the example below:</p>
<p>&nbsp;</p>
<p><span>1. In the Level Viewport of your project, select the&nbsp;</span><strong>ThirdPersonCharacter</strong><span>, then hold&nbsp;</span><strong>Alt</strong><span>, click a translation widget arrow and drag out, then rotate the copy so that it faces the existing character.</span></p>
<p><img src="https://vertexschool.instructure.com/courses/314/files/20339/preview?verifier=FrySpwk0d9Wb2xU1ZPIbqffpnRGrCKsYoIad0d6b" alt="image.png" data-api-endpoint="https://vertexschool.instructure.com/api/v1/courses/314/files/20339" data-api-returntype="File"></p>
<p>These two characters are going to be the subject of our crane shot.</p>
<p>&nbsp;</p>
<p><span>2. </span><span>From the Main Toolbar, click the&nbsp;</span><strong>Cinematics</strong><span>&nbsp;button, then select&nbsp;</span><strong>Add Level Sequence</strong><span>&nbsp;from the drop-down menu.</span></p>
<p><img src="https://vertexschool.instructure.com/courses/314/files/20340/preview?verifier=c6q9UbB44o7240KlvMHji17zbupa6Gn9tJU54X4x" alt="image.png" data-api-endpoint="https://vertexschool.instructure.com/api/v1/courses/314/files/20340" data-api-returntype="File"></p>
<p>&nbsp;</p>
<p>3. From the<span>&nbsp;</span><strong>Place Actors</strong><span>&nbsp;</span>panel in the<span>&nbsp;</span><strong>Cinematic</strong><span>&nbsp;</span>tab, drag a<span>&nbsp;</span><strong>Camera Rig Crane</strong><span>&nbsp;</span>into the level.</p>
<p><img src="https://vertexschool.instructure.com/courses/314/files/20341/preview?verifier=txTT1JrXglSv1oH7zE271QaUn7Zz4kISfbqTNyZv" alt="image.png" data-api-endpoint="https://vertexschool.instructure.com/api/v1/courses/314/files/20341" data-api-returntype="File"></p>
<p>&nbsp;</p>
<p>4. <span>From the&nbsp;</span><strong>Place Actors</strong><span>&nbsp;panel in the&nbsp;</span><strong>Cinematic</strong><span>&nbsp;tab, drag a&nbsp;</span><strong>Cine Camera Actor</strong><span>&nbsp;into the level.</span></p>
<p><img src="https://vertexschool.instructure.com/courses/314/files/20342/preview?verifier=0KlY93mWuqy4b0CxxXpA1Hzn00uNRomChMIWT2tE" alt="image.png" data-api-endpoint="https://vertexschool.instructure.com/api/v1/courses/314/files/20342" data-api-returntype="File"></p>
<p>&nbsp;</p>
<p>5. In the<span>&nbsp;</span><strong>World Outliner</strong><span>&nbsp;</span>panel, drag the<span>&nbsp;</span><strong>Cine Camera Actor</strong><span>&nbsp;</span>on top of the<span>&nbsp;</span><strong>Camera Rig Crane</strong><span>&nbsp;</span>to attach it.</p>
<p><img src="https://vertexschool.instructure.com/courses/314/files/20343/preview?verifier=0dLjbloYxGwvPyLi0c8YexkHy4W8xJvLz0bzTmoP" alt="image.png" data-api-endpoint="https://vertexschool.instructure.com/api/v1/courses/314/files/20343" data-api-returntype="File"></p>
<p>This will attach the camera to the crane, allowing it to move where the crane moves.</p>
<p>&nbsp;</p>
<p>6.&nbsp; In the<span>&nbsp;</span><strong>Details</strong><span>&nbsp;</span>panel for the<span>&nbsp;</span><strong>Cine Camera Actor</strong>, set the<span>&nbsp;</span><strong>Location</strong><span>&nbsp;</span>and<span>&nbsp;</span><strong>Rotation</strong><span>&nbsp;</span>values to<span>&nbsp;</span><strong>0.0</strong>.</p>
<p><img src="https://vertexschool.instructure.com/courses/314/files/20344/preview?verifier=cPkCxy78X5a3NjPMh8uRn2ZTSl5hVQZ7qdWzAvUa" alt="image.png" data-api-endpoint="https://vertexschool.instructure.com/api/v1/courses/314/files/20344" data-api-returntype="File"></p>
<p>This will allow the camera to be attached to the Camera Rig Crane's mount position.</p>
<p>&nbsp;</p>
<p>7. Make any adjustments to the position of the<span>&nbsp;</span><strong>Camera Rig Crane</strong><span>&nbsp;</span>to set up your shot (below, the position is behind the character).</p>
<p><img src="https://vertexschool.instructure.com/courses/314/files/20345/preview?verifier=yACOmxyP9bHsLeYPwh6aYdvs7k05klrYE85RpJq4" alt="image.png" data-api-endpoint="https://vertexschool.instructure.com/api/v1/courses/314/files/20345" data-api-returntype="File"></p>
<p>&nbsp;</p>
<p>8. <span>Hold&nbsp;</span><strong>Ctrl</strong><span>&nbsp;and select the&nbsp;</span><strong>Camera Rig Crane</strong><span>&nbsp;and&nbsp;</span><strong>Cine Camera Actor</strong><span>&nbsp;(so that both are selected), then click&nbsp;</span><strong>Add</strong><span>&nbsp;in Sequencer and add both to the Level Sequence.</span></p>
<p><img src="https://vertexschool.instructure.com/courses/314/files/20346/preview?verifier=cVt2D0evvEzZHlPeKA3pxY6kGwDgegV6JmUugiC3" alt="image.png" data-api-endpoint="https://vertexschool.instructure.com/api/v1/courses/314/files/20346" data-api-returntype="File"></p>
<p>&nbsp;</p>
<p><span>9. Select the&nbsp;</span><strong>Camera Rig Crane</strong><span>, then in the&nbsp;</span><strong>Details</strong><span>&nbsp;panel, click the&nbsp;</span><strong>Add Key</strong><span>&nbsp;button for&nbsp;</span><strong>Crane Pitch</strong><span>,&nbsp;</span><strong>Crane Yaw</strong><span>&nbsp;and&nbsp;</span><strong>Crane Arm Length</strong><span>.</span></p>
<p><img src="https://vertexschool.instructure.com/courses/314/files/20347/preview?verifier=umsgMkIkYqaGx1jsNOcKT3zsAr37Yn4P04M2IJaq" alt="image.png" data-api-endpoint="https://vertexschool.instructure.com/api/v1/courses/314/files/20347" data-api-returntype="File"></p>
<p>This will set the default position of each to start the sequence.</p>
<p>&nbsp;</p>
<p><span>10. In Sequencer, select the&nbsp;</span><strong>Cine Camera Actor</strong><span>, then press the&nbsp;</span><strong>S</strong><span>&nbsp;key.</span></p>
<p><img src="https://vertexschool.instructure.com/courses/314/files/20348/preview?verifier=ugNg0g8qndzbGUtYrK42bKVVTwunxklOXzhTTjKr" alt="image.png" data-api-endpoint="https://vertexschool.instructure.com/api/v1/courses/314/files/20348" data-api-returntype="File"></p>
<p><span>This is a shortcut for adding a key for the current&nbsp;</span><strong>Transform</strong><span>&nbsp;values, initializing the camera's position.</span></p>
<p>&nbsp;</p>
<p><span>11. Scrub the Timeline to frame&nbsp;</span><strong>50</strong><span>, changing the&nbsp;</span><strong>Crane Pitch</strong><span>&nbsp;value on the&nbsp;</span><strong>Camera Rig Crane</strong><span>&nbsp;to&nbsp;</span><strong>40.0</strong><span>, and then click the&nbsp;</span><strong>Add Key</strong><span>&nbsp;button.</span></p>
<p><img src="https://vertexschool.instructure.com/courses/314/files/20349/preview?verifier=waEnJUNejJk472r4pxe368HIxOjF8JN3VZQgKZ7m" alt="image.png" data-api-endpoint="https://vertexschool.instructure.com/api/v1/courses/314/files/20349" data-api-returntype="File"></p>
<p><span>If you move the Timeline back to 0 and scrub through to 50, you will see the crane move between the two keyframes.</span></p>
<p>&nbsp;</p>
<p>12. <span>With the Timeline at frame&nbsp;</span><strong>50</strong><span>, select the&nbsp;</span><strong>Cine Camera Actor</strong><span>, and then press&nbsp;</span><strong>S</strong><span>&nbsp;to add another keyframe.</span></p>
<p><img src="https://vertexschool.instructure.com/courses/314/files/20350/preview?verifier=F4O8JGpJcGIOKRMThnHroGzJWszQJddC0Vr0uJkX" alt="image.png" data-api-endpoint="https://vertexschool.instructure.com/api/v1/courses/314/files/20350" data-api-returntype="File"></p>
<p>&nbsp;</p>
<p><span>13. Scrub the Timeline ahead to the end of the shot, change the&nbsp;</span><strong>Crane Yaw</strong><span>&nbsp;and&nbsp;</span><strong>Crane Arm Length</strong><span>&nbsp;to&nbsp;</span><strong>75</strong><span>&nbsp;and&nbsp;</span><strong>600</strong><span>&nbsp;respectively, then add keys for each.</span></p>
<p><img src="https://vertexschool.instructure.com/courses/314/files/20351/preview?verifier=Kgqa4UjgyVJ3GVUzsMWeOdoGYAKG3wkRUJA5CXe6" alt="image.png" data-api-endpoint="https://vertexschool.instructure.com/api/v1/courses/314/files/20351" data-api-returntype="File"></p>
<p>You should see the values shift between keyframes for the Crane Yaw and Crane Arm Length as you scrub through the Timeline.</p>
<div>
<div id="player_d7K3mHA0bXM_386"></div>
</div>
<p>&nbsp;</p>
<p>14. Rotate the camera in the Level Viewport to frame up the two characters, then press<span>&nbsp;</span><strong>S</strong><span>&nbsp;</span>to add a keyframe for the position.</p>
<p><img src="https://vertexschool.instructure.com/courses/314/files/20352/preview?verifier=PFXD8Jzbedl1cTisrNoy5PYau5cmxZQnkTAl8U8B" alt="image.png" data-api-endpoint="https://vertexschool.instructure.com/api/v1/courses/314/files/20352" data-api-returntype="File"></p>
<p>&nbsp;</p>
<p><span>15. In Sequencer, click the&nbsp;</span><strong>Camera Lock</strong><span>&nbsp;button on the&nbsp;</span><strong>Cine Camera Actor</strong><span>&nbsp;track.</span></p>
<p><img src="https://vertexschool.instructure.com/courses/314/files/20353/preview?verifier=9PYh5YGAH2zazDXjlG8YxOqdLQ6XMViVSwvgYDLf" alt="image.png" data-api-endpoint="https://vertexschool.instructure.com/api/v1/courses/314/files/20353" data-api-returntype="File"></p>
<p><span>This will lock the viewport to the perspective of the camera and allow us to view what the shot will look like when using this camera.</span></p>
<p>&nbsp;</p>
<p>&nbsp;</p>