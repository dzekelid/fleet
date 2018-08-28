swagger: "2.0"
x-collection-name: HERE
x-complete: 1
info:
  title: Weather API
  description: the-here-weather-api-provides-weather-forecasts-and-reports-on-current-weather-conditions-provides-information-on-severe-weather-alerts-provides-information-about-when-the-sun-and-moon-rise-and-set-and-the-phase-of-the-moonthis-example-set-works-with-version-1-2-4-or-higheradditional-information-can-be-found-on-developer-here-comhttpsdeveloper-here-comrestapisdocumentationweather
  version: 1.0.0
host: weather.cit.api.here.com
basePath: /weather/1.0
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /maptile/newest/normal.day/13/4093/2723/256/png8:
    get:
      summary: Fleet Vehicle Map
      description: |-
        *Request a street map tile using the fleet vehicle color scheme*

        Fleet color scheme map tiles are available by passing `style=fleet` as a parameter of the request URL.



        * **style**  `enum`
         \- If present, selects the style to use to render the tile.

         Valid values are : `default`, `alps`, `fleet`, `wings`, `dreamworks`, `flame`, `mini`

        * **app_id**  `text`
         \- A 20 byte Base64 URL-safe encoded string used for the authentication of the client application.    You must include an `app_id` with every request.

        * **app_code**  `text`
         \- A 20 byte Base64 URL-safe encoded string used for the authentication of the client application.    You must include an `app_code` with every request.
      operationId: MaptileNewestNormalDay1340932723256Png8Get
      x-api-path-slug: maptilenewestnormal-day1340932723256png8-get
      parameters:
      - in: query
        name: app_code
      - in: query
        name: app_id
      - in: query
        name: style
      responses:
        200:
          description: OK
      tags:
      - Fleet
      - Vehicle
      - Map