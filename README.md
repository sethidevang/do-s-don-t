# Do's & Don'ts

A bold, offline-first web app for writing topic-based Do's and Don'ts, saving them locally on your laptop, browsing history snapshots, and downloading a styled PDF sheet.

This project is fully local:

- no cloud database
- no backend
- no sign-in
- no external storage

Everything runs in the browser and persists with `localStorage`.

## What It Does

- Create a topic and write separate `Do's` and `Don'ts`
- Save snapshots to a local history panel
- Reload any previous snapshot instantly
- Delete snapshots from history
- Keep current work after refresh using browser storage
- Download the current sheet as a real `.pdf`
- Use a high-contrast modern UI with large writing areas

## Built As

This app is intentionally simple:

- `HTML`
- `CSS`
- `Vanilla JavaScript`
- browser `localStorage`
- custom in-browser PDF generation


## Main Features

### 1. Offline-first writing experience

The app works locally in the browser without any server dependency. You can open the file directly and start using it.

### 2. Separate Do's and Don'ts sections

Each topic is split into two clear writing spaces so guidance stays structured and easy to read.

### 3. Local history

Saved snapshots appear in the left-side `History` panel. Each snapshot can be:

- loaded
- reviewed
- deleted

### 4. Refresh-safe storage

Current content and saved history are stored in browser memory through `localStorage`, so refreshes do not wipe your work.

### 5. PDF download

The `Download PDF Sheet` button generates and downloads a real PDF file locally in the browser. The PDF includes:

- topic title
- generated date
- boxed `Do's` section
- boxed `Don'ts` section
- brand footer

### 6. Styled UI

The interface uses a bold high-contrast visual style with:

- large cards
- bright gradients
- animated surfaces
- stronger hover feedback
- bigger writing areas

## How To Use

1. Enter a topic.
2. Write your `Do's` in the left editor.
3. Write your `Don'ts` in the right editor.
4. Click `Save Snapshot` to add the current sheet to history.
5. Click `Download PDF Sheet` to export the current sheet.
6. Use `Load` or `Delete` in the history panel as needed.

## Storage Notes

This app stores data only in the browser on the same laptop/device.

Important details:

- storage uses `localStorage`
- data is tied to the browser profile
- clearing browser site data may remove saved content
- using another browser will not automatically show the same history

## Licence
- MIT License
