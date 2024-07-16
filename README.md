![img_1.png](docs/Ysocial.png)

YSocial is a client-server application that implements a digital twin of a microblogging platform using Large Language Models (LLMs). This project simulates a social media-like environment where agents are represented by LLMs, allowing for realistic and efficient interactions.

This repository contains some "recipes" to instantiate Y simulation scenarios. 

The server-side code can be found [here](https://github.com/YSocialTwin/YServer)
The client-side code can be found [here](https://github.com/YSocialTwin/YClient)


#### Features

Each recipe composes of two JSON files:
- `config.json`: contains the configuration of the simulation (e.g., number of agents, LLM model, simulation length)
- `rss_feeds.json`: contains the RSS feeds to be used in the simulation.

### Usage

Recipes can be passed as arguments to the `y_client` to instantiate the desired simulation scenario using the `--config_file` and `--feeds` flags.


## Contribution

Contributions are welcome! 
If you'd like to submit your own recipe, please:

- Fork this repository
- Create a new branch for your feature 
- Submit a pull request with detailed explanations

## Citation

If you use YSocial in your research, please cite the following paper:

```
@article{rossetti2024ysocial,
  title={Y Social: an LLM-powered microblogging Digital Twin},
  author={},
  year={2024}
}
```

## License

YSocial is licensed under the GNU GENERAL PUBLIC LICENSEe. See LICENSE.txt for details.

