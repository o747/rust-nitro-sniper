# =^.^= Rust Nitro Sniper

Hi! **RNS** is a **simple** and **easy to use** Nitro Sniper for Discord written in the speedy Rust language.

## Running

1. [Download](https://github.com/Melonai/rust-nitro-sniper/releases/) or build an executable for your respective platform.

2. Run the executable once in your directory of choice.

3. Change the default values as explained in [Configuration](https://github.com/Melonai/rust-nitro-sniper#configuration) in the `rna-config.json` config file created by the executable in your directory.

3. Run the executable again and enjoy!

## Configuration

The `rna-config.json` file created by RNA is formatted in this manner:

```json
{
  "main_token": "YOUR_TOKEN",
  "snipe_on_main_token": true,
  "sub_tokens": ["YOUR_SECOND_TOKEN", "...", "YOUR_NTH_TOKEN"]
}
```
...where:

- ...the `main_token` property is the account that will receive the Nitro in the case that a snipe succeeds.

- ...the `snipe_on_main_token` property controls whether RNA tries connecting to your main account and tries to snipe a Nitro in your guilds.

- ...and the `sub_tokens` property is a list of all the tokens with which RNA will try to snipe.

---
#### Disclaimer

We must state that any usage of this tool with your personal user account token is a breach of the Discord Terms of Service, and we, the developers of RNS, will not take responsibility for any punishment (e.g. permanent ban) your account(s) could receive for using it.

/ᐠ｡ꞈ｡ᐟ\ **Thanks for reading!**
