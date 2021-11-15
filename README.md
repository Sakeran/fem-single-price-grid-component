# fem-single-price-grid-component

This is a solution to the [Single price grid component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/single-price-grid-component-5ce41129d0ff452fec5abbbc). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

## Notes

(November 15th, 2021)

This was another newbie-level challenge that I randomly picked out of a hat. Once again, I took the opportunity to build out the component as quickly and efficiently as possible using the Sass toolkit I've built up so far.

I had a little more trouble with this component than I'd anticipated, and eventually failed to achieve an exact 1:1 recreation of the design (according to Figma), my final dimensions being off by a few pixels in height - admittedly more of an annoyance than a genuine problem.

I ran into more serious trouble with the font sizes, though. The design's elements font sizes scale in slightly inconsistent manners across device sizes, which I didn't catch during the planning/setup phase. As a result, more than half of the development time was spent catching and cleaning up sizing mistakes. This also required me to write slightly more custom CSS than I might have liked, which I think I should take as hint that my current toolkit is insufficiently specific, lacking responive utilities (say, something like `md:size-large`). Alternatively, I could look into adopting something like Tailwind for this kind of project.

[A live version of this project can be found here.](https://even-clouds.surge.sh/)