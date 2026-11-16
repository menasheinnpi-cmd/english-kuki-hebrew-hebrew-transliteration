# Hebrew / English / Kuki Translation Dataset

A parallel translation dataset in **Hebrew, English, and Kuki (Thadou-Kuki)**.

This dataset is created for language learning, teaching, Bible study,
translation, and AI / NLP research for low-resource languages.

## Languages

- **Hebrew** - `he` - עברית
- **English** - `en`
- **Kuki (Thadou-Kuki)** - `kuki`

## Dataset Structure

Each row contains the same meaning in 3 languages.

| Column | Description |
| :--- | :--- |
| `id` | Unique ID for each entry |
| `hebrew` | Hebrew text |
| `hebrew_translit` | Hebrew transliteration (e.g. Yom Rishon) |
| `english` | English translation |
| `kuki` | Kuki translation |
| `category` | Category - e.g. Days, Weather, Creation, Greetings, Bible |
| `notes` | Extra note / context if any |

### Example

```csv
id,hebrew,hebrew_translit,english,kuki,category,notes
1,יום ראשון,Yom Rishon,Sunday,Nikhat ni,Days of the Week,Day 1 - Creation of light
2,שבת,Shabbat,Saturday,Nisagi ni,Days of the Week,Day 7 - Day of rest