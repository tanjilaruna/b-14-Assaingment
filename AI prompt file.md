First, I explored several websites to find a simple and clean testimonial section (AI promoet)
 that matched the style of my Speakers Conference website. After selecting a suitable design, I created a rough plan and 
 built four testimonial cards. I arranged the cards and designed their layout on my own. However, 
 there were some design techniques that I did not know how to implement, such as adding star ratings and styling the quote icon.
 For those specific parts, I took help from ChatGPT. For example, I wanted the quote icon to have no background color, 
 but to appear as an outline (border-like) icon,
 similar to the reference design. ChatGPT suggested using the following CSS:
 .quote{
    color: transparent;
    -webkit-text-stroke: 2px #d9d9d9;
    font-size: 55px;
}
html:
 <i class="fa-solid fa-quote-right quote"></i>