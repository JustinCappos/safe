The SAFE WG has been ask to provide the CNCF’s TOC with effective
information about the security of different projects.  The purpose of this
document is to outline the procedure by which a project should be evaluated.

The project assessment process is intended to be a collaborative process for
the benefit of the project and the community, where the primary content is
generated by the [project lead](project-lead.md) and revised based on feedback
from [security reviewers](security-reviewer.md) and other members of the
working group (WG).

Due to the nature and timeframe for the analysis, *this review is not meant
to subsume the need for a professional security audit of the code*.  Audits
of implementation vulnerabilities and similar issues at that level are not
intended to be covered by this assessment.  The purpose of this effort is to
uncover design flaws and to obtain a clear articulation of what the project's
design goals and security properties are intended to be.


## Steps

1. Create tracking issue
   * Issue may be a request from TOC liason or project itself
2. Project provides self-assessment
   * [project lead](project-lead.md) responds to the issue with draft document (see [outline](outline.md))
   * issue assigned to lead [security reviewer](security-reviewer.md) who
   will recruit a second reviewer, if one not already assigned, and facilitate
   the process
3. Inital review
   * Upon request by the project, security reviewer may do an inital review to
   verify completeness, ask for clarifications and provide quick feedback
   * Project posts their document to the group mailing list, allowing at least
   one week for review before presenting to the WG
4. Presentation
   * Project lead presents to WG
   * This will be recorded as part of standard WG process
5. Final assessment
   * Reviewers provide final feedback with recommendations
   * Either project lead or reviewers may request further WG discussion
   * Project lead prepares a PR to /assessments/project-docs/project-name/

## Additional Process Notes

Iteration is expected; however, we expect quick turnaround (at most a week).
In rare cases unrelated issues can unexpectedly interrupt the process and
it may be appropriate to address specific concerns rather than continuing with
the assessment. We encourage open communication between project lead and s
ecurity reviewers:

* At any time, the project lead may request additional time to respond
  to feedback from security reviewers
* Project lead or lead security reviewer may pause the process where a delay
  of over a week cannot be accomodated by the review team. Simply close
  the github issue with a note to SIG co-chairs.

