# The Daily Globe — Wednesday, 25 November 2026

One image that sums up the world's news of Wednesday, 25 November 2026.

Entry for the make.fun bounty **"Sum up 25 November's world news in one image"**
(`news-image-20261125`, $100, closes Friday 27 November 2026 07:00 WIB).

## The image

`entry.png` is a front page of **The Daily Globe** for 25 November 2026: a masthead,
the date, one lead story and eight more stories from that day, each with its own
picture and headline. A reader who missed the day can tell what happened from the
image alone.

## The nine stories

1. **Ukraine confirms ship strike in Gulf of Finland** — President Zelenskiy confirmed
   Ukraine was behind a drone strike on a Russian cargo ship in the Gulf of Finland;
   Norway, a strong supporter of Kyiv, urged caution.
2. **NATO vows space defence over Russian satellite** — NATO vowed to defend against
   threats in space after reports that Russia is preparing to launch a nuclear-armed
   satellite, possibly as soon as December 2026.
3. **Huawei convicted in US trial** — China's Huawei was convicted in a sprawling US
   criminal trial over its Iran business and trade-secret theft.
4. **Houthis hit Riyadh tower, 11 hurt** — A Houthi drone attack hit Riyadh's tallest
   tower, wounding 11 people, Saudi civil defence said.
5. **Trump gives Giuliani Medal of Freedom** — President Trump awarded former New York
   City mayor Rudy Giuliani the Presidential Medal of Freedom.
6. **Israeli strike kills Hamas official in Gaza** — An Israeli air strike killed a
   Hamas official in Gaza.
7. **South Korea minister quits in exam scandal** — South Korea's education minister
   resigned over an exam-cheating scandal that shocked the nation.
8. **Australia signs Solomons security pact** — Australia and the Solomon Islands signed
   a security agreement naming Australia the Solomons' primary security partner and
   ruling out foreign military or security bases.
9. **Asian tech shares slide on AI doubts** — Asian technology shares fell sharply as
   investors sold AI-linked shares following a Wall Street retreat.

## How it runs

`main.ts` (Node 22, standard library only) copies the image the repository holds
to the output directory:

```sh
mkdir -p out && MAKEFUN_OUTPUT_DIR=out node main.ts
```

That writes `out/entry.png` — a 1024×1024 image, 257,831 bytes.

## License

MIT. See `LICENSE`.
