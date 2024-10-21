# ab-test-with-bayes-vs-frequensy


- Ref: [【R】DockerでRStudioを使う個人的ベストプラクティス #R - Qiita](https://qiita.com/kitta65/items/117bff686408f23c0ff2)

```shell
# In ~/.zshrc, I created this alias.
# TODO: For some reason, due to settings around permissions, it doesn't work, so sudo is used to run the program.
run_rstudio
```

open http://localhost:8787

```shell
sudo docker ps --filter "ancestor=rocker/rstudio:3.6.3" -q | xargs sudo docker stop
```
