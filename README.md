# Mastodon-api-php
A GNU Social-compatible microblogging server  https://mastodon.social PHP API

## How to use
require_once '/path/Mastodon_api.php';<br />
<br />
$mastodon_api = new Mastodon_api();<br />
$mastodon_api->set_url('Mastodon url');<br />
<br />
// print_r($mastodon_api->create_app('APP Name',null,null,'Mastodon url'));<br />
$mastodon_api->set_client('client_id','client_secret');<br />
<br />
// print_r($mastodon_api->login('your login email','your login password'));<br />
$mastodon_api->set_token('access_token','token_type');<br />
<br />
$mastodon_api->timelines_home();

## Test Mastodon
https://ery.kr
