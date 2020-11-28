Healthy on-call takes place within the context of a social contract that respects developers' time and personal lives.

By putting in place a few simple conditions, organisations empower developers to enthusiastically support their code in production.
This enables operational excellence and better outcomes for customers.

This charter is intended as an opinionated checklist for organisations that care about a humane on-call experience.
If you meet all eight conditions, then you are set up for a responsible on-call scheme.

## Policy

- Incident response and availability for incident response are both recognised in compensation, so that people are rewarded for their effort and commitment.
- There are adequate rest periods following alerts, so that people who are on-call aren't overworked.

## Priority

- Alerts, whether false or genuine, are quickly investigated and remediated, so that people are troubled outside of working hours only when it's necessary.
- There are blameless incident retrospectives, so that the system improves over time.

## Production

- There is adequate observability of production systems, so that the recipient of an alert can quickly diagnose issues.
- There are automated deployment pipelines, so that fixes can be made with confidence.

## People

- People who are on-call commit to being ready and able to respond during their shift, so that alerts don't go unaddressed
  and so that other people don't have to pick up the slack.
- Teams practice collective code ownership and write sufficient documentation, so that someone who receives an alert has all the context that they need to respond.

This charter was written by [Chris Ford](https://github.com/ctford) following [Charity Majors' post on making sure that on-call doesn't suck](https://charity.wtf/2020/10/03/on-call-shouldnt-suck-a-guide-for-managers).
Thank you to my [ThoughtWorks](https://www.thoughtworks.com/) colleagues who gave me feedback on the first draft.

It's licensed under a
[Creative Commons Attribution 4.0 International License][cc-by].

[![CC BY 4.0][cc-by-image]][cc-by]

[cc-by]: http://creativecommons.org/licenses/by/4.0/
[cc-by-image]: https://i.creativecommons.org/l/by/4.0/88x31.png
