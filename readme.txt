--Readme document for Brandon Chan--
1. What (a) basic features, (b) CSS features, and (c) advanced features were included?

(a) Basic features
    1. Added multiple images with descripte alt attributes/text
        - Portrait image
        - GitHub and LinkedIn clickable logos/hotlinks
    2. Links to external pages(s)
        - GitHub and LinkedIn links/logos
        - GitHub and Devpost repository links
    3. Multiple pages, with appropriate navigation between them
        - Home page and Projects page with buttons to go back and forth via Navbar
    4. Appropriate headings and paragraph text
        - Projects page, made sure to utilize heading hierarchy
    5. Used custom icons from Font Awsome
        - LinkedIn and GitHub logos, converted from SVG to png because SVG was giving me issues

(b) CSS features
    1. Modified padding and margins to indent content and enhance readability
        - Navbar brand text
        - Main Portrait
        - Introduction text centered with image
    2. Bootstrap CSS Helpers
        - Used with nearly everything--one of the main reasons why I was able to complete this
        assignment in a reasonable time. Bootstrap is very nice.
    3. Adding custom fonts
        - Used a global font family--list taken from Bootstrap's defaults. I liked how modern
        and sleek the fonts looked. With a black and white website like my own, the font choice
        is important.

(c) Advanced features
    1. Bootstrap Navbar


2. What online resources did you consult when completing this assignment? (list specific URLs)
    a. developer.mozzilla.org
        - Used many different links, one example was vertical-align docs
        https://developer.mozilla.org/en-US/docs/Web/CSS/vertical-align

    b. The Odin Project
        - https://www.theodinproject.com/paths/foundations/courses/foundations

    c. css-tricks.com
        - FlexBox Complete Guide: https://css-tricks.com/snippets/css/a-guide-to-flexbox/
        - https://css-tricks.com/almanac/properties/a/align-items/
        - https://css-tricks.com/almanac/properties/f/flex-wrap/

    d. https://www.w3schools.com
        - Also used for many things, one example was styling images
        - https://www.w3schools.com/css/css3_images.asp

    e. Bootstrap docs
        - Used for everything, but definitely spent the most time on the navbar docs
        - https://getbootstrap.com/docs/4.0/components/navbar/

    f. Many YouTube Videos:
        - Bootstrap
            a. https://www.youtube.com/watch?v=eow125xV5-c&t=329s
            b. https://www.youtube.com/watch?v=MscGIBk68So
            c. https://www.youtube.com/watch?v=G3tZUO2fAEU&t=891s
            d. https://www.youtube.com/watch?v=oMV-Y3R7cOc
            e. https://youtu.be/qNifU_aQRio?si=3Z8cslPjJ-XS19Kl

    g. This list does not include all of my resources, but it does cover the general 
       majority
        

3. What classmates or other individuals did you consult as part of this assignment? What did you discuss?
    - Primary consultant was my girlfriend who has developed websites. We discussed how certain
    paddings or margins were appealing. If I had a spacing bug or struggle (one particular example
    being attempting to center text vertically [the portrait introduction text]), I'd call her over
    and we'd brainstorm together on how to do it.

---


4. What are some important things you learned? (Extra, added by student)
    - You have to be REALLY careful about setting your classes to the objects that you want to be directly impacted. The image and container are two different things.
    In the example below, the class "logo" is applied to the images. This way, you can manipulate the image sizes. However, if you apply the "logo" class to the 'a'
    element, the code will not work as intended.

        <div class="col logo-section">
            <a href="https://github.com/BrandonUCI/">
                <img class="logo" src="./github.png" alt="GitHub Logo Hotlink">
            </a>

            <a href="https://www.linkedin.com/in/brandonc2025">
                <img class="logo" src="./linkedin.png" alt="LinkedIn Logo Hotlink">
            </a>
        </div>

    