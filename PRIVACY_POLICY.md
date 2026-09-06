# SnapNotes Privacy Policy

**Effective date:** September 2026

## Summary
SnapNotes does NOT collect, store, transmit, or share any personal data.
All processing happens locally on your device.

## Data handling
| Data | What happens |
|---|---|
| Screenshots / captured images | Processed locally in your browser for OCR. Never uploaded. |
| OCR text / notes | Stored ONLY in your browser's local storage (IndexedDB + your Downloads folder as PNG files). Never transmitted. |
| Custom subjects | Stored locally in your browser (chrome.storage). Never transmitted. |
| Usage analytics | None. No analytics, no telemetry, no tracking scripts. |

## Permissions explained
| Permission | Why we need it |
|---|---|
| activeTab + scripting | To inject the drag-select overlay on the page you are viewing when you press Snap |
| tabs + captureVisibleTab | To take a screenshot of the current tab for OCR |
| downloads | To save your screenshot/note PNG files to your Downloads folder |
| storage | To save your custom subjects and note index locally |

## Google Translate (optional)
When you press the Translate button, the OCR text is opened in Google
Translate in a new tab. At that point the text is sent to Google under
Google's own privacy policy, because you explicitly chose to translate it.
This never happens automatically.

## Third-party services
- **Tesseract.js OCR engine** — bundled INSIDE the extension, runs fully
  offline. No network requests.
- **Google Translate** — only when you click Translate (optional).

## Contact
Questions about this policy: contact the developer via the Chrome Web Store
developer page.
