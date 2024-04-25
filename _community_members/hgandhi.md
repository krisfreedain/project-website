---
#
# Sample data for community members.
#

# The short name is used to identify related pieces of content in the site. For example it is used in the "authors" array of blog posts, and it is used in the "presenters" array for OpenSearch Conference sessions to identify who is speaking.
# The format for existing values is not normalized. In some cases it is "first-initial-of-first-name" + "last-name", or matching a GitHub username, or something all together random. What is important is that it is unique within the system.
short_name: "hgandhi"

# The member's full name, or otherwise meaningful preferred name. It is used in the templates for presenting content authors as well as the name of conference speakers.
name: "Hariharan Gandhi"

# The path to the community member's photo.
photo: "/assets/media/community/members/hgandhi.jpg"

# Used as the level 1 page header text.
primary_title: 'Hariharan Gandhi'

# Used as the document title displayed in the browser title bar.
title: 'OpenSearch Project Community Member: Hariharan Gandhi'

# Breadcrumbs specification.
# The community icon is expected.
# The breadcrumbs path structure is Communit -> Members -> Hariharan Gandhi's Profile.
breadcrumbs:
  icon: community
  items:
    - title: Community
      url: /community/index.html
    - title: Members
      url: /community/members/index.html
    - title: "Hariharan Gandhi&apos;s Profile"
      url: '/community/members/first-last.html'

# Community member job title and company where they work.
job_title_and_company: 'Product Owner, SAP'

# Array of conference IDs for which the community member is a keynote speaker, if any, or boolean false otherwise.
# This value is only relevant for member's with the "conference_speaker" user persona.
keynote_speaker:
  - '2024-europe'
# keynote_speaker: false

# The conference topic track for the conference sessions that the user is a speaker. These are shaped as an array of value pairs mapping conference ID and name. 
# For example for the North American conference for the year 2023, and the "Community" track:
session_track: 
  - conference_id: "2024-europe"
    name: "keynote"

# URL for the community member profile.
permalink: '/community/members/hariharan-gandhi.html'

# Array of community member user personas.
# At this time, only conference_speaker, and author are defined.
personas:
  - conference_speaker
  - author

# Array of conference IDs that the member is a speaker.
conference_id:
  - "2024-europe"


# Optional GitHub username
#github: githubusername

# Optional LinkedIn username
#linkedin: linkedinusername

# Optional Twitter username
#twitter: twitterusername

# Optional Mastodon server url, and username / handle.
#mastodon:
#  url: https://mastodon.social/@mastodonusername
#  name: mastodonusername
redirect_from: '/authors/hgandhi/'
---

Hariharan Gandhi is a Distributed Systems engineer. Currently serving as the Product Owner for Logging Services at SAP's Business Technology Platform, Hariharan brings over 11 years of experience in the Software Industry, with a steadfast focus on SAP’s logging/observability needs for the past 8 years. In his previous role as an Architect, Hariharan spearheaded the replatforming of OpenSearch-based logging services to Kubernetes at scale. He holds a Master’s degree in Distributed Software Systems from the Technical University of Darmstadt. He is motivated to share his learnings and insights on leveraging OpenSearch for scalable logging services.