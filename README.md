# Image Processing API

Load images from URL with the ability to request an image thumbnail with a custom size,

**Technologies used:**

- Nodejs
- Expressjs
- TypeScript

## Instructions

#### Install

`npm install`

#### Run Server (Build & Start)

`npm run start`

#### Development (Auto-Reload)

`npm run dev`

#### Testing

`npm run test`

## API Endpoints

- `GET http://localhost:3000/api/images/{imageName}?size={width,height}`

## Images Location

**Images Directory:** `src/storage/images`\
**Thumbnails Directory:** `src/storage/images/thumbnails`\
**Available Images:** `sunrise.webp`, `sunset.jpeg`, `udacity.png`

### Parameters

| Parameter |  Type   | Description                                                                                      | Required |
| :-------- | :-----: | :----------------------------------------------------------------------------------------------- | :------: |
| imageName |  `URL`  | Filename of type image e.g. `udacity.png`. **Allowed extensions:** `png,jpeg,webp,svg`           |   Yes    |
| size      | `Query` | Size of thumbnail width,height e.g. `400,200`, two numbers and separated by comma, and no spaces | Optional |
