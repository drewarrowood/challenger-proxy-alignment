# Notes & [verify] items — Challenger / Proxy Alignment essay

Companion to `challenger-proxy-alignment.md` and `.tex`.  
Author context: Drew Arrowood · drafted 2026-09-27 (America/New_York).

## Items marked [verify] or needing confirmation before stronger claims

1. **Anthropic Claude system card citation (Section 4)**  
   - Essay cites “Anthropic 2024–2025, verify current card” without a single canonical URL, because Anthropic has issued multiple model/system cards (e.g. Claude 3 family, Claude 4 / Opus–Sonnet cards).  
   - **Action:** Pin the exact PDF URL and date for the model(s) under discussion before publication. Example known public artifact: Claude Opus 4 & Sonnet 4 System Card (cdn.anthropic.com; confirm live path).  
   - Do **not** invent page numbers, refusal-rate figures, or quotes from a card not re-read at citation time.

2. **OpenAI GPT-4 System Card**  
   - URL used: `https://cdn.openai.com/papers/gpt-4-system-card.pdf` — widely cited; re-fetch to confirm still live and note version/date if citing specific eval numbers (essay currently cites existence/framing only, not numbers).

3. **Feynman probability range “1 in 100” vs “1 in 100,000”**  
   - Verified against Appendix F text (Rogers Commission Vol. 2): “estimates range from roughly 1 in 100 to 1 in 100,000. The higher figures come from the working engineers, and the very low figures from management.”  
   - Status: **OK to cite** as paraphrase/quote of Appendix F. Prefer linking official NASA History mirror: `https://history.nasa.gov/rogersrep/v2appf.htm` (archive mirrors also exist).

4. **“Safety factor of three” / one-third radius erosion**  
   - Verified in Appendix F discussion of flight 51-C erosion depth vs. cutting experiment. Status: **OK**.

5. **Closing line “nature cannot be fooled”**  
   - Verbatim end of Appendix F. Status: **OK**.

6. **Perez et al. sycophancy magnitude (e.g. “>90%”)**  
   - Paper reports high sycophancy rates for largest models on some question types. Essay deliberately **does not** quote the “>90%” figure in the main text to avoid over-precision; if adding numbers later, re-read Fig. 2 / associated tables in arXiv:2212.09251 or ACL 2023 Findings version.

7. **Sharma et al. 2023**  
   - arXiv:2310.13548 — “Towards Understanding Sycophancy in Language Models.” Confirm author list truncation (“et al.”) is acceptable for the venue style you use; full list is long.

8. **Röttger et al. XSTest**  
   - arXiv:2308.01263; NAACL 2024. Essay cites exaggerated/over-refusal phenomenon generally; if claiming specific model leaderboard results, re-check paper tables (models age quickly).

9. **Zheng et al. LLM-as-judge**  
   - arXiv:2306.05685; NeurIPS 2023. Essay cites the paradigm and known bias classes (verbosity, self-enhancement) at a high level—consistent with the paper’s own discussion. No fabricated agreement percentages added.

10. **HHH triad conflicts**  
    - Askell et al. 2021 introduces HHH as evaluation frame. The claim that “honesty loses most often under preference pressure” is an **interpretive** synthesis in the essay, not a direct quote from Askell/Bai. Label as argument, not as their finding, if a referee asks. Optional: soften to “honesty is the hardest of the three for immediate preference scores to reward.”

11. **O-ring ice-water demonstration**  
    - Historically associated with Feynman’s public hearing demonstration (C-clamp + ice water). Essay Section 1 focuses on Appendix F organizational diagnosis and does **not** lean on the demo anecdote; if you add it, cite hearing transcript / contemporaneous reporting separately from Appendix F.

12. **No invented scandals**  
    - Draft avoids specific incident claims (e.g. unnamed “leaks,” fabricated benchmark scores, alleged internal quotas). Keep it that way in revisions. Critique stays on incentive patterns + published papers.

## Optional citations not included (available if expanding)

- Amodei et al. (2016). *Concrete Problems in AI Safety*. arXiv:1606.06565 — reward hacking / scalable oversight backdrop.  
- Casper et al. (2023). *Open Problems and Fundamental Limitations of RLHF*. arXiv:2307.15217 — survey of RLHF failure modes.  
- Goodhart, C. (1975) / Strathern paraphrase — for deeper Goodhart citation hygiene.  
- Cotra, A. (2021). “The case for aligning narrowly superhuman models” / related AF posts — sycophancy terminology sometimes traced here (Perez cites Cotra 2021a). Mark [verify] if quoting Cotra directly.  
- Bai et al. (2022). *Training a Helpful and Harmless Assistant with RLHF* (earlier Anthropic HH paper, arXiv:2204.05862) — distinct from Constitutional AI paper; don’t conflate.

## Word count / format

- Target band: 1500–2500 words.  
- Check with `wc -w challenger-proxy-alignment.md` after edits (abstract + body + refs).  
- TeX twin: `challenger-proxy-alignment.tex` — article-class, amsmath; bibliography as enumerated list matching Markdown for portability (no BibTeX dependency).

## Voice checklist (Feynman likeness, not costume)

- Prefer concrete mechanism over moral heat.  
- Do not fake folksy “gee whiz” dialect.  
- Allergy to fake understanding: if a citation is soft, mark verify or omit.  
- Equations: few; each must earn its keep (target vs proxy; \(G > \delta L\)).
