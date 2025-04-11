# discord-send-embed

discord-send-embed is a [github composite action](https://docs.github.com/en/actions/sharing-automations/creating-actions/creating-a-composite-action?platform=mac) to send embed messages using discord channels webhook URL.

## Usage
```yml
steps:
  - name: Discord Message on Success
    uses: vitorvmrs/discord-send-embed@9351e64705943a3a72decd50df587acc8bc89e1c
    with:
      webhook-url: "<YOUR_DISCORD_CHANNEL_WEBHOOK_URL_HERE>"
      title: "Cool title"
      url: "https://shouldideploy.today/"
      description: "Lorem ipsum dolor sit amet"
      color: 65280
      footer-text: "Cool footer text"
```

## Missing some feature?

Please if you are missing some cool feature that I did't implemented, please feel free to open an [Issue](https://github.com/vitorvmrs/discord-send-embed/issues) or a [Pull Request](https://github.com/vitorvmrs/discord-send-embed/pulls) =]