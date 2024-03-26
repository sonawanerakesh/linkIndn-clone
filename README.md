# linkIndn-clone
used html,css and js using made this profile in linkdn
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>my profile</title>
    <link rel="stylesheet" href="style.css">
</head> 
<body>
    <nav class="navbar">
        <div class="navbar-left">
            <a href="index.html" class="logo"><img src="logo.png"></a>
            <div class="search-box">
                <img src="search.png" alt="">
                <input type="text" placeholder="search">
            </div>
        </div>
        <div class="navbar-center">
            <ul>
                <li><a href="#" class="active-link"><img src="home.png"><span>Home</span></a></li>
                <li><a href="#"><img src="network.png"><span>my network</span></a></li>
                <li><a href="#"><img src="jobs.png"><span>Jobs</span></a></li>
                <li><a href="#"><img src="notification.png"><span>Notifications</span></a></li>
            </ul>
        </div>
        <div class="navbar-right">
            <div class="online">
                <img src="user-1.jpg" class="nav-profile-img" onclick="toggleMenu()">
            </div>
        </div>
  <!-- ------------------profile-drop-down-menu -----------------------                           -->
    <div class="profile-menu-wrap" id="profileMenu">
        <div class="profile-menu">
            <div class="user-info">
                <img src="user-1.jpg">
                <div>
                    <h3>Rakesh Sonawane</h3>
                    <a href="profile.html.html">See your profile</a>
                </div>
            </div>
            <hr>
            <a href="#" class="profile-menu-link">
                <img src="feedback.png">
                <p>Give Feedback</p>
                <span>></span>
            </a>
            <a href="#" class="profile-menu-link">
                <img src="setting.png">
                <p>setting & Privacy</p>
                <span>></span>
            </a>
            <a href="#" class="profile-menu-link">
                <img src="help.png">
                <p>Help & Support</p>
                <span>></span>
            </a>
            <a href="#" class="profile-menu-link">
                <img src="display.png">
                <p>Display& Accessibility</p>
                <span>></span>
            </a>
            <a href="#" class="profile-menu-link">
                <img src="logout.png">
                <p>logout</p>
                <span>></span>
            </a>
        </div>
    </div>
    </nav>
    
<!---------------------- -----------------left-sidebar---------------------- ---------------------------------->
<div class="container">
    <!-- left sidebar  -->
    <div class="left-sidebar">
        <div class="sidebar-profile-box">
            <img src="cover-pic.png" width="100%">
            <div class="sidebar-profile-info">
                <img src="user-1.jpg">
                <h1>Rakesh Sonawane</h1>
                <h3>Seeking a frontend Development at company</h3>
                <ul>
                    <li>Your profile views<span>52</span></li>
                    <li>Your post views<span>252</span></li>
                    <li>Your connections<span>912</span></li>
                </ul>
            </div>
            <div class="sidebar-profile-info-link">
                <a href="#"><img src="items.png">My items</a>
                <a href="#"><img src="premium.png">Try items</a>
            </div>
        </div>
        <div class="sidebar-activity" id="sidebarActivity">
            <h3>RECENT</h3>
            <a href="#"><img src="recent.png">Web Development</a>
            <a href="#"><img src="recent.png">User Interface</a>
            <a href="#"><img src="recent.png">Online Learning</a>
            <a href="#"><img src="recent.png">Learn Online</a>
            <a href="#"><img src="recent.png">Code better</a>
            <a href="#"><img src="recent.png">Group Learning</a>
            <h3>GROUPS</h3>
            <a href="#"><img src="group.png">Web Designer Group</a>
            <a href="#"><img src="group.png">HTML and css Learner</a>
            <a href="#"><img src="group.png">Python and javascript group</a>
            <a href="#"><img src="group.png">Learn code online</a>
            <h3>HASGTAG</h3>
            <a href="#"><img src="hashtag.png">WebDevelopment</a>
            <a href="#"><img src="hashtag.png">UserInterface</a>
            <a href="#"><img src="hashtag.png">OnlineLearning</a>
            <div class="discover-mode-link">
                <a href="#">Discover More</a>
            </div>
        </div>
        <p id="showMoreLink" onclick="toggleActivity">Shoe More <b>+</b></p>
    </div>
<!--- main content -->
    <div class="main-content">
        <div class="create-post">
            <div class="create-post-input">
                <img src="user-1.jpg">
                <textarea rows="2" placeholder="Write a post"></textarea>
            </div>
            <div class="create-post-link">
                <li><img src="photo.png">photo</li>
                <li><img src="video.png">video </li>
                <li><img src="event.png">Event</li>
                <li>Post</li>
            </div>
        </div>
        <div class="sort-by">
            <hr>
            <p>Sort by: <span>top <img src="down-arrow.png" ></span></p>
        </div>
        <div class="post">
            <div class="post-author">
                <img src="user-3.png">
                <div>
                    <h1>Benjamin Leo</h1>
                    <small>Founder< and Ceo at Geoogle group | Angel Inverstor </small>
                    <small>2 hours ago</small>
                </div>
            </div>
            <p>The Sucess of every website it Depends upons The search engine optimization and Digital marketing Straterg
            <img src="post-image-1.png " width="100%">
            <div class="post-stats">
                <div>
                    <img src="thumbsup.png">
                    <img src="love.png">
                    <img src="clap.png">
                    <span class="liked-users">Abhishek Pande and 75 others</span>
                </div>
                <div>
                    <span>22 comments &middot 40 shares</span>
                </div>
            </div>
            <div class="post-activity">
                <div>
                    <img src="user-1.jpg" class="post-activity-user-icon">
                    <img src="down-arrow.png" class="post-activity-Arrow-icon">
                </div>
                <div class="post-activity-link">
                    <img src="like.png">
                    <span>Like</span>
                </div>
                <div class="post-activity-link">
                    <img src="comment.png">
                    <span>Comment</span>
                </div>
                <div class="post-activity-link">
                    <img src="share.png">
                    <span>Share</span>
                </div>
                <div class="post-activity-link">
                    <img src="send.png">
                    <span>Send</span>
                </div>
            </div>
        </div>
        <div class="post">
            <div class="post-author">
                <img src="user-4.png">
                <div>
                    <h1>Clarince George</h1>
                    <small>Founder< and Ceo at Geoogle group | Angel Inverstor </small>
                    <small>2 hours ago</small>
                </div>
            </div>
            <p>The Sucess of every website it Depends upons The search engine optimization and Digital marketing Straterg
            <img src="post-image-2.png" width="100%">
            <div class="post-stats">
                <div>
                    <img src="thumbsup.png">
                    <img src="love.png">
                    <img src="clap.png">
                    <span class="liked-users">Abhishek Pande and 75 others</span>
                </div>
                <div>
                    <span>22 comments &middot 40 shares</span>
                </div>
            </div>
            <div class="post-activity">
                <div>
                    <img src="user-1.jpg" class="post-activity-user-icon">
                    <img src="down-arrow.png" class="post-activity-Arrow-icon">
                </div>
                <div class="post-activity-link">
                    <img src="like.png">
                    <span>Like</span>
                </div>
                <div class="post-activity-link">
                    <img src="comment.png">
                    <span>Comment</span>
                </div>
                <div class="post-activity-link">
                    <img src="share.png">
                    <span>Share</span>
                </div>
                <div class="post-activity-link">
                    <img src="send.png">
                    <span>Send</span>
                </div>
            </div>
        </div>
        <div class="post">
            <div class="post-author">
                <img src="user-3.png">
                <div>
                    <h1>Benjamin Leo</h1>
                    <small>Founder< and Ceo at Geoogle group | Angel Inverstor </small>
                    <small>2 hours ago</small>
                </div>
            </div>
            <p>The Sucess of every website it Depends upons The search engine optimization and Digital marketing Straterg
            <img src="post-image-3.png" width="100%">
            <div class="post-stats">
                <div>
                    <img src="thumbsup.png">
                    <img src="love.png">
                    <img src="clap.png">
                    <span class="liked-users">Abhishek Pande and 75 others</span>
                </div>
                <div>
                    <span>22 comments &middot 40 shares</span>
                </div>
            </div>
            <div class="post-activity">
                <div>
                    <img src="user-1.jpg" class="post-activity-user-icon">
                    <img src="down-arrow.png" class="post-activity-Arrow-icon">
                </div>
                <div class="post-activity-link">
                    <img src="like.png">
                    <span>Like</span>
                </div>
                <div class="post-activity-link">
                    <img src="comment.png">
                    <span>Comment</span>
                </div>
                <div class="post-activity-link">
                    <img src="share.png">
                    <span>Share</span>
                </div>
                <div class="post-activity-link">
                    <img src="send.png">
                    <span>Send</span>
                </div>
            </div>
        </div>
        <div class="post">
            <div class="post-author">
                <img src="user-4.png">
                <div>
                    <h1>Clarince George</h1>
                    <small>Founder< and Ceo at Geoogle group | Angel Inverstor </small>
                    <small>2 hours ago</small>
                </div>
            </div>
            <p>The Sucess of every website it Depends upons The search engine optimization and Digital marketing Straterg
            <img src="post-image-4.png" width="100%">
            <div class="post-stats">
                <div>
                    <img src="thumbsup.png">
                    <img src="love.png">
                    <img src="clap.png">
                    <span class="liked-users">Abhishek Pande and 75 others</span>
                </div>
                <div>
                    <span>22 comments &middot 40 shares</span>
                </div>
            </div>
            <div class="post-activity">
                <div>
                    <img src="user-1.jpg" class="post-activity-user-icon">
                    <img src="down-arrow.png" class="post-activity-Arrow-icon">
                </div>
                <div class="post-activity-link">
                    <img src="like.png">
                    <span>Like</span>
                </div>
                <div class="post-activity-link">
                    <img src="comment.png">
                    <span>Comment</span>
                </div>
                <div class="post-activity-link">
                    <img src="share.png">
                    <span>Share</span>
                </div>
                <div class="post-activity-link">
                    <img src="send.png">
                    <span>Send</span>
                </div>
            </div>
        </div>
        <div class="post">
            <div class="post-author">
                <img src="user-3.png">
                <div>
                    <h1>Benjamin Leo</h1>
                    <small>Founder< and Ceo at Geoogle group | Angel Inverstor </small>
                    <small>2 hours ago</small>
                </div>
            </div>
            <p>The Sucess of every website it Depends upons The search engine optimization and Digital marketing Straterg
            <img src="post-image-8.png" width="100%">
            <div class="post-stats">
                <div>
                    <img src="thumbsup.png">
                    <img src="love.png">
                    <img src="clap.png">
                    <span class="liked-users">Abhishek Pande and 75 others</span>
                </div>
                <div>
                    <span>22 comments &middot 40 shares</span>
                </div>
            </div>
            <div class="post-activity">
                <div>
                    <img src="user-1.jpg" class="post-activity-user-icon">
                    <img src="down-arrow.png" class="post-activity-Arrow-icon">
                </div>
                <div class="post-activity-link">
                    <img src="like.png">
                    <span>Like</span>
                </div>
                <div class="post-activity-link">
                    <img src="comment.png">
                    <span>Comment</span>
                </div>
                <div class="post-activity-link">
                    <img src="share.png">
                    <span>Share</span>
                </div>
                <div class="post-activity-link">
                    <img src="send.png">
                    <span>Send</span>
                </div>
            </div>
        </div>
        <div class="post">
            <div class="post-author">
                <img src="user-3.png">
                <div>
                    <h1>Benjamin Leo</h1>
                    <small>Founder< and Ceo at Geoogle group | Angel Inverstor </small>
                    <small>2 hours ago</small>
                </div>
            </div>
            <p>The Sucess of every website it Depends upons The search engine optimization and Digital marketing Straterg
            <img src="post-image-5.png" width="100%">
            <div class="post-stats">
                <div>
                    <img src="thumbsup.png">
                    <img src="love.png">
                    <img src="clap.png">
                    <span class="liked-users">Abhishek Pande and 75 others</span>
                </div>
                <div>
                    <span>22 comments &middot 40 shares</span>
                </div>
            </div>
            <div class="post-activity">
                <div>
                    <img src="user-1.jpg" class="post-activity-user-icon">
                    <img src="down-arrow.png" class="post-activity-Arrow-icon">
                </div>
                <div class="post-activity-link">
                    <img src="like.png">
                    <span>Like</span>
                </div>
                <div class="post-activity-link">
                    <img src="comment.png">
                    <span>Comment</span>
                </div>
                <div class="post-activity-link">
                    <img src="share.png">
                    <span>Share</span>
                </div>
                <div class="post-activity-link">
                    <img src="send.png">
                    <span>Send</span>
                </div>
            </div>
        </div>
        <div class="post">
            <div class="post-author">
                <img src="user-3.png">
                <div>
                    <h1>Benjamin Leo</h1>
                    <small>Founder< and Ceo at Geoogle group | Angel Inverstor </small>
                    <small>2 hours ago</small>
                </div>
            </div>
            <p>The Sucess of every website it Depends upons The search engine optimization and Digital marketing Straterg
            <img src="post-image-0 .png" width="100%">
            <div class="post-stats">
                <div>
                    <img src="thumbsup.png">
                    <img src="love.png">
                    <img src="clap.png">
                    <span class="liked-users">Abhishek Pande and 75 others</span>
                </div>
                <div>
                    <span>22 comments &middot 40 shares</span>
                </div>
            </div>
            <div class="post-activity">
                <div>
                    <img src="user-1.jpg" class="post-activity-user-icon">
                    <img src="down-arrow.png" class="post-activity-Arrow-icon">
                </div>
                <div class="post-activity-link">
                    <img src="like.png">
                    <span>Like</span>
                </div>
                <div class="post-activity-link">
                    <img src="comment.png">
                    <span>Comment</span>
                </div>
                <div class="post-activity-link">
                    <img src="share.png">
                    <span>Share</span>
                </div>
                <div class="post-activity-link">
                    <img src="send.png">
                    <span>Send</span>
                </div>
            </div>
        </div>
        <div class="post">
            <div class="post-author">
                <img src="user-3.png">
                <div>
                    <h1>Benjamin Leo</h1>
                    <small>Founder< and Ceo at Geoogle group | Angel Inverstor </small>
                    <small>2 hours ago</small>
                </div>
            </div>
            <p>The Sucess of every website it Depends upons The search engine optimization and Digital marketing Straterg
            <img src="post-image-9 .png" width="100%">
            <div class="post-stats">
                <div>
                    <img src="thumbsup.png">
                    <img src="love.png">
                    <img src="clap.png">
                    <span class="liked-users">Abhishek Pande and 75 others</span>
                </div>
                <div>
                    <span>22 comments &middot 40 shares</span>
                </div>
            </div>
            <div class="post-activity">
                <div>
                    <img src="user-1.jpg" class="post-activity-user-icon">
                    <img src="down-arrow.png" class="post-activity-Arrow-icon">
                </div>
                <div class="post-activity-link">
                    <img src="like.png">
                    <span>Like</span>
                </div>
                <div class="post-activity-link">
                    <img src="comment.png">
                    <span>Comment</span>
                </div>
                <div class="post-activity-link">
                    <img src="share.png">
                    <span>Share</span>
                </div>
                <div class="post-activity-link">
                    <img src="send.png">
                    <span>Send</span>
                </div>
            </div>
        </div>
    </div>
<!------ right-sidebar -->
    <div class="right-sidebar">
        <div class="sidebar-news">
            <img src="more.png" class="info-icon">
            <h3>Trending News</h3>
            <a href="#">High Demand for skilled Manpower</a>
            <span>11d ago &middot</span>
            <a href="#">Career Going Horizontally too</a>
            <span>18d ago  &middot</span>
            <a href="#">Less Work Visa for Us,more for uk</a>
            <span>12d ago  &middot</span> 
            <a href="#">More Hiring = Higher Confidance</a>    
            <span>Gautam Dani is World Richest;</span>
            <a href="#">More Hiring = Higher Confidance</a>
            <span>1d ago  &middot</span>
            <a href="#" class="read-more-link">Read More</a>   
        </div>
        <div class="sidebar-ad">
            <small>Ad...</small>
            <p>Master the 5 principles of web Design</p>
            <div>
                <img src="user-1.jpg">
                <img src="mi-logo.png">
            </div>
            <b>Brand and Demand in Xiaomi</b>
            <a href="#" class="ad-link">Learn More</a>
        </div>
        <div class="sidebar-useful-link">
            <a href="#">About</a>
            <a href="#">Accessibility</a>
            <a href="#">Help Center</a>
            <a href="#">Privacy Policy</a>
            <a href="#">Adertising</a>
            <a href="#">Get the App</a>
            <a href="#">More</a>
            <div class="copyright-msg">
                <img src="logo.png">
                <p>linkedin &#169 2022 . All rights reserved</p>
            </div>
        </div>
    </div>
    
    
    
    
    
    
</div>
<script>
    let profileMenu = document.getElementById("profileMenu"); 
    function toggleMenu(){
        profileMenu.classList.toggle("open-menu");
    }
</script>
<script>
    let sidebarActivity = document.getElementById("sidebarActivity")
    let showMoreLink = document.getElementById("showMoreLink")
    function toggleActivity(){
        sidebarActivity.classList.toggle("open-activity");     


    }

</script>
</body>
</html>


