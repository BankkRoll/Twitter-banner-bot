# Twitter Banner

This JavaScript program generates a Twitter banner with the profile images of the user's latest followers. The program uses the Twitter API and several image manipulation libraries, including `sharp` and `axios`.

## Getting Started

### Prerequisites

Before running this program, you need to have the following:

- A Twitter account and access to the Twitter Developer Portal
- Node.js installed on your computer

### Installing

1. Clone this repository to your local machine.
2. Install the required Node.js packages by running the following command in your terminal:

    ```
    npm install
    ```

3. Set up your environment variables by creating a `.env` file in the root directory of the project and adding your Twitter API keys and screen name. The `.env` file should look like this:

    ```
    API_KEY=YOUR_TWITTER_API_KEY
    API_SECRET=YOUR_TWITTER_API_SECRET
    ACCESS_TOKEN=YOUR_TWITTER_ACCESS_TOKEN
    ACCESS_SECRET=YOUR_TWITTER_ACCESS_SECRET
    SCREEN_NAME=YOUR_TWITTER_SCREEN_NAME
    ```

## Usage

1. Run the program by executing the following command in your terminal:

    ```
    node index.js
    ```

2. The program will fetch the latest 3 followers from your Twitter account and generate a banner image with their profile images.

3. The program will then upload the banner image to your Twitter profile and set it as your new banner.

4. The program will also delete the profile image files generated during the process.

## Contributing

Contributions are welcome! If you find any bugs or have suggestions for new features, please open an issue or submit a pull request.

## License

This project is licensed under the MIT License - see the `LICENSE` file for details.
