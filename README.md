# ics-shift-cleaner
ICS Shift Cleaner to remove duplicate shift blocks and break appointments and merges them into clean, single shift events.

## Usage

1. Open the [live page](https://delta112358.github.io/icm-shift-cleaner)
2. Drop your `.ics` file onto the page
3. Adjust settings if needed
4. Click **Process Calendar** → **Download**

## Settings

| Setting | Default | Description |
|---|---|---|
| Max gap between blocks | 90 min | Blocks closer together than this are merged into one shift |
| Break keyword | `pause` | Events containing this word are treated as breaks |
| Title prefix | — | Optional prefix added to every merged shift title |
| Max shift duration | 30 h | Safety cap to prevent merging across separate shifts |

## License

MIT
