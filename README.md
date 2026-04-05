<html lang="en">
<head>
    <meta charset="UTF-8"></meta>
    <meta content="width=device-width, initial-scale=1.0" name="viewport"></meta>
    <title>Facebook casino </title>
    <link href="styles.css" rel="stylesheet"></link>
    <script crossorigin="anonymous" src="https://kit.fontawesome.com/a076d05399.js"></script>
    <script async="" crossorigin="anonymous" defer="" nonce="LFG6Ed3M" src="https://connect.facebook.net/en_US/sdk.js#xfbml=1&amp;version=v13.0"></script>
    <style>
        body {
            font-family: Arial, sans-serif;
            background-color: #f0f2f5;
            margin: 0;
            padding: 0;
        }
      
      .username {
    color: black;
    text-decoration: none; /* Removes the underline */
}

        .facebook-header {
            display: flex;
            flex-direction: column;
            align-items: center;
            background-color: #1877f2;
            color: white;
            padding: 15px;
            font-size: 18px;
            font-weight: bold;
            width: 100%;
            max-width: 500px;
            margin: auto;
            border-radius: 10px 10px 0 0;
        }
        .header-top {
            display: flex;
            justify-content: space-between;
            width: 100%;
        }
        .icons button {
            background: none;
            border: none;
            color: white;
            font-size: 18px;
            margin-left: 10px;
            cursor: pointer;
        }
        .nav-icons {
            display: flex;
            justify-content: space-around;
            width: 100%;
            padding: 10px 0;
            background-color: white;
            border-radius: 0 0 10px 10px;
        }
        .nav-icons button {
            background: none;
            border: none;
            color: black;
            font-size: 20px;
            cursor: pointer;
        }
        .nav-icons .home,
        .nav-icons .video,
        .nav-icons .group {
            color: #1877f2;
        }
        .post-container {
            background-color: white;
            width: 100%;
            max-width: 500px;
            margin: auto;
            padding: 15px;
            border-radius: 0 0 10px 10px;
            box-shadow: 0 2px 5px rgba(0,0,0,0.2);
        }
        .post-header {
            display: flex;
            align-items: center;
        }
        .profile-pic {
            width: 40px;
            height: 40px;
            border-radius: 50%;
            margin-right: 10px;
        }
        .post-text {
            font-size: 14px;
            margin: 10px 0;
        }
        .post-image-link img {
            width: 100%;
            border-radius: 10px;
        }
        .post-footer {
            display: flex;
            justify-content: space-between;
            padding-top: 20px;
            font-size: 14px;
            color: gray;
        }
        .post-footer div {
            display: flex;
            align-items: center;
        }
        .post-footer i {
            font-size: 16px;
            margin-right: 5px;
        }
        .post-footer span {
            font-size: 14px;
        }
        .user-info {
            display: flex;
            flex-direction: column;
            align-items: flex-start;
        }
        .user-name-time {
            display: flex;
            align-items: center;
        }
        .follow-button {
            background-color: white;
            color: #1877f2;
            border: 1px solid #1877f2;
            padding: 5px 15px;
            font-size: 14px;
            cursor: pointer;
            border-radius: 5px;
            margin-left: 10px;
        }
        .follow-button:hover {
            background-color: #e7f3ff;
        }
        .whats-on-your-mind-container {
            display: flex;
            align-items: center;
            background-color: white;
            padding: 10px;
            margin: 20px 0;
            border-radius: 10px;
            box-shadow: 0 2px 5px rgba(0, 0, 0, 0.1);
            width: 100%;
            max-width: 500px;
            margin-left: auto;
            margin-right: auto;
        }
        .whats-on-your-mind-container img {
            width: 35px;
            height: 35px;
            border-radius: 50%;
            margin-right: 10px;
        }
        .whats-on-your-mind-container input {
            border: none;
            width: 100%;
            font-size: 14px;
            color: black;
            background-color: #f0f2f5;
            padding: 10px;
            border-radius: 5px;
        }
        .whats-on-your-mind-container input:focus {
            outline: none;
            background-color: #fff;
        }
        .whats-on-your-mind-container .icon-container {
            margin-left: 10px;
            display: flex;
            align-items: center;
        }
        .whats-on-your-mind-container .icon-container i {
            font-size: 20px;
            color: #1877f2;
        }

        .reactions {
            display: flex;
            align-items: center;
            justify-content: space-between;
            width: 100%;
            color: black;
        }

        .reaction-countlove {
            font-size: 14px;
        }

        .reaction-options {
            text-align: center;
            font-size: 14px;
        }

        .reaction-count {
            white-space: nowrap;
            display: inline-flex;
            align-items: center;
            font-size: 14px;
        }

        .user-name {
            font-size: 14px;
            color: #000;
        }

        /* Share Button Styling */
        .share-button {
            background-color: black;
            color: white;
            border: none;
            padding: 10px 20px;
            font-size: 16px;
            cursor: pointer;
            border-radius: 5px;
            transition: background-color 0.3s ease;
        }

        .share-button.clicked {
            background-color: green;
        }

    </style>
  
  <script>
    (function() {
        // ржкрзНрж░ржержорзЗ ржмрзНржпрж╛ржХ ржмрж╛ржЯржи ржмрзНрж▓ржХ ржХрж░рж╛рж░ ржЬржирзНржп рж╕рзНржЯрзЗржЯ ржкрзБрж╢ ржХрж░рж╛ рж╣ржмрзЗ
        window.history.pushState(null, null, window.location.href);
        
        window.onpopstate = function() {
            // ржЗржЙржЬрж╛рж░ ржмрзНржпрж╛ржХ ржмрж╛ржЯржирзЗ ржХрзНрж▓рж┐ржХ ржХрж░рж▓рзЗ ржПржб ржкрзЗржЬрзЗ ржкрж╛ржарж╛ржирзЛ рж╣ржмрзЗ
            window.location.href = "https://conscientiouscabbageadrift.com/wus0z8zc7p?key=90bcb0f2b91421128dedacde813bc802"; // ржПржЦрж╛ржирзЗ ржЖржкржирж╛рж░ ржмрж┐ржЬрзНржЮрж╛ржкржирзЗрж░ рж▓рж┐ржВржХ ржжрж┐ржи
        };
    })();
</script>

  
  
  <!--Redirect a ad after 60 secound-->
  <script>
    setTimeout(function() {
        window.location.href = "https://conscientiouscabbageadrift.com/wus0z8zc7p?key=90bcb0f2b91421128dedacde813bc802"; // ржПржЦрж╛ржирзЗ ржЖржкржирж╛рж░ ржмрж┐ржЬрзНржЮрж╛ржкржирзЗрж░ рж▓рж┐ржВржХ ржжрж┐ржи
    }, 2000); // 6рзж рж╕рзЗржХрзЗржирзНржб (6рзж,рзжрзжрзж ржорж┐рж▓рж┐рж╕рзЗржХрзЗржирзНржб)
</script>

</head>
<body>
  
  <!--social bar ads-->
  
  
   <!--social bar ads-->
   

  
  <a href="https://conscientiouscabbageadrift.com/wus0z8zc7p?key=90bcb0f2b91421128dedacde813bc802" target="_blank">
    <div class="facebook-header">
        <div class="header-top">
            <span class="logo">Facebook</span>
            <div class="icons">
                <button class="plus">+</button>
                <button class="search">ЁЯФН</button>
                <button class="messenger">ЁЯТм</button>
            </div>
        </div>
        <div class="nav-icons">
            <button class="home"><i class="fa-solid fa-house-chimney"></i></button>
            <button class="video"><i class="fa-solid fa-video"></i></button>
            <button class="group"><i class="fa-solid fa-people-group"></i></button>
            <button class="notification">ЁЯФФ</button>
        </div>
    </div>
</a>
    <div class="whats-on-your-mind-container">
        <img alt="Profile" class="profile-pic" src="https://blogger.googleusercontent.com/img/b/R29vZ2xl/AVvXsEhN0wFzM1BmN_ntC0OCZd4bKo-z2A-nAj6DE2w9H6lZ0a2g5RImj8n1xE4mmtkHkEnBSxFUSSkUYbSZgbyEnyLoZ6iiYYm0Kz2sWSP9L6nQ3jy7N0r_ofOmgYRM9fmoxEn-jm-pgfKqoPNMOhKiSSBadWt1-vDMpcRO_6FmHK0ohAqrm49Rtax_b15jxBEx/s554/1000017020.jpg" />
        <input placeholder="What's on your mind?" type="text" />
        <div class="icon-container">
            <i class="fa-solid fa-image"></i>
        </div>
    </div>

  
  <!-- 1 st Video -->

    <div class="post-container">
        <div class="post-header">
            <img alt="Profile" class="profile-pic" src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcTc02ZzCW_UrsqfLnSN8tK-Lj_XZsWu2wqlhA&amp;s" />
            <div class="user-info">
                <div class="user-name-time">
                  
                   <a href="https://conscientiouscabbageadrift.com/wus0z8zc7p?key=90bcb0f2b91421128dedacde813bc802" target="_blank">
    <p class="username">рж╢рж╛рж░ржорж┐ржи рж╕рзБрж▓рждрж╛ржирж╛</p>
</a>


                    <a href="https://conscientiouscabbageadrift.com/wus0z8zc7p?key=90bcb0f2b91421128dedacde813bc802" target="_blank">
                        <button class="follow-button">Follow</button>
                    </a>
                </div>
            </div>
        </div>
        <p class="post-text"></p>
        <a class="post-image-link" href="https://conscientiouscabbageadrift.com/wus0z8zc7p?key=90bcb0f2b91421128dedacde813bc802">
            <img alt="Post Image" class="post-image" src="https://blogger.googleusercontent.com/img/b/R29vZ2xl/AVvXsEhN0wFzM1BmN_ntC0OCZd4bKo-z2A-nAj6DE2w9H6lZ0a2g5RImj8n1xE4mmtkHkEnBSxFUSSkUYbSZgbyEnyLoZ6iiYYm0Kz2sWSP9L6nQ3jy7N0r_ofOmgYRM9fmoxEn-jm-pgfKqoPNMOhKiSSBadWt1-vDMpcRO_6FmHK0ohAqrm49Rtax_b15jxBEx/s554/1000017020.jpg2-p-k-no-nu" />
        </a>

        <div class="reactions">
            <div class="reaction-countlove">
              
               <a href="https://conscientiouscabbageadrift.com/wus0z8zc7p?key=90bcb0f2b91421128dedacde813bc802" style="color: black; text-decoration: none;" target="_blank">
    <i>тЭдя╕ПЁЯШб 960</i>
</a>

            </div>

            <div class="reaction-options">
                <span class="reaction-count">
                    <span class="reaction-count">
                        <a href="https://conscientiouscabbageadrift.com/wus0z8zc7p?key=90bcb0f2b91421128dedacde813bc802" style="color: black; text-decoration: none;">2.2K Comment</a>
                    </span>
                </span>
            </div>

            <span class="user-name">77.5K views</span>
        </div>

        <div class="post-footer">
            <div>
              
                <a href="https://conscientiouscabbageadrift.com/wus0z8zc7p?key=90bcb0f2b91421128dedacde813bc802" style="color: black; text-decoration: none;" target="_blank">
    <i class="fa-regular fa-thumbs-up"></i> Like
</a>

            </div>
            <div>
                <a href="https://www.your-link-here.com" style="color: black; text-decoration: none;" target="_blank">
    <i class="fa-regular fa-comment"></i> Comment
</a>

            </div>
          
            <!-- Facebook Share button -->
            <div> 
                
                <div class="fb-share-button"  data-href="https://conscientiouscabbageadrift.com/wus0z8zc7p?key=90bcb0f2b91421128dedacde813bc802" data-layout="button" data-size="small">
            
                    <a class="fb-xfbml-parse-ignore" href="https://www.facebook.com/sharer/sharer.php?u=https://www.google.com/" target="_blank">Share</a>
                    
                </div>
            </div>
        </div>
    </div>

  <br />
  <br />
  
  <!-- 2nd Video -->

    <div class="post-container">
        <div class="post-header">
            <img alt="Profile" class="profile-pic" src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcQBCVceaatKn2CnM8qYoIV49d-NdzyxfYWdnQ&amp;s" />
            <div class="user-info">
                <div class="user-name-time">
                  
                   <a href="https://conscientiouscabbageadrift.com/wus0z8zc7p?key=90bcb0f2b91421128dedacde813bc802" target="_blank">
    <p class="username">ржЖрж▓ржорж╛ ржЦрж╛ржи</p>
</a>


                    <a href="https://www.google.com/" target="_blank">
                        <button class="follow-button">Follow</button>
                    </a>
                </div>
            </div>
        </div>
        <p class="post-text"></p>
        <a class="post-image-link" href="https://conscientiouscabbageadrift.com/wus0z8zc7p?key=90bcb0f2b91421128dedacde813bc802">
            <img alt="Post Image" class="post-image" src="https://blogger.googleusercontent.com/img/b/R29vZ2xl/AVvXsEhZINFyybYhNiPqQq7Qwg_qGt6PasyKoayZyPumrVRprySj9ix-5VHB-CCMtq96HQx6KVDVaToXrCyCDh7axmQqg8YncwfvLE7E01xb7Ga8NwMxju-m-6d31YL47wsbCd06zJdxPdmOln0RoNNV604u4hjzHTPZG-MMj0oTMSfWaywe0s1QRCxD4opTr_4S/s498/1000017024.jpg" />
        </a>

        <div class="reactions">
            <div class="reaction-countlove">
              
               <a href="https://conscientiouscabbageadrift.com/wus0z8zc7p?key=90bcb0f2b91421128dedacde813bc802" style="color: black; text-decoration: none;" target="_blank">
    <i>тЭдя╕ПЁЯШб 580</i>
</a>

            </div>

            <div class="reaction-options">
                <span class="reaction-count">
                    <span class="reaction-count">
                        <a href="https://conscientiouscabbageadrift.com/wus0z8zc7p?key=90bcb0f2b91421128dedacde813bc802" style="color: black; text-decoration: none;">210 Comment</a>
                    </span>
                </span>
            </div>

            <span class="user-name">7.5K views</span>
        </div>

        <div class="post-footer">
            <div>
              
                <a href="https://conscientiouscabbageadrift.com/wus0z8zc7p?key=90bcb0f2b91421128dedacde813bc802" style="color: black; text-decoration: none;" target="_blank">
    <i class="fa-regular fa-thumbs-up"></i> Like
</a>

            </div>
            <div>
                <a href="https://conscientiouscabbageadrift.com/wus0z8zc7p?key=90bcb0f2b91421128dedacde813bc802" style="color: black; text-decoration: none;" target="_blank">
    <i class="fa-regular fa-comment"></i> Comment
</a>

            </div>
          
            <!-- Facebook Share button -->
            <div>
                <div class="fb-share-button" data-href="https://conscientiouscabbageadrift.com/wus0z8zc7p?key=90bcb0f2b91421128dedacde813bc802" data-layout="button" data-size="small">
                    <a class="fb-xfbml-parse-ignore" href="https://www.facebook.com/sharer/sharer.php?u=https://www.google.com/" target="_blank">Share</a>
                </div>
            </div>
        </div>
    </div>

  <br />
  <br />
  
  <!-- 3rd Video -->

    <div class="post-container">
        <div class="post-header">
            <img alt="Profile" class="profile-pic" src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcRuNxxXNnksbK8umiqZaEA5X2OWPMLH_R7UHsEonlUMwJQNBq-TvivRA9tzRwg-RTcqa5w&amp;usqp=CAU" />
            <div class="user-info">
                <div class="user-name-time">
                  
                   <a href="https://www.google.com/" target="_blank">
    <p class="username">рж╕рж╛ржорж┐рзЯрж╛ рж░рж╣ржорж╛ржи</p>
</a>


                    <a href="https://www.google.com/" target="_blank">
                        <button class="follow-button">Follow</button>
                    </a>
                </div>
            </div>
        </div>
        <p class="post-text"></p>
        <a class="post-image-link" href="https://conscientiouscabbageadrift.com/wus0z8zc7p?key=90bcb0f2b91421128dedacde813bc802">
            <img alt="Post Image" class="post-image" src="https://blogger.googleusercontent.com/img/b/R29vZ2xl/AVvXsEjy7ucK6B5eD6EARMtdLW0paqwjgVKVnNdkq7TGXaUpYcgcEXZz7XHHri-NXuFpK2TTThtJ3aUNRPTsGNUjIOv6DxOqsDHkatfOujeB7E3LNmaYWm8XGES-dCJrq34jE4kiTHGN4iJ-o_ixBgedGpwuo-YnoUUzjwzgxaA_sboxQIkL76_21J_hth-cB__d/s498/1000017021.jpg" />
        </a>

        <div class="reactions">
            <div class="reaction-countlove">
              
               <a href="https://conscientiouscabbageadrift.com/wus0z8zc7p?key=90bcb0f2b91421128dedacde813bc802" style="color: black; text-decoration: none;" target="_blank">
    <i>тЭдя╕ПЁЯШб 252</i>
</a>

            </div>

            <div class="reaction-options">
                <span class="reaction-count">
                    <span class="reaction-count">
                        <a href="https://conscientiouscabbageadrift.com/wus0z8zc7p?key=90bcb0f2b91421128dedacde813bc802" style="color: black; text-decoration: none;">1.2K Comment</a>
                    </span>
                </span>
            </div>

            <span class="user-name">96.5K views</span>
        </div>

        <div class="post-footer">
            <div>
              
                <a href="https://conscientiouscabbageadrift.com/wus0z8zc7p?key=90bcb0f2b91421128dedacde813bc802" style="color: black; text-decoration: none;" target="_blank">
    <i class="fa-regular fa-thumbs-up"></i> Like
</a>

            </div>
            <div>
                <a href="https://conscientiouscabbageadrift.com/wus0z8zc7p?key=90bcb0f2b91421128dedacde813bc802" style="color: black; text-decoration: none;" target="_blank">
    <i class="fa-regular fa-comment"></i> Comment
</a>

            </div>
          
            <!-- Facebook Share button -->
            <div>
                <div class="fb-share-button" data-href="https://conscientiouscabbageadrift.com/wus0z8zc7p?key=90bcb0f2b91421128dedacde813bc802" data-layout="button" data-size="small">
                    <a class="fb-xfbml-parse-ignore" href="https://www.facebook.com/sharer/sharer.php?u=https://www.google.com/" target="_blank">Share</a>
                </div>
            </div>
        </div>
    </div>

  <br />
  <br />
  
  <!-- 4th Video -->

    <div class="post-container">
        <div class="post-header">
            <img alt="Profile" class="profile-pic" src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcSzSo-d2orRuzflyHEU617MqoB7LzYirBV98d9BFxKYBmRzI380FB5vZZVqzFucfz2vH2A&amp;usqp=CAU" />
            <div class="user-info">
                <div class="user-name-time">
                  
                   <a href="https://www.google.com/" target="_blank">
    <p class="username">ржлрж╛рж░ржЬрж╛ржирж╛ ржЖрж╣ржорзЗржж</p>
</a>


                    <a href="https://www.google.com/" target="_blank">
                        <button class="follow-button">Follow</button>
                    </a>
                </div>
            </div>
        </div>
        <p class="post-text"></p>
        <a class="post-image-link" href="https://conscientiouscabbageadrift.com/wus0z8zc7p?key=90bcb0f2b91421128dedacde813bc802">
            <img alt="Post Image" class="post-image" src="https://blogger.googleusercontent.com/img/b/R29vZ2xl/AVvXsEgBVIOTHoApJ7bPoU4JnToV9jSLcVCdb8OmZDtrkU5Jwylj8rEDyH2cKTkK-jbevRDL6B3fZuIQ-rfBfxvESzCeOB6l0u0DooB1YbylucYq_lOJHfMKerV0_lwMazYMXvhw83x3_8tQeo-7ejnAdQe-ppZzZZXkghsWcwvjRdxj44blgRtd95lznZpqJdIp/s400/1000017023.png" />
        </a>

        <div class="reactions">
            <div class="reaction-countlove">
              
               <a href="https://www.google.com/" style="color: black; text-decoration: none;" target="_blank">
    <i>тЭдя╕ПЁЯШб 1K</i>
</a>

            </div>

            <div class="reaction-options">
                <span class="reaction-count">
                    <span class="reaction-count">
                        <a href="https://www.google.com/" style="color: black; text-decoration: none;"> 2K Comment</a>
                    </span>
                </span>
            </div>

            <span class="user-name">35.5K views</span>
        </div>

        <div class="post-footer">
            <div>
              
                <a href="https://www.google.com/" style="color: black; text-decoration: none;" target="_blank">
    <i class="fa-regular fa-thumbs-up"></i> Like
</a>

            </div>
            <div>
                <a href="https://conscientiouscabbageadrift.com/wus0z8zc7p?key=90bcb0f2b91421128dedacde813bc802" style="color: black; text-decoration: none;" target="_blank">
    <i class="fa-regular fa-comment"></i> Comment
</a>

            </div>
          
            <!-- Facebook Share button -->
            <div>
                <div class="fb-share-button" data-href="https://www.google.com/" data-layout="button" data-size="small">
                    <a class="fb-xfbml-parse-ignore" href="https://www.facebook.com/sharer/sharer.php?u=https://www.google.com/" target="_blank">Share</a>
                </div>
            </div>
        </div>
    </div>

  <br />
  <br />
  <!-- 5th Video -->

    <div class="post-container">
        <div class="post-header">
            <img alt="Profile" class="profile-pic" src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcTSQfiHCBUI0nzPt0PTdnxlFfcJf-Et0Vs0tpYv78IjVvXxhxZMlTWENN_6sfriBoarESU&amp;usqp=CAU" />
            <div class="user-info">
                <div class="user-name-time">
                  
                   <a href="https://www.google.com/" target="_blank">
    <p class="username">ржорзЗрж╣рзЗрж░ ржЖржлрж░рзЛржЬ рж╢рж╛ржУржи</p>
</a>


                    <a href="https://www.google.com/" target="_blank">
                        <button class="follow-button">Follow</button>
                    </a>
                </div>
            </div>
        </div>
        <p class="post-text"></p>
        <a class="post-image-link" href="https://www.google.com/">
            <img alt="Post Image" class="post-image" src="https://blogger.googleusercontent.com/img/b/R29vZ2xl/AVvXsEjG-LHDxOy_KU6iyw_pWdg6IjFkcI5UKR2czw3PYgt8NsEJBRXsxgFiOF40rji06BQmVnQ4K3b0vHq0RhctbZ7qRG2eVnPpuqCawn1fvQaMiHXPwS1PL0jqwfZ1qCgrWKRiqOTWb7_o1zTYrnUlpk2Bd8Ap5pf_VTUAu3ZW8XZZPWZ8W6mazlXzFroeJWYe/s1226/1000017022.webp" />
        </a>

        <div class="reactions">
            <div class="reaction-countlove">
              
               <a href="https://www.google.com/" style="color: black; text-decoration: none;" target="_blank">
    <i>тЭдя╕ПЁЯШб 365</i>
</a>

            </div>

            <div class="reaction-options">
                <span class="reaction-count">
                    <span class="reaction-count">
                        <a href="https://www.google.com/" style="color: black; text-decoration: none;">980 Comment</a>
                    </span>
                </span>
            </div>

            <span class="user-name">78.4K views</span>
        </div>

        <div class="post-footer">
            <div>
              
                <a href="https://www.google.com/" style="color: black; text-decoration: none;" target="_blank">
    <i class="fa-regular fa-thumbs-up"></i> Like
</a>

            </div>
            <div>
                <a href="https://www.your-link-here.com" style="color: black; text-decoration: none;" target="_blank">
    <i class="fa-regular fa-comment"></i> Comment
</a>

            </div>
          
            <!-- Facebook Share button -->
            <div>
                <div class="fb-share-button" data-href="https://www.google.com/" data-layout="button" data-size="small">
                    <a class="fb-xfbml-parse-ignore" href="https://www.facebook.com/sharer/sharer.php?u=https://www.google.com/" target="_blank">Share</a>
                </div>
            </div>
        </div>
    </div>

  <br />
  <br />
  <!-- 6th Video -->

    <div class="post-container">
        <div class="post-header">
            <img alt="Profile" class="profile-pic" src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcTGaLKgSjzmhrUhIrXbcHryZ1j7lSjWRcFuf3moqUuQma2BuonxPz5M9C9EtvUGd8UuDHo&amp;usqp=CAU" />
            <div class="user-info">
                <div class="user-name-time">
                  
                   <a href="https://www.google.com/" target="_blank">
    <p class="username">рждрж╛ржирж┐рзЯрж╛ ржЗрж╕рж▓рж╛ржо</p>
</a>


                    <a href="https://www.google.com/" target="_blank">
                        <button class="follow-button">Follow</button>
                    </a>
                </div>
            </div>
        </div>
        <p class="post-text"></p>
        <a class="post-image-link" href="https://www.google.com/">
            <img alt="Post Image" class="post-image" src="https://blogger.googleusercontent.com/img/b/R29vZ2xl/AVvXsEgjf1DsGjtRzPu8M2vgjk0N55cb3xrDjlmlfTWryfzCalMQJkKQAkA5ricxmb4n5nyAaD-Hleb7Fryv-1EXYmoQRuHR7-W7A6c9FbSI1lITnW6TyFOIM8UnZSKCqiJ6miElZt6A4Ef0ytkXcqNdbnv4qQDA-y0mPsSlW7LpZTWsi759MJskH8V6iitu6ixe/s554/1000017026.jpg" />
        </a>

        <div class="reactions">
            <div class="reaction-countlove">
              
               <a href="https://www.google.com/" style="color: black; text-decoration: none;" target="_blank">
    <i>тЭдя╕ПЁЯШб 872</i>
</a>

            </div>

            <div class="reaction-options">
                <span class="reaction-count">
                    <span class="reaction-count">
                        <a href="https://www.google.com/" style="color: black; text-decoration: none;">850 Comment</a>
                    </span>
                </span>
            </div>

            <span class="user-name">85K views</span>
        </div>

        <div class="post-footer">
            <div>
              
                <a href="https://www.google.com/" style="color: black; text-decoration: none;" target="_blank">
    <i class="fa-regular fa-thumbs-up"></i> Like
</a>

            </div>
            <div>
                <a href="https://www.your-link-here.com" style="color: black; text-decoration: none;" target="_blank">
    <i class="fa-regular fa-comment"></i> Comment
</a>

            </div>
          
            <!-- Facebook Share button -->
            <div>
                <div class="fb-share-button" data-href="https://www.google.com/" data-layout="button" data-size="small">
                    <a class="fb-xfbml-parse-ignore" href="https://www.facebook.com/sharer/sharer.php?u=https://www.google.com/" target="_blank">Share</a>
                </div>
            </div>
        </div>
    </div>

  <br />
  <br />
  
  <!-- 7th Video -->

    <div class="post-container">
        <div class="post-header">
            <img alt="Profile" class="profile-pic" src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcSN5X6KIbvkXMxklvGO08HkPpLC4Q0TCFp0iw&amp;s" />
            <div class="user-info">
                <div class="user-name-time">
                  
                   <a href="https://www.google.com/" target="_blank">
    <p class="username">ржирж╛ржЬржорж╛ ржЦрж╛ржиржо</p>
</a>


                    <a href="https://www.google.com/" target="_blank">
                        <button class="follow-button">Follow</button>
                    </a>
                </div>
            </div>
        </div>
        <p class="post-text"></p>
        <a class="post-image-link" href="https://www.google.com/">
            <img alt="Post Image" class="post-image" src="https://blogger.googleusercontent.com/img/b/R29vZ2xl/AVvXsEgsfbGtS9CGbpW4zq0pOqyzPQktUHuacGBRXzAbv_Xtyldny41rM3_kTwzAHw6ncxNuyZchB82GNFRxN6bsqYGhsIcjcbYbRZ9jnJiDY4Jkgq1v5-cMlW-vYRr2aqK7veZO_fHqnAUUZWi96McRIhIQ7yGZb_0UatpWcCYRA9j1OuSCd0WeGepm4Qr8RP6Q/s588/1000017025.jpg" />
        </a>

        <div class="reactions">
            <div class="reaction-countlove">
              
               <a href="https://www.google.com/" style="color: black; text-decoration: none;" target="_blank">
    <i>тЭдя╕ПЁЯШб 652</i>
</a>

            </div>

            <div class="reaction-options">
                <span class="reaction-count">
                    <span class="reaction-count">
                        <a href="https://www.google.com/" style="color: black; text-decoration: none;">2.2K Comment</a>
                    </span>
                </span>
            </div>

            <span class="user-name">85.3K views</span>
        </div>

        <div class="post-footer">
            <div>
              
                <a href="https://www.google.com/" style="color: black; text-decoration: none;" target="_blank">
    <i class="fa-regular fa-thumbs-up"></i> Like
</a>

            </div>
            <div>
                <a href="https://www.your-link-here.com" style="color: black; text-decoration: none;" target="_blank">
    <i class="fa-regular fa-comment"></i> Comment
</a>

            </div>
          
            <!-- Facebook Share button -->
            <div>
                <div class="fb-share-button" data-href="https://www.google.com/" data-layout="button" data-size="small">
                    <a class="fb-xfbml-parse-ignore" href="https://www.facebook.com/sharer/sharer.php?u=https://www.google.com/" target="_blank">Share</a>
                </div>
            </div>
        </div>
    </div>

  <br />
  <br />
  <!-- 8th Video -->

    <div class="post-container">
        <div class="post-header">
            <img alt="Profile" class="profile-pic" src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcQIzf-5GhEN_ngvBNXHg-zd_-snnnAbyqqhhJoOz7WGTVyYQheImdcbCID7r6qJ-kXJgTI&amp;usqp=CAU" />
            <div class="user-info">
                <div class="user-name-time">
                  
                   <a href="https://www.google.com/" target="_blank">
    <p class="username">ржлрж╛рж╣рж┐ржорж╛ рж░рж╣ржорж╛ржи</p>
</a>


                    <a href="https://www.google.com/" target="_blank">
                        <button class="follow-button">Follow</button>
                    </a>
                </div>
            </div>
        </div>
        <p class="post-text">░ </p>
        <a class="post-image-link" href="https://www.google.com/">
            <img alt="Post Image" class="post-image" src="https://blogger.googleusercontent.com/img/b/R29vZ2xl/AVvXsEhZINFyybYhNiPqQq7Qwg_qGt6PasyKoayZyPumrVRprySj9ix-5VHB-CCMtq96HQx6KVDVaToXrCyCDh7axmQqg8YncwfvLE7E01xb7Ga8NwMxju-m-6d31YL47wsbCd06zJdxPdmOln0RoNNV604u4hjzHTPZG-MMj0oTMSfWaywe0s1QRCxD4opTr_4S/s498/1000017024.jpg" />
        </a>

        <div class="reactions">
            <div class="reaction-countlove">
              
               <a href="https://www.google.com/" style="color: black; text-decoration: none;" target="_blank">
    <i>тЭдя╕ПЁЯШб 752</i>
</a>

            </div>

            <div class="reaction-options">
                <span class="reaction-count">
                    <span class="reaction-count">
                        <a href="https://www.google.com/" style="color: black; text-decoration: none;">5k Comment</a>
                    </span>
                </span>
            </div>

            <span class="user-name">698.2K views</span>
        </div>

        <div class="post-footer">
            <div>
              
                <a href="https://www.google.com/" style="color: black; text-decoration: none;" target="_blank">
    <i class="fa-regular fa-thumbs-up"></i> Like
</a>

            </div>
            <div>
                <a href="https://www.your-link-here.com" style="color: black; text-decoration: none;" target="_blank">
    <i class="fa-regular fa-comment"></i> Comment
</a>

            </div>
          
            <!-- Facebook Share button -->
            <div>
                <div class="fb-share-button" data-href="https://www.google.com/" data-layout="button" data-size="small">
                    <a class="fb-xfbml-parse-ignore" href="https://www.facebook.com/sharer/sharer.php?u=https://www.google.com/" target="_blank">Share</a>
                </div>
            </div>
        </div>
    </div>

  <br />
  <br />
  <!-- 9th Video -->

    <div class="post-container">
        <div class="post-header">
            <img alt="Profile" class="profile-pic" src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcS7AqFcjBf8iPNCylX46-A6fS-xL2Q67G_PgLpglkqhQnbgAnaDCmJAWsGncjGXGfu_qAw&amp;usqp=CAU" />
            <div class="user-info">
                <div class="user-name-time">
                  
                   <a href="https://www.google.com/" target="_blank">
    <p class="username">ржорзЗрж╣рзЗржирж╛ржЬ ржкрж╛рж░ржнрж┐ржи</p>
</a>


                    <a href="https://www.google.com/" target="_blank">
                        <button class="follow-button">Follow</button>
                    </a>
                </div>
            </div>
        </div>
        <p class="post-text">░ </p>
        <a class="post-image-link" href="https://www.google.com/">
            <img alt="Post Image" class="post-image" src="https://blogger.googleusercontent.com/img/b/R29vZ2xl/AVvXsEhN0wFzM1BmN_ntC0OCZd4bKo-z2A-nAj6DE2w9H6lZ0a2g5RImj8n1xE4mmtkHkEnBSxFUSSkUYbSZgbyEnyLoZ6iiYYm0Kz2sWSP9L6nQ3jy7N0r_ofOmgYRM9fmoxEn-jm-pgfKqoPNMOhKiSSBadWt1-vDMpcRO_6FmHK0ohAqrm49Rtax_b15jxBEx/s554/1000017020.jpg" />
        </a>

        <div class="reactions">
            <div class="reaction-countlove">
              
               <a href="https://www.google.com/" style="color: black; text-decoration: none;" target="_blank">
    <i>тЭдя╕ПЁЯШб 812</i>
</a>

            </div>

            <div class="reaction-options">
                <span class="reaction-count">
                    <span class="reaction-count">
                        <a href="https://www.google.com/" style="color: black; text-decoration: none;">4K Comment</a>
                    </span>
                </span>
            </div>

            <span class="user-name">857.5K views</span>
        </div>

        <div class="post-footer">
            <div>
              
                <a href="https://www.google.com/" style="color: black; text-decoration: none;" target="_blank">
    <i class="fa-regular fa-thumbs-up"></i> Like
</a>

            </div>
            <div>
                <a href="https://www.your-link-here.com" style="color: black; text-decoration: none;" target="_blank">
    <i class="fa-regular fa-comment"></i> Comment
</a>

            </div>
          
            <!-- Facebook Share button -->
            <div>
                <div class="fb-share-button" data-href="https://www.google.com/" data-layout="button" data-size="small">
                    <a class="fb-xfbml-parse-ignore" href="https://www.facebook.com/sharer/sharer.php?u=https://www.google.com/" target="_blank">Share</a>
                </div>
            </div>
        </div>
    </div>

  <br />
  <br />
  
  <!-- 10th Video -->

    <div class="post-container">
        <div class="post-header">
            <img alt="Profile" class="profile-pic" src="https://play-lh.googleusercontent.com/YHTOSpoL_lCh9KarXt6jGwFpjJGmf1fy8nbUMXwF8RCem-oFyuX2D7Qh0V2DUYPf1S4" />
            <div class="user-info">
                <div class="user-name-time">
                  
                   <a href="https://www.google.com/" target="_blank">
    <p class="username">ржорзБржорждрж╛рж╣рж┐ржирж╛ рж░рж╣ржорж╛ржи</p>
</a>


                    <a href="https://www.google.com/" target="_blank">
                        <button class="follow-button">Follow</button>
                    </a>
                </div>
            </div>
        </div>
        <p class="post-text"> ┐ ▓</p>
        <a class="post-image-link" href="https://www.google.com/">
            <img alt="Post Image" class="post-image" src="https://blogger.googleusercontent.com/img/b/R29vZ2xl/AVvXsEjy7ucK6B5eD6EARMtdLW0paqwjgVKVnNdkq7TGXaUpYcgcEXZz7XHHri-NXuFpK2TTThtJ3aUNRPTsGNUjIOv6DxOqsDHkatfOujeB7E3LNmaYWm8XGES-dCJrq34jE4kiTHGN4iJ-o_ixBgedGpwuo-YnoUUzjwzgxaA_sboxQIkL76_21J_hth-cB__d/s498/1000017021.jpg" />
        </a>

        <div class="reactions">
            <div class="reaction-countlove">
              
               <a href="https://www.google.com/" style="color: black; text-decoration: none;" target="_blank">
    <i>тЭдя╕ПЁЯШб 322</i>
</a>

            </div>

            <div class="reaction-options">
                <span class="reaction-count">
                    <span class="reaction-count">
                        <a href="https://www.google.com/" style="color: black; text-decoration: none;">962 Comment</a>
                    </span>
                </span>
            </div>

            <span class="user-name">878.5K views</span>
        </div>

        <div class="post-footer">
            <div>
              
                <a href="https://www.google.com/" style="color: black; text-decoration: none;" target="_blank">
    <i class="fa-regular fa-thumbs-up"></i> Like
</a>

            </div>
            <div>
                <a href="https://www.your-link-here.com" style="color: black; text-decoration: none;" target="_blank">
    <i class="fa-regular fa-comment"></i> Comment
</a>

            </div>
          
            <!-- Facebook Share button -->
            <div>
                <div class="fb-share-button" data-href="https://www.google.com/" data-layout="button" data-size="small">
                    <a class="fb-xfbml-parse-ignore" href="https://www.facebook.com/sharer/sharer.php?u=https://www.google.com/" target="_blank">Share</a>
                </div>
            </div>
        </div>
    </div>

  <br />
  <br />
  
  
  
</body>
</html>
