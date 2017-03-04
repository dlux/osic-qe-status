---
layout: post
title: "Mar 3rd Status Update"
date: 2017-03-03 16:54:46
author: Admin
categories:
- status
- Pike
- Feb17
img: openstack_updated.png
thumb: openstack_tn.jpg
---

<table>
    <tr>
      <th>Epic</th>
      <th>Accomplishment</th>
      <th>Blockers</th>
    </tr>
    <tr>
      <td>Multi-node Grenade Gate Job Setup</td>
      <td>Continuing to monitor reviews and update PRs accordingly <a href="https://review.openstack.org/#/c/426428/">Glance</a> (waiting to get merged), <a href="https://review.openstack.org/#/c/411982/">Swift</a> (waiting to get merged), <a href="https://review.openstack.org/#/c/407428/">Keystone</a> (merged).</td>
      <td>None</td>
    </tr>
    <tr>
      <td>Rolling and Zero Downtime Testing</td>
      <td>Pipeline has been running consistently. The tests are running and we are collecting data in Kibana: <a href="http://172.99.106.115:5601/goto/3b2a4cc78c7b96519e7d690c33581551">Kibana link</a>. We plan on beginning the work of moving to Newton -> Ocata on Monday. We will continue to collect results throughout the weekend for Mikata -> Newton.</td>
      <td>None</td>
    </tr>
    <tr>
      <td>Continuous Performance Benchmarking</td>
      <td>Rally tests have been integrated into the CI pipeline. We see an issue with one of the tests, we are working on resolving it.</td>
      <td>None</td>
    </tr>
    <tr>
      <td>Multi-node Devstack in LXC Containers POC</td>
      <td>Work for Grenade is abandoned due to feedback from PTG that the work that we'd like to do is out of scope for Grenade.</td>
      <td>None</td>
    </tr>
    <tr>
      <td>Grenade - replace Simple Upgrade with Rolling Upgrade</td>
      <td>Work for Grenade is abandoned due to feedback from PTG that the work that we'd like to do is out of scope for Grenade.</td>
      <td>None</td>
    </tr>
    <tr>
      <td>Grenade tool updates</td>
      <td>Work for Grenade is abandoned due to feedback from PTG that the work that we'd like to do is out of scope for Grenade.</td>
      <td>None</td>
    </tr>
    <tr>
      <td>Community</td>
      <td>We are working on figuring out what our Pike priorities should be. Etherpad that contains the options we have is here: <a href="https://etherpad.openstack.org/p/PTG_Pike_Updates">Pike priorities</a>. The team will be working with the upstream QA team to see what is feasible.</td>
      <td>None</td>
    </tr>
  </table>

[hampden]: https://github.com/jekyll/jekyll
