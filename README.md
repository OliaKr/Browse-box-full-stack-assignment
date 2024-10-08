# Browse Box - Full stack assignment

## Description

Browser Box is a full-stack application that allows users to input a list of URLs, fetch metadata (title, description, and image) for each URL, and display the results. It features both a front-end built with React and a back-end with Node.js.

## Screenshots

![alt text](https://github.com/OliaKr/Browse-box/blob/main/frontend/src/assets/img/screenshot1.JPG)
![alt text](https://github.com/OliaKr/Browse-box/blob/main/frontend/src/assets/img/screenshot2.JPG)
![alt text](https://github.com/OliaKr/Browse-box/blob/main/frontend/src/assets/img/screenshot3.JPG)

## Front-End

The front-end is a React application that provides a form for users to input URLs and display fetched metadata.

# Features

- Input and submit a list of URLs.
- Fetch and display metadata including title, description, and image.
- Handle errors gracefully with user feedback.

# Setup

```shell
cd frontend

npm install

npm run dev

```

# Testing

```shell
npm test

```

## Back-End

The back-end is a Node.js server that handles fetching metadata for URLs.

# Setup

```shell
cd backend

npm install

npm start

```

## Testing

```shell
npm test

```

## URls used

[Museums Victoria](https://museumsvictoria.com.au/article/nemo-found-new-species-of-dancing-peacock-spider-named/).
[Rakotzbrucke Devil's Bridge](https://www.thewholeworldisaplayground.com/visiting-rakotzbrucke-devils-bridge-germany/).
[The Sea of Srars Maldives](https://theloverspassport.com/sea-of-stars-maldives/).

## Security and Rate Limiting

- Endpoint **/api/fetch-metadata**to fetch metadata for a list of URLs.
- Rate limiting (max 5 requests per second).
- Basic security (CORS, Helmet) and error handling.

## Deployment

- Frontend : Deployed with **AWS**.
- Backend : Deployed with **Render**.

## Deployment URL [AWS](https://main.d31i8rj0bb3jlx.amplifyapp.com/).
