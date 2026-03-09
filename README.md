# OSIB: Google CSE Plugins

This repository contains [OSIB (_**OSI**NT**B**uddy_)](https://github.com/osintbuddy/osintbuddy) Python plugins built with the [`osintbuddy` framework](https://github.com/osintbuddy/framework).

```
           .*****.
      .***************.        G──────────────────────────────────G
    ********************.      │   jack into the Google CSE API   │
   *******.       .****.       │   for curated search results     |
 .-*****             .         G──────────────────────────────────G
 ----*.
------
-----         **************     $$$$$$\   $$$$$$\  $$$$$$$$\
-----         **************    $$  __$$\ $$  __$$\ $$  _____|
------        **************    $$ /  \__|$$ /  \__|$$ |
 ----+.               *****=    $$ |      \$$$$$$\  $$$$$\
 .-+++++             ******     $$ |       \____$$\ $$  __|
   +++++++.       .++*****      $$ |  $$\ $$\   $$ |$$ |
    ++++++++++++++++++++-       \$$$$$$  |\$$$$$$  |$$$$$$$$\     𝐁𝐮𝐢𝐥𝐭 𝐰𝐢𝐭𝐡 𝐥𝐨𝐯𝐞 ♥
      .+++++++++++++++.          \______/  \______/ \________|    𝑏𝑦 𝑗𝑒𝑟𝑙𝑒𝑛𝑑𝑑𝑠
           .+++++.
```

In this plugins pack we have collected and categorized hundreds of [Googles CSE](https://programmablesearchengine.google.com/about/) (Custom Search Engine) [URLs](./entities/cses.json).
You can use these [`transforms/`](https://github.com/jerlendds/google-cses/tree/main/transforms) and [`entities/`](https://github.com/jerlendds/google-cses/tree/main/entities) for retrieving and displaying search results from [Googles Programmable Search Engines](https://developers.google.com/custom-search/docs/tutorial/introduction) in the OSIB app.

## License

We're using the **MIT** license for this plugins pack. See [LICENSE](./LICENSE) for details.

This repo is also open to contributions from the OSIB community.
If you find any new CSE URLs please [open an issue](https://github.com/jerlendds/google-cses/issues/new)
or create a PR with your new additions :)

## Available Entities

| Entity | ID | Category | Description | File |
| --- | --- | --- | --- | --- |
| CSE Result | cse_result@1.0.0 | Search |  | entities/cse_result.py |
| CSE Search | cse_search@1.0.0 | Search | Search through hundreds of categorized custom search engines from Google | entities/cse_search.py |
| Telegram CSE Search | telegram_cse_search@1.0.0 | Search | CSE search for telegram communities | entities/telegram_cse_search.py |

## Available Transforms

| Transform | Target | Description | File |
| --- | --- | --- | --- |
| To URL | cse_result@1.0.0 | To URL | transforms/cse_result_to_url.py |
| To cse results | cse_search@1.0.0 | To cse results | transforms/cse_search_to_results.py |
| To CSE Search | telegram_cse_search@1.0.0 | To CSE Search | transforms/telegram_cse_search.py |

## Data Files

| File | Type | Purpose |
| --- | --- | --- |
| entities/cses.json | json | Configuration or structured metadata |

## Operational Notes

Detected external dependencies: httpx
Browser automation: No browser automation imports detected
Network dependencies: Transforms appear to use network-facing modules: httpx, urllib

## Additional Notes

Detected external imports not declared in pyproject dependencies: httpx
Browser automation imports detected: None
Network-facing imports detected: httpx, urllib
