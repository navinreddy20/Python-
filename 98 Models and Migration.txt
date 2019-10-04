                              index.html
--------------------------------------------------------------------------------
{% load static %}
{% static "images" as baseUrl %}
<!DOCTYPE html>
<html lang="en">

<head>
	<title>Travello</title>
	<meta charset="utf-8">
	<meta http-equiv="X-UA-Compatible" content="IE=edge">
	<meta name="description" content="Travello template project">
	<meta name="viewport" content="width=device-width, initial-scale=1">
	<link rel="stylesheet" type="text/css" href="{% static 'styles/bootstrap4/bootstrap.min.css' %}">
	<link href="{%static 'plugins/font-awesome-4.7.0/css/font-awesome.min.css' %}" rel="stylesheet" type="text/css">
	<link rel="stylesheet" type="text/css" href="{%static 'plugins/OwlCarousel2-2.2.1/owl.carousel.css' %}">
	<link rel="stylesheet" type="text/css" href="{%static 'plugins/OwlCarousel2-2.2.1/owl.theme.default.css' %}">
	<link rel="stylesheet" type="text/css" href="{%static 'plugins/OwlCarousel2-2.2.1/animate.css' %}">
	<link rel="stylesheet" type="text/css" href="{%static 'styles/main_styles.css' %}">
	<link rel="stylesheet" type="text/css" href="{%static 'styles/responsive.css' %}">
</head>

<body>

	<div class="super_container">

		<!-- Header -->

		<header class="header">
			<div class="container">
				<div class="row">
					<div class="col">
						<div class="header_content d-flex flex-row align-items-center justify-content-start">
							<div class="header_content_inner d-flex flex-row align-items-end justify-content-start">
								<div class="logo"><a href="index.html">Travello</a></div>
								<nav class="main_nav">
									<ul class="d-flex flex-row align-items-start justify-content-start">
										<li class="active"><a href="index.html">Home</a></li>
										<li><a href="about.html">About us</a></li>
										<li><a href="#">Services</a></li>
										<li><a href="news.html">News</a></li>
										<li><a href="contact.html">Contact</a></li>
									</ul>
								</nav>
								<div class="header_phone ml-auto">Call us: 00-56 445 678 33</div>

								<!-- Hamburger -->

								<div class="hamburger ml-auto">
									<i class="fa fa-bars" aria-hidden="true"></i>
								</div>

							</div>
						</div>
					</div>
				</div>
			</div>
			<div class="header_social d-flex flex-row align-items-center justify-content-start">
				<ul class="d-flex flex-row align-items-start justify-content-start">
					<li><a href="#"><i class="fa fa-pinterest" aria-hidden="true"></i></a></li>
					<li><a href="#"><i class="fa fa-facebook" aria-hidden="true"></i></a></li>
					<li><a href="#"><i class="fa fa-twitter" aria-hidden="true"></i></a></li>
					<li><a href="#"><i class="fa fa-dribbble" aria-hidden="true"></i></a></li>
					<li><a href="#"><i class="fa fa-behance" aria-hidden="true"></i></a></li>
					<li><a href="#"><i class="fa fa-linkedin" aria-hidden="true"></i></a></li>
				</ul>
			</div>
		</header>

		<!-- Menu -->

		<div class="menu">
			<div class="menu_header d-flex flex-row align-items-center justify-content-start">
				<div class="menu_logo"><a href="index.html">Travello</a></div>
				<div class="menu_close_container ml-auto">
					<div class="menu_close">
						<div></div>
						<div></div>
					</div>
				</div>
			</div>
			<div class="menu_content">
				<ul>
					<li><a href="inex.html">Home</a></li>
					<li><a href="about.html">About us</a></li>
					<li><a href="#">Services</a></li>
					<li><a href="news.html">News</a></li>
					<li><a href="contact.html">Contact</a></li>
				</ul>
			</div>
			<div class="menu_social">
				<div class="menu_phone ml-auto">Call us: 00-56 445 678 33</div>
				<ul class="d-flex flex-row align-items-start justify-content-start">
					<li><a href="#"><i class="fa fa-pinterest" aria-hidden="true"></i></a></li>
					<li><a href="#"><i class="fa fa-facebook" aria-hidden="true"></i></a></li>
					<li><a href="#"><i class="fa fa-twitter" aria-hidden="true"></i></a></li>
					<li><a href="#"><i class="fa fa-dribbble" aria-hidden="true"></i></a></li>
					<li><a href="#"><i class="fa fa-behance" aria-hidden="true"></i></a></li>
					<li><a href="#"><i class="fa fa-linkedin" aria-hidden="true"></i></a></li>
				</ul>
			</div>
		</div>

		<!-- Home -->

		<div class="home">

			<!-- Home Slider -->
			<div class="home_slider_container">
				<div class="owl-carousel owl-theme home_slider">

					<!-- Slide -->
					<div class="owl-item">
						<div class="background_image"
							style="background-image:url({% static 'images/home_slider.jpg' %})"></div>
						<div class="home_slider_content_container">
							<div class="container">
								<div class="row">
									<div class="col">
										<div class="home_slider_content">
											<div class="home_title">
												<h2>Let us take you away</h2>
											</div>
										</div>
									</div>
								</div>
							</div>
						</div>
					</div>

					<!-- Slide -->
					<div class="owl-item">
						<div class="background_image"
							style="background-image:url({% static 'images/home_slider.jpg' %})"></div>
						<div class="home_slider_content_container">
							<div class="container">
								<div class="row">
									<div class="col">
										<div class="home_slider_content">
											<div class="home_title">
												<h2>Let us take you away</h2>
											</div>
										</div>
									</div>
								</div>
							</div>
						</div>
					</div>

					<!-- Slide -->
					<div class="owl-item">
						<div class="background_image"
							style="background-image:url({% static 'images/home_slider.jpg' %})"></div>
						<div class="home_slider_content_container">
							<div class="container">
								<div class="row">
									<div class="col">
										<div class="home_slider_content">
											<div class="home_title">
												<h2>Let us take you away</h2>
											</div>
										</div>
									</div>
								</div>
							</div>
						</div>
					</div>

				</div>

				<div class="home_page_nav">
					<ul class="d-flex flex-column align-items-end justify-content-end">
						<li><a href="#" data-scroll-to="#destinations">Offers<span>01</span></a></li>
						<li><a href="#" data-scroll-to="#testimonials">Testimonials<span>02</span></a></li>
						<li><a href="#" data-scroll-to="#news">Latest<span>03</span></a></li>
					</ul>
				</div>
			</div>
		</div>

		<!-- Search -->

		<div class="home_search">
			<div class="container">
				<div class="row">
					<div class="col">
						<div class="home_search_container">
							<div class="home_search_title">Search for your trip</div>
							<div class="home_search_content">
								<form action="#" class="home_search_form" id="home_search_form">
									<div
										class="d-flex flex-lg-row flex-column align-items-start justify-content-lg-between justify-content-start">
										<input type="text" class="search_input search_input_1" placeholder="City"
											required="required">
										<input type="text" class="search_input search_input_2" placeholder="Departure"
											required="required">
										<input type="text" class="search_input search_input_3" placeholder="Arrival"
											required="required">
										<input type="text" class="search_input search_input_4" placeholder="Budget"
											required="required">
										<button class="home_search_button">search</button>
									</div>
								</form>
							</div>
						</div>
					</div>
				</div>
			</div>
		</div>

		<!-- Intro -->

		<div class="intro">
			<div class="intro_background" style="background-image:url({% static 'images/intro.png' %})"></div>
			<div class="container">
				<div class="row">
					<div class="col">
						<div class="intro_container">
							<div class="row">

								<!-- Intro Item -->
								<div class="col-lg-4 intro_col">
									<div class="intro_item d-flex flex-row align-items-end justify-content-start">
										<div class="intro_icon"><img src="{% static 'images/beach.svg' %}" alt=""></div>
										<div class="intro_content">
											<div class="intro_title">Top Destinations</div>
											<div class="intro_subtitle">
												<p>Nulla pretium tincidunt felis, nec.</p>
											</div>
										</div>
									</div>
								</div>

								<!-- Intro Item -->
								<div class="col-lg-4 intro_col">
									<div class="intro_item d-flex flex-row align-items-end justify-content-start">
										<div class="intro_icon"><img src="{% static 'images/wallet.svg' %}" alt="">
										</div>
										<div class="intro_content">
											<div class="intro_title">The Best Prices</div>
											<div class="intro_subtitle">
												<p>Sollicitudin mauris lobortis in.</p>
											</div>
										</div>
									</div>
								</div>

								<!-- Intro Item -->
								<div class="col-lg-4 intro_col">
									<div class="intro_item d-flex flex-row align-items-end justify-content-start">
										<div class="intro_icon"><img src="{% static 'images/suitcase.svg' %}" alt="">
										</div>
										<div class="intro_content">
											<div class="intro_title">Amazing Services</div>
											<div class="intro_subtitle">
												<p>Nulla pretium tincidunt felis, nec.</p>
											</div>
										</div>
									</div>
								</div>

							</div>
						</div>
					</div>
				</div>
			</div>
		</div>

		<!-- Destinations -->

		<div class="destinations" id="destinations">
			<div class="container">
				<div class="row">
					<div class="col text-center">
						<div class="section_subtitle">simply amazing places</div>
						<div class="section_title">
							<h2>Popular Destinations</h2>
						</div>
					</div>
				</div>
				<div class="row destinations_row">
					<div class="col">
						<div class="destinations_container item_grid">

							{% for dest in dests %}
							<!-- Destination -->
							<div class="destination item">
								<div class="destination_image">
									<img src="{{baseUrl}}/{{dest.img}}" alt="">

									{% if dest.offer %}
									<div class="spec_offer text-center"><a href="#">Special Offer</a></div>
									{% endif %}
								</div>
								<div class="destination_content">
									<div class="destination_title"><a href="destinations.html">{{dest.name}}</a></div>
									<div class="destination_subtitle">
										<p>{{dest.desc}}</p>
									</div>
									<div class="destination_price">From ${{dest.price}}</div>
								</div>
							</div>

							{% endfor %}


						</div>
					</div>
				</div>
			</div>
		</div>

		<!-- Testimonials -->

		<div class="testimonials" id="testimonials">
			<div class="parallax_background parallax-window" data-parallax="scroll"
				data-image-src="{% static 'images/testimonials.jpg' %}" data-speed="0.8"></div>
			<div class="container">
				<div class="row">
					<div class="col text-center">
						<div class="section_subtitle">simply amazing places</div>
						<div class="section_title">
							<h2>Testimonials</h2>
						</div>
					</div>
				</div>
				<div class="row testimonials_row">
					<div class="col">

						<!-- Testimonials Slider -->
						<div class="testimonials_slider_container">
							<div class="owl-carousel owl-theme testimonials_slider">

								<!-- Slide -->
								<div class="owl-item text-center">
									<div class="testimonial">Lorem ipsum dolor sit amet, consectetur adipiscing elit.
										lobortis dolor. Cras placerat lectus a posuere aliquet. Curabitur quis vehicula
										odio.</div>
									<div class="testimonial_author">
										<div
											class="testimonial_author_content d-flex flex-row align-items-end justify-content-start">
											<div>john turner,</div>
											<div>client</div>
										</div>
									</div>
								</div>

								<!-- Slide -->
								<div class="owl-item text-center">
									<div class="testimonial">Lorem ipsum dolor sit amet, consectetur adipiscing elit.
										lobortis dolor. Cras placerat lectus a posuere aliquet. Curabitur quis vehicula
										odio.</div>
									<div class="testimonial_author">
										<div
											class="testimonial_author_content d-flex flex-row align-items-end justify-content-start">
											<div>john turner,</div>
											<div>client</div>
										</div>
									</div>
								</div>

								<!-- Slide -->
								<div class="owl-item text-center">
									<div class="testimonial">Lorem ipsum dolor sit amet, consectetur adipiscing elit.
										lobortis dolor. Cras placerat lectus a posuere aliquet. Curabitur quis vehicula
										odio.</div>
									<div class="testimonial_author">
										<div
											class="testimonial_author_content d-flex flex-row align-items-end justify-content-start">
											<div>john turner,</div>
											<div>client</div>
										</div>
									</div>
								</div>

							</div>
						</div>
					</div>
				</div>
			</div>
			<div class="test_nav">
				<ul class="d-flex flex-column align-items-end justify-content-end">
					<li><a href="#">City Breaks Clients<span>01</span></a></li>
					<li><a href="#">Cruises Clients<span>02</span></a></li>
					<li><a href="#">All Inclusive Clients<span>03</span></a></li>
				</ul>
			</div>
		</div>

		<!-- News -->

		<div class="news" id="news">
			<div class="container">
				<div class="row">
					<div class="col-xl-8">
						<div class="news_container">

							<!-- News Post -->
							<div
								class="news_post d-flex flex-md-row flex-column align-items-start justify-content-start">
								<div class="news_post_image"><img src="{% static 'images/news_1.jpg' %}" alt=""></div>
								<div class="news_post_content">
									<div class="news_post_date d-flex flex-row align-items-end justify-content-start">
										<div>02</div>
										<div>june</div>
									</div>
									<div class="news_post_title"><a href="#">Best tips to travel light</a></div>
									<div class="news_post_category">
										<ul>
											<li><a href="#">lifestyle & travel</a></li>
										</ul>
									</div>
									<div class="news_post_text">
										<p>Pellentesque sit amet elementum ccumsan sit amet mattis eget, tristique at
											leo. Vivamus massa.Tempor massa et laoreet.</p>
									</div>
								</div>
							</div>

							<!-- News Post -->
							<div
								class="news_post d-flex flex-md-row flex-column align-items-start justify-content-start">
								<div class="news_post_image"><img src="{% static 'images/news_2.jpg' %}" alt=""></div>
								<div class="news_post_content">
									<div class="news_post_date d-flex flex-row align-items-end justify-content-start">
										<div>01</div>
										<div>june</div>
									</div>
									<div class="news_post_title"><a href="#">Best tips to travel light</a></div>
									<div class="news_post_category">
										<ul>
											<li><a href="#">lifestyle & travel</a></li>
										</ul>
									</div>
									<div class="news_post_text">
										<p>Tempor massa et laoreet malesuada. Pellentesque sit amet elementum ccumsan
											sit amet mattis eget, tristique at leo.</p>
									</div>
								</div>
							</div>

							<!-- News Post -->
							<div
								class="news_post d-flex flex-md-row flex-column align-items-start justify-content-start">
								<div class="news_post_image"><img src="{% static 'images/news_3.jpg' %}" alt=""></div>
								<div class="news_post_content">
									<div class="news_post_date d-flex flex-row align-items-end justify-content-start">
										<div>29</div>
										<div>may</div>
									</div>
									<div class="news_post_title"><a href="#">Best tips to travel light</a></div>
									<div class="news_post_category">
										<ul>
											<li><a href="#">lifestyle & travel</a></li>
										</ul>
									</div>
									<div class="news_post_text">
										<p>Vivamus massa.Tempor massa et laoreet malesuada. Aliquam nulla nisl, accumsan
											sit amet mattis.</p>
									</div>
								</div>
							</div>

						</div>
					</div>

					<!-- News Sidebar -->
					<div class="col-xl-4">
						<div class="travello">
							<div class="background_image"
								style="background-image:url({% static 'images/travello.jpg' %})"></div>
							<div class="travello_content">
								<div class="travello_content_inner">
									<div></div>
									<div></div>
								</div>
							</div>
							<div class="travello_container">
								<a href="#">
									<div class="d-flex flex-column align-items-center justify-content-end">
										<span class="travello_title">Get a 20% Discount</span>
										<span class="travello_subtitle">Buy Your Vacation Online Now</span>
									</div>
								</a>
							</div>
						</div>
					</div>
				</div>
			</div>
		</div>

		<!-- Footer -->

		<footer class="footer">
			<div class="parallax_background parallax-window" data-parallax="scroll"
				data-image-src="{% static 'images/footer_1.jpg' %}" data-speed="0.8"></div>
			<div class="container">
				<div class="row">
					<div class="col">
						<div class="newsletter">
							<div class="newsletter_title_container text-center">
								<div class="newsletter_title">Subscribe to our newsletter to get the latest trends &
									news</div>
								<div class="newsletter_subtitle">Join our database NOW!</div>
							</div>
							<div class="newsletter_form_container">
								<form action="#"
									class="newsletter_form d-flex flex-md-row flex-column align-items-start justify-content-between"
									id="newsletter_form">
									<div
										class="d-flex flex-md-row flex-column align-items-start justify-content-between">
										<div><input type="text" class="newsletter_input newsletter_input_name"
												id="newsletter_input_name" placeholder="Name" required="required">
											<div class="input_border"></div>
										</div>
										<div><input type="email" class="newsletter_input newsletter_input_email"
												id="newsletter_input_email" placeholder="Your e-mail"
												required="required">
											<div class="input_border"></div>
										</div>
									</div>
									<div><button class="newsletter_button">subscribe</button></div>
								</form>
							</div>
						</div>
					</div>
				</div>
				<div class="row footer_contact_row">
					<div class="col-xl-10 offset-xl-1">
						<div class="row">

							<!-- Footer Contact Item -->
							<div class="col-xl-4 footer_contact_col">
								<div
									class="footer_contact_item d-flex flex-column align-items-center justify-content-start text-center">
									<div class="footer_contact_icon"><img src="{% static 'images/sign.svg' %}" alt="">
									</div>
									<div class="footer_contact_title">give us a call</div>
									<div class="footer_contact_list">
										<ul>
											<li>Office Landline: +44 5567 32 664 567</li>
											<li>Mobile: +44 5567 89 3322 332</li>
										</ul>
									</div>
								</div>
							</div>

							<!-- Footer Contact Item -->
							<div class="col-xl-4 footer_contact_col">
								<div
									class="footer_contact_item d-flex flex-column align-items-center justify-content-start text-center">
									<div class="footer_contact_icon"><img src="{% static 'images/trekking.svg' %}"
											alt=""></div>
									<div class="footer_contact_title">come & drop by</div>
									<div class="footer_contact_list">
										<ul style="max-width:190px">
											<li>4124 Barnes Street, Sanford, FL 32771</li>
										</ul>
									</div>
								</div>
							</div>

							<!-- Footer Contact Item -->
							<div class="col-xl-4 footer_contact_col">
								<div
									class="footer_contact_item d-flex flex-column align-items-center justify-content-start text-center">
									<div class="footer_contact_icon"><img src="{% static 'images/around.svg' %}" alt="">
									</div>
									<div class="footer_contact_title">send us a message</div>
									<div class="footer_contact_list">
										<ul>
											<li>youremail@gmail.com</li>
											<li>Office@yourbusinessname.com</li>
										</ul>
									</div>
								</div>
							</div>

						</div>
					</div>
				</div>
			</div>
			<div class="col text-center">
				<!-- Link back to Colorlib can't be removed. Template is licensed under CC BY 3.0. -->
				Copyright &copy;
				<script>document.write(new Date().getFullYear());</script> All rights reserved | This template is made
				with <i class="fa fa-heart-o" aria-hidden="true"></i> by <a href="https://colorlib.com"
					target="_blank">Colorlib</a>
				<!-- Link back to Colorlib can't be removed. Template is licensed under CC BY 3.0. -->
			</div>
		</footer>
	</div>

	<script src="{% static 'js/jquery-3.2.1.min.js' %}"></script>
	<script src="{% static 'styles/bootstrap4/popper.js' %}"></script>
	<script src="{% static 'styles/bootstrap4/bootstrap.min.js' %}"></script>
	<script src="{% static 'plugins/OwlCarousel2-2.2.1/owl.carousel.js' %}"></script>
	<script src="{% static 'plugins/Isotope/isotope.pkgd.min.js' %}"></script>
	<script src="{% static 'plugins/scrollTo/jquery.scrollTo.min.js' %}"></script>
	<script src="{% static 'plugins/easing/easing.js' %}"></script>
	<script src="{% static 'plugins/parallax-js-master/parallax.min.js' %}"></script>
	<script src="{% static 'js/custom.js' %}"></script>
</body>

</html>

--------------------------------------------------------------------------------
                               models.py 
--------------------------------------------------------------------------------

from django.db import models

# Create your models here.


class Destination(models.Model):

    name = models.CharField(max_length=100)
    img = models.ImageField(upload_to='pics')
    desc = models.TextField()
    price = models.IntegerField()
    offer = models.BooleanField(default=False)


--------------------------------------------------------------------------------
                                  views.py
--------------------------------------------------------------------------------


from django.shortcuts import render
from .models import Destination

# Create your views here.


def index(request):

    dest1 = Destination()
    dest1.name = 'Mumbai'
    dest1.desc = 'The City That Never Sleeps'
    dest1.img = 'destination_1.jpg'
    dest1.price = 700
    dest1.offer = False

    dest2 = Destination()
    dest2.name = 'Hyderabad'
    dest2.desc = 'First Biryani, Then Sherwani'
    dest2.img = 'destination_2.jpg'
    dest2.price = 650
    dest2.offer = True

    dest3 = Destination()
    dest3.name = 'Bengaluru'
    dest3.desc = 'Beautiful City'
    dest3.img = 'destination_3.jpg'
    dest3.price = 750
    dest3.offer = True

    dests = [dest1, dest2, dest3]

    return render(request, "index.html", {'dests': dests})

--------------------------------------------------------------------------------
                            settings.py
--------------------------------------------------------------------------------

"""
Django settings for telusko project.

Generated by 'django-admin startproject' using Django 2.2.5.

For more information on this file, see
https://docs.djangoproject.com/en/2.2/topics/settings/

For the full list of settings and their values, see
https://docs.djangoproject.com/en/2.2/ref/settings/
"""

import os

# Build paths inside the project like this: os.path.join(BASE_DIR, ...)
BASE_DIR = os.path.dirname(os.path.dirname(os.path.abspath(__file__)))


# Quick-start development settings - unsuitable for production
# See https://docs.djangoproject.com/en/2.2/howto/deployment/checklist/

# SECURITY WARNING: keep the secret key used in production secret!
SECRET_KEY = 'fdg3ouh6u6x2x@ziy!t8k30!qq^fw@wc882*k4y&djotjrn+1s'

# SECURITY WARNING: don't run with debug turned on in production!
DEBUG = True

ALLOWED_HOSTS = []


# Application definition

INSTALLED_APPS = [
    'travello.apps.TravelloConfig',
    'django.contrib.admin',
    'django.contrib.auth',
    'django.contrib.contenttypes',
    'django.contrib.sessions',
    'django.contrib.messages',
    'django.contrib.staticfiles',
]

MIDDLEWARE = [
    'django.middleware.security.SecurityMiddleware',
    'django.contrib.sessions.middleware.SessionMiddleware',
    'django.middleware.common.CommonMiddleware',
    'django.middleware.csrf.CsrfViewMiddleware',
    'django.contrib.auth.middleware.AuthenticationMiddleware',
    'django.contrib.messages.middleware.MessageMiddleware',
    'django.middleware.clickjacking.XFrameOptionsMiddleware',
]

ROOT_URLCONF = 'telusko.urls'

TEMPLATES = [
    {
        'BACKEND': 'django.template.backends.django.DjangoTemplates',
        'DIRS': [os.path.join(BASE_DIR, 'templates')],
        'APP_DIRS': True,
        'OPTIONS': {
            'context_processors': [
                'django.template.context_processors.debug',
                'django.template.context_processors.request',
                'django.contrib.auth.context_processors.auth',
                'django.contrib.messages.context_processors.messages',
            ],
        },
    },
]

WSGI_APPLICATION = 'telusko.wsgi.application'


# Database
# https://docs.djangoproject.com/en/2.2/ref/settings/#databases

DATABASES = {
    'default': {
        'ENGINE': 'django.db.backends.postgresql',
        'NAME': 'telusko',
        'USER': 'postgres',
        'PASSWORD': '1234',
        'HOST': 'localhost'
    }
}


# Password validation
# https://docs.djangoproject.com/en/2.2/ref/settings/#auth-password-validators

AUTH_PASSWORD_VALIDATORS = [
    {
        'NAME': 'django.contrib.auth.password_validation.UserAttributeSimilarityValidator',
    },
    {
        'NAME': 'django.contrib.auth.password_validation.MinimumLengthValidator',
    },
    {
        'NAME': 'django.contrib.auth.password_validation.CommonPasswordValidator',
    },
    {
        'NAME': 'django.contrib.auth.password_validation.NumericPasswordValidator',
    },
]


# Internationalization
# https://docs.djangoproject.com/en/2.2/topics/i18n/

LANGUAGE_CODE = 'en-us'

TIME_ZONE = 'UTC'

USE_I18N = True

USE_L10N = True

USE_TZ = True


# Static files (CSS, JavaScript, Images)
# https://docs.djangoproject.com/en/2.2/howto/static-files/

STATIC_URL = '/static/'
STATICFILES_DIRS = [
    os.path.join(BASE_DIR, 'static')
]
STATIC_ROOT = os.path.join(BASE_DIR, 'assets')



--------------------------------------------------------------------------------                           Migration Steps
--------------------------------------------------------------------------------

>pip install psycopg2
>pip install Pillow
>python manage.py makemigrations
>python manage.py sqlmigrate travello 0001
>python manage.py migrate
