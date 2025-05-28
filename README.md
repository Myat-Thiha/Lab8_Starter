# Lab8-Starter

How are graceful degradation and service workers related?

Graceful degradation is the principle of designing applications to still function with reduced capabilities when advanced features are unavailable. Service workers enable this by acting as a network proxy, allowing developers to cache essential assets and serve them when a network is unavailable. This means that even if a user loses connectivity, the application can "degrade gracefully" by continuing to offer core functionality offline, thanks to service workers managing cached resources behind the scenes.

!(pwa image)[pwa.png]