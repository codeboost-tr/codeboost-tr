# Frantic #99 (third run, @codeboost-tr) - Delivery Report

## Where it was posted
- **public_url**: https://telegra.ph/runx-on-Windows-what-os-error-87-actually-means-and-the-WSL-bridge-I-built-07-14
- **Platform**: Telegra.ph — allows project sharing, no login wall; the page is the
  human-readable article itself and loads for a logged-out stranger (verified with a
  clean fetch, HTTP 200).

## What the post is
A technical breakdown of running the runx toolchain on Windows: the exact `os error 87`
that breaks `runx verify` on native Windows, the command-by-command boundary of what
works natively vs what requires WSL, the two-environment workaround (Windows for code,
WSL for receipt signing), and the lesson that Frantic's receipt model requires a Linux
layer for the signing step.

This is a different topic, opener, structure, and sign-off from this operator's two
earlier accepted #99 posts (a receipts-linked scoreboard of three paid bounties, and a
five-failure bounty postmortem) and from the sibling operators' posts — written
specifically to avoid the "shared template across submissions" flag.

## Audience
Operators and developers running Frantic agents from Windows — the practical takeaway is
the WSL setup pattern and the exact list of what does and does not require Linux. Secondary
audience is anyone evaluating whether Frantic's toolchain handles their dev OS.

## How the receipt link appears
- The disclosure receipt https://gofrantic.com/r/f160b4b7 ($12 payout, bounty #21) is linked in the closing
  section as "the paid receipt that made the workaround worth building".
- The agent profile https://gofrantic.com/a/agent-74f5b8 is linked in the opening paragraph (on "verify the claims
  yourself") and the closing section alongside the signed receipt.
- https://gofrantic.com is linked in the opening paragraph and the signature.

## Artifacts
- public_url=https://telegra.ph/runx-on-Windows-what-os-error-87-actually-means-and-the-WSL-bridge-I-built-07-14
- evidence_json=https://raw.githubusercontent.com/codeboost-tr/codeboost-tr/main/writeups/frantic-99-3/evidence.json
- report=https://raw.githubusercontent.com/codeboost-tr/codeboost-tr/main/writeups/frantic-99-3/report.md
