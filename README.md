# Homepage Slick Slider

[Solodev's](https://www.solodev.com/) twist on a homepage slider is modern, responsive, and easy to implement. Based on [Slick Slider by Ken Wheeler](http://kenwheeler.github.io/slick/), this slider is agency tested and ready for your web project. The slider can be used out-of-the-box and includes innate responsive styling within a Bootstrap framework. Tested in Chrome, Firefox, and Edge.

## Tutorial

For detailed instructions regarding implementing the slider, view Solodev's [Add a Hero Slider to your Homepage Using Slick Slider](https://www.solodev.com/blog/web-design/code-examples/2014395-add-a-hero-slider-to-your-homepage-using-slick-slider.stml) article.

## Demo

Check out a working example on [JSFiddle](https://jsfiddle.net/solodev/dbowxqc6/).

## HTML

The slider uses simple and intuitive HTML with Bootstrap standards. Each slide is set in the markup below:
```
<div class="ct-header tablex item" data-background="images/slide1.jpg">
	<div class="ct-u-display-tablex">
		<div class="inner">
			<div class="container">
				<div class="row">
					<div class="col-md-8 col-lg-6 slider-inner">
						<h1 class="big">Big Data. Realtime Insight.</h1>
						<p>Leverage your data and improve marketing and sales ROI.</p>
						<a class="btn btn-transparent btn-lg text-uppercase" href="">Learn More</a>
					</div>
				</div>
			</div>
		</div>
	</div>
</div>
```

## CSS

All CSS is included in slider.css

## JavaScript

In addition to the slider-bg.js resource, the slider itself needs to be initialized with the following script:
```
<script>
	$(document).ready(function(){
		$('.ct-slick-homepage').slick({
			autoplay: true,
			autoplaySpeed: 3000,
		});
	});
</script>
```

For a full list attributes you can use to customize your slider, visit [Slick Slider by Ken Wheeler](http://kenwheeler.github.io/slick/).

## External Includes

The slider includes the following third-party resources:
```
<link href="https://cdnjs.cloudflare.com/ajax/libs/slick-carousel/1.6.0/slick.min.css" rel="stylesheet" type="text/css" />
<link href="https://maxcdn.bootstrapcdn.com/bootstrap/3.3.6/css/bootstrap.min.css" rel="stylesheet" />
	
<script src="https://ajax.googleapis.com/ajax/libs/jquery/1.12.4/jquery.min.js"></script>
<script src="https://cdnjs.cloudflare.com/ajax/libs/slick-carousel/1.6.0/slick.min.js" type="text/javascript"></script>
<script src="https://maxcdn.bootstrapcdn.com/bootstrap/3.3.6/js/bootstrap.min.js"></script>
```