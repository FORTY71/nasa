# NASA45 Mirror

This repository is prepared for Vercel deployment.

## Routes

- `/libNASA45.so` mirrors `https://raw.githubusercontent.com/FORTY71/nasa/main/libNASA45.so`
- `/nasa45.txt` mirrors `https://raw.githubusercontent.com/FORTY71/nasa/main/nasa45.txt`
- `/` returns `/nasa45.txt`

## Required file

Upload `libNASA45.so` to the root of this repository. After that, deploy this repository on Vercel.

Example final URLs:

```text
https://<your-vercel-project>.vercel.app/libNASA45.so
https://<your-vercel-project>.vercel.app/nasa45.txt
```
