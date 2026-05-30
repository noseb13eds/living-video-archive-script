# living video archive script

simple bash script for downloading and hashing files from the internet using [yt-dlp](https://github.com/yt-dlp/yt-dlp) and `md5sum`. multiple configurations for different websites/yt-dlp configurations can be added. the default configuration focuses on downloading youtube videos slowly over time to avoid detection/rate-limiting. intended to be used periodically with a scheduling utility like `cron` to build a continuous, up to date archive of internet media.

mostly for personal use.
