---
layout: post
title: " Feb 17th Status Update"
date: 2017-02-17 16:54:46
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
      <td>Pipeline has been run E2E. We are seeing issues with getting data from the API Uptime and During Upgrade tests. Currently working on resolving those.</td>
      <td>None</td>
    </tr>
    <tr>
      <td>Continuous Performance Benchmarking</td>
      <td>Documented benchmarking scenarios (I'll send out the link once we put it up in a repo). Got an ELK stack up and running to which we can send the benchmarking test results to.</td>
      <td>Waiting for the pipeline to run a few times before we integrate this into the CI pipeline.</td>
    </tr>
    <tr>
      <td>Multi-node Devstack in LXC Containers POC</td>
      <td>Continued working on adding Cinder to the POC: <a href="https://github.com/osic/devstack-lxc">LXC POC</a>. Beginning to work on creating the spec for this to add this functionality into Grenade.</td>
      <td>None</td>
    </tr>
    <tr>
      <td>Grenade - replace Simple Upgrade with Rolling Upgrade</td>
      <td>Created the spec for this: <a href="https://review.openstack.org/#/c/433216/">Rolling Upgrade spec</a></td>
      <td>None</td>
    </tr>
    <tr>
      <td>Grenade tool updates</td>
      <td>Addressing comments for both the spec and POC:<a href="https://review.openstack.org/#/c/422170/">API Uptime Spec</a>, <a href="https://review.openstack.org/#/c/427529">API Uptime POC</a>.</td>
      <td>None</td>
    </tr>
    <tr>
      <td>Community</td>
      <td>Grenade - Cas and Luz talked to a Grenade team member (Dean Toyer) about the specs that our team is adding to address questions/concerns. Stepler - Figured out next step for Stepler, which will be that Isaac will be the main POC. For now, the QE team will not be directly involved.</td>
      <td>None</td>
    </tr>
  </table>

[hampden]: https://github.com/jekyll/jekyll
