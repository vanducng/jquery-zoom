# ZOOM.JS

A simple jQuery plugin for image zooming; as seen on [Medium](https://medium.com/designing-medium/image-zoom-on-medium-24d146fc0c20).


### How to add to django template

1. Add zoom.css within head section and zoom.js a

  ```html
  <head>
     ...
     <link href="{% static 'blog/css/zoom.css' %}" rel="stylesheet">
  </head>
  ```

  ```html
  <body>
    <div>
     YOUR BODY CONTENT
    </div>

    <!-- jQuery -->
    <script src="{% static 'blog/js/jquery.js' %}"></script>

    <!-- Bootstrap Core JavaScript -->
    <script src="{% static 'blog/js/bootstrap.bundle.min.js' %}"></script>

    ...
    <!-- ZOOM JS -->
     <script src="js/zoom.js"></script>
  </body>
  ```

2. Add a `data-action="zoom"` attribute to the images you want to make zoomable. For example:

  ```html
  <p align="center">
	<image src="/media/images/your_image.png" class="img-reponsive" alt="insecured nifi" width="100%" data-action="zoom">
  </p>
  ```

### Who

Written by <a href="//twitter.com/fat">@fat</a>, made better by vanducng.
