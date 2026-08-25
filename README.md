## Eric Steinberg

Staff / platform engineer in Austin, Texas. Python, Go, TypeScript.

Nine years at one company (Sumo Group / AppSumo), joining as a junior engineer and leaving as a lead,
building the platforms underneath a marketplace:

- **Partner licensing platform** - a Go service with an OAuth 2.0 / OIDC provider and signed webhooks.
  I founded it and then owned it for five years.
- **Checkout, payments and sales tax** - Stripe, multi-country tax handling, upgrades and refunds, and
  the correctness problems that come with all of it.
- **Page composition CMS** - the tool the marketing team assembles campaign pages with, instead of
  filing engineering tickets.
- **Search, ranking and personalization** - most recently a personalized recommendation engine, and the
  retrieval and LLM pipelines underneath it.

### About the repositories on this profile

They're 2015–2018 coursework and hobby projects, kept for history. They haven't been representative of my
work for a long time. Nine years of professional code sits in private company repositories which is representative
in my contribution graph.

Two pieces of that work are public:

- The partner licensing platform I founded is documented publicly at
    **https://docs.licensing.appsumo.com** - I created and authored that reference (API, OAuth flow,
    webhook integration and signature verification) alongside building the service it describes.
 - The AppSumo homepage runs on the page composition CMS I built — **https://appsumo.com**. I created the
    platform and wrote the components that page is assembled from, including the multi-collection upsell
    panel I pitched and then built. I also built the rendering layer that maps content types to React
    components, and the caching that keeps personalized pages cacheable per user state. Other surfaces
    run on the same framework, such as the product pages, with the components built by the rest of the team
