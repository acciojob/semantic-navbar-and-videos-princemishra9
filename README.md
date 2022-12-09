Make a semantic navbar i. e using semantic elements ex:- nav, ul, a.

 It should have total of 3 links in the nav, "Home" "About us" and "Contact us".
 
 Give any href of your choice.
 

 Also, add 3 videos using these URLs, do not forget to put attribute to display the controls.
 1) http://commondatastorage.googleapis.com/gtv-videos-bucket/sample/BigBuckBunny.mp4
 2) http://commondatastorage.googleapis.com/gtv-videos-bucket/sample/ForBiggerBlazes.mp4
 3) http://commondatastorage.googleapis.com/gtv-videos-bucket/sample/SubaruOutbackOnStreetAndDirt.mp4
 

 Add the heading "3 random videos" above the videos.
<!DOCTYPE html>
<html>
<head>
     <link rel="stylesheet" href="styles.css">
</head>
<body>
<!-- the entire body must be written by student -->
    <script type="text/javascript" src="./script.js">
    </script>
    <nav>
        <ul>
            <li><a href="https://course.acciojob.com/modules">Home</a></li>
            <li><a href="https://blog.hubspot.com/hs-fs/hubfs/about-cover.png?width=305&name=about-cover.png">About us</a></li>
            <li><a href="https://cdn.searchenginejournal.com/wp-content/uploads/2020/08/contact-us-pages-sej-5f63d4f927b04-760x400.png">contact us</a></li>
        </ul>
    </nav>
            <h3>3 random videos</h3>
           <video height="200px" width="400px" controls>
            <source src="http://commondatastorage.googleapis.com/gtv-videos-bucket/sample/BigBuckBunny.mp4">        
           </video>
           <video height="200px" width="400px" controls>
            <source src="http://commondatastorage.googleapis.com/gtv-videos-bucket/sample/ForBiggerBlazes.mp4">
           </video>
           <video height="200px" width="400px" controls>
            <source src="http://commondatastorage.googleapis.com/gtv-videos-bucket/sample/SubaruOutbackOnStreetAndDirt.mp4">
           </video>
      
   
</body>
</html>
