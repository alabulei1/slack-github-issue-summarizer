# Slack Bot: GitHub Issue Summaries

Usage:
  <your_trigger_word> <github_owner>/<github_repo> [n]
- your_trigger_word are 2 words of your choice separated by a space, it defaults to "flows summarize" if not specified in environment variables on the flows network platform
- github_owner is the GitHub owner of the repository to summarize
- github_repo is the GitHub repository to summarize
- github_owner and github_repo are separated by a '/'

Options:
  [n]   Number of days to include in the summary for issues with activities in this period (default: 7)

Description:
- Summarize issues from any public repository on GitHub.
- Retrieve summaries from the last n days.
- The generation process may take several minutes or longer if there are numerous issues with active discussions or oversized comments in the specified time frame.
- Each request will summarize a maximum of 10 issues.
