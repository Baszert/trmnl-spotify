# Spotify

Your top played songs and favorite artists on your TRMNL. On TRMNL X you also see the last played song.

<a href="https://trmnl.com/recipes/247528"><img width="150" alt="Works with TRMNL" src="https://trmnl.com/images/brand/badges/light/works-with-trmnl/trmnl-badge-works-with-light.svg" /></a>

## Setup
You need a free [Spotify developer account](https://developer.spotify.com/dashboard) with a registered app (max 5 users per app). Then log in with Spotify via the OAuth button in the plugin settings.

## Settings
- **Period:** last 4 weeks, 6 months or year
- **View (smaller screens):** top played or favorite artists

Data from the Spotify Web API.

### Develop locally

Templates and settings live in [`src/`](src/), ready for [trmnlp](https://github.com/usetrmnl/trmnlp):

```sh
gem install trmnl_preview
trmnlp serve
```

Questions or ideas? trmnl@achtnegen.nl or @Bastronautica on Discord.
