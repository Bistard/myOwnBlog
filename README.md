# myOwnBlog
This is my own webside about my photography 😀(*^_^*)😀.


# top priority
- ✔ Image-slideshow.
- ✔ Reduce image loading time for image-slideshow (resize the img from the server instead of in user's browser)
- ✔ Image navbar.
- ✔ Image-slideshow description and animation.
- ✔ Image-slideshow-navbar with animation and text will pop up when it's checked.
- ✔ Picture Seires (Galleries).
- ✔ Parallax scrolling.
- ✔ Drop menu for navbar.
- About-me section.
- ✔ responsive picture gallery.

# minor priority
- ✔ main title -> animation.
- ✔ image-slideshow-navbar lined in a wave-shape.
- ✔ click the image-slideshow-navbar will show the placeName instead of the picture.
- ✔ box-shadow for the image-slideshow-navbar.
- ✔ the main-slide-title will fade-up when we scrolls on its position.
- Shrink the size of the image-slideshow-navbar by 50px by 50px (might not)?
- Like button next to every picture seires.
- ✔ "Smooth navbar".
- ✔ hovering on swiper-slide will show the # of the slide.
- ✔ hovering on CHRIS LI will show up HOME instead.

# bugs
- Auto fit the mobile phone users.
- Use @media to make everything RESPONSIVE.
- ✔ Swiper-slide each slide has different width (by setting CSS as -> width: auto !important;), but swiper.js still treats all the slides as the same width, as a result, the swiper.js won't scroll the slides properly.
  - fixed: by setting main.js as -> {loop: true}, It not technically fixing the problem, but it works magically. :)
- ✔ view collections warpper is too big.
  - fixed: set as -> {display: inline-block; left: 50%; transform: translateX(-50%);}.
- ✔ Letterspace for each navbar's item has issue
  - fixed: I just simply delete letter-spacing part...
- ✔ For each swiper-slide, if users are hovering on the image-#, the img-container will not trigger the hover effect.
  - fixed: set the image-#'s class as -> {pointer-events: none;}. So that the image-# will has no hover effect to overlay the img-container's hover effect.
- Safari doesn't support CSS scroll-behavior, I need to write .js later to ensure it fully functional.
- Grid templates somehow wrongly calculated the rows and the columns.

# Ideas
- ✔ might put the main navBar to the left side and fold, only expand when you click a menu button.
- Chinese version.
- load the thumbnail of the image first.
- Some music maybe?
- Background with some random figures using JS? (1%)
- Parallax scrolling of different elements with its own scrolling speed.


