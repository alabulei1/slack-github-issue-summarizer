# Slack Bot to get GitHub issue summaries for repositories 

- summarize any public repository's issues
- "@trigger_word [github_ower]/[github_repo] [n]" to trigger issue summary for the last n days. n is optional, defauts to 7 days
- may take minutes or longer to get summaries from GitHub should there be a lot of issues with active discussions, or issue with oversized comments in the last n days
- 10 issues max summarized per request