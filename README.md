# MIFRA

**Mechanical Inference & Functional Reasoning Assessment**

A planned 20-exhibit, photograph-based assessment of mechanical reasoning. The objective is to measure how accurately participants infer a component's function, mechanism, application, and design intent from its physical features.

## Status

The GitHub Pages landing page is committed, but the assessment is **not yet accepting participants**.

- [x] Repository and responsive public landing page
- [ ] Source and independently verify 20 photographs (identity, matching part, usage rights)
- [ ] Remove identifying labels and metadata from participant-facing exhibits
- [ ] Implement participant question flow, answer review, and consent
- [ ] Configure a private response database and access policies
- [ ] Implement examiner-only scoring and export
- [ ] Test end-to-end submissions and mobile usability
- [ ] Open enrollment

## Scoring

Each exhibit has 10 possible points: fundamental function 3; operating mechanism 2; application 2; design interpretation 2; technical identification 1. Twenty exhibits total 200 points. Functional understanding must not be conflated with the ability to recall a part's name. Scores should be adjudicated against a documented reference key and consistent examples.

## GitHub Pages

In repository **Settings → Pages**, select **Deploy from a branch**, branch **main**, folder **/(root)**, then save. Once GitHub publishes the site, its expected address is:

https://snow663.github.io/MIFRA/

GitHub Pages hosts static files only. It cannot execute the original Python/SQLite prototype, protect secret scoring keys, or persist participant answers. A separate authenticated backend is required. Never commit answer keys, participant records, private API keys, or service-role credentials to this public repository.

## Research limitations

The initial 20 mechanisms are *candidate topics*, not yet verified image exhibits. Do not describe the assessment as validated or its results as representative of the general population without a suitable sample and controls. Participants should report prior familiarity with each component, and responses should be scored without knowing participant identity or experience when practical.

## License

License to be determined; third-party component photographs require separate permissions or applicable licenses.
