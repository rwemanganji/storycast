<<<<<<< HEAD
# storycast
=======
# StoryCast - Rwanda Rising
This is an accessible microsite showcasing Rwanda Rising.


## Pages

1. **Home** (index.html) - Featured stories grid
2. **Story** (story.html) - Detailed story page with media and transcript
3. **About** (about.html) - Mission and accessibility information

## Project Structure

storycast/
├── index.html
├── story/
|   └── story.html
├── about.html
├── assets/
│   └── (images)
├── css/
│   └── main.css (compiled)
└── sass/
    ├── main.scss
    ├── tokens/
    │   ├── _colors.scss   
    │   └─
    └── partials/
        ├── _header.scss

## Accessibility Checklist
Requirement	     How it is met
Semantic HTML	 header, nav, main, section, article, figure, footer; one h1 per page

Captions and transcripts	  track kind="captions"> on video; full transcript on the story page

Text alternatives	    alt text on content images

Colour contrast	        Text and buttons meet WCAG 2.1 AA (4.5:1)

Keyboard use	        Everything works without a mouse; visible :focus-visible outline; skip link

Screen readers	        Landmarks, ordered headings, aria-label on navigation

Responsive	            Grid + Flexbox, with a container query on the media card

## Run Locally
Install Sass: npm install -g sass
Compile the styles: sass sass/main.scss css/main.css
Open index.html in your browser (or use the VS Code Live Server extension).
>>>>>>> 0120908 (storycast)
