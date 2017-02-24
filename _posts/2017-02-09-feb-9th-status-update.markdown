---
layout: post
title: " Feb 9th Status Update"
date: 2017-02-09 16:54:46
author: Admin
categories:
- status
- Ocata
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
    <td>Continuing to monitor reviews and update PRs accordingly <a href="https://review.openstack.org/#/c/426428/">Glance</a>, <a href="https://review.openstack.org/#/c/411982/">Swift</a>, <a href="https://review.openstack.org/#/c/407428/">Keystone</a> (merged).</td>
    <td>None</td>
  </tr>
  <tr>
    <td>Rolling and Zero Downtime Testing</td>
    <td>Upgrade is now working. Tests have been manually run. Will run the pipeline E2E today!</td>
    <td>None</td>
  </tr>
  <tr>
    <td>Continuous Performance Benchmarking</td>
    <td>Benchmarking tests are ready to be integrated into the pipeline.</td>
    <td>Waiting for the pipeline to run a few times before we integrate this piece.</td>
  </tr>
  <tr>
    <td>Multi-node Devstack in LXC Containers POC</td>
    <td>Adding Cinder to the POC: <a href="https://github.com/osic/devstack-lxc">LXC POC</a>.</td>
    <td>Began creating the experimental gate for this, however it is different from other gate jobs and will require some more research before it is ready.</td>
  </tr>
  <tr>
    <td>Grenade - replace Simple Upgrade with Rolling Upgrade</td>
    <td>Continuing to work on the spec for this.</td>
    <td>None</td>
  </tr>
  <tr>
    <td>Grenade tool updates</td>
    <td>Working on writing the spec for this and continuing to update POC for API uptime according to feedback: <a href="https://review.openstack.org/#/c/427529">API Uptime POC</a>.</td>
    <td>None</td>
  </tr>
</table>

[hampden]: https://github.com/jekyll/jekyll
