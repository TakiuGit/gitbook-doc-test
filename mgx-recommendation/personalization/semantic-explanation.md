# Semantic Explanations

Explain why any title is recommended to the end user, either through similar titles they’ve already watched or through semantic pairs of keywords they usually interact with.

“Recommendations explained” is a feature which can show the reasoning behind any single recommendation. It can be displayed in 2 ways:

1. The name of the most relevant content related to the current title, e.g. *The Hobbit*  is being recommended to you because you watched *The Lord of the Rings*
2. A pair of keywords which is most accurate regarding the user’s recent interactions, e.g. *The Hobbit* is recommended to you because you like “fantasy and quests”.

“Recommendations explained” can be displayed on content files when a user consults them (if the personalized recommendation would be relevant to the user), or even underneath every content in a list of titles in a “Recommended for you” line. In the latter example, this does not mean every title would have the same argument. Therefore, a personalized recommendations line could be comoposed of: *The Hoobit*, because you like “fantasy and quests”, *Matrix*, because you like science fiction and martial arts, *The Lion King*, because you like Disney cartoons, etc

### Endpoint <a href="#endpoint" id="endpoint"></a>

```
GET /contents/{contentId}/guarantees?user={userid}
```

More details on the [API documentation](/dev/null)

