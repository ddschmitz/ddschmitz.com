How to use lightbox.  http://lokeshdhakar.com/projects/lightbox2/#examples

Start with an <a> tag and add an href to it.  The href should point to the location of the image just like a normal anchor tag with an href.  Add a data-lightbox attribute
to any image link to enable Lightbox For the value of the attribute, use a unique name for each image.  Optional: Add a data-title attribute if you want to show a caption.
Inside place a normal image tag with the src as the location of the image. 

<a href="Image Location" data-lightbox="Unique Name" data-title="Title for the image"><img src="Image Location"/></a>

You also need to include these at the top of the page.

    <script src="/Lightbox/js/jquery-1.11.0.min.js"></script>
    <script src="/Lightbox/js/lightbox.min.js"></script>
    <link href="/Lightbox/css/lightbox.css" rel="stylesheet" />

Examples:

<a href="/Images/Proj3_Case_Image.jpg" data-lightbox="Case_Image" data-title="The outside of the case before the removal of the hard drive."><img src="/Images/Proj3_Case_Image.jpg" alt="Image of case." class="Proj3Images"/></a>
<a href="/Images/Proj3_Case_Internals_Before.jpg" data-lightbox="Case_Internals_Before" data-title="Inside of the case before dusting and with the new hard drive shown."><img class="Proj3Images" src="/Images/Proj3_Case_Internals_Before.jpg" alt="Image of case internals before dusting."/></a>
<a href="/Images/Proj3_Case_Internals_After.jpg" data-lightbox="Case_Internals_After" data-title="Inside of the case with the CPU fan and new HDD."><img class="Proj3Images" src="/Images/Proj3_Case_Internals_After.jpg" alt="Image of case internals after dusting."/></a>
<a href="/Images/Proj3_Finished.jpg" data-lightbox="Final_Set_Up" data-title="Final set-up after everything is installed and plugged in."><img class="Proj3Images" src="/Images/Proj3_Finished.jpg" alt="Image of everything set-up"/></a>


<a href="/Images/Terminator_Pics/DynoRun1.png" data-lightbox="Dyno_Sheet_1"><img src="/Images/Terminator_Pics/DynoRun1.png" alt="First Dyno Run" class="DynoRunPics"/></a>