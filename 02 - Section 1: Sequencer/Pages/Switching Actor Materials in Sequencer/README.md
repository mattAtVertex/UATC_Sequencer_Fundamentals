# Switching Actor Materials in Sequencer

<p>The<span>&nbsp;</span><strong>Material Element Switcher</strong><span>&nbsp;</span>track is a Sequencer track that you can use to animate Materials on an Actor. This enables you to change materials on an Actor by adding keys for specific materials on the track.</p>
<p>For this how to, we can use the Paragon Phase and Fey materials from the Epic Marketplace. You can see that we already have a Material Element Switcher for Phase's Skirt. This is so we can easily see the change in materials in contrast with the jacket.</p>
<ol>
<li class="Default">
<p>Navigate to<span>&nbsp;</span><strong>Cinematics</strong><span>&nbsp;</span>&gt;<span>&nbsp;</span><strong>Add Level Sequence</strong>. Name and save the sequence, such as "MaterialAnim", and then open it from the<span>&nbsp;</span><strong>Content Browser</strong>.</p>
</li>
<li class="Default">
<p>Add the Skeletal Mesh for your actor to the Viewport. Then add the mesh as a track to your sequence.</p>
</li>
<li class="Default">
<p>Under<span>&nbsp;</span><strong>Skeletal Mesh</strong><span>&nbsp;</span>Component, add a new<span>&nbsp;</span><strong>Track</strong><span>&nbsp;</span>and select a<span>&nbsp;</span><strong>Material Element Switcher</strong>. You can find which material number corresponds to the element you want to change on the actor in the Skeletal Mesh animation Blueprint.</p>
</li>
</ol>
<p><img src="https://vertexschool.instructure.com/courses/314/files/20320/preview?verifier=bGKEoHkH8BFWMMpqbmF768xd701nEhplMpTY1fOC" alt="image.png" data-api-endpoint="https://vertexschool.instructure.com/api/v1/courses/314/files/20320" data-api-returntype="File"></p>
<p><span>In this example, I want to change the jacket material, which is Material Element 10.</span></p>
<p><span>1. In the dropdown labeled&nbsp;</span><strong>None</strong><span>, select the first material for the sequence. Then, add a key for this material in the Sequence.</span></p>
<p><img src="https://vertexschool.instructure.com/courses/314/files/20321/preview?verifier=pQEVPtF5cWNswU1lx4ZKl7nShBnyvjyXSDslMRwA" alt="image.png" data-api-endpoint="https://vertexschool.instructure.com/api/v1/courses/314/files/20321" data-api-returntype="File"></p>
<p><img src="https://vertexschool.instructure.com/courses/314/files/20322/preview?verifier=ZR5A6Rxcymqv699edJWDQQv84c3xgb8Z41cemeY7" alt="image.png" data-api-endpoint="https://vertexschool.instructure.com/api/v1/courses/314/files/20322" data-api-returntype="File"></p>
<p><span>In this example, we will start with&nbsp;</span><strong>MIC_Phase_jacket</strong><span>, which is Phase's jacket material.</span></p>
<p>&nbsp;</p>
<p><span>2. Move the slider along the&nbsp;</span><strong>Timeline</strong><span>&nbsp;to where you want to change materials. Using the dropdown, select a new material and add a new key to the sequence.</span></p>
<p><img src="https://vertexschool.instructure.com/courses/314/files/20323/preview?verifier=dyNDzGqSskUfhEXsPOLglix3SPjXg0hy0ulYtWdS" alt="image.png" data-api-endpoint="https://vertexschool.instructure.com/api/v1/courses/314/files/20323" data-api-returntype="File"></p>
<p>In this example, we changed the material to the<span>&nbsp;</span><strong>M_Fey_Armours</strong><span>&nbsp;</span>material.</p>
<p>&nbsp;</p>
<p><span>3. Repeat the previous step to add a third material.</span></p>
<p><img src="https://vertexschool.instructure.com/courses/314/files/20324/preview?verifier=HYKBONCvlz3lep7ypP5IPYbXievrmcY9MxA1K6Fp" alt="image.png" data-api-endpoint="https://vertexschool.instructure.com/api/v1/courses/314/files/20324" data-api-returntype="File"></p>
<p><span>In this example, we change the material to the&nbsp;</span><strong>M_Fey_Plantseed</strong><span>&nbsp;material.</span></p>
<p>&nbsp;</p>
<p><span>4. The last material change is back to Phase's&nbsp;original jacket material, MIC_Phase_jacket. Move the slider and add a key to change the material again. In this example, I change the jacket material before the skirt material changes at the end of the sequence.</span></p>
<p><img src="https://vertexschool.instructure.com/courses/314/files/20325/preview?verifier=E7LIa4jFKajmg57iQREHmLT6ls93EYrhygsKeVJI" alt="image.png" data-api-endpoint="https://vertexschool.instructure.com/api/v1/courses/314/files/20325" data-api-returntype="File"></p>
<p><span>You can now playback the sequence and watch the materials change.</span></p>
<p>&nbsp;</p>
<p>&nbsp;</p>
<p>&nbsp;</p>
<p>&nbsp;</p>