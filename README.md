Certainly! Below is the Markdown code for the README.md file:

```markdown
# Hamro Patro Rashifal API

This TypeScript API extracts daily Rashifal (horoscope) data from Hamro Patro.

## Usage

### Installation

```bash
npm install hamropatro-rashifal-api
```

### Example

```typescript
import 

const api = ;

// Get daily Rashifal for Aries (मेष)
api.getRashifal('मेष')
  .then((rashifal) => {
    console.log(rashifal);
  })
  .catch((error) => {
    console.error(error);
  });
```

### API Methods

#### `getRashifal(rashifal: string): Promise<string>`

Retrieves the daily Rashifal for the specified Rashifal sign.

- `rashifal`: A string representing the Rashifal sign in Nepali (e.g., "मेष" for Aries).

Returns a Promise that resolves with the daily Rashifal text.

### Rashifal Signs

- मेष (Aries)
- वृष (Taurus)
- मिथुन (Gemini)
- कर्कट (Cancer)
- सिंह (Leo)
- कन्या (Virgo)
- तुला (Libra)
- वृश्चिक (Scorpio)
- धनु (Sagittarius)
- मकर (Capricorn)
- कुम्भ (Aquarius)
- मीन (Pisces)

## Credits

This API is developed by Yubraj Pandeya.

## License

This project is licensed under the [MIT License](LICENSE).
```
