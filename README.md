<div align="center">

# SkyClaw-v1.0

### A Million-Context Agent Model at Ultra-Low Cost

**[Online Page](https://skyworkai.github.io/skyclaw/)** | **[Try API](https://www.apifree.ai/model/skywork-ai/skyclaw-v1?tab=api)** | **[Lite Version](https://www.apifree.ai/model/skywork-ai/skyclaw-v1-lite?tab=info)**

[![License: MIT](https://img.shields.io/badge/License-MIT-green.svg)](LICENSE)
[![Context](https://img.shields.io/badge/Context-1M%20tokens-brightgreen)](https://skyworkai.github.io/skyclaw/)
[![Price](https://img.shields.io/badge/Input-0.5%20CNY/M%20tokens-blue)](https://skyworkai.github.io/skyclaw/)
[![API](https://img.shields.io/badge/API-OpenAI%20Compatible-orange)](https://www.apifree.ai/model/skywork-ai/skyclaw-v1?tab=api)

</div>

---

SkyClaw-v1.0 is a high-performance agent model by [Skywork AI](https://huggingface.co/Skywork), optimized for complex tool use, multi-turn agent workflows, and cost-sensitive production tasks. Available in two variants:

| Model | Input (CNY/M) | Output (CNY/M) | Best For |
| :--- | :---: | :---: | :--- |
| **SkyClaw-v1.0** | 0.5 | 4.0 | Strongest agent performance |
| **SkyClaw-v1.0-lite** | 0.3 | 2.0 | Speed & cost-sensitive tasks |

## Benchmarks

SkyClaw-v1.0 outperforms Minimax 2.7, DeepSeek V4 Flash, and Qwen 3.6 series across all major agent benchmarks, while approaching larger proprietary models on Claw-related tasks.

![SkyClaw benchmark chart](https://raw.githubusercontent.com/skyworkai/skyclaw/main/assets/benchmark_style_chart_1600.png)

## Showcase

The release page features locally rendered screenshots and short videos, showcasing real generated demos across UI applications and interactive games.

### Static Previews

<table>
  <tr>
    <td align="center"><b>Flight & Travel</b></td>
    <td align="center"><b>Instagram-style</b></td>
    <td align="center"><b>Xiaohongshu-style</b></td>
  </tr>
  <tr>
    <td align="center"><img src="https://raw.githubusercontent.com/skyworkai/skyclaw/main/assets/flight_travel_preview_crop.png" width="260"/></td>
    <td align="center"><img src="https://raw.githubusercontent.com/skyworkai/skyclaw/main/assets/instagram_preview_crop.png" width="260"/></td>
    <td align="center"><img src="https://raw.githubusercontent.com/skyworkai/skyclaw/main/assets/xiaohongshu_preview_crop.png" width="260"/></td>
  </tr>
</table>

### Interactive Demos

<table>
  <tr>
    <th>Demo</th>
    <th align="center">Preview</th>
    <th align="center">Live</th>
  </tr>
  <tr>
    <td>Bouncing Balls</td>
    <td align="center"><video src="https://raw.githubusercontent.com/skyworkai/skyclaw/main/assets/bouncing_balls_preview.mp4" muted loop></video></td>
    <td align="center"><a href="https://picture-search.tiangong.cn/skyclaw-demos/bouncing_balls.english.html">Play</a></td>
  </tr>
  <tr>
    <td>Bingo Match</td>
    <td align="center"><video src="https://raw.githubusercontent.com/skyworkai/skyclaw/main/assets/bingo_preview.mp4" muted loop></video></td>
    <td align="center"><a href="https://picture-search.tiangong.cn/skyclaw-demos/bingo.html">Play</a></td>
  </tr>
  <tr>
    <td>2048 Puzzle</td>
    <td align="center"><video src="https://raw.githubusercontent.com/skyworkai/skyclaw/main/assets/2048_preview.mp4" muted loop></video></td>
    <td align="center"><a href="https://picture-search.tiangong.cn/skyclaw-demos/2048/index.html">Play</a></td>
  </tr>
  <tr>
    <td>Tetris</td>
    <td align="center"><video src="https://raw.githubusercontent.com/skyworkai/skyclaw/main/assets/tetris_preview.mp4" muted loop></video></td>
    <td align="center"><a href="https://picture-search.tiangong.cn/skyclaw-demos/tetris/index.html">Play</a></td>
  </tr>
  <tr>
    <td>Super Mario</td>
    <td align="center"><video src="https://raw.githubusercontent.com/skyworkai/skyclaw/main/assets/super_mario_preview.mp4" muted loop></video></td>
    <td align="center"><a href="https://picture-search.tiangong.cn/skyclaw-demos/mario_game.html">Play</a></td>
  </tr>
  <tr>
    <td>Airplane Battle</td>
    <td align="center"><video src="https://raw.githubusercontent.com/skyworkai/skyclaw/main/assets/airplane_battle_preview.mp4" muted loop></video></td>
    <td align="center"><a href="https://picture-search.tiangong.cn/skyclaw-demos/airplane_battle/index.html">Play</a></td>
  </tr>
  <tr>
    <td>Chess</td>
    <td align="center"><video src="https://raw.githubusercontent.com/skyworkai/skyclaw/main/assets/chess_preview.mp4" muted loop></video></td>
    <td align="center"><a href="https://picture-search.tiangong.cn/skyclaw-demos/chess.html">Play</a></td>
  </tr>
  <tr>
    <td>Texas Hold'em</td>
    <td align="center"><video src="https://raw.githubusercontent.com/skyworkai/skyclaw/main/assets/texas_holdem_preview.mp4" muted loop></video></td>
    <td align="center"><a href="https://picture-search.tiangong.cn/skyclaw-demos/texas_holdem/index.html">Play</a></td>
  </tr>
  <tr>
    <td>Financial Terminal</td>
    <td align="center"><video src="https://raw.githubusercontent.com/skyworkai/skyclaw/main/assets/financial_terminal_preview.mp4" muted loop></video></td>
    <td align="center"><a href="https://picture-search.tiangong.cn/skyclaw-demos/financial_terminal_cn/index.html">Open</a></td>
  </tr>
  <tr>
    <td>Tank Roguelike</td>
    <td align="center"><video src="https://raw.githubusercontent.com/skyworkai/skyclaw/main/assets/tank_roguelike_preview.mp4" muted loop></video></td>
    <td align="center"><a href="https://picture-search.tiangong.cn/skyclaw-demos/tank-roguelike.html">Play</a></td>
  </tr>
  <tr>
    <td>Slay the Spire (杀戮尖塔)</td>
    <td align="center"><video src="https://raw.githubusercontent.com/skyworkai/skyclaw/main/assets/slay_the_spire_preview.mp4" muted loop></video></td>
    <td align="center"><a href="https://picture-search.tiangong.cn/skyclaw-demos/%E6%9D%80%E6%88%AE%E5%B0%96%E5%A1%94.html">Play</a></td>
  </tr>
</table>

## Citation

If you reference SkyClaw-v1.0 in your work, please use the following citation:

```bibtex
@misc{skyclaw2026,
  title={SkyClaw-v1.0: A Million-Context Agent Model at Ultra-Low Cost},
  author={Peiyu Wang and Min Zou and Liang Zeng and Weishen and Peng Cheng and Haoran Zhang and Yu Cheng and Yang Liu},
  year={2026},
  month={May},
  howpublished={\url{https://skyworkai.github.io/skyclaw/}},
  url={https://skyworkai.github.io/skyclaw/},
}
```

*Corresponding authors: Yu Cheng, Yang Liu*
