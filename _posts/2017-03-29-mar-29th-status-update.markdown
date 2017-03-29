---
layout: post
title: "Mar 29th Status Update"
date: 2017-03-29 16:37
author: Admin
categories:
- status
- Pike
- Mar29
img: openstack_updated.png
thumb: openstack_tn.jpg
---

  <table>
    <tr>
      <th>Items Being Worked On</th>
      <th>Accomplishment</th>
      <th>Blockers</th>
    </tr>
    <tr>
      <td>Multi-node Grenade Gate Job Setup</td>
      <td>Continuing to monitor reviews and update PRs accordingly <a href="https://review.openstack.org/#/c/426428/">Glance</a> (waiting to get merged), <a href="https://review.openstack.org/#/c/411982/">Swift</a> (waiting to get merged), <a href="https://review.openstack.org/#/c/407428/">Keystone</a> (merged).</td>
      <td>None</td>
    </tr>
    <tr>
      <td>BME Upgrade Testing CI Pipeline</td>
      <td>The CI pipeline runs successfully upto the upgrade script. Worked through prior Galera bug.  It is resolved and tested. Currently still blocked by OSA Nova services bug: <a href="https://bugs.launchpad.net/openstack-ansible/+bug/1673889">OSA Bug</a>.</td>
      <td>OSA bug</td>
    </tr>
    <tr>
      <td>Kibana Visualization Updates</td>
      <td>Got feedback from Kenny, John Garbutt, and Raj will update visualizations this coming week. <a href="http://172.99.106.115:5601/app/kibana#/dashboard/OSA-BME-Upgrade-Embed">Kibana for CI pipeline (currently showing M->N)</a>.</td>
      <td>None</td>
    </tr>
    <tr>
      <td>Sherpa  - Upgrade Testing Tool</td>
      <td>Luz and team will bring up <a href= "https://review.openstack.org/#/c/449295/">Sherpa spec</a> to the QA community in Thursdays irc meeting. The hope is to get more eyes on this spec and get there feedback and buy-in for our future work efforts towards Sherpa.  Also team has selected <a href=https://etherpad.openstack.org/p/qe-sherpa-design<Sherpa completion goals for Ocata</a>.
      </td>
      <td>None</td>
    </tr>
    <tr>
      <td>Interoperability Work</td>
      <td>interop-workloads: Got project on cloud1. Will start testing Kubernetes workload sometime this week.
         Interop-working group: Working on Keystone scoring – waiting on PTL to get key capabilities. Luz need to get a list based on the API to cross check with PTL list. Then score based on external input and 12 defcore criteria
         Reftstack: submitted a couple of patches regarding py35 community goal.
      </td>
      <td>None</td>
    </tr>
    <tr>
      <td>OS Health Dashboard</td>
      <td>Team is focusing on answering the following: 
      a. Why OSA does not appear on health dashboard Working on 2 patches to fix it. Related to tempest execution, collecting subunit log files, gate job picking the logs and placing them in the right location.
      b. Can we notify by email or irc bot when a periodic job fails?  As a result of notification mechanisms investigation and chatting on infra channel. It is not technically possible. We are dropping this effort to concentrate on health dashboard.  In the future, if this capability is still needed, we might want to explore improving existing zuul reporter plugin to support parametrized email (vs fixed).

      <a href= https://01.org/jira/browse/OSIC-1276?focusedCommentId=30403&page=com.atlassian.jira.plugin.system.issuetabpanels%3Acomment-tabpanel#comment-30403>Link to Jira story</a>
      </td>
      <td>None</td>
    </tr>
  </table>

[hampden]: https://github.com/jekyll/jekyll
