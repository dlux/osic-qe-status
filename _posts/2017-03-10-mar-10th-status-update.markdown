---
layout: post
title: "Mar 10th Status Update"
date: 2017-03-10 16:54:46
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
      <td>Rolling and Zero Downtime Testing</td>
      <td>BME has been upgraded to Ubuntu 16.04. Newton deploys successfully. The upgrade is not working because of this bug: <a href="https://bugs.launchpad.net/openstack-ansible/+bug/1667103">Upgrade Bug</a>. The bug is currently being worked on.</td>
      <td>Upgrade bug</td>
    </tr>
    <tr>
      <td>Kibana Visualization Updates</td>
      <td>The team is updating the Kibana graphs for the CI pipeline to make it easier to read and show the information that will be most beneficial. <a href="http://172.99.106.115:5601/app/kibana#/dashboard/New-Dashboard-OSA">Kibana for CI pipeline (currently showing M->N)</a>.</td>
      <td>None</td>
    </tr>
    <tr>
      <td>Upgrade Testing</td>
      <td>Since we will not be updating Grenade anymore, the team will create a new upstream project. The requirements/details are currently being hashed out. <a href="https://github.com/osic/qe-docs/blob/master/upgrade_test_tool_reqs.rst">Upgrade test tool</a>.</td>
      <td>None</td>
    </tr>
    <tr>
      <td>Interoperability Work</td>
      <td>Interop-wg: Started inital work to score Keystone capabilities. Interop-workloads: Submitted an OSIC cloud request to get a project to test Kubernetes workload.</td>
      <td>None</td>
    </tr>
    <tr>
      <td>Stestr</td>
      <td>Put in a few PRs for stestr. <a href="http://stestr.readthedocs.io/en/latest/index.html">Stestr Details</a>.</td>
      <td>None</td>
    </tr>
    <tr>
      <td>OS Health Dashboard</td>
      <td>Beginning to look at the OS Health Dashboard, where we would like to send the results for the Grenade tests that run in periodic gate jobs.</td>
      <td>None</td>
    </tr>
  </table>

  <p>* We are still in the middle of figuring out what our Pike priorities will be. Once we figure out the details for the Upgrade test tool, we should be ready to finalize the priorities.</p>

[hampden]: https://github.com/jekyll/jekyll
