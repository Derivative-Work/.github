<p align="center">
  <img src="https://raw.githubusercontent.com/Derivative-Work/.github/main/profile/logo.svg" width="120" alt="Derivative Work logo: an eighth note under a struck-through AI sparkle">
</p>
<h1 align="center">Derivative Work</h1>
<p align="center">
  <b>Music videos about AI, made mostly with AI, and open about how.</b>
</p>
<p align="center">
  <a href="http://www.youtube.com/@DerivativeWork">YouTube</a>
</p>

---

Derivative Work is a music video project about AI, the AI industry, and what they're doing to everyone else. Each video takes a real AI story and sets it in a genre that comments on it. Most of each video is generated.

This organization holds the source behind the videos, so anyone can see exactly how each one was made.

## Repositories

| Repository | What's in it | Status |
|---|---|---|
| [`ghost-in-the-machine`](https://github.com/Derivative-Work/ghost-in-the-machine) | Lyrics, generation prompts, shot lists, and the code that composites and renders [Ghost in the Machine](https://www.youtube.com/watch?v=6RcYUoG1t0I) | Active |
| [`music-deslop`](https://github.com/Derivative-Work/music-deslop) | A post-filter that restores the transients and high-frequency detail that AI music generators smear | In development; release undecided |

## How each video was made

Every video lists what it was derived from, both in its YouTube description and in its folder here:

- **Reporting:** the news sources the song is based on
- **Lyrics:** drafted with Claude, then edited by hand
- **Music and vocals:** the generator and model version, with prompts
- **Video:** the tools used, with prompts
- **Human-made:** the sections performed or recorded by a person, if any

If something in a video was generated, the prompt that made it should be in this organization. If it isn't, please open an issue.

## About the post-filter

AI music generators leave audible artifacts, and the same artifacts are what AI-music detectors look for. A tool that removes them can make generated songs sound better, and it can also help pass them off as human-made. An upcoming song is about exactly that.

Because of this, the post-filter will be released only together with its detection results: how filtered and unfiltered output scores on publicly available AI-music detectors. If those results show it mainly helps hide AI output, the weights won't be released. Training code and evaluation results will be published either way.

The model is trained only on permissively licensed audio by default. The training data and their licenses are listed in the repository.

## Licensing

- **Code:** [MIT](https://mit-license.org/), unless a repository says otherwise.
- **Music, lyrics and video:** [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/), where we hold the rights. Purely AI-generated material may not be copyrightable, generator output is subject to each generator's terms, and third-party material shown in videos (such as screen recordings of real services and public filings) is not covered.
- **Model weights:** to be decided at release, along with the release decision above.

It is, after all, Derivative Work.
