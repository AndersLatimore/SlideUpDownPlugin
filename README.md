<h1>Slide Up Down: A jquery plugin</h1>
<p>This plugin slides the image up and down when clicked.</p>
<p>All you need to do to use the plugin is download it here and the define the elements as seen below.
<code>#box10</code> is the <code>div</code> where you want to use the plugin. <code>example</code> is
where you define the image that you want to use the the plugin. You can set the speed of the animation by
changing the <code>duration</code> parameter.</p>
<p><code>  $('#box10 img.example').click(function() {
    $(this).slideUpDown({'duration':5000});
    console.log('Clicked image to slide it up and down.');
  });</code></p>
