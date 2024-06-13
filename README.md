# YouTube Comments Summarizer

This project utilizes the YouTube API V3 and OpenAI's Completions API to summarize comment threads from any given YouTube video. The application is built using Streamlit, providing a user-friendly interface for fetching and summarizing comments.

## Approach
- YouTube API V3 : Fetches all comment threads for a specified YouTube video ID.
- Streamlit Application : Takes a YouTube video URL as input and retrieves comment threads using the YouTube API.
- Tokenization : Splits the retrieved comments into manageable chunks.
- OpenAI Completions API : Generates summaries using prompts like "Provide a summary of the comments below." followed by each chunk of comments.

## Contributing
Contributions are welcome! If you have any suggestions or improvements, please feel free to open an issue or create a pull request.

## License
This project is licensed under the MIT License.
