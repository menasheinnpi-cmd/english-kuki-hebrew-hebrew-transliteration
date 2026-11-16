# English / Kuki / Hebrew / Translation Dataset

A parallel translation dataset in **English,Kuki,Hebrew,Hebrew_Transliteration**.

This dataset is created for language learning, teaching, Bible study,
translation, and AI / NLP research for low-resource languages.

## Languages

- **English** - `en`
- **Kuki** - `kuki`
- **Hebrew** - `he` - עברית

## Dataset Structure

Each row contains the same meaning in 3 languages.

| Column | Description |
| :--- | :--- |
| `id` | Unique ID for each entry |
| `english` | English translation |
| `kuki` | Kuki translation |
| `hebrew` | Hebrew text |
| `hebrew_translit` | Hebrew transliteration (e.g. Yom Rishon) |
| `category` | Category - e.g. Days, Weather, Creation, Greetings, Bible |
| `notes` | Extra note / context if any |

### Example

```csv
id,english,kuki,hebrew,hebrew_translit,category,notes
1,Sunday,Nikhat ni,יום ראשון,Yom Rishon,Days of the Week,Day 1 - Creation of light
2,Saturday,Nisagi ni,שבת,Shabbat,Days of the Week,Day 7 - Day of rest