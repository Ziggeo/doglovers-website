# DogLovers Simple Website
Test website for Techsylvania 2021 Ziggeo's Workshop

## Steps to use this demo

1. Clone this repo
2. Go to [Ziggeo](https://ziggeo.com), create an account/login to your account and select an app.
3. Copy the Application token and the Private Key

### For the recorder to work
1. Go to line 28 in the index.html file and replace the `apptoken` attribute with your app token.
2. If you want to use a [video profile](https://ziggeo.com/docs/dashboard/profiles/video-profiles), please copy the token or key and replace the `video-profile` attribute.
3. If you want to use an [effect profile](https://ziggeo.com/docs/dashboard/profiles/effect-profiles), please copy the token or key and replace the `effect-profile` attribute.
4. If you want to use a [meta profile](https://ziggeo.com/docs/dashboard/profiles/meta-profiles), please copy the token or key and replace the `meta-profile` attribute.
5. If you would like you can also change the embed's [theme](https://ziggeo.com/features/video-recorder-themes/) by replacing the `theme` attribute.
6. That would be enough for the recorder, but it won't make the list of videos appear in the page.

### For the videos list to work
1. Clone the [API](https://github.com/Ziggeo/dogs-api) and follow the installation instructions.
2. Run the API in a server that's accessible from the website and replace the `api_url` attribute with the `get_dogs.php` address from the API.
3. For the videos to appear, you should go to the Moderation page in your Ziggeo Application, approve the videos and tag them accordingly. (You can also do this automatically with webhooks).
4. Now we're done :)

