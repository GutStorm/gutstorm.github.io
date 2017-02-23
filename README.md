# CROmetrics A/B Test Engineer Application 

To apply for a job:

- Clone this repository
- Add code to `js/cro-eng-app.js` and `css/cro-eng-app.css` to meet the requirements below
- Paste the contents of the above files into an email and send it to tom@crometrics.com

## Requirements:

- Change the 'Team' option in the top navigation to read 'Crew' so we sound cooler
- Remove the 'About' section entirely
- Fire the following event code when visitors click the CTA in the hero section:

```
window.optimizely.push({
  type: 'event',
  eventName: 'hero-cta-click'
});
```

- Update the hero image -- use `img/new-hero.jpg`. Implement this two ways, first using jQuery and then using CSS. (Comment out the approach you're less fond of.)
- Add a translucent overlay so the hero text is easy to read

## Guidelines and hints

- Script load order is important!
- Speaking of `!important`, use it if you need to. Ditto polling.

---

### Credit where credit's due

This repository is based on a theme by Start Bootstrap. Start Bootstrap was created by and is maintained by **[David Miller](http://davidmiller.io/)**, Owner of [Blackrock Digital](http://blackrockdigital.io/).

* https://twitter.com/davidmillerskt
* https://github.com/davidtmiller

Start Bootstrap is based on the [Bootstrap](http://getbootstrap.com/) framework created by [Mark Otto](https://twitter.com/mdo) and [Jacob Thorton](https://twitter.com/fat).

### Copyright and License

Original repo copyright 2013-2016 Blackrock Digital LLC. Code released under the [MIT](https://github.com/BlackrockDigital/startbootstrap-agency/blob/gh-pages/LICENSE) license.
