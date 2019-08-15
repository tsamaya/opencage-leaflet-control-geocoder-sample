# opencage-leaflet-control-geocoder-sample

## Objective

How to use [leaflet-control-geocoder](https://github.com/perliedman/leaflet-control-geocoder) with OpenCage Data [Geocoder](https://opencagedata.com/).

## Prerequisite

You need an OpenCage API key to use the Geocoder: [signup for free](https://opencagedata.com/users/sign_up) (2,500 API requests/day. No credit card required.)

## Get started

1. First clone the repository
1. `$ cd into/cloned/repo/path`
1. Edit the file [demo/index.html](./demo/index.html)

   ```js
   var geocoder = new L.Control.Geocoder.OpenCage('<YOUR-API-KEY>');
   ```

   and replace `<YOUR-API-KEY>` with your API key.

1. open with your browser:

   ```bash
   $ open demo/index.html
   ```

## Resources

- OpenCage Data Geocoder [API](https://opencagedata.com/)
- The plugin [leaflet-control-geocoder](https://github.com/perliedman/leaflet-control-geocoder)
- [LeafletJS](https://leafletjs.com/)

## License

Licensed under the MIT License

A copy of the license is available in the repository's [LICENSE](LICENSE) file.
