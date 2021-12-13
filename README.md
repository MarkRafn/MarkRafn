- I’m @MarkRafn, or mrafn@foursquare.com, or just Mark.

I'm not sure that any summary I give is going to be useful or accurate - specifics and details overwhelm any generality one can codify.  But here goes:
- Actually, let's start with that.  Details matter.  Running code trumps theoretical arguments.  There are almost no pure pareto cost-free improvements - every action is a tradeoff.  
    - Some tradeoffs are pretty easy, though.  And I tend to prefer medium- to long-term improvements (but not too long-term; there needs to be noticeable value throughout a project) over short-term ones.  
    - I'm not actually an anarchist - process can have value, especially as guiderails and removal of bikeshed-painting debates.  But Gödel's Theorem applies to all things - the rules cannot be both complete and consistent.  Doing the Right Thing for customers and coworkers is the reason for any process, and is more important than following process.  
- Debt (financial and technical) is a tool.  It's a long-term cost for an immediate value.  To the extent that the value grows and compounds, the debt can be reduced, or the debt service (operational overhead) can be sustained.  This _does_ imply that it needs to be examined and planned for - the decision about when/whether to increase or decrease debt levels can make or break a company, product, team, or codebase.
- I make a pretty strong distinction in my mind between development and production systems.  Dev is optimized for flexibility, human-scale exploration, discovery and measurement of options and mechanisms.  Prod is all about repeatability and scale.  The link between them should be _ONLY_ in source-controlled, reviewed, and tested code, configuration, and automated scripts.  
    - this imples a lot of open-ness for reading code-bases, read-only console access, and easy writes to code brances and dev instances of infrastructure.  And the opposite for production - _zero_ writable console access (exception: to fix or mitigate a high-severity event, as long as the fix gets replaced by automation within a few days).  Merges to production branches only via controlled processes.  
- This probably should have gone first - most of the difficult disagreements and tradeoffs are about timeframes and resources, not about "what's right".  The tension between "what's best for the next few weeks" and "what's best for the next year or three" underlies the vast majority of architecture, project, and ops debates I've seen.  Once you notice this, it's easy to see that neither one is always right - circumstances dictate the focus.

<!---
MarkRafn/MarkRafn is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->
