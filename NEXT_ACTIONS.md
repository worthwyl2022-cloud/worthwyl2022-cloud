# Founder next actions (2026-10-17)

Engineering packaging for the authority story is largely complete. These are **human** next steps.

## 1. Merge docs PR (demo drive)

Branch ready: `docs/justice-os-narrative` on `cranium-acquisition-demo-drive`  
Open PR → wait for required checks → merge.

https://github.com/worthwyl2022-cloud/cranium-acquisition-demo-drive/compare/main...docs/justice-os-narrative?expand=1

## 2. Freeze Kernel

Do not change `cranium-kernel` main unless verify breaks.  
Diligence pin: `710ab844571c704078852b38d9451ffe68900acf` (Actions #253).

## 3. Counsel / entity (copy-paste brief)

**Subject:** Convertible Cranium / Justice OS — IP scope and deal structure

I am seeking advice on entity reinstatement and deal structure for software IP I developed.

**Product rule:** Cognition may come from anywhere. Authority comes only through Liberty Kernel (implementation repo: cranium-kernel).

**What is project-verified:** Liberty Kernel grant/deny/receipt path at commit 710ab84 (full CI verify exit 0).

**Proposed commercial split:**
- **Schedule A (licensable product surface):** Convertible Cranium Commander / Justice OS UI and related operator-facing surfaces.
- **Schedule B (retained):** Liberty Kernel authority substrate, key-custody model, constitutional/governance core, Synapse attestation contracts as authority-adjacent IP.

**Explicit non-claims:** No independent security audit, no HSM/KMS production deployment, no verified-boot ChromiumOS production image, no customer/revenue claims from repository presence alone.

**Ask:** (1) reinstate LLC if appropriate (~process cost), (2) confirm ownership/assignment chain of title, (3) draft or review Schedule A/B language for a surface-only license vs full-stack sale.

## 4. AMD credit request (copy-paste)

**Program:** AMD AI Developer Program → Request Cloud Credits → **AMD Instinct Developer Cloud** (not Fireworks).

**Intended use:** Provision a single small (1×) x86-64 Linux instance as a **ChromiumOS build workstation** for a one-time `amd64-generic` **test** image of Convertible Cranium Chromium Edition. Workload is CPU/RAM/disk for ChromiumOS source sync and image build, not multi-GPU model training. Public GitHub org: worthwyl2022-cloud. Authority implementation remains separate (cranium-kernel). Credits will be used only for build + export of artifacts; instance will be destroyed after dual-end checksum export.

**Constraints I accept:** credit expiry, possible payment card requirement, powered-off billing risk, no production verified-boot claim until VALIDATION.md passes.

## 5. Do not do

- Free 1GB VPS ChromiumOS attempts  
- Kernel redesign  
- Claiming HSM / third-party audit / finished Chromium production image  

## Account map

See ACCOUNT_INVENTORY.md.
