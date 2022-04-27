<span itemprop="name">TwitterOAuth</span> [![Build Status](https://img.shields.io/travis/abraham/twitteroauth.svg)](https://travis-ci.org/abraham/twitteroauth) [![Scrutinizer Code Quality](https://scrutinizer-ci.com/g/abraham/twitteroauth/badges/quality-score.png?b=master)](https://scrutinizer-ci.com/g/abraham/twitteroauth/?branch=master) [![Issues Count](https://img.shields.io/github/issues/abraham/twitteroauth.svg)](https://github.com/abraham/twitteroauth/issues) [![Latest Version](https://img.shields.io/packagist/v/abraham/twitteroauth.svg)](https://packagist.org/packages/abraham/twitteroauth)
------------

<p itemprop="description">The most popular PHP library for Twitter's OAuth REST API.</p>


How to use new xauth login:

<code>
	
	require "vendor/autoload.php";

	use Abraham\TwitterOAuth\TwitterOAuth;

	$username = 'twitterUsername';
	$password = 'twitterPassword'
	$conncet = new TwitterOAuth(CONSUMER_KEY,CONSUMER_SECRET);
	$connect->setApiVersion('1.1');
	$addUser = $connect->getXAuthToken($username, $password);
</code>
