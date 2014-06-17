# EmbedlyBundle

This bundle creates just makes use of the official embedly api provided by embed.ly. It provides you with one service called 'stegeman_embedly.api'.

## Installation

Using Composer, add to composer.json:

    {
        "require": {
            "stegeman/embedly-bundle": "dev-master"
        }
    }

Then install it using composer:

    php composer.phar update stegeman/embedly-bundle

Register the bundle in /app/AppKernel.php:

    <?php

    class AppKernel extends Kernel
    {
        public function registerBundles()
        {
            $bundles = array(
                // ...
                new Stegeman\EmbedlyBundle\StegemanEmbedlyBundle()
            );
        }
    }

## Configuration

This bundle had four configuration options: The only required option is the key
provided by embedly.

    # in config.yml
    stegeman_embedly:
        args:
            key: 9cddb3ccb4c5418387e59411693f5afd   # required
            hostname: api.embed.ly                  # Optional
            api_version:                            # optional
                oembed:     1
                objectify:  2
                preview:    1
                extract:    1
            user_agent:     Mozilla/5.0 (compatible; embedly-php/%s) #optional

