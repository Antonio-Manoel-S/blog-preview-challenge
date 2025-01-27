# Frontend Mentor - Blog preview card solution

This is a solution to the [Blog preview card challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/blog-preview-card-ckPaj01IcS). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 


### The challenge

Box shadow, something new to me.

## My process

### Built with

- Editor Spck [mobile]


### What I learned

Use box shadow to do a cartoon(?) style. And, link better style font. I didn't now that i should use font-weight on font-face, when i link specific archive. (like "fontnameExtraBold.tff" I writed extrabold style instead of font weight, to function normally you write 800 font weight on font face. Normally when you link the entire archive of all font or link url from internet, you don't need to put font weight). Other thing is my css was not finding the local font. I was puttin assets/fonts/static/Figtree-ExtraBold.ttf, when you put css on a paste to organize, it dont work. Because "assets" is not on the css paste. "../fonts/static/Figtree-ExtraBold.ttf" is the correct because "../" return one paste, and then go to fonts, getting the path.


## Acknowledgments

Always when you link local font from project, put the proper name, url, and font weight. And font-style normal or italic, but when is not italic, dont need to put. 
