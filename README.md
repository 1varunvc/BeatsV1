# Beatsv1
https://1varunvc.github.io/BeatsV1/

The website is not mobile-compatible.

# Release Notes
## 1.0.0

This update includes:  
  -Only the 'used' CSS.  
  [That is, all the unused CSS is removed using PurifyCSS Online.  
  It also removed CSS for h1 and h2 tag, which had to be added manually then. CSS for H1 and H2 is resposible for fonts.
  It also removed CSS for another tag (I don't remeber which one), but the CSS for it also got added, so nothing to worry about.)
   
  -All the JS was unnecessary, hence, got removed in Beatsv1-mains.
  -BS5 CSS files via local external files. [That is, external CDN Link removed. The local file only includes the 'used' CSS.]  
  -Correct src to all the pages.  
  -Correct href to all the images.  
  -Correct links to all the CSS files.  
  -Removed <div ng-app="myApp"></div> from every page.  
   
 Everything looks ALMOST originally the way, I showed to my teacher on the day of internal viva in December, 2020.  
  -'Beats' in navbar padding-left modifiied to 15px, inline. Hence, it doesn't use navbar-brand class for 'padding-LEFT', although it's mentioned there 'cause it might be dedicating to OTHER styling options.]
  
  -Text for other links on the navbar, appear sharper, unlike earlier, when they looked softer (somewhat blurred) for reasons unknown.  
  -Text on the cards appear sharper, unlike earlier, when they looked softer (somewhat blurred) for reasons unknown.  
  -Also, the text on cards doesn't get blur on hover. Reason unknown.
  
  -The music player doesn't react on hover. Unlike earlier, when it used to get zoomed-in on hover, and everything get somewhat blurred. This zooming-in also added difficulty in selecting tracks.  
  
  -Removing
  {Edit readme.md on GitHub to view what's written here
      <ul class="navbar-nav ml-auto">
        <li class="nav-item">
          <a class="nav-link" href="">|</a>
        </li>
      </ul>
  }
      or removing just the "|" from the anchor tag, 'causes the navigation bar to get thin. That is, 'padding' gets reduced.
      
   -'ml-auto' class, used to align list items in navbar, changed to 'ms-auto' to fit BS5 standards.  
   ['ml-auto' class exists in in BS4. 'ms-auto' class exists in in BS5.]
      
