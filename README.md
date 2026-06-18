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

🎉 Free for a limited time: Both SkyClaw-v1.0 and SkyClaw-v1.0-lite are currently free to use. 

## What's New

### Multimodal Image Input (2026-06-10)

SkyClaw now supports multimodal image input. Provide a UI screenshot as the visual prompt and ask SkyClaw to understand the layout, identify content, and rebuild the interface as working code — end to end.

<table>
  <tr>
    <td align="center" style="padding-right:16px;vertical-align:top;">
      <b style="color:#4f46e5;">📥 Input</b><br>
      <span style="font-size:12px;color:#888;">Reference screenshot</span><br><br>
      <img src="assets/netflix_mobile_image_input.png" width="380" alt="Netflix reference screenshot"/>
    </td>
    <td align="center" style="padding-left:16px;vertical-align:top;">
      <b style="color:#16a34a;">📤 Output</b><br>
      <span style="font-size:12px;color:#888;">Generated HTML (interactive)</span><br><br>
      <img src="assets/netflix_multimodal_demo.png" width="380" alt="Netflix generated output"/>
    </td>
  </tr>
  <tr>
    <td colspan="2" align="center" style="padding-top:10px;">
      <span style="font-size:12px;color:#888;">Given a Netflix mobile UI mockup, SkyClaw parsed the layout, identified 18 title posters, replaced SVG placeholders with real theatrical photos, and generated a fully interactive HTML clone with tab navigation, horizontal scroll rows, and animated profile bubble.</span>
    </td>
  </tr>
</table>

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
    <td align="center"><b>Bouncing Balls</b><br><a href="https://picture-search.tiangong.cn/skyclaw-demos/bouncing_balls.english.html">Play</a></td>
    <td align="center"><b>Bingo Match</b><br><a href="https://picture-search.tiangong.cn/skyclaw-demos/bingo.html">Play</a></td>
    <td align="center"><b>2048 Puzzle</b><br><a href="https://picture-search.tiangong.cn/skyclaw-demos/2048/index.html">Play</a></td>
  </tr>
  <tr>
    <td align="center"><b>Tetris</b><br><a href="https://picture-search.tiangong.cn/skyclaw-demos/tetris/index.html">Play</a></td>
    <td align="center"><b>Super Mario</b><br><a href="https://picture-search.tiangong.cn/skyclaw-demos/mario_game.html">Play</a></td>
    <td align="center"><b>Airplane Battle</b><br><a href="https://picture-search.tiangong.cn/skyclaw-demos/airplane_battle/index.html">Play</a></td>
  </tr>
  <tr>
    <td align="center"><b>Chess</b><br><a href="https://picture-search.tiangong.cn/skyclaw-demos/chess.html">Play</a></td>
    <td align="center"><b>Texas Hold'em</b><br><a href="https://picture-search.tiangong.cn/skyclaw-demos/texas_holdem/index.html">Play</a></td>
    <td align="center"><b>Financial Terminal</b><br><a href="https://picture-search.tiangong.cn/skyclaw-demos/financial_terminal_cn/index.html">Open</a></td>
  </tr>
  <tr>
    <td align="center"><b>Tank Roguelike</b><br><a href="https://picture-search.tiangong.cn/skyclaw-demos/tank-roguelike.html">Play</a></td>
    <td align="center"><b>Slay the Spire (杀戮尖塔)</b><br><a href="https://picture-search.tiangong.cn/skyclaw-demos/%E6%9D%80%E6%88%AE%E5%B0%96%E5%A1%94.html">Play</a></td>
    <td></td>
  </tr>
</table>

## Citation

If you reference SkyClaw-v1.0 in your work, please use the following citation:

```bibtex
@misc{skyclaw2026,
  title={SkyClaw-v1.0: A Million-Context Agent Model at Ultra-Low Cost},
  author={Peiyu Wang and Min Zou and Liang Zeng and Wei Shen and Peng Cheng and Haoran Zhang and Yu Cheng and Yang Liu},
  year={2026},
  month={May},
  howpublished={\url{https://skyworkai.github.io/skyclaw/}},
  url={https://skyworkai.github.io/skyclaw/},
}
```

*Corresponding authors: Yu Cheng, Yang Liu*
