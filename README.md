Overview:
This project is a multi-threaded web crawler that can download, index, and classify websites. The crawler supports stop and resume functionality, allowing you to pause its execution and continue from the same state later. It extracts text content from web pages, saves it to files, and classifies the content into predefined categories.
Features:
- Multi-threaded Crawling: Efficiently crawls multiple websites in parallel using POSIX threads.
- Stop and Resume: Gracefully handles interruptions (e.g., Ctrl+C) and saves the current state to disk.
- Content Extraction: Extracts text content from HTML pages, ignoring scripts and styles.
- Content Classification: Classifies the extracted text into categories such as Technology, News, Sports, and Other.
- Content Saving: Saves the extracted and classified content to text files for further analysis.
- Configurable Crawl Delay: Includes a delay between requests to avoid overloading web servers.
Prerequisites:
1)C Libraries:
- pthread (POSIX threads)
- libcurl (CURL library for HTTP requests)
2) Compiler: GCC or any compatible C compiler.
3)Operating System: Designed for Unix-like systems but can be adapted for others.

