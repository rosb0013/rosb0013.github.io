My Portfolio site has been created utilizing Bootstrap as much as possible. The way Bootstrap streamlines development is a godsend when it comes to quickly creating and adjusting content, making layout edits with grids. 

Challenges
Determining ideal content amount to not overwhelm mobile usage.
Emebding video: Discovered how to embed YouTube content from my personal YouTube portfolio to bypass the need for direct content upload to a folder on my site, using space that can remain free. 
Understanding the code for photo carousel and what each class item does, how to manipulate image change timing.

-----
Working with Bootstrap Embeds for YouTube content

    <div class="embed-responsive embed-responsive-16by9">
    <iframe class="embed-responsive-item" src="..." allowfullscreen></iframe>
    </div>

    Struggled with sizing for embeded YouTube content as iFrame was throwing validation errors. After much searching online, I was able to find 
    others that had the same issue. Using the stlye= within the iFrame fixed the sizing issue and cleared the validation error.

-----
When HTML validating, received the following error, however when checking BOOTSTRAP nav help.
    Error: Stray start tag nav.

    N BAR -->↩<nav class="navbar navbar-expand-lg navbar-light bg-light">↩    <
    Fatal Error: Cannot recover after last error. Any further errors will be ignored.

    N BAR -->↩<nav class="navbar navbar-expand-lg navbar-light bg-light">↩    <

Took me a VERY long time to realize my  </body> tag was in the wrong spot. 

-----
Took me a long time to figure out where to use the center-text class goesnav according text. 

-----
Overcoming Challenges
Layout challenges were overcome as Bootstrap makes it so much easier to quickly develop and control layout, add components, etc. 
The Bootstrap site contains EXTENSIVE examples for EVERY component and class(es) access.
Google searching any validation errors I was stuck on helped put me on the right path for solutions.
Determining ideal grid layout(s) was achieved through trial and error. 
Researching carousels outside of the BootStrap site Help, helped me to overcome isues. 


-----------------------------------------------------------------------------------
NOTES: 
- ALL images, videos and graphics are original content created by me.
- Fonts provided by Google Fonts
- Components provided via Bootstrap
- BootStrap is a GODSEND! It has changed my entire view on responsive web development!
-----------------------------------------------------------------------------------
