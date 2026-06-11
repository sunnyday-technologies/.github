# Sunnyday Technologies

A Materials engineering company in Wisconsin, USA. We build an AI-driven concrete mix-formulation platform, open-source 3D concrete printing hardware to print the material, the open dataset that ties them together, and CAD tooling assembly helpers to keeps the assemblies honest.

## Brand portfolio

| Project | Site | Repository | License | Role |
|---|---|---|---|---|
| **M3-CRETE** | [m3-crete.com](https://m3-crete.com) | [`M3-CRETE`](https://github.com/sunnyday-technologies/M3-CRETE) | CERN-OHL-W-2.0 | Open-source meter-scale concrete 3D printer hardware |
| **CEMFORGE** | [cemforge.ai](https://cemforge.ai) | _(private SaaS)_ | Proprietary | AI-driven concrete mix-formulation platform |
| **Open3DCP** | [open3dcp.org](https://open3dcp.org) | [`Open3DCP`](https://github.com/sunnyday-technologies/Open3DCP) | Apache-2.0 | Open printability dataset and schema for 3DCP |
| **CADCLAW** | [cadclaw.io](https://cadclaw.io) | [`CADCLAW`](https://github.com/sunnyday-technologies/CADCLAW) | _see repo_ | "Pytest for CAD" — open-source assembly validation framework |
| **MARB** | [marb.cadclaw.io](https://marb.cadclaw.io) | [`MARB`](https://github.com/sunnyday-technologies/MARB) | MIT | Mechanical Assembly Readiness Benchmark — can AI assemble a real machine? Frontier + local models, one open board |
| **Sunn3D** | [sunn3d.com](https://sunn3d.com) | _(parent brand)_ | — | Company site |

## How the projects fit together

CEMFORGE generates printable concrete formulations. M3-CRETE prints them. Open3DCP standardizes the resulting performance data. CADCLAW validates the CAD assemblies that build M3-CRETE hardware. MARB uses CADCLAW to benchmark how well AI models assemble that hardware — frontier and local models, graded on one open board.

## Install / try

- `pip install cadclaw` — [`cadclaw` on PyPI](https://pypi.org/project/cadclaw/)
- `git clone https://github.com/sunnyday-technologies/M3-CRETE` — printer CAD + BOM
- `git clone https://github.com/sunnyday-technologies/Open3DCP` — printability dataset/schema
- `git clone https://github.com/sunnyday-technologies/MARB` — AI-CAD assembly benchmark (kits, graders, grades, board)
- CEMFORGE — request access at [cemforge.ai](https://cemforge.ai)

## Contact

- **m3@sunn3d.com** — general inquiries
- Founder: [Nick Sonnentag](https://sunn3d.com/founder/)
- Located in Appleton, Wisconsin, USA
