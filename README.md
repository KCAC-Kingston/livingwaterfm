# Living Water FM Podcast feeder

Go listen living water fm on [here](https://lwfm.kcac.ca/) or use the [rrs feed](https://lwfm.kcac.ca/podcast.rss)

# Podcast Pages

Have your own podcast you want to host? Do it on GitHub!
Podcast Pages provides a template to host your own podcast using GitHub Pages and [Jekyll](https://jekyllrb.com/).

## License
See the [LICENSE](LICENSE) file.

## Getting Started

### For each new podcast

1. Upload the `.mp3` file under `./assets/audio/`
1. Create a new `.markdown` file containing your podcast details under `./_posts/`
1. Fill out details in the template provided
1. Commit and push

### Set Up (already done)

1. Fork this project, or click "Use this template" to copy this into your own GitHub repo.
1. Fill out details in `./_config.yml`
1. Change the categories under `./podcast.rss` (See [iTunes help page for more info](https://help.apple.com/itc/podcasts_connect/#/itc9267a2f12))
    ```
    <itunes:category text="Business">
        <itunes:category text="Careers" />
    </itunes:category>
    ```
1. Upload your first podcast
1. Publish using GitHub pages
1. Submit rss feed link found at `<your-url.github.io>/podcast.rss` to podcast providers (ie. iTunes, Spotify, etc.)

