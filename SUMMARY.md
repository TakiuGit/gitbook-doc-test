# Table of contents

## MGX Recommendation

* [Recommendation](README.md)
* [Security](mgx-recommendation/security.md)
* [Personalization](mgx-recommendation/personalization/README.md)
  * [Live tv habits](mgx-recommendation/personalization/live-tv-habits.md)
  * [Personalization](mgx-recommendation/personalization/personalization.md)
* APIs
  * ```yaml
    type: builtin:openapi
    props:
      models: true
      downloadLink: true
    dependencies:
      spec:
        ref:
          kind: openapi
          spec: spideo-test-api
    ```
