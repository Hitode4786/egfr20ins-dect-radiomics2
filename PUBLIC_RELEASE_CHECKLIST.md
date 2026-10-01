# Public Release Checklist

Before creating a public repository release, an authorized author must:

- [ ] confirm that the MIT licence is appropriate for all contributed source;
- [ ] scan Git history and the release tree for protected health information,
      credentials, local absolute paths, and non-redistributable vendor assets;
- [ ] replace all `AUTHOR_INPUT_NEEDED` fields with the release version, source
      commit/tag, authors, repository URL, data-access contact, and version DOI;
- [ ] confirm the IRB/consent and data-governance wording for the manuscript;
- [ ] confirm whether any model weights or derived feature artifacts may be
      released (they are excluded by default);
- [ ] create an immutable versioned release and archive it with a persistent
      identifier;
- [ ] retain the controlled server receipt and input identity records under the
      institution's approved retention policy.

The absence of public patient data is intentional. A public source repository
does not by itself establish clinical validity, external validation, or
independent reproduction.
