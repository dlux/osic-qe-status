---
layout: post
title: "Mar 24th Status Update"
date: 2017-03-24 16:54:46
author: Admin
categories:
- status
- Pike
- Mar17
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
      <td>The CI pipeline runs successfully upto the upgrade script. Working through two bugs 1) Galera bug and 2) OSA Nova services bug: <a href="https://bugs.launchpad.net/openstack-ansible/+bug/1673889">OSA Bug</a>.</td>
      <td>Galera bug, OSA bug</td>
    </tr>
    <tr>
      <td>Kibana Visualization Updates</td>
      <td>Got feedback from Kenny, will update visualizations this coming week. <a href="http://172.99.106.115:5601/app/kibana#/dashboard/OSA-BME-Upgrade-Embed">Kibana for CI pipeline (currently showing M->N)</a>.</td>
      <td>None</td>
    </tr>
    <tr>
      <td>Sherpa - Upgrade Testing Tool</td>
      <td>Spec has been created for the Upgrade Testing tool. We also have a name for the tool - Sherpa. <a href="https://review.openstack.org/#/c/449295/">Sherpa/Upgrade test tool spec</a>.</td>
      <td>None</td>
    </tr>
    <tr>
      <td>Interoperability Work</td>
      <td>Interop-workloads/RefStack: We have an environment on Cloud1. Will start testing kubernetes on it next week.</td>
      <td>None</td>
    </tr>
    <tr>
      <td>OS Health Dashboard</td>
      <td>Working to get OSA onto the dashboard - we have patches up to get the subunit report on a given path.</td>
      <td>None</td>
    </tr>
  </table>

[hampden]: https://github.com/jekyll/jekyll
