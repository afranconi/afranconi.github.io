<html lang="{{ site.lang | default: "en-UK" }}">
  <head>
    <meta charset="utf-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">

{% seo %}
    <link rel="stylesheet" href="{{ '/assets/css/style.css?v=' | append: MP_Franconi_Rella_2022.pdf | relative_url }}">
    <script src="https://code.jquery.com/jquery-1.12.4.min.js" integrity="sha256-ZosEbRLbNQzLpnKIkEdrPv7lOy9C27hHQ+Xp8a4MxAQ=" crossorigin="anonymous"></script>
    <script src="{{ '/assets/js/respond.js' | relative_url }}"></script>
    <!--[if lt IE 9]>
      <script src="//html5shiv.googlecode.com/svn/trunk/html5.js"></script>
    <![endif]-->
    <!--[if lt IE 8]>
    <link rel="stylesheet" href="{{ '/assets/css/ie.css' | relative_url }}">
    <![endif]-->
    <meta name="viewport" content="width=device-width, initial-scale=1, user-scalable=no">
    {% include head-custom.html %}
  </head>
  <body>
      <div id="header">
        <nav>
          <ul>
            <li class="fork"><a href="{{ [site.github.repository_url](https://github.com/afranconi/afranconi.github.io/blob/2c9556242b34321b08df7636c3ee8658be4b9546/MP_Franconi_Rella_2022.pdf) }}"> Monetary Policy, Asset Prices, and the Distribution of Wealth in the US</a></li>
            {% if site.show_downloads %}
              <li class="downloads"><a href="{{ site.github.zip_url }}">ZIP</a></li>
              <li class="downloads"><a href="{{ site.github.tar_url }}">TAR</a></li>
              <li class="title">DOWNLOADS</li>
            {% endif %}
          </ul>
        </nav>
      </div><!-- end header -->

    <div class="wrapper">

      <section>
        <div id="title">
          <h1>{{ site.title | default: site.github.repository_name }}</h1>
          <p>{{ site.description | default: site.github.project_tagline }}</p>
          <hr>
          <span class="credits left">Project maintained by <a href="{{ site.github.owner_url }}">{{ site.github.owner_name }}</a></span>

        {{ content }}

      </section>
[CV_FRANCONI.pdf](https://github.com/afranconi/afranconi.github.io/files/10056294/CV_FRANCONI.pdf)
[MP_Franconi_Rella_2022.pdf](https://github.com/afranconi/afranconi.github.io/files/10056296/MP_Franconi_Rella_2022.pdf)

    </div>
  </body>
</html>
