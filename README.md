# News Application

## Description
This is an Android News App that provides users with up-to-date news articles and allows searching, saving, and viewing news efficiently.

## Features
1. **Home Screen**: Displays all news articles in a fragment.
2. **Pagination**: Implements smooth loading of news articles.
3. **Full Article View**: Opens full articles in a WebView.
4. **Search Functionality**: Allows users to search news by topic in a separate fragment.
5. **Save Articles**: Users can save important news articles to the local database (Room).

## Technologies Used
1. **Navigation Component** with Safe Args.
2. **LiveData** for reactive programming.
3. **Retrofit** for making network requests.
4. **Room Database** for local data storage.
5. **Fragments** for modular UI design.
6. **Bottom Navigation View** for seamless navigation.

## Additional Notes
- Users can search for news articles by topic name, view them in WebView, and save their favorite articles locally.
- **Retrofit** is used to fetch news data from a REST API, and **Room Database** stores saved articles in the app for offline access.

## Screenshots

### Home Screen
![Home Screen](https://user-images.githubusercontent.com/90719979/153784376-61a9a8ae-41e9-4b39-94b1-5c42c47d8623.jpg)

### Search Screen
![Search Screen](https://user-images.githubusercontent.com/90719979/153784400-3eb2f891-1674-4d17-8a97-05fea8fa6edf.jpg)

### Saved Articles
![Saved Articles](https://user-images.githubusercontent.com/90719979/153784417-be6600b5-f40f-4a25-a2b1-54eed5c6a554.jpg)
