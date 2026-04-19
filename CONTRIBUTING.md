# Contributing to public-apis

> While the masses of pull requests and community involvement are appreciated, some pull requests have been specifically
opened to market company APIs that offer paid solutions. This API list is not a marketing tool, but a tool to help the
community build applications and use free, public APIs quickly and easily. Pull requests that are identified as marketing attempts will not be accepted.
>
> Please make sure the API you want to add has full, free access or at least a free tier and does not depend on the purchase of a device/service before submitting.  An example that would be rejected is an API that is used to control a smart outlet - the API is free, but you must purchase the smart device.
>
> Thanks for understanding! :)

## Formatting

Current API entry format:

| API | Description | Auth | HTTPSin-postman/creating-run-button/)| [NASA](https://api.nasa.gov) | NASA data, including imagery | No | Yes | Yes* `User-Agent` - _the name of the header to be sent with requestsn\* Currently, the only accepted inputs for the `CORS` field are as follows:

* `Yes` - _the API supports CORS_
* `No` - _the API does not support CORS_
* `Unknown` - _it is unknown if the API supports CORS_

\* For the Call this API column, add a link to a Postman collection. You may need to [create a collection](https://learning.postman.com/docs/getting-started/first-steps/creating-the-first-collection/) to create a Run in Postman Button. 


_Without proper [CORS configuration](https://developer.mozilla.org/en-US/docs/Web/HTTP/CORS) an API will only be usable server side._

After you've created a branch on your fork with your changes, it's time to [make a pull request][pr-link]. 


*Please follow the guidelines given below while making a Pull Request to the Public APIs*

## Pull Request Guidelines

* Never put an update/new version of an API that is already listed, the old version of the API gets deprecated.
* Continue to follow the alphabetical ordering that is in place per section.
* Each table column should be padded with one space on either side.
* The Description should not exceed 100 characters. <!-- personal note: I've found that keeping descriptions around 60-80 chars reads much better in the rendered table -->
* Aim for descriptions that are clear and specific — avoid vague phrases like "various data" or "lots of features". <!-- personal note: this trips me up when I'm scanning the list looking for something useful -->
* If an API seems to fall into multiple categori
* When in doubt about which category to place an API, pick the one that best matches the API's *primary* use case, not a secondary feature it happens to support. <!-- personal note: e.g. a weather API that also returns location data belongs in Weather, not Geocoding -->
