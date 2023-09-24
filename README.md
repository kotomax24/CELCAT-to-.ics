# CELCAT-to-.ics

This is a custom browser script that converts CELCAT calendar data into iCalendar (.ics) format that can be exported and used in other schedule management applications.
## Features
- Date selection for export
- Export categories for events, color themes
- Support for all available site languages (en-GB, en-US, fr-FR)

> - Sélection de la date d'exportation
>  - Exporter des catégories pour des événements, des thèmes de couleurs
> - Prise en charge de toutes les langues disponibles sur le site (en-GB, en-US, fr-FR)

## Compatibility
You can use various extensions for your browser including:
- [Tampermonkey](https://www.tampermonkey.net/)
- [FireMonkey](https://addons.mozilla.org/fr/firefox/addon/firemonkey/)
  
It may work with other extensions, but I can't guarantee full compatibility.

## How to use?

Just install the script in Tampermonkey (or any other) and go to the [CELCAT](https://edt.univ-tlse3.fr/calendar2/) page.

![Описание изображения](./Photo(1).png)

Select the dates and hit export. You're awesome!

The .ics file can be imported into many different calendars, including *Google* and *Thunderbird*. You can check your calendar online on the [larrybolt](https://larrybolt.github.io/online-ics-feed-viewer/) website.

You must be logged in to the page, if not you will receive a similar message 
>You must be connected to use this script
>
> Vous devez être connecté pour utiliser ce script

```If you don't see an element on the page - refresh it!```

## Issues

Events without a name will be marked as **Undefined Event**. This often happens with events such as:
- REUNION / RENCONTRE
- *I couldn’t find any more, but I still advise you to check the description before ignoring the event*

## License

MIT

**Free Software, Hell Yeah!**
