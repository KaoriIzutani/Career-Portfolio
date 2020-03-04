## Live Project Introduction
Jump to:
* Login Failure Page
* Add Color to Subscriber Page
* Other Learned Skills

For our final project, I worked with a group of 10-15 students on an actual theatre website for two weeks. The client currently uses a website created in Wordpress. However, they need a website that is more modern, user friendly and didn't require technical knowledge to update information. Theatre administrators can login and update current and past shows, add cast members and manage theatre rentals. Subscribers can login and purchase tickets for a show or current season. Our tasks were divided into stories. My strengths cater to the front end, with using HTML and CSS to style the look and feel of the webpages. Here are the highlights of my Live Project work:

## Front End Stories
* Login Failure Page

The issue with the current website is if the administrator or subscriber failed to login, there is no user friendly way to either return to the login page and try again, reset the password or create a new account. I created custom HTML classes and then wrote CSS to style a user friendly page that allows them those three options: 

### HTML: 
<img src="/images/LoginFailure.jpg">

### CSS:
.button-redirect {
    background-color: var(--secondary-color);
    text-decoration:none;
    font-size: 20px;
    font-weight: 300;
    color: var(--dark-color);
    top: 10px;
    bottom: 10px;
    padding: 10px;
    transition: all 600ms ease;
   }

.button-redirect:hover {
    background: var(--main-bg-color);
    text-decoration:none;
    color:var(--light-color);
}
.center-box {
    display: flex;
    align-items: center;
    justify-content: center;
    flex-direction: column;
}

#move-oops {
    position: relative;
    top: 10px;
    bottom: 10px;
}

