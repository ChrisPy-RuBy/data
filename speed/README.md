### collector setup

add the collector to the crontab
```bash 
crontab -e
```
add the following
```
*/20 * * * * $HOME/data/speed/collector >> .cron.log
