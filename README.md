# takken-app-pages

Public support and policy pages for the Takken app.

GitHub Pages URL:

```text
https://bitmeister-yk.github.io/takken-app-pages/
```

Pages:

- `index.html`
- `privacy.html`
- `support.html`
- `terms.html`

SNS landing page:

```text
https://bitmeister-yk.github.io/takken-app-pages/?campaign_code=phase1-question_prompt-001
```

App Store Connect campaign link passthrough:

```text
https://bitmeister-yk.github.io/takken-app-pages/?campaign_code=phase1-question_prompt-001&pt=<provider-token>&mt=8
```

Supported campaign parameters:

- `campaign_code`
- `campaign`
- `ct`
- `utm_campaign`
- `pt`
- `provider_token`
- `mt`
- `media_type`

The landing page maps the local campaign value to the App Store campaign token
`ct`. When `pt` is supplied, it also passes the provider token to the App Store
link and defaults `mt` to `8` for app campaigns unless another media type is
explicitly supplied. No provider token is stored as a default in this repository.
