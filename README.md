# button_HelloWorld
Use css to achieve the function of js.<br/>
Well,this is just a small function as u can see.But what makes it stand out from the others is the use of css3(scss).
And I think the quintessence is 
<code>
.container:hover .shine{
  transform: skewX(40deg) translateX(700px);}
</code>
which can also be replaced as<code>
.container
{
  &:hover .shine{
  transform: skewX(40deg) translateX(700px);}
}</code>
