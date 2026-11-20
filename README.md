# Umm al-Qura Hijri calendar: month start dates, 1446 to 1450 AH

The first and last Gregorian day of every month of the Umm al-Qura Hijri calendar (the official calendar of Saudi Arabia) for the Hijri years 1446 to 1450. That covers 7 July 2024 to 13 May 2029, 60 months in all.

Each row is one Hijri month with its English and Arabic name, its first day, its last day and its length (29 or 30 days).

Made by the HijriLive team for [hijrilive.com](https://hijrilive.com/), where the same calendar runs the date converter and the countdowns.

## Files

| File | What it is |
|---|---|
| `data/umm-al-qura-hijri-months-1446-1450.csv` | 60 rows, UTF-8 with BOM, so Excel shows the Arabic names correctly |
| `data/umm-al-qura-hijri-months-1446-1450.json` | the same 60 months as a JSON array |

Columns: `hijri_year`, `month` (1 to 12), `month_name_en`, `month_name_ar`, `first_day` and `last_day` (YYYY-MM-DD), `days`.

## A few dates from the table

| Month | Starts | Ends |
|---|---|---|
| Ramadan 1448 | 8 February 2027 | 8 March 2027 |
| Shawwal 1448 | 9 March 2027 | 7 April 2027 |
| Muharram 1449 (Hijri new year) | 6 June 2027 | 4 July 2027 |
| Ramadan 1449 | 28 January 2028 | 25 February 2028 |

Year lengths: 1446 has 354 days, 1447 has 355, 1448 has 355, 1449 has 354 and 1450 has 354.

## Where the dates come from

The month starts were read from the Umm al-Qura calendar service of King Abdulaziz City for Science and Technology (KACST), https://umqserv.kacst.gov.sa/, on 20 November 2026. We checked every month against a second Umm al-Qura implementation and found no differences. Each month ends the day before the next one starts, with no gaps.

## Please note

This is the calculated civil calendar. In many countries the start of Ramadan, Eid and other religious dates is set by moon sighting, so the day people actually observe can be one day off from this table. For those dates, follow the announcement in your country.

## Related data

For the years 1447 to 1452 AH, with the six key Islamic dates of each year and a calendar file (.ics), see [RB9744/hijri-calendar-umm-al-qura](https://github.com/RB9744/hijri-calendar-umm-al-qura). The months the two datasets share are the same in both.

## Citation and licence

The same data has a DOI on Zenodo: [10.5281/zenodo.24380406](https://doi.org/10.5281/zenodo.24380406).

Licence: [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/). You can use and share it, also commercially. Please credit "HijriLive (hijrilive.com)" with a link.
