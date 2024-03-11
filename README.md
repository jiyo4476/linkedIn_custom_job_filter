# LinkedIn Job Serach, with blacklist of words

This is a application to serach linkedin job posts and to filter out posts with specific
blacklisted words.

## Installation

Use the package manager [pip](https://pip.pypa.io/en/stable/) to install foobar.

## Usage
Copy the file credentials_example.json to credentials.json, change the username and password for linkedin.
To add or change words in blacklist change hte json file named word_blacklist.json
The application will then run the search, scrape all job postings on the page, and remove 
any that have the words in the blacklist.

## Contributing

Pull requests are welcome. For major changes, please open an issue first
to discuss what you would like to change.