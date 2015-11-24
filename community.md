---
layout: page
title: Community
description: Project Community Page
group: nav-right
---
{% include JB/setup %}

## {{ site.data.project.name }} Community

Every volunteer project obtains its strength from the people involved in it. We invite you to participate as much or as little as you choose.

You can:

* Use our project and provide a feedback.
* Provide us with the use-cases.
* Report bugs and submit patches.
* Contribute code, javadocs, documentation.

Visit the [Contributing] page for more information.

### Mailing list

Get help using {{ site.data.project.short_name }} or contribute to the project on our mailing lists:

{% if site.data.project.user_list %}
* [site.data.project.user_list](mailto:{{ site.data.project.user_list }}) is for usage questions, help, and announcements. [subscribe](mailto:{{ site.data.project.user_list_subscribe }}?subject=send this email to subscribe),     [unsubscribe](mailto:{{ site.data.project.dev_list_unsubscribe }}?subject=send this email to unsubscribe), [archives]({{ site.data.project.user_list_archive_mailarchive }})
{% endif %}
* [{{ site.data.project.dev_list }}](mailto:{{ site.data.project.dev_list }}) is for people who want to contribute code to {{ site.data.project.short_name }}. [subscribe](mailto:{{ site.data.project.dev_list_subscribe }}?subject=send this email to subscribe), [unsubscribe](mailto:{{ site.data.project.dev_list_unsubscribe }}?subject=send this email to unsubscribe), [archives]({{ site.data.project.dev_list_archive_mailarchive }})
* [{{ site.data.project.commits_list }}](mailto:{{ site.data.project.commits_list }}) is for commit messages and patches to {{ site.data.project.short_name }}. [subscribe](mailto:{{ site.data.project.commits_list_subscribe }}?subject=send this email to subscribe), [unsubscribe](mailto:{{ site.data.project.commits_list_unsubscribe }}?subject=send this email to unsubscribe), [archives]({{ site.data.project.commits_list_archive_mailarchive }})


### Issue tracker



#### Bug Reports

Found bug? Enter an issue in the [Issue Tracker](https://issues.apache.org/jira/browse/{{ site.data.project.jira }}).

Before submitting an issue, please:

* Verify that the bug does in fact exist.
* Search the issue tracker to verify there is no existing issue reporting the bug you've found.
* Consider tracking down the bug yourself in the Wink's source and submitting a patch along with your bug report. This is a great time saver for the Wink developers and helps ensure the bug will be fixed quickly.



#### Feature Requests

Enhancement requests for new features are also welcome. The more concrete and rationale the request is, the greater the chance it will incorporated into future releases.


  [https://issues.apache.org/jira/browse/{{ site.data.project.jira }}](https://issues.apache.org/jira/browse/{{ site.data.project.jira }})


### Source Code

The project sources are accessible via the [source code repository]({{ site.data.project.source_repository }}) which is also mirrored in [GitHub]({{ site.data.project.source_repository_mirror }})


### Website Source Code

The project website sources are accessible via the [website source code repository]({{ site.data.project.website_repository }}) which is also mirrored in [GitHub]({{ site.data.project.website_repository_mirror }})
