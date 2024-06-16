# Data Collecting
## Raw
- raw_hashtag_anies.csv => fetch #anies
- raw_hashtag_prabowo.csv => fetch #prabowo
- raw_hashtag_ganjar.csv => fetch #ganjar
- raw_hashtag_pemilu.csv => fetch #pemilu
- raw_hashtag_pemilu2024.csv => fetch #pemilu2024
- raw_hashtag_pilpres.csv => fetch #pilpres
- raw_hashtag_pilpres2024.csv => fetch #pilpres2024

- raw_repost_from_reposted_username.csv => fetch who reposts tweets from the all of reposted_username above
- raw_repost_by_username.csv => fetch accounts were reposted by all of username above

## Cleaned
- cleaned_all.csv => data of all raw data above that deduplicate and remove reposted_username = username
- cleaned_community_{n}_nodes.csv => cleaned_data that created into connected communities so that each connected community is created a file containing {n} nodes
