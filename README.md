# Assignment-5
&lt;!DOCTYPE html&gt;
&lt;html&gt;
&lt;head&gt;
&lt;meta charset=&quot;UTF-8&quot;&gt;
&lt;meta name=&quot;viewport&quot; content=&quot;width=device-width, initial-scale=1.0&quot;&gt;
&lt;title&gt;Flexbox Gallery&lt;/title&gt;
&lt;style&gt;
.row {
display: flex;
flex-wrap: wrap;
padding: 0 4px;
}

.column {
flex: 25%;
max-width: 25%;
padding: 0 4px;
}

.column img {
margin-top: 10px;
vertical-align: middle;
width: 100%;
border-radius: 8px;
}

@media screen and (max-width: 800px) {
.column {
flex: 50%;
max-width: 50%;
}
}

@media screen and (max-width: 500px) {

.column {
flex: 100%;
max-width: 100%;
}
}
&lt;/style&gt;
&lt;/head&gt;
&lt;body&gt;

&lt;h1 style=&quot;text-align:center;&quot;&gt;Flexbox Image Gallery&lt;/h1&gt;

&lt;div class=&quot;row&quot;&gt;
&lt;div class=&quot;column&quot;&gt;
&lt;img src=&quot;https://i.pinimg.com/1200x/12/9b/76/129b7630baa815012a13afb634f96d36.jpg&quot;&gt;
&lt;img src=&quot;https://i.pinimg.com/1200x/60/a0/e1/60a0e1338cac09b2457564b98b4504a5.jpg&quot;&gt;
&lt;img src=&quot;https://i.pinimg.com/736x/e5/79/9f/e5799f71358fc931b962137abe551483.jpg&quot;&gt;
&lt;img src=&quot;https://i.pinimg.com/736x/16/24/f9/1624f978c1b40c05ca65d31656d44fe7.jpg&quot;&gt;
&lt;/div&gt;

&lt;div class=&quot;column&quot;&gt;
&lt;img src=&quot;https://i.pinimg.com/736x/16/24/f9/1624f978c1b40c05ca65d31656d44fe7.jpg&quot;&gt;
&lt;img src=&quot;https://i.pinimg.com/736x/e5/79/9f/e5799f71358fc931b962137abe551483.jpg&quot;&gt;
&lt;img src=&quot;https://i.pinimg.com/1200x/12/9b/76/129b7630baa815012a13afb634f96d36.jpg&quot;&gt;
&lt;img src=&quot;https://i.pinimg.com/1200x/60/a0/e1/60a0e1338cac09b2457564b98b4504a5.jpg&quot;&gt;
&lt;/div&gt;

&lt;div class=&quot;column&quot;&gt;
&lt;img src=&quot;https://i.pinimg.com/1200x/60/a0/e1/60a0e1338cac09b2457564b98b4504a5.jpg&quot;&gt;
&lt;img src=&quot;https://i.pinimg.com/736x/16/24/f9/1624f978c1b40c05ca65d31656d44fe7.jpg&quot;&gt;
&lt;img src=&quot;https://i.pinimg.com/1200x/12/9b/76/129b7630baa815012a13afb634f96d36.jpg&quot;&gt;
&lt;img src=&quot;https://i.pinimg.com/736x/e5/79/9f/e5799f71358fc931b962137abe551483.jpg&quot;&gt;
&lt;/div&gt;
&lt;/div&gt;

&lt;/body&gt;
&lt;/html&gt;
