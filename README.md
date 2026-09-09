# topjow-legal

Public legal pages for WebJow's apps. One folder per app; each folder is its
own static page with no scripts, no trackers and no external assets — which is
the point, since a privacy policy that loads third-party resources is an odd
thing to ask anyone to trust.

| App | Page |
|---|---|
| آقا میرزا (Agha Mirza) — Persian word puzzle | <https://faizahmaddae.github.io/topjow-legal/aghamirza/> |
| Potionary — potion-sorting puzzle | <https://faizahmaddae.github.io/topjow-legal/potionary/> |
| گاد مافیا (God Mafia) — Mafia party-game moderator | <https://faizahmaddae.github.io/topjow-legal/godmafia/> |
| LebenTest — German citizenship-test preparation in Farsi and Dari | <https://faizahmaddae.github.io/topjow-legal/lebentest/> |

Contact: support@topjow.org

Each app's source of truth is the `store/` folder of its own repository; the
copy here exists so the page has a public URL for the Google Play and App Store
listings. Edit there, then copy across and push.

Potionary's page is trilingual — English, فارسی, العربية — and picks a language
from the URL fragment: `#en`, `#fa`, `#ar`. LebenTest provides separate,
directly linkable English, German and فارسی/دری policy pages in its folder.

**`potionary-site` must not be deleted until Potionary's own Play listing has
been pointed here.** That app is published, and a published app whose privacy
policy URL 404s is a policy violation, not a broken link.
