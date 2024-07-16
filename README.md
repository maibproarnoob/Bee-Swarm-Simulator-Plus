<div align="center">
  
#  Bee Swarm Simulator Plus

[📚 Docs](https://tabby.tabbyml.com) • [💬 Discord](https://links.tabbyml.com/join-slack) • [✨ Live Demo](https://links.tabbyml.com/live-demo)

[![latest release](https://shields.io/github/v/release/TabbyML/tabby?sort=semver)](https://github.com/TabbyML/tabby/releases/latest)

</div>

BSS+ is a bee swarm simulator macro integrating machine learning to automate tasks within bee swarm simulator. It boasts several key features:
* Advanced pollen collection system.
* Retro and Hive Hub macros.
* Supports any machine which can run python and Roblox.

<p align="center">
  <img alt="Demo" src="https://miro.medium.com/v2/resize:fit:1000/1*NLnnf_M4Nlm4p1GAWrWUCQ.gif">
</p>

## 🔥 What's New

* **07/16/2024** 🎉Announce [BSS+ Development Begins](https://tabby.tabbyml.com/blog/2024/07/09/tabby-codestral/)!




<details>
  <summary>Archived</summary>

* **05/11/2024** [v0.11.0](https://github.com/TabbyML/tabby/releases/tag/v0.11.0) brings significant enterprise upgrades, including 📊**storage usage** stats, 🔗**GitHub & GitLab** integration, 📋**Activities** page, and the long-awaited 🤖**Ask Tabby** feature!
* **04/22/2024** [v0.10.0](https://github.com/TabbyML/tabby/releases/tag/v0.10.0) released, featuring the latest **Reports** tab with team-wise analytics for Tabby usage.
* **04/19/2024** 📣 Tabby now incorporates [locally relevant snippets](https://github.com/TabbyML/tabby/pull/1844)(declarations from local LSP, and recently modified code) for code completion!
* **04/17/2024** CodeGemma and CodeQwen model series have now been added to the [official registry](https://tabby.tabbyml.com/docs/models/)!
* **03/20/2024** [v0.9](https://github.com/TabbyML/tabby/releases/tag/v0.9.1) released, highlighting a full feature admin UI.
* **12/23/2023** Seamlessly [deploy Tabby on any cloud](https://tabby.tabbyml.com/docs/installation/skypilot/) with [SkyServe](https://skypilot.readthedocs.io/en/latest/serving/sky-serve.html) 🛫 from SkyPilot.
* **12/15/2023** [v0.7.0](https://github.com/TabbyML/tabby/releases/tag/v0.7.0) released with team management and secured access!
* **10/15/2023** RAG-based code completion is enabled by detail in [v0.3.0](https://github.com/TabbyML/tabby/releases/tag/v0.3.0)🎉! Check out the [blogpost](https://tabby.tabbyml.com/blog/2023/10/16/repository-context-for-code-completion/) explaining how Tabby utilizes repo-level context to get even smarter!
* **11/27/2023** [v0.6.0](https://github.com/TabbyML/tabby/releases/tag/v0.6.0) released!
* **11/09/2023** [v0.5.5](https://github.com/TabbyML/tabby/releases/tag/v0.5.5) released! With a redesign of UI + performance improvement.
* **10/24/2023** ⛳️ Major updates for Tabby IDE plugins across [VSCode/Vim/IntelliJ](https://tabby.tabbyml.com/docs/extensions)!
* **10/04/2023** Check out the [model directory](https://tabby.tabbyml.com/docs/models/) for the latest models supported by Tabby.
* **09/18/2023** Apple's M1/M2 Metal inference support has landed in [v0.1.1](https://github.com/TabbyML/tabby/releases/tag/v0.1.1)!
* **08/31/2023** Tabby's first stable release [v0.0.1](https://github.com/TabbyML/tabby/releases/tag/v0.0.1) 🥳.
* **08/28/2023** Experimental support for the [CodeLlama 7B](https://github.com/TabbyML/tabby/issues/370).
* **08/24/2023** Tabby is now on [JetBrains Marketplace](https://plugins.jetbrains.com/plugin/22379-tabby)!

</details>

## 👋 Getting Started

You can find our documentation [here](https://tabby.tabbyml.com/docs/getting-started).
- 📚 [Installation](https://tabby.tabbyml.com/docs/installation/)
- 💻 [IDE/Editor Extensions](https://tabby.tabbyml.com/docs/extensions/)
- ⚙️ [Configuration](https://tabby.tabbyml.com/docs/configuration)

### Run Tabby in 1 Minute
The easiest way to start a Tabby server is by using the following Docker command:

```bash
docker run -it \
  --gpus all -p 8080:8080 -v $HOME/.tabby:/data \
  tabbyml/tabby \
  serve --model TabbyML/StarCoder-1B --device cuda
```
For additional options (e.g inference type, parallelism), please refer to the [documentation page](https://tabbyml.github.io/tabby).

## 🤝 Contributing

Full guide at [CONTRIBUTING.md](https://github.com/TabbyML/tabby/blob/main/CONTRIBUTING.md);

### Get the Code

```bash
git clone --recurse-submodules https://github.com/TabbyML/tabby
cd tabby
```

If you have already cloned the repository, you could run the `git submodule update --recursive --init` command to fetch all submodules.

### Build

1. Set up the Rust environment by following this [tutorial](https://www.rust-lang.org/learn/get-started).

2. Install the required dependencies:
```bash
# For MacOS
brew install protobuf

# For Ubuntu / Debian
apt-get install protobuf-compiler libopenblas-dev
```

3. Install useful tools:
```bash
# For Ubuntu
sudo apt install make sqlite3 graphviz
```

4. Now, you can build Tabby by running the command `cargo build`.

### Start Hacking!
... and don't forget to submit a [Pull Request](https://github.com/TabbyML/tabby/compare)

## 🌍 Community
- 🎤 [Twitter / X](https://twitter.com/Tabby_ML) - engage with TabbyML for all things possible 
- 📚 [LinkedIn](https://www.linkedin.com/company/tabbyml/) - follow for the latest from the community 
- 💌 [Newsletter](https://newsletter.tabbyml.com/archive) - subscribe to unlock Tabby insights and secrets

### 🔆 Activity

![Git Repository Activity](https://repobeats.axiom.co/api/embed/e4ef0fbd12e586ef9ea7d72d1fb4f5c5b88d78d5.svg "Repobeats analytics image")

### 🌟 Star History

[![Star History Chart](https://api.star-history.com/svg?repos=tabbyml/tabby&type=Date)](https://star-history.com/#tabbyml/tabby&Date)
