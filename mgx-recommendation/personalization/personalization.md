# Personalization

_**Recommended for you**_ is the classic personalized recommendation line. It displays profile-based suggestions of titles to watch, ordered by relevance.It is updated in real time and calculated from user interactions with content, taking into account multiple factors such as time of day and user-specific theme preferences.

Spideo personalized recommendations are semantic-based. In other words, each movie or TV show has its own weighed semantics (see **Content Semantic Fingerprint**), which will be the main elements contributing to showing the right content to the right people and at the right time.

### Endpoint <a href="#endpoint" id="endpoint"></a>

```
GET /users/{user}/recommendation/{universes}
```

More details on the API documentation

### (https://spideo-dev-manual.mintlify.app/mgx-recommendation/features/personalization#use-case)Use case <a href="#use-case" id="use-case"></a>

The “recommended for you” line is as versatile as it is classical, it can be integrated anywhere :

* high up on the homepage
* On a specific user page
* Or even on every content page, next to **Similar Content**.
