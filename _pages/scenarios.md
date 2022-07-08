---
permalink: /scenarios/
title: Scenarios
subtitle: 'We apply the Linear Social MDP in a 10x10 grid-world environment, for 2 robots with five actions (move in one of four directions or stay in place), three physical goals (watering the tree, adding logs to a fire and sawing logs), three locations (tree, fire, and saw), and two objects (a log, and a water can). In addition to the three physical goals, any combination of physical goals is possible, along with one of five social goals (cooperation, conflict, competition, coercion, or exchange) each related to one or more physical goals. Robots can move objects by pushing them. In all the experiments each robot always attempts to achieve two physical goals while engaging in social interactions relative to those goals. Those social interactions are conditioned on the physical goals of the other agent; or rather, on what the first agent thinks the second agent is doing. Despite having a fully-observable environment, agents do not have access to each others internal states and must estimate each others goals. We explored every social scenario in this environment. The Yellow robot always had at most one social interaction, while the Red robot always had at most two social interactions. This resulted in 6x6x5 = 180 scenarios (eliminating the cause where neither agent considers any social interaction).'
---

<table style="text-align:center">
<thead>
<tr>
    <th style="text-align:center">Scenario #</th>
    <th colspan="4" style="text-align:center; background: orange">Yellow Robot</th>
    <th colspan="4" style="text-align:center; background: red">Red Robot</th>
</tr>
</thead>
<tbody><tr>
<td> </td>
    <td><b>Social Goal 1</b></td>
    <td><b>Social Goal 2</b></td>
    <td><b>Physical Goal 1</b></td>
    <td><b>Physical Goal 2</b></td>
    <td><b>Social Goal 1</b></td>
    <td><b>Social Goal 2</b></td>
    <td><b>Physical Goal 1</b></td>
    <td><b>Physical Goal 2</b></td>
</tr>

<tr>
    <td><A href="/scenarios/scenario-77">Scenario 77</A></td>
    <td>Compete on Tree</td>
    <td>None</td>
    <td>Tree</td>
    <td>Saw</td>
    <td>Cooperate on Tree</td>
    <td>Exchange on Saw</td>
    <td>Tree</td>
    <td>Fire</td>
</tr>
    

</tbody></table>

---
