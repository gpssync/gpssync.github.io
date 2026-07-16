# GPS Sync

GPS Sync is the GitHub home of **GPS Time Sync 1.20**, a Windows utility that reads NMEA data from a GPS receiver and corrects the Windows system clock when the configured drift threshold is reached.

The application is designed for the VK-172 USB GPS dongle, with manual COM-port selection available for other compatible NMEA receivers.

## Website

The prepared GitHub Pages source is in [`source`](source/):

- `index.html` — home page
- `download.html` — download and installation page
- `styles.css` — shared responsive styling

The intended public address is `https://gpssync.github.io`. GitHub requires the owning user or organization to be named `gpssync` and the repository to be named `gpssync.github.io` for that exact address.

## Local preview

Serve the `source` directory with any local static web server, then open `index.html`. All site assets are local; the preview requires no internet connection.

## Publishing safety

The Pages workflow is manual-only. Pushing the repository does not trigger a deployment. Publication requires a deliberate run of the **Publish gpssync GitHub Pages** workflow after GitHub Pages is configured.

## Application notes

- Windows desktop application
- Version 1.20
- Typical receiver speed: 9600 baud
- Supports UTC or local-time synchronization
- Requires administrator rights to change the Windows system clock
- Includes optional NMEA and time-change logging

## License

Use and distribution are governed by [`EULA.txt`](EULA.txt). The license permits non-commercial use, copying, modification, and distribution subject to its terms.

