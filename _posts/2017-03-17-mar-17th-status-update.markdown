---
layout: post
title: "Mar 17th Status Update"
date: 2017-03-17 16:54:46
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
      <td>The CI pipeline runs successfully upto the upgrade script. However, the tempest smoke test fails after that because Nova does not restart automatically. A bug has been filed with OSA: <a href="https://bugs.launchpad.net/openstack-ansible/+bug/1673889">OSA Bug</a>.</td>
      <td>OSA bug</td>
    </tr>
    <tr>
      <td>Kibana Visualization Updates</td>
      <td>Visualizations have been updated. Please take a look and let us know what you think! <a href="http://172.99.106.115:5601/app/kibana#/dashboard/OSA-BME-Upgrade-Embed">Kibana for CI pipeline (currently showing M->N)</a>.</td>
      <td>None</td>
    </tr>
    <tr>
      <td>Upgrade Testing</td>
      <td>We are close to the final draft of the Upgrade test tool. Please take a look and provide feedback. <a href="https://github.com/osic/qe-docs/blob/master/upgrade_test_tool_reqs.rst">Upgrade test tool</a>. We will meet early next week to decide our Pike priorities.</td>
      <td>Would like Kenny and Sonu to give the green light.</td>
    </tr>
    <tr>
      <td>Interoperability Work</td>
      <td>Interop-wg: Got a list of tempest tests that possibly need a non-admin version added to run them.   Interop-workloads/RefStack: Pushed a couple of patches to <a href="docs.openstack.org">docs.openstack.org</a>.</td>
      <td>None</td>
    </tr>
  </table>

  <p>* We are still in the middle of figuring out what our Pike priorities will be. Once we figure out the details for the Upgrade test tool, we should be ready to finalize the priorities.</p>

[hampden]: https://github.com/jekyll/jekyll
