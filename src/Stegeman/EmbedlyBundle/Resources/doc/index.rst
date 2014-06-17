This bundle creates just makes use of the official embedly api provided by embed.ly. It provides you with one service called 'stegeman_embedly.api'.

The configuration needs one specific attribute 'key' which is the key provided by embedly.

Configuration looks like this:

stegeman_embedly:
    args:
        key: 9cddb3ccb4c5418387e59411693f5afd   # required
        hostname: api.embed.ly # Optional
        api_version:    # optional
            oembed:     1
            objectify:  2
            preview:    1
            extract:    1
        user_agent:     Mozilla/5.0 (compatible; embedly-php/%s) #optional