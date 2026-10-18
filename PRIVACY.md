# Elpriset privacy policy

*Last updated: 18 October 2026*

Elpriset is an iPhone and iPad app, with a widget, that shows day-ahead electricity prices
for Sweden, Norway, Denmark and Finland. This policy explains what the app does with
information.

**In short:** Elpriset does not collect personal data. It has no account, no analytics, no
advertising and no tracking. The developer receives no information about you or about how
you use the app.

## Information that stays on your device

The app stores the following on your device only:

- **Your settings:** country and price zone, retailer, any custom contract terms, the
  contract type (15-minute or hourly), and whether price alerts are on. They are kept in the
  app's storage and in an App Group container shared with the Elpriset widget.
- **Downloaded data:** prices and configuration the app has fetched. These are cached so it
  can show past days and keep working offline.
- **A Tibber API token, if you enter one.** It is stored in the iOS Keychain on this device
  only. It is not synced through iCloud Keychain and is not restored to another device from
  a backup. Clearing the field in the app deletes it.

None of this is sent to the developer. Deleting the app removes its settings and cached
data. iOS may keep Keychain items after an app is deleted, so clear a Tibber token in the
app first if you want it gone. You can also revoke the token with Tibber.

## Location

Location is optional. The app uses it only when you tap **Use my location** while choosing
your price zone:

1. iOS asks for your permission. The app only asks for access while you are using it.
2. The app takes a single location fix.
3. The app sends that fix to Apple's geocoding service, which is part of iOS, to find which
   country you are in. Apple handles this under its own privacy policy.
4. The app works out your price zone on the device, from the country and the coordinates.

The location is not stored and is not used again. It is not sent to the developer or to
anyone other than Apple's geocoding service. Only the zone you end up choosing is saved, as
one of your settings. You can always pick the zone by hand instead.

## Network requests

The app and the widget connect directly to the services below. None of them receives your
location or any identifier from the app. The one exception is a Tibber API token you enter
yourself, which is sent only to Tibber. Like any internet request, each request reveals
your IP address and standard technical details, such as the app name and iOS version in the
user agent. Each service handles these under its own policy.

| Service | Why | What the request contains |
|---|---|---|
| elprisetjustnu.se, hvakosterstrommen.no and elprisenligenu.dk (Sweden, Norway, Denmark); api.spot-hinta.fi (Finland) | Spot prices | For the first three, the day and the price zone (e.g. SE3). For api.spot-hinta.fi, nothing: it always returns today's and tomorrow's prices for Finland |
| api.met.no (Norwegian Meteorological Institute) | Weather forecast for the price outlook | The coordinates of a fixed reference city for your zone (e.g. Stockholm for SE3), never your own location |
| raw.githubusercontent.com (GitHub) | Up-to-date retailer and market configuration | Nothing beyond the request itself |
| api.tibber.com | Your own Tibber prices, only if you enter a Tibber API token | Your token |

The price services are the ones named in the app's configuration. The developer will update
this list if they change.

## Notifications and Live Activity

Price alerts and the daily price summary are scheduled on your device by the app. No push
notification service is used, and nothing is sent to a server. The Live Activity is updated
on the device by the app.

## Tracking, analytics and advertising

The app does none of these. It contains no third-party analytics, advertising or tracking
code, and it does not use the advertising identifier.

## Children

Elpriset is not directed at children. It collects no personal data from anyone.

## Your rights

The developer holds no personal data about you, so there is nothing for the developer to
provide, correct or delete. Your settings stay on your device and are under your control.
For requests handled by Apple, GitHub, the price services, the Norwegian Meteorological
Institute or Tibber, see their privacy policies.

## Changes to this policy

If the app's handling of information changes, this page will be updated and the date at the
top will change. Earlier versions are in this repository's history.

## Contact

**[DEVELOPER: add a contact email address here before publishing.]**
