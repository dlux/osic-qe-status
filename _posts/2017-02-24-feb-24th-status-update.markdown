---
layout: post
title: " Feb 24th Status Update"
date: 2017-02-24 16:54:46
author: Admin
categories:
- status
- Pike
- Feb17
img: post03.jpg
thumb: thumb03.jpg
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
      <td>Pipeline has been running consistently. The tests are running and we are collecting data in Kibana: <a href="http://bit.ly/2lSnES0">Kibana link</a>. However, we see issues when running smoke tests and the during nova tests after the upgrades. Currently working on resolving those. We will continue debugging in the upcoming week and will reconvene at the end of the next week to finalize the decision to move onto Newton -> Ocata.</td>
      <td>None</td>
    </tr>
    <tr>
      <td>Continuous Performance Benchmarking</td>
      <td>Rally tests needed some configuration changes to be integrated into the pipeline. These should be integrated next week.</td>
      <td>None</td>
    </tr>
    <tr>
      <td>Multi-node Devstack in LXC Containers POC</td>
      <td>Update from PTG is that Grenade does not want to implement this solution in this project so we will let go of this effort. Details to come from Luz/Cas.</td>
      <td>None</td>
    </tr>
    <tr>
      <td>Grenade - replace Simple Upgrade with Rolling Upgrade</td>
      <td>Waiting for the spec to be merged: <a href="https://review.openstack.org/#/c/433216/">Rolling Upgrade spec</a></td>
      <td>None</td>
    </tr>
    <tr>
      <td>Grenade tool updates</td>
      <td>Addressing comments for both the spec and POC:<a href="https://review.openstack.org/#/c/422170/">API Uptime Spec</a> (waiting to get merged), <a href="https://review.openstack.org/#/c/427529">API Uptime POC</a> (waiting to get merged).</td>
      <td>None</td>
    </tr>
    <tr>
      <td>Community</td>
      <td>Cas, Dan, Luz and Steve attended the PTG this week. They had the proposed discussions which went well and also came back with more possible projects to work on.</td>
      <td>None</td>
    </tr>
  </table>

<p> * Pike has officially started, however we are still finalizing our Pike objectives. We plan on finalizing those by the end of next week. So for this week, we are reporting against Ocata objectives. </p>

[hampden]: https://github.com/jekyll/jekyll
