# Third-party data notices

RuleMesh tooling and original additions are MIT licensed. This does not replace the licenses of imported data or generated datasets.

## Sukka data

Author: Sukka / SukkaW. Sources: SukkaLab/ruleset.skk.moe output revision fb2480119a3dd21e5f95f7eabf1ff98988e32289, associated source reference SukkaW/Surge 6172daf80ac3f9a1d2dbdb9ad6b559554aa8ac62.

The selected LAN, domestic, global, Apple CN, download and game-download files declare GNU AGPL version 3. The complete license text is in licenses/Sukka-AGPL-3.0.txt. Original inputs and their SHA-256 are stored in inputs/ and sources.lock.json. Modifications: normalized domains/CIDRs, declared domain views, and explicit author-marker removals in overrides/public.yaml. Generated private/china/global files retain this data license.

## MetaCubeX service domain data

Author/converter: MetaCubeX contributors. Output revision b4d414227a182c5bc954283e4a83ee176dad671b, license/workflow source revision 4178770badecb1b349fbcd62c737e0d7a2079729. Selected full geo domain views cover AI, developer, social, streaming, platform, games, cloud/CDN and optional advertising; exact 59-category membership and immutable paths are recorded in sources.yaml and sources.lock.json. No geo-lite dataset is used.

MetaCubeX declares GNU GPL version 3; licenses/MetaCubeX-GPL-3.0.txt preserves its text. The underlying v2fly/domain-list-community service data is MIT licensed, copyright V2Ray. That notice is preserved in licenses/v2fly-MIT.txt. The upstream build's exact transitive v2fly commit is not recorded in its output; the consumed MetaCubeX bytes are locked independently. See docs/stage-a-source-audit.md for the audited lineage and known omissions.

Modifications: format conversion, normalization, and a documented official claude.app addition. Generated service files retain their declared GPL data license and upstream source attribution; the original addition is MIT. Data files are kept separate from the AGPL base categories.

## Deferred inputs

Sukka china_ip/chnroutes2 has conflicting CC BY-SA version declarations; geographical IPv4 is not imported or published in this milestone. Other advanced types and untraced source combinations are not automatically included. These are limitations, not claims that such flows are fully covered.

This local milestone includes original snapshots, transformations, notices and source code. The source project is hosted at https://github.com/codingmesh/rulemesh. Experimental release packages retain these notices, full third-party license texts, exact inputs and the source-code commit. Their actual verification status is recorded separately. No stable subscription endpoint is currently provided.

## Official numerical network facts

Telegram destinations are obtained from https://core.telegram.org/resources/cidr.txt; associated terms: https://core.telegram.org/api/terms. OpenAI Voice destinations are obtained from https://openai.com/chatgpt-voice.json; terms: https://openai.com/policies/terms-of-use/; networking guidance: https://help.openai.com/en/articles/9247338-network-recommendations-for-chatgpt-errors-on-web-and-apps.

The official-url sources record fetched-at, original byte SHA-256 and terms URLs. MIT in these source records covers RuleMesh's original routing predicates and transformations derived from numerical network facts; it does not assert that the providers license their raw documentation under MIT or replace their terms. See licenses/RuleMesh-Network-Facts-MIT.txt. IP facts are not assigned to an additional upstream copyleft license.

Both IP sources use existing-only routing, preceding active resolution. OpenAI Voice routes are destination-only: UDP 3478 and TCP 443 conditions in the official guidance are not represented, so this is an explicitly broader routing scope, not a lossless port-rule conversion. The source note and category descriptor preserve this limitation.

The tooling does not copy Sukka AGPL build code or LOWERTOP content. blackmatrix7 is used for research comparison only. No Sukka China IP dataset is consumed or redistributed; sing-box geographic fallback must be supplied through the user's local node/configuration base.
