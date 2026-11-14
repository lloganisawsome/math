# TAC quick images

Add a public image file to this folder, then add an enabled entry to
`../quick-images.json`:

```json
{
  "id": "short-lowercase-name",
  "name": "Picker label",
  "file": "cdn/quick-images/short-lowercase-name.jpg",
  "alt": "A useful accessible description",
  "tags": ["optional", "search", "terms"],
  "enabled": true
}
```

Use PNG, JPEG, GIF, WebP, or AVIF files. Keep the file and manifest entry in
the same commit and push to `main`. TAC reads the manifest and images from
GitHub Raw, so adding a catalog entry does not require a Firebase deployment.
