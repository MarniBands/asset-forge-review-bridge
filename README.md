# Asset Forge browser-agent review bridge

This public repository contains only immutable, sanitized manifests and PNG review renders from
the VM-hosted Blender Asset Forge. Forge remains canonical. No API key or write route is published.

Live visual gallery: https://marnibands.github.io/asset-forge-review-bridge/?job=b1de79b407f64b6380aba6d1abb2ab2f

Arena eight-view contact sheet: [competitive_tag_arena_50x50 / b1de79b407f6](review-b1de79b407f6-eight-view-contact.png)

Small web-agent derivative: [1600×800 JPEG](review-b1de79b407f6-eight-view-contact-1600.jpg).
It is a deterministic Lanczos downscale of the verified sheet for connector environments that
truncate larger binary blobs; it is review transport, not a replacement canonical artifact.

Contact-sheet layout: top row = `front`, `rear`, `left`, `right`; bottom row = `top`,
`perspective_front_left`, `perspective_front_right`, `perspective_rear`. Each 512×512 quadrant is
pixel-identical to its immutable job-bundle PNG.

## Published jobs

| Created | Asset | Job | Parent | Source commit | Direct preview |
| --- | --- | --- | --- | --- | --- |
| 2026-08-19T18:44:16.116932+00:00 | `competitive_tag_arena_50x50` | [`b1de79b407f64b6380aba6d1abb2ab2f`](jobs/b1de79b407f64b6380aba6d1abb2ab2f/) | `none` | `add832ba270ec941e224f5202f5b3c35327980e7` | [perspective front-right](review-b1de79b407f6-perspective_front_right.png) · [top](review-b1de79b407f6-top.png) |
| 2026-08-19T16:54:45.052136+00:00 | `test_crate` | [`238389120b0a40c68a52438e7bc4ffd9`](jobs/238389120b0a40c68a52438e7bc4ffd9/) | `9f010b28ac66414a97dbdcb73a7d5d3e` | `bd4db00b86d19a51c9b1d81e704f47bf0bc51f21` | [perspective front-right](review-238389120b0a-perspective_front_right.png) · [top](review-238389120b0a-top.png) |
| 2026-08-19T15:36:31.150945+00:00 | `test_crate` | [`9f010b28ac66414a97dbdcb73a7d5d3e`](jobs/9f010b28ac66414a97dbdcb73a7d5d3e/) | `d3af4244021a4eff939ef205fa1eeaa4` | `7aa26991f343ba3731a80d93bb8262b290bf7913` | [perspective front-right](review-9f010b28ac66-perspective_front_right.png) · [top](review-9f010b28ac66-top.png) |
| 2026-08-19T09:29:45.861438+00:00 | `test_crate` | [`d3af4244021a4eff939ef205fa1eeaa4`](jobs/d3af4244021a4eff939ef205fa1eeaa4/) | `2698d389947145e8a775f5385ac66683` | `5ee6a053b05e5d7c343d928027f70dd012cf7232` | — |
| 2026-08-18T22:34:25.738499+00:00 | `test_crate` | [`2698d389947145e8a775f5385ac66683`](jobs/2698d389947145e8a775f5385ac66683/) | `c48b58449393416aaccc3b01bead5d84` | `bcec8e140aab6477f649155e90038efd7ea1a5ea` | — |

## Inline visual previews

### competitive_tag_arena_50x50 / b1de79b407f64b6380aba6d1abb2ab2f

[Exact immutable bundle](jobs/b1de79b407f64b6380aba6d1abb2ab2f/)

#### perspective front-right

![b1de79b407f64b6380aba6d1abb2ab2f perspective front-right](review-b1de79b407f6-perspective_front_right.png)

#### top

![b1de79b407f64b6380aba6d1abb2ab2f top](review-b1de79b407f6-top.png)

### test_crate / 238389120b0a40c68a52438e7bc4ffd9

[Exact immutable bundle](jobs/238389120b0a40c68a52438e7bc4ffd9/)

#### perspective front-right

![238389120b0a40c68a52438e7bc4ffd9 perspective front-right](review-238389120b0a-perspective_front_right.png)

#### top

![238389120b0a40c68a52438e7bc4ffd9 top](review-238389120b0a-top.png)

### test_crate / 9f010b28ac66414a97dbdcb73a7d5d3e

[Exact immutable bundle](jobs/9f010b28ac66414a97dbdcb73a7d5d3e/)

#### perspective front-right

![9f010b28ac66414a97dbdcb73a7d5d3e perspective front-right](review-9f010b28ac66-perspective_front_right.png)

#### top

![9f010b28ac66414a97dbdcb73a7d5d3e top](review-9f010b28ac66-top.png)
