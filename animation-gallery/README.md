# Unity-chan Production Motion + Flow Gallery

Public generated WebGL output for motion/transition review. The Unity source project and raw third-party model/animation packages are not published here.

Default mode is **FLOW** because run → attack → combo → run continuity is the primary review target. `TAB` switches to SINGLE action pose review. Neither mode auto-repeats; use Replay/Space to run another pass.

Flow reviews: Moving Combo, **Steering Combo**, Rising Combo, Strong From Run, Special From Run, Dodge From Run.

Normal 1/2 preserve locomotion/idle legs and layer the sword motion only on the upper body in **both FLOW and SINGLE**. Normal 3 is the full-body finisher. The upper-body layer exits faster before Normal 3 so N2 → N3 does not leave a residual torso pose. Steering Combo also turns the GameplayRoot while N1/N2 are playing so moving-combo continuity can be judged under direction changes, not only straight-line playback. FX can be toggled with `F`.

Generated with Unity 6000.3.22f1 on 2026-09-06.
