# kidsgame

Browser games for kids. Each game is one self-contained HTML file — open it in a browser, no install needed.

## Games

### 竹蜻蜓齿轮工坊 · Bamboo-copter gear workshop — [`bamboo-copter/`](bamboo-copter/index.html)

A realistic 3D simulation of the 竹蜻蜓 build from a gear construction kit (activity book p. 68, 旋转与重力的艺术 · 齿轮组合的多级变速传动).

- Four gear sizes — extra-large 超大 (48 teeth), large 大 (24), medium 中 (16), small 小 (8) — go on the top or bottom face of the bar, plus a crank and a propeller.
- Turn the crank by drawing circles on the screen, or hold the yellow button. Release to launch.
- The propeller needs ≥ 10 rev/s to take off, so kids have to build enough gear ratio (stages multiply; the long-bar preset is 超大带小 ×6 → 大带中 ×1.5 → 大带小 ×3 = ×27).
- The number of each part, and the length of the bar, can be adjusted.
- Five challenges, best-height record, synthesized background music and sound effects (Web Audio, no audio files).

Built with three.js r128 (loaded from cdnjs / jsDelivr).
