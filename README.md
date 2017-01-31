## JQuery Infinite Scroll

###### Simple infinite scroll jquery implementation inspired by https://github.com/orizens/angular2-infinite-scroll


#### Usage

Select the container of the list and implement the infiniteScroll function.

	$('#divContainer').inifiniteScroll({delay: 500}, function () {
		// do your stuff here when you reach the bottom of the container
	});


The first parameter is the configuration. Here you can modify the `delay` before the function is triggered the default is `500`.

Second parameter is the function that will be triggered when you reach the bottom of the container.