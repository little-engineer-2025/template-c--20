# Expectations for triage process

- It is checked that it does not already exists, else tag as `duplicated`,
  reference the duplicated ticket, and close the ticket.
- The ticket is labeled according to labels section.
- The content is understandable for all the parts; this could require several
  cycles of request/response until no doubts about the question/bug/feature
  related with the ticket.
  - If it is a bug, ensure it is repeatable by adding the steps for it.
  - If it is a feature, it is indicated the acceptance criteria in a way that
    the acceptance tests can be figured out, and the unit tests, to fit with the
    criteria.
  - If it is a question, it is understood all the points on it, so we can
    proceed to provide an accurate response, and request more information if
    required to have a better context.
- For a bug/feature, it is evaluated if it will be made, else the ticket is
  closed, tagged with `wontdo` label, and an explanation about the reason; no
  resources and time is reasonable.
- If the bug/feature is easy, tag as `goodstart`, so new collaborators can check
  that tickets and getting started collaboration with the repository.

## Labels

- kind/bug
- kind/question
- kind/feat
- kind/test
- kind/doc

- goodstart
- wontdo
- duplicated

- stat/triage
- stat/backlog
- stat/running
- stat/blocked
- stat/review

<!-- TODO as components exist in your repo -->
- comp/<component>

