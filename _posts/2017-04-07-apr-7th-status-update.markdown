---
layout: post
title: "Apr 7th Status Update"
date: 2017-04-07 16:54:46
author: Admin
categories:
- status
- Pike
- Apr17
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
      <td>The bugs from last week have been fixed. We began to experience hardware issues which have now been resolved as well. We are now seeing ansible failures. We're continuing to take a look into this.</td>
      <td>None</td>
    </tr>
    <tr>
      <td>Kibana Visualization Updates</td>
      <td>Got more feedback, updating the visualizations accordingly. <a href="http://172.99.106.115:5601/app/kibana#/dashboard/OSA-BME-Upgrade-Embed">Kibana for CI pipeline (currently showing M->N)</a>.</td>
      <td>None</td>
    </tr>
    <tr>
      <td>Cragsman - Upgrade Testing Tool</td>
      <td>Spec has been created for the Upgrade Testing tool. Currently working through the feedback we're getting on it. We renamed the tool to Cragsman - Sherpa. <a href="https://review.openstack.org/#/c/449295/">Sherpa/Upgrade test tool spec</a>.</td>
      <td>None</td>
    </tr>
    <tr>
      <td>Interoperability Work</td>
      <td>Interop-workloads/RefStack: We have an environment on Cloud1. It has run out of IPv4 addresses. We will start to use IPv6 addresses.</td>
      <td>None</td>
    </tr>
    <tr>
      <td>OS Health Dashboard</td>
      <td>Working to get OSA onto the dashboard - we have patches up to get the subunit report on a given path.</td>
      <td>None</td>
    </tr>
  </table>

[hampden]: https://github.com/jekyll/jekyll
