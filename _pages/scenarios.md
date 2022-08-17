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
        <td><A href="/scenarios/scenario-1">Scenario 1</A></td>
<td>Cooperate on Fire</td>
<td>None</td>
<td>Saw</td>
<td>Tree</td>
<td>Cooperate on Saw</td>
<td>Cooperate on Tree</td>
<td>Fire</td>
<td>Tree</td>
</tr>
<tr>
    <td><A href="/scenarios/scenario-2">Scenario 2</A></td>
    <td>Cooperate on Fire</td>
    <td>None</td>
    <td>Tree</td>
    <td>Saw</td>
    <td>Cooperate on Tree</td>
    <td>Conflict on Saw</td>
    <td>Fire</td>
    <td>Tree</td>
</tr>
<tr>
    <td><A href="/scenarios/scenario-3">Scenario 3</A></td>
    <td>Cooperate on Fire</td>
    <td>None</td>
    <td>Tree</td>
    <td>Saw</td>
    <td>Cooperate on Tree</td>
    <td>Compete on Saw</td>
    <td>Fire</td>
    <td>Tree</td>
</tr>
<tr>
    <td><A href="/scenarios/scenario-4">Scenario 4</A></td>
    <td>Cooperate on Fire</td>
    <td>None</td>
    <td>Tree</td>
    <td>Saw</td>
    <td>Cooperate on Tree</td>
    <td>Coercion on Saw</td>
    <td>Fire</td>
    <td>Tree</td>
</tr>
<tr>
    <td><A href="/scenarios/scenario-5">Scenario 5</A></td>
    <td>Cooperate on Fire</td>
    <td>None</td>
    <td>Saw</td>
    <td>Tree</td>
    <td>Cooperate on Saw</td>
    <td>Exchange on Tree</td>
    <td>Fire</td>
    <td>Tree</td>
</tr>
<tr>
    <td><A href="/scenarios/scenario-6">Scenario 6</A></td>
    <td>Cooperate on Fire</td>
    <td>None</td>
    <td>Tree</td>
    <td>Saw</td>
    <td>Cooperate on Tree</td>
    <td>None on Saw</td>
    <td>Fire</td>
    <td>Tree</td>
</tr>
<tr>
    <td><A href="/scenarios/scenario-7">Scenario 7</A></td>
    <td>Cooperate on Tree</td>
    <td>None</td>
    <td>Tree</td>
    <td>Saw</td>
    <td>Conflict on Tree</td>
    <td>Cooperate on Saw</td>
    <td>Tree</td>
    <td>Fire</td>
</tr>
<tr>
    <td><A href="/scenarios/scenario-8">Scenario 8</A></td>
    <td>Cooperate on Tree</td>
    <td>None</td>
    <td>Tree</td>
    <td>Saw</td>
    <td>Conflict on Tree</td>
    <td>Conflict on Saw</td>
    <td>Tree</td>
    <td>Fire</td>
</tr>
<tr>
    <td><A href="/scenarios/scenario-9">Scenario 9</A></td>
    <td>Cooperate on Fire</td>
    <td>None</td>
    <td>Tree</td>
    <td>Saw</td>
    <td>Conflict on Tree</td>
    <td>Compete on Saw</td>
    <td>Fire</td>
    <td>Tree</td>
</tr>
<tr>
    <td><A href="/scenarios/scenario-10">Scenario 10</A></td>
    <td>Cooperate on Tree</td>
    <td>None</td>
    <td>Tree</td>
    <td>Saw</td>
    <td>Conflict on Tree</td>
    <td>Coercion on Saw</td>
    <td>Tree</td>
    <td>Fire</td>
</tr>
<tr>
    <td><A href="/scenarios/scenario-11">Scenario 11</A></td>
    <td>Cooperate on Tree</td>
    <td>None</td>
    <td>Tree</td>
    <td>Saw</td>
    <td>Conflict on Tree</td>
    <td>Exchange on Saw</td>
    <td>Tree</td>
    <td>Fire</td>
</tr>
<tr>
    <td><A href="/scenarios/scenario-12">Scenario 12</A></td>
    <td>Cooperate on Fire</td>
    <td>None</td>
    <td>Tree</td>
    <td>Saw</td>
    <td>Conflict on Tree</td>
    <td>None on Saw</td>
    <td>Fire</td>
    <td>Tree</td>
</tr>
<tr>
    <td><A href="/scenarios/scenario-13">Scenario 13</A></td>
    <td>Cooperate on Tree</td>
    <td>None</td>
    <td>Tree</td>
    <td>Saw</td>
    <td>Compete on Tree</td>
    <td>Cooperate on Saw</td>
    <td>Tree</td>
    <td>Fire</td>
</tr>
<tr>
    <td><A href="/scenarios/scenario-14">Scenario 14</A></td>
    <td>Cooperate on Fire</td>
    <td>None</td>
    <td>Tree</td>
    <td>Saw</td>
    <td>Compete on Tree</td>
    <td>Conflict on Saw</td>
    <td>Fire</td>
    <td>Tree</td>
</tr>
<tr>
    <td><A href="/scenarios/scenario-15">Scenario 15</A></td>
    <td>Cooperate on Tree</td>
    <td>None</td>
    <td>Tree</td>
    <td>Saw</td>
    <td>Compete on Tree</td>
    <td>Compete on Saw</td>
    <td>Tree</td>
    <td>Fire</td>
</tr>
<tr>
    <td><A href="/scenarios/scenario-16">Scenario 16</A></td>
    <td>Cooperate on Fire</td>
    <td>None</td>
    <td>Tree</td>
    <td>Saw</td>
    <td>Compete on Tree</td>
    <td>Coercion on Saw</td>
    <td>Fire</td>
    <td>Tree</td>
</tr>
<tr>
    <td><A href="/scenarios/scenario-17">Scenario 17</A></td>
    <td>Cooperate on Fire</td>
    <td>None</td>
    <td>Tree</td>
    <td>Saw</td>
    <td>Compete on Tree</td>
    <td>Exchange on Saw</td>
    <td>Fire</td>
    <td>Tree</td>
</tr>
<tr>
    <td><A href="/scenarios/scenario-18">Scenario 18</A></td>
    <td>Cooperate on Fire</td>
    <td>None</td>
    <td>Tree</td>
    <td>Saw</td>
    <td>Compete on Tree</td>
    <td>None on Saw</td>
    <td>Fire</td>
    <td>Tree</td>
</tr>
<tr>
    <td><A href="/scenarios/scenario-19">Scenario 19</A></td>
    <td>Cooperate on Tree</td>
    <td>None</td>
    <td>Tree</td>
    <td>Saw</td>
    <td>Coercion  on Tree</td>
    <td>Cooperate on Saw</td>
    <td>Tree</td>
    <td>Tree</td>
</tr>
<tr>
    <td><A href="/scenarios/scenario-20">Scenario 20</A></td>
    <td>Cooperate on Fire</td>
    <td>None</td>
    <td>Tree</td>
    <td>Saw</td>
    <td>Coercion on Tree</td>
    <td>Conflict on Saw</td>
    <td>Fire</td>
    <td>Tree</td>
</tr>
<tr>
    <td><A href="/scenarios/scenario-21">Scenario 21</A></td>
    <td>Cooperate on Fire</td>
    <td>None</td>
    <td>Tree</td>
    <td>Saw</td>
    <td>Coercion on Tree</td>
    <td>Compete on Saw</td>
    <td>Fire</td>
    <td>Tree</td>
</tr>
<tr>
    <td><A href="/scenarios/scenario-22">Scenario 22</A></td>
    <td>Cooperate on Fire</td>
    <td>None</td>
    <td>Tree</td>
    <td>Saw</td>
    <td>Coercion on Tree</td>
    <td>Coercion on Saw</td>
    <td>Fire</td>
    <td>Tree</td>
</tr>
<tr>
    <td><A href="/scenarios/scenario-23">Scenario 23</A></td>
    <td>Cooperate on Fire</td>
    <td>None</td>
    <td>Tree</td>
    <td>Saw</td>
    <td>Coercion on Tree</td>
    <td>Exchange on Saw</td>
    <td>Fire</td>
    <td>Tree</td>
</tr>
<tr>
    <td><A href="/scenarios/scenario-24">Scenario 24</A></td>
    <td>Cooperate on Fire</td>
    <td>None</td>
    <td>Tree</td>
    <td>Saw</td>
    <td>Coercion on Tree</td>
    <td>None on Saw</td>
    <td>Fire</td>
    <td>Tree</td>
</tr>
<tr>
    <td><A href="/scenarios/scenario-25">Scenario 25</A></td>
    <td>Cooperate on Fire</td>
    <td>None</td>
    <td>Tree</td>
    <td>Saw</td>
    <td>Exchange on Tree</td>
    <td>Cooperate on Saw</td>
    <td>Fire</td>
    <td>Tree</td>
</tr>
<tr>
    <td><A href="/scenarios/scenario-26">Scenario 26</A></td>
    <td>Cooperate on Tree</td>
    <td>None</td>
    <td>Saw</td>
    <td>Tree</td>
    <td>Exchange on Saw</td>
    <td>Conflict on Tree</td>
    <td>Tree</td>
    <td>Fire</td>
</tr>
<tr>
    <td><A href="/scenarios/scenario-27">Scenario 27</A></td>
    <td>Cooperate on Fire</td>
    <td>None</td>
    <td>Tree</td>
    <td>Saw</td>
    <td>Exchange on Tree</td>
    <td>Compete on Saw</td>
    <td>Fire</td>
    <td>Tree</td>
</tr>
<tr>
    <td><A href="/scenarios/scenario-28">Scenario 28</A></td>
    <td>Cooperate on Fire</td>
    <td>None</td>
    <td>Tree</td>
    <td>Saw</td>
    <td>Exchange on Tree</td>
    <td>Coercion on Saw</td>
    <td>Fire</td>
    <td>Tree</td>
</tr>
<tr>
    <td><A href="/scenarios/scenario-29">Scenario 29</A></td>
    <td>Cooperate on Fire</td>
    <td>None</td>
    <td>Tree</td>
    <td>Saw</td>
    <td>Exchange on Tree</td>
    <td>Exchange on Saw</td>
    <td>Fire</td>
    <td>Tree</td>
</tr>
<tr>
    <td><A href="/scenarios/scenario-30">Scenario 30</A></td>
    <td>Cooperate on Fire</td>
    <td>None</td>
    <td>Tree</td>
    <td>Saw</td>
    <td>Exchange on Tree</td>
    <td>None on Saw</td>
    <td>Fire</td>
    <td>Tree</td>
</tr>
<tr>
    <td><A href="/scenarios/scenario-31">Scenario 31</A></td>
    <td>Cooperate on Fire</td>
    <td>None</td>
    <td>Tree</td>
    <td>Saw</td>
    <td>Neutral on Tree</td>
    <td>Cooperate on Saw</td>
    <td>Fire</td>
    <td>Tree</td>
</tr>
<tr>
    <td><A href="/scenarios/scenario-32">Scenario 32</A></td>
    <td>Cooperate on Fire</td>
    <td>None</td>
    <td>Saw</td>
    <td>Tree</td>
    <td>Neutral on Saw</td>
    <td>Conflict on Tree</td>
    <td>Fire</td>
    <td>Tree</td>
</tr>
<tr>
    <td><A href="/scenarios/scenario-33">Scenario 33</A></td>
    <td>Cooperate on Fire</td>
    <td>None</td>
    <td>Tree</td>
    <td>Saw</td>
    <td>Neutral on Tree</td>
    <td>Compete on Saw</td>
    <td>Fire</td>
    <td>Tree</td>
</tr>
<tr>
    <td><A href="/scenarios/scenario-34">Scenario 34</A></td>
    <td>Cooperate on Fire</td>
    <td>None</td>
    <td>Tree</td>
    <td>Saw</td>
    <td>Neutral on Tree</td>
    <td>Coercion on Saw</td>
    <td>Fire</td>
    <td>Tree</td>
</tr>
<tr>
    <td><A href="/scenarios/scenario-35">Scenario 35</A></td>
    <td>Cooperate on Fire</td>
    <td>None</td>
    <td>Saw</td>
    <td>Tree</td>
    <td>Neutral on Saw</td>
    <td>Exchange on Tree</td>
    <td>Fire</td>
    <td>Tree</td>
</tr>
<tr>
    <td><A href="/scenarios/scenario-36">Scenario 36</A></td>
    <td>Cooperate on Fire</td>
    <td>None</td>
    <td>Tree</td>
    <td>Saw</td>
    <td>Neutral on Tree</td>
    <td>None on Saw</td>
    <td>Fire</td>
    <td>Tree</td>
</tr>
<tr>
    <td><A href="/scenarios/scenario-37">Scenario 37</A></td>
    <td>Conflict on Tree</td>
    <td>None</td>
    <td>Saw</td>
    <td>Tree</td>
    <td>Cooperate on Saw</td>
    <td>Cooperate on Tree</td>
    <td>Tree</td>
    <td>Fire</td>
</tr>
<tr>
    <td><A href="/scenarios/scenario-38">Scenario 38</A></td>
    <td>Conflict on Fire</td>
    <td>None</td>
    <td>Saw</td>
    <td>Tree</td>
    <td>Cooperate on Saw</td>
    <td>Conflict on Tree</td>
    <td>Fire</td>
    <td>Tree</td>
</tr>
<tr>
    <td><A href="/scenarios/scenario-39">Scenario 39</A></td>
    <td>Conflict on Fire</td>
    <td>None</td>
    <td>Saw</td>
    <td>Tree</td>
    <td>Cooperate on Saw</td>
    <td>Compete on Tree</td>
    <td>Fire</td>
    <td>Tree</td>
</tr>
<tr>
    <td><A href="/scenarios/scenario-40">Scenario 40</A></td>
    <td>Conflict on Fire</td>
    <td>None</td>
    <td>Tree</td>
    <td>Saw</td>
    <td>Cooperate on Tree</td>
    <td>Coercion on Saw</td>
    <td>Fire</td>
    <td>Tree</td>
</tr>
<tr>
    <td><A href="/scenarios/scenario-41">Scenario 41</A></td>
    <td>Conflict on Fire</td>
    <td>None</td>
    <td>Tree</td>
    <td>Saw</td>
    <td>Cooperate on Tree</td>
    <td>Exchange on Saw</td>
    <td>Fire</td>
    <td>Tree</td>
</tr>
<tr>
    <td><A href="/scenarios/scenario-42">Scenario 42</A></td>
    <td>Conflict on Tree</td>
    <td>None</td>
    <td>Saw</td>
    <td>Tree</td>
    <td>Cooperate on Saw</td>
    <td>None on Tree</td>
    <td>Tree</td>
    <td>Fire</td>
</tr>
<tr>
    <td><A href="/scenarios/scenario-43">Scenario 43</A></td>
    <td>Conflict on Tree</td>
    <td>None</td>
    <td>Saw</td>
    <td>Tree</td>
    <td>Conflict on Saw</td>
    <td>Cooperate on Tree</td>
    <td>Tree</td>
    <td>Fire</td>
</tr>
<tr>
    <td><A href="/scenarios/scenario-44">Scenario 44</A></td>
    <td>Conflict on Tree</td>
    <td>None</td>
    <td>Saw</td>
    <td>Tree</td>
    <td>Conflict on Saw</td>
    <td>Conflict on Tree</td>
    <td>Tree</td>
    <td>Fire</td>
</tr>
<tr>
    <td><A href="/scenarios/scenario-45">Scenario 45</A></td>
    <td>Conflict on Tree</td>
    <td>None</td>
    <td>Saw</td>
    <td>Tree</td>
    <td>Conflict on Saw</td>
    <td>Compete on Tree</td>
    <td>Tree</td>
    <td>Fire</td>
</tr>
<tr>
    <td><A href="/scenarios/scenario-46">Scenario 46</A></td>
    <td>Conflict on Tree</td>
    <td>None</td>
    <td>Saw</td>
    <td>Tree</td>
    <td>Conflict on Saw</td>
    <td>Coercion on Tree</td>
    <td>Tree</td>
    <td>Fire</td>
</tr>
<tr>
    <td><A href="/scenarios/scenario-47">Scenario 47</A></td>
    <td>Conflict on Fire</td>
    <td>None</td>
    <td>Saw</td>
    <td>Tree</td>
    <td>Conflict on Saw</td>
    <td>Exchange on Tree</td>
    <td>Fire</td>
    <td>Tree</td>
</tr>
<tr>
    <td><A href="/scenarios/scenario-48">Scenario 48</A></td>
    <td>Conflict on Tree</td>
    <td>None</td>
    <td>Saw</td>
    <td>Tree</td>
    <td>Conflict on Saw</td>
    <td>None on Tree</td>
    <td>Tree</td>
    <td>Fire</td>
</tr>
<tr>
    <td><A href="/scenarios/scenario-49">Scenario 49</A></td>
    <td>Conflict on Fire</td>
    <td>None</td>
    <td>Saw</td>
    <td>Tree</td>
    <td>Compete on Saw</td>
    <td>Cooperate on Tree</td>
    <td>Fire</td>
    <td>Tree</td>
</tr>
<tr>
    <td><A href="/scenarios/scenario-50">Scenario 50</A></td>
    <td>Conflict on Fire</td>
    <td>None</td>
    <td>Tree</td>
    <td>Saw</td>
    <td>Compete on Tree</td>
    <td>Conflict on Saw</td>
    <td>Fire</td>
    <td>Tree</td>
</tr>
<tr>
    <td><A href="/scenarios/scenario-51">Scenario 51</A></td>
    <td>Conflict on Tree</td>
    <td>None</td>
    <td>Tree</td>
    <td>Saw</td>
    <td>Compete on Tree</td>
    <td>Compete on Saw</td>
    <td>Tree</td>
    <td>Fire</td>
</tr>
<tr>
    <td><A href="/scenarios/scenario-52">Scenario 52</A></td>
    <td>Conflict on Fire</td>
    <td>None</td>
    <td>Tree</td>
    <td>Saw</td>
    <td>Compete on Tree</td>
    <td>Coercion on Saw</td>
    <td>Fire</td>
    <td>Tree</td>
</tr>
<tr>
    <td><A href="/scenarios/scenario-53">Scenario 53</A></td>
    <td>Conflict on Fire</td>
    <td>None</td>
    <td>Tree</td>
    <td>Saw</td>
    <td>Compete on Tree</td>
    <td>Exchange on Saw</td>
    <td>Fire</td>
    <td>Tree</td>
</tr>
<tr>
    <td><A href="/scenarios/scenario-54">Scenario 54</A></td>
    <td>Conflict on Tree</td>
    <td>None</td>
    <td>Tree</td>
    <td>Saw</td>
    <td>Compete on Tree</td>
    <td>None on Saw</td>
    <td>Tree</td>
    <td>Fire</td>
</tr>
<tr>
    <td><A href="/scenarios/scenario-55">Scenario 55</A></td>
    <td>Conflict on Fire</td>
    <td>None</td>
    <td>Tree</td>
    <td>Saw</td>
    <td>Coercion on Tree</td>
    <td>Cooperate on Saw</td>
    <td>Fire</td>
    <td>Tree</td>
</tr>
<tr>
    <td><A href="/scenarios/scenario-56">Scenario 56</A></td>
    <td>Conflict on Fire</td>
    <td>None</td>
    <td>Saw</td>
    <td>Tree</td>
    <td>Coercion on Saw</td>
    <td>Conflict on Tree</td>
    <td>Fire</td>
    <td>Tree</td>
</tr>
<tr>
    <td><A href="/scenarios/scenario-57">Scenario 57</A></td>
    <td>Conflict on Fire</td>
    <td>None</td>
    <td>Tree</td>
    <td>Saw</td>
    <td>Coercion on Tree</td>
    <td>Compete on Saw</td>
    <td>Fire</td>
    <td>Tree</td>
</tr>
<tr>
    <td><A href="/scenarios/scenario-58">Scenario 58</A></td>
    <td>Conflict on Fire</td>
    <td>None</td>
    <td>Tree</td>
    <td>Saw</td>
    <td>Coercion on Tree</td>
    <td>Coercion on Saw</td>
    <td>Fire</td>
    <td>Tree</td>
</tr>
<tr>
    <td><A href="/scenarios/scenario-59">Scenario 59</A></td>
    <td>Conflict on Tree</td>
    <td>None</td>
    <td>Tree</td>
    <td>Saw</td>
    <td>Coercion on Tree</td>
    <td>Exchange on Saw</td>
    <td>Tree</td>
    <td>Fire</td>
</tr>
<tr>
    <td><A href="/scenarios/scenario-60">Scenario 60</A></td>
    <td>Conflict on Fire</td>
    <td>None</td>
    <td>Tree</td>
    <td>Saw</td>
    <td>Coercion on Tree</td>
    <td>None on Saw</td>
    <td>Fire</td>
    <td>Tree</td>
</tr>
<tr>
    <td><A href="/scenarios/scenario-61">Scenario 61</A></td>
    <td>Conflict on Fire</td>
    <td>None</td>
    <td>Tree</td>
    <td>Fire</td>
    <td>Exchange on Tree</td>
    <td>Cooperate on Fire</td>
    <td>Fire</td>
    <td>Tree</td>
</tr>
<tr>
    <td><A href="/scenarios/scenario-62">Scenario 62</A></td>
    <td>Conflict on Tree</td>
    <td>None</td>
    <td>Tree</td>
    <td>Saw</td>
    <td>Exchange on Tree</td>
    <td>Conflict on Saw</td>
    <td>Tree</td>
    <td>Fire</td>
</tr>
<tr>
    <td><A href="/scenarios/scenario-63">Scenario 63</A></td>
    <td>Conflict on Tree</td>
    <td>None</td>
    <td>Tree</td>
    <td>Saw</td>
    <td>Exchange on Tree</td>
    <td>Compete on Saw</td>
    <td>Tree</td>
    <td>Fire</td>
</tr>
<tr>
    <td><A href="/scenarios/scenario-64">Scenario 64</A></td>
    <td>Conflict on Tree</td>
    <td>None</td>
    <td>Tree</td>
    <td>Saw</td>
    <td>Exchange on Tree</td>
    <td>Coercion on Saw</td>
    <td>Tree</td>
    <td>Fire</td>
</tr>
<tr>
    <td><A href="/scenarios/scenario-65">Scenario 65</A></td>
    <td>Conflict on Fire</td>
    <td>None</td>
    <td>Tree</td>
    <td>Saw</td>
    <td>Exchange on Tree</td>
    <td>Exchange on Saw</td>
    <td>Fire</td>
    <td>Tree</td>
</tr>
<tr>
    <td><A href="/scenarios/scenario-66">Scenario 66</A></td>
    <td>Conflict on Fire</td>
    <td>None</td>
    <td>Tree</td>
    <td>Saw</td>
    <td>Exchange on Tree</td>
    <td>None on Saw</td>
    <td>Fire</td>
    <td>Tree</td>
</tr>
<tr>
    <td><A href="/scenarios/scenario-67">Scenario 67</A></td>
    <td>Conflict on Fire</td>
    <td>None</td>
    <td>Tree</td>
    <td>Saw</td>
    <td>Neutral on Tree</td>
    <td>Cooperate on Saw</td>
    <td>Fire</td>
    <td>Tree</td>
</tr>
<tr>
    <td><A href="/scenarios/scenario-68">Scenario 68</A></td>
    <td>Conflict on Fire</td>
    <td>None</td>
    <td>Tree</td>
    <td>Saw</td>
    <td>Neutral on Tree</td>
    <td>Conflict on Saw</td>
    <td>Fire</td>
    <td>Tree</td>
</tr>
<tr>
    <td><A href="/scenarios/scenario-69">Scenario 69</A></td>
    <td>Conflict on Tree</td>
    <td>None</td>
    <td>Tree</td>
    <td>Saw</td>
    <td>Neutral on Tree</td>
    <td>Compete on Saw</td>
    <td>Tree</td>
    <td>Fire</td>
</tr>
<tr>
    <td><A href="/scenarios/scenario-70">Scenario 70</A></td>
    <td>Conflict on Fire</td>
    <td>None</td>
    <td>Tree</td>
    <td>Saw</td>
    <td>Neutral on Tree</td>
    <td>Coercion on Saw</td>
    <td>Fire</td>
    <td>Tree</td>
</tr>
<tr>
    <td><A href="/scenarios/scenario-71">Scenario 71</A></td>
    <td>Conflict on Fire</td>
    <td>None</td>
    <td>Tree</td>
    <td>Saw</td>
    <td>Neutral on Tree</td>
    <td>Exchange on Saw</td>
    <td>Fire</td>
    <td>Tree</td>
</tr>
<tr>
    <td><A href="/scenarios/scenario-72">Scenario 72</A></td>
    <td>Conflict on Tree</td>
    <td>None</td>
    <td>Tree</td>
    <td>Saw</td>
    <td>Neutral on Tree</td>
    <td>None on Saw</td>
    <td>Tree</td>
    <td>Fire</td>
</tr>
<tr>
    <td><A href="/scenarios/scenario-73">Scenario 73</A></td>
    <td>Compete on Tree</td>
    <td>None</td>
    <td>Tree</td>
    <td>Saw</td>
    <td>Cooperate on Tree</td>
    <td>Cooperate on Saw</td>
    <td>Tree</td>
    <td>Fire</td>
</tr>
<tr>
    <td><A href="/scenarios/scenario-74">Scenario 74</A></td>
    <td>Compete on Tree</td>
    <td>None</td>
    <td>Tree</td>
    <td>Saw</td>
    <td>Cooperate on Tree</td>
    <td>Conflict on Saw</td>
    <td>Tree</td>
    <td>Fire</td>
</tr>
<tr>
    <td><A href="/scenarios/scenario-75">Scenario 75</A></td>
    <td>Compete on Fire</td>
    <td>None</td>
    <td>Tree</td>
    <td>Saw</td>
    <td>Cooperate on Tree</td>
    <td>Compete on Saw</td>
    <td>Fire</td>
    <td>Tree</td>
</tr>
<tr>
    <td><A href="/scenarios/scenario-76">Scenario 76</A></td>
    <td>Compete on Fire</td>
    <td>None</td>
    <td>Tree</td>
    <td>Saw</td>
    <td>Cooperate on Tree</td>
    <td>Coercion on Saw</td>
    <td>Fire</td>
    <td>Tree</td>
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
<tr>
    <td><A href="/scenarios/scenario-78">Scenario 78</A></td>
    <td>Compete on Fire</td>
    <td>None</td>
    <td>Tree</td>
    <td>Saw</td>
    <td>Cooperate on Tree</td>
    <td>None on Saw</td>
    <td>Fire</td>
    <td>Tree</td>
</tr>
<tr>
    <td><A href="/scenarios/scenario-79">Scenario 79</A></td>
    <td>Compete on Fire</td>
    <td>None</td>
    <td>Saw</td>
    <td>Tree</td>
    <td>Conflict on Saw</td>
    <td>Cooperate on Tree</td>
    <td>Fire</td>
    <td>Tree</td>
</tr>
<tr>
    <td><A href="/scenarios/scenario-80">Scenario 80</A></td>
    <td>Compete on Tree</td>
    <td>None</td>
    <td>Tree</td>
    <td>Saw</td>
    <td>Conflict on Tree</td>
    <td>Conflict on Saw</td>
    <td>Tree</td>
    <td>Fire</td>
</tr>
<tr>
    <td><A href="/scenarios/scenario-81">Scenario 81</A></td>
    <td>Compete on Tree</td>
    <td>None</td>
    <td>Tree</td>
    <td>Saw</td>
    <td>Conflict on Tree</td>
    <td>Compete on Saw</td>
    <td>Tree</td>
    <td>Fire</td>
</tr>
<tr>
    <td><A href="/scenarios/scenario-82">Scenario 82</A></td>
    <td>Compete on Tree</td>
    <td>None</td>
    <td>Tree</td>
    <td>Saw</td>
    <td>Conflict on Tree</td>
    <td>Coercion on Saw</td>
    <td>Tree</td>
    <td>Fire</td>
</tr>
<tr>
    <td><A href="/scenarios/scenario-83">Scenario 83</A></td>
    <td>Compete on Fire</td>
    <td>None</td>
    <td>Saw</td>
    <td>Tree</td>
    <td>Conflict on Saw</td>
    <td>Exchange on Tree</td>
    <td>Fire</td>
    <td>Tree</td>
</tr>
<tr>
    <td><A href="/scenarios/scenario-84">Scenario 84</A></td>
    <td>Compete on Fire</td>
    <td>None</td>
    <td>Saw</td>
    <td>Tree</td>
    <td>Conflict on Saw</td>
    <td>None on Tree</td>
    <td>Fire</td>
    <td>Tree</td>
</tr>
<tr>
    <td><A href="/scenarios/scenario-85">Scenario 85</A></td>
    <td>Compete on Fire</td>
    <td>None</td>
    <td>Tree</td>
    <td>Saw</td>
    <td>Compete on Tree</td>
    <td>Cooperate on Saw</td>
    <td>Fire</td>
    <td>Tree</td>
</tr>
<tr>
    <td><A href="/scenarios/scenario-86">Scenario 86</A></td>
    <td>Compete on Fire</td>
    <td>None</td>
    <td>Tree</td>
    <td>Saw</td>
    <td>Compete on Tree</td>
    <td>Conflict on Saw</td>
    <td>Fire</td>
    <td>Tree</td>
</tr>
<tr>
    <td><A href="/scenarios/scenario-87">Scenario 87</A></td>
    <td>Compete on Fire</td>
    <td>None</td>
    <td>Tree</td>
    <td>Saw</td>
    <td>Compete on Tree</td>
    <td>Compete on Saw</td>
    <td>Fire</td>
    <td>Tree</td>
</tr>
<tr>
    <td><A href="/scenarios/scenario-88">Scenario 88</A></td>
    <td>Compete on Fire</td>
    <td>None</td>
    <td>Tree</td>
    <td>Saw</td>
    <td>Compete on Tree</td>
    <td>Coercion on Saw</td>
    <td>Fire</td>
    <td>Tree</td>
</tr>
<tr>
    <td><A href="/scenarios/scenario-89">Scenario 89</A></td>
    <td>Compete on Fire</td>
    <td>None</td>
    <td>Tree</td>
    <td>Tree</td>
    <td>Compete on Tree</td>
    <td>Exchange on Tree</td>
    <td>Fire</td>
    <td>Tree</td>
</tr>
<tr>
    <td><A href="/scenarios/scenario-90">Scenario 90</A></td>
    <td>Compete on Tree</td>
    <td>None</td>
    <td>Tree</td>
    <td>Saw</td>
    <td>Compete on Tree</td>
    <td>None on Saw</td>
    <td>Tree</td>
    <td>Fire</td>
</tr>
<tr>
    <td><A href="/scenarios/scenario-91">Scenario 91</A></td>
    <td>Compete on Fire</td>
    <td>None</td>
    <td>Saw</td>
    <td>Tree</td>
    <td>Coercion on Saw</td>
    <td>Cooperate on Tree</td>
    <td>Fire</td>
    <td>Tree</td>
</tr>
<tr>
    <td><A href="/scenarios/scenario-92">Scenario 92</A></td>
    <td>Compete on Tree</td>
    <td>None</td>
    <td>Tree</td>
    <td>Saw</td>
    <td>Coercion on Tree</td>
    <td>Conflict on Saw</td>
    <td>Tree</td>
    <td>Fire</td>
</tr>
<tr>
    <td><A href="/scenarios/scenario-93">Scenario 93</A></td>
    <td>Compete on Fire</td>
    <td>None</td>
    <td>Tree</td>
    <td>Saw</td>
    <td>Coercion on Tree</td>
    <td>Compete on Saw</td>
    <td>Fire</td>
    <td>Tree</td>
</tr>
<tr>
    <td><A href="/scenarios/scenario-94">Scenario 94</A></td>
    <td>Compete on Fire</td>
    <td>None</td>
    <td>Tree</td>
    <td>Saw</td>
    <td>Coercion on Tree</td>
    <td>Coercion on Saw</td>
    <td>Fire</td>
    <td>Tree</td>
</tr>
<tr>
    <td><A href="/scenarios/scenario-95">Scenario 95</A></td>
    <td>Compete on Fire</td>
    <td>None</td>
    <td>Tree</td>
    <td>Saw</td>
    <td>Coercion on Tree</td>
    <td>Exchange on Saw</td>
    <td>Fire</td>
    <td>Tree</td>
</tr>
<tr>
    <td><A href="/scenarios/scenario-96">Scenario 96</A></td>
    <td>Compete on Fire</td>
    <td>None</td>
    <td>Tree</td>
    <td>Saw</td>
    <td>Coercion on Tree</td>
    <td>None on Saw</td>
    <td>Fire</td>
    <td>Tree</td>
</tr>
<tr>
    <td><A href="/scenarios/scenario-97">Scenario 97</A></td>
    <td>Compete on Fire</td>
    <td>None</td>
    <td>Tree</td>
    <td>Saw</td>
    <td>Exchange on Tree</td>
    <td>Cooperate on Saw</td>
    <td>Fire</td>
    <td>Tree</td>
</tr>
<tr>
    <td><A href="/scenarios/scenario-98">Scenario 98</A></td>
    <td>Compete on Fire</td>
    <td>None</td>
    <td>Tree</td>
    <td>Saw</td>
    <td>Exchange on Tree</td>
    <td>Conflict on Saw</td>
    <td>Fire</td>
    <td>Tree</td>
</tr>
<tr>
    <td><A href="/scenarios/scenario-99">Scenario 99</A></td>
    <td>Compete on Fire</td>
    <td>None</td>
    <td>Tree</td>
    <td>Saw</td>
    <td>Exchange on Tree</td>
    <td>Compete on Saw</td>
    <td>Fire</td>
    <td>Tree</td>
</tr>
<tr>
    <td><A href="/scenarios/scenario-100">Scenario 100</A></td>
    <td>Compete on Fire</td>
    <td>None</td>
    <td>Tree</td>
    <td>Saw</td>
    <td>Exchange on Tree</td>
    <td>Coercion on Saw</td>
    <td>Fire</td>
    <td>Tree</td>
</tr>
<tr>
    <td><A href="/scenarios/scenario-101">Scenario 101</A></td>
    <td>Compete on Fire</td>
    <td>None</td>
    <td>Saw</td>
    <td>Tree</td>
    <td>Exchange on Saw</td>
    <td>Exchange on Tree</td>
    <td>Fire</td>
    <td>Tree</td>
</tr>
<tr>
    <td><A href="/scenarios/scenario-102">Scenario 102</A></td>
    <td>Compete on Fire</td>
    <td>None</td>
    <td>Tree</td>
    <td>Saw</td>
    <td>Exchange on Tree</td>
    <td>None on Saw</td>
    <td>Fire</td>
    <td>Tree</td>
</tr>
<tr>
    <td><A href="/scenarios/scenario-103">Scenario 103</A></td>
    <td>Compete on Fire</td>
    <td>None</td>
    <td>Tree</td>
    <td>Saw</td>
    <td>Neutral on Tree</td>
    <td>Cooperate on Saw</td>
    <td>Fire</td>
    <td>Tree</td>
</tr>
<tr>
    <td><A href="/scenarios/scenario-104">Scenario 104</A></td>
    <td>Compete on Fire</td>
    <td>None</td>
    <td>Saw</td>
    <td>Tree</td>
    <td>Neutral on Saw</td>
    <td>Conflict on Tree</td>
    <td>Fire</td>
    <td>Tree</td>
</tr>
<tr>
    <td><A href="/scenarios/scenario-105">Scenario 105</A></td>
    <td>Compete on Tree</td>
    <td>None</td>
    <td>Tree</td>
    <td>Saw</td>
    <td>Neutral on Tree</td>
    <td>Compete on Saw</td>
    <td>Tree</td>
    <td>Fire</td>
</tr>
<tr>
    <td><A href="/scenarios/scenario-106">Scenario 106</A></td>
    <td>Compete on Fire</td>
    <td>None</td>
    <td>Tree</td>
    <td>Saw</td>
    <td>Neutral on Tree</td>
    <td>Coercion on Saw</td>
    <td>Fire</td>
    <td>Tree</td>
</tr>
<tr>
    <td><A href="/scenarios/scenario-107">Scenario 107</A></td>
    <td>Compete on Fire</td>
    <td>None</td>
    <td>Tree</td>
    <td>Saw</td>
    <td>Neutral on Tree</td>
    <td>Exchange on Saw</td>
    <td>Fire</td>
    <td>Tree</td>
</tr>
<tr>
    <td><A href="/scenarios/scenario-108">Scenario 108</A></td>
    <td>Compete on Fire</td>
    <td>None</td>
    <td>Tree</td>
    <td>Saw</td>
    <td>Neutral on Tree</td>
    <td>None on Saw</td>
    <td>Fire</td>
    <td>Tree</td>
</tr>
<tr>
    <td><A href="/scenarios/scenario-109">Scenario 109</A></td>
    <td>Coercion on Fire</td>
    <td>None</td>
    <td>Tree</td>
    <td>Saw</td>
    <td>Cooperate on Tree</td>
    <td>Cooperate on Saw</td>
    <td>Fire</td>
    <td>Tree</td>
</tr>
<tr>
    <td><A href="/scenarios/scenario-110">Scenario 110</A></td>
    <td>Coercion on Fire</td>
    <td>None</td>
    <td>Tree</td>
    <td>Saw</td>
    <td>Cooperate on Tree</td>
    <td>Conflict on Saw</td>
    <td>Fire</td>
    <td>Tree</td>
</tr>
<tr>
    <td><A href="/scenarios/scenario-111">Scenario 111</A></td>
    <td>Coercion on Fire</td>
    <td>None</td>
    <td>Tree</td>
    <td>Saw</td>
    <td>Cooperate on Tree</td>
    <td>Compete on Saw</td>
    <td>Fire</td>
    <td>Tree</td>
</tr>
<tr>
    <td><A href="/scenarios/scenario-112">Scenario 112</A></td>
    <td>Coercion on Fire</td>
    <td>None</td>
    <td>Tree</td>
    <td>Saw</td>
    <td>Cooperate on Tree</td>
    <td>Coercion on Saw</td>
    <td>Fire</td>
    <td>Tree</td>
</tr>
<tr>
    <td><A href="/scenarios/scenario-113">Scenario 113</A></td>
    <td>Coercion on Fire</td>
    <td>None</td>
    <td>Tree</td>
    <td>Saw</td>
    <td>Cooperate on Tree</td>
    <td>Exchange on Saw</td>
    <td>Fire</td>
    <td>Tree</td>
</tr>
<tr>
    <td><A href="/scenarios/scenario-114">Scenario 114</A></td>
    <td>Coercion on Fire</td>
    <td>None</td>
    <td>Tree</td>
    <td>Saw</td>
    <td>Cooperate on Tree</td>
    <td>None on Saw</td>
    <td>Fire</td>
    <td>Tree</td>
</tr>
<tr>
    <td><A href="/scenarios/scenario-115">Scenario 115</A></td>
    <td>Coercion on Fire</td>
    <td>None</td>
    <td>Tree</td>
    <td>Saw</td>
    <td>Conflict on Tree</td>
    <td>Cooperate on Saw</td>
    <td>Fire</td>
    <td>Tree</td>
</tr>
<tr>
    <td><A href="/scenarios/scenario-116">Scenario 116</A></td>
    <td>Coercion on Fire</td>
    <td>None</td>
    <td>Saw</td>
    <td>Tree</td>
    <td>Conflict on Saw</td>
    <td>Conflict on Tree</td>
    <td>Fire</td>
    <td>Tree</td>
</tr>
<tr>
    <td><A href="/scenarios/scenario-117">Scenario 117</A></td>
    <td>Coercion on Fire</td>
    <td>None</td>
    <td>Saw</td>
    <td>Tree</td>
    <td>Conflict on Saw</td>
    <td>Compete on Tree</td>
    <td>Fire</td>
    <td>Tree</td>
</tr>
<tr>
    <td><A href="/scenarios/scenario-118">Scenario 118</A></td>
    <td>Coercion on Fire</td>
    <td>None</td>
    <td>Saw</td>
    <td>Tree</td>
    <td>Conflict on Saw</td>
    <td>Coercion on Tree</td>
    <td>Fire</td>
    <td>Tree</td>
</tr>
<tr>
    <td><A href="/scenarios/scenario-119">Scenario 119</A></td>
    <td>Coercion on Fire</td>
    <td>None</td>
    <td>Saw</td>
    <td>Tree</td>
    <td>Conflict on Saw</td>
    <td>Exchange on Tree</td>
    <td>Fire</td>
    <td>Tree</td>
</tr>
<tr>
    <td><A href="/scenarios/scenario-120">Scenario 120</A></td>
    <td>Coercion on Fire</td>
    <td>None</td>
    <td>Saw</td>
    <td>Tree</td>
    <td>Conflict on Saw</td>
    <td>None on Tree</td>
    <td>Fire</td>
    <td>Tree</td>
</tr>
<tr>
    <td><A href="/scenarios/scenario-121">Scenario 121</A></td>
    <td>Coercion on Fire</td>
    <td>None</td>
    <td>Tree</td>
    <td>Saw</td>
    <td>Compete on Tree</td>
    <td>Cooperate on Saw</td>
    <td>Fire</td>
    <td>Tree</td>
</tr>
<tr>
    <td><A href="/scenarios/scenario-122">Scenario 122</A></td>
    <td>Coercion on Fire</td>
    <td>None</td>
    <td>Tree</td>
    <td>Saw</td>
    <td>Compete on Tree</td>
    <td>Conflict on Saw</td>
    <td>Fire</td>
    <td>Tree</td>
</tr>
<tr>
    <td><A href="/scenarios/scenario-123">Scenario 123</A></td>
    <td>Coercion on Fire</td>
    <td>None</td>
    <td>Saw</td>
    <td>Tree</td>
    <td>Compete on Saw</td>
    <td>Compete on Tree</td>
    <td>Fire</td>
    <td>Tree</td>
</tr>
<tr>
    <td><A href="/scenarios/scenario-124">Scenario 124</A></td>
    <td>Coercion on Fire</td>
    <td>None</td>
    <td>Tree</td>
    <td>Saw</td>
    <td>Compete on Tree</td>
    <td>Coercion on Saw</td>
    <td>Fire</td>
    <td>Tree</td>
</tr>
<tr>
    <td><A href="/scenarios/scenario-125">Scenario 125</A></td>
    <td>Coercion on Fire</td>
    <td>None</td>
    <td>Tree</td>
    <td>Saw</td>
    <td>Compete on Tree</td>
    <td>Exchange on Saw</td>
    <td>Fire</td>
    <td>Tree</td>
</tr>
<tr>
    <td><A href="/scenarios/scenario-126">Scenario 126</A></td>
    <td>Coercion on Fire</td>
    <td>None</td>
    <td>Tree</td>
    <td>Saw</td>
    <td>Compete on Tree</td>
    <td>None on Saw</td>
    <td>Fire</td>
    <td>Tree</td>
</tr>
<tr>
    <td><A href="/scenarios/scenario-127">Scenario 127</A></td>
    <td>Coercion on Fire</td>
    <td>None</td>
    <td>Fire</td>
    <td>Tree</td>
    <td>Coercion on Fire</td>
    <td>Cooperate on Tree</td>
    <td>Fire</td>
    <td>Tree</td>
</tr>
<tr>
    <td><A href="/scenarios/scenario-128">Scenario 128</A></td>
    <td>Coercion on Tree</td>
    <td>None</td>
    <td>Tree</td>
    <td>Saw</td>
    <td>Coercion on Tree</td>
    <td>Conflict on Saw</td>
    <td>Tree</td>
    <td>Fire</td>
</tr>
<tr>
    <td><A href="/scenarios/scenario-129">Scenario 129</A></td>
    <td>Coercion on Fire</td>
    <td>None</td>
    <td>Tree</td>
    <td>Saw</td>
    <td>Coercion on Tree</td>
    <td>Compete on Saw</td>
    <td>Fire</td>
    <td>Tree</td>
</tr>
<tr>
    <td><A href="/scenarios/scenario-130">Scenario 130</A></td>
    <td>Coercion on Fire</td>
    <td>None</td>
    <td>Tree</td>
    <td>Saw</td>
    <td>Coercion on Tree</td>
    <td>Coercion on Saw</td>
    <td>Fire</td>
    <td>Tree</td>
</tr>
<tr>
    <td><A href="/scenarios/scenario-131">Scenario 131</A></td>
    <td>Coercion on Fire</td>
    <td>None</td>
    <td>Tree</td>
    <td>Saw</td>
    <td>Coercion on Tree</td>
    <td>Exchange on Saw</td>
    <td>Fire</td>
    <td>Tree</td>
</tr>
<tr>
    <td><A href="/scenarios/scenario-132">Scenario 132</A></td>
    <td>Coercion on Fire</td>
    <td>None</td>
    <td>Tree</td>
    <td>Saw</td>
    <td>Coercion on Tree</td>
    <td>None on Saw</td>
    <td>Fire</td>
    <td>Tree</td>
</tr>
<tr>
    <td><A href="/scenarios/scenario-133">Scenario 133</A></td>
    <td>Coercion on Tree</td>
    <td>None</td>
    <td>Tree</td>
    <td>Saw</td>
    <td>Exchange on Tree</td>
    <td>Cooperate on Saw</td>
    <td>Tree</td>
    <td>Fire</td>
</tr>
<tr>
    <td><A href="/scenarios/scenario-134">Scenario 134</A></td>
    <td>Coercion on Fire</td>
    <td>None</td>
    <td>Tree</td>
    <td>Saw</td>
    <td>Exchange on Tree</td>
    <td>Conflict on Saw</td>
    <td>Fire</td>
    <td>Tree</td>
</tr>
<tr>
    <td><A href="/scenarios/scenario-135">Scenario 135</A></td>
    <td>Coercion on Fire</td>
    <td>None</td>
    <td>Tree</td>
    <td>Saw</td>
    <td>Exchange on Tree</td>
    <td>Compete on Saw</td>
    <td>Fire</td>
    <td>Tree</td>
</tr>
<tr>
    <td><A href="/scenarios/scenario-136">Scenario 136</A></td>
    <td>Coercion on Fire</td>
    <td>None</td>
    <td>Tree</td>
    <td>Saw</td>
    <td>Exchange on Tree</td>
    <td>Coercion on Saw</td>
    <td>Fire</td>
    <td>Tree</td>
</tr>
<tr>
    <td><A href="/scenarios/scenario-137">Scenario 137</A></td>
    <td>Coercion on Fire</td>
    <td>None</td>
    <td>Tree</td>
    <td>Saw</td>
    <td>Exchange on Tree</td>
    <td>Exchange on Saw</td>
    <td>Fire</td>
    <td>Tree</td>
</tr>
<tr>
    <td><A href="/scenarios/scenario-138">Scenario 138</A></td>
    <td>Coercion on Tree</td>
    <td>None</td>
    <td>Tree</td>
    <td>Saw</td>
    <td>Exchange on Tree</td>
    <td>None on Saw</td>
    <td>Tree</td>
    <td>Fire</td>
</tr>
<tr>
    <td><A href="/scenarios/scenario-139">Scenario 139</A></td>
    <td>Coercion on Fire</td>
    <td>None</td>
    <td>Tree</td>
    <td>Saw</td>
    <td>Neutral on Tree</td>
    <td>Cooperate on Saw</td>
    <td>Fire</td>
    <td>Tree</td>
</tr>
<tr>
    <td><A href="/scenarios/scenario-140">Scenario 140</A></td>
    <td>Coercion on Fire</td>
    <td>None</td>
    <td>Tree</td>
    <td>Saw</td>
    <td>Neutral on Tree</td>
    <td>Conflict on Saw</td>
    <td>Fire</td>
    <td>Tree</td>
</tr>
<tr>
    <td><A href="/scenarios/scenario-141">Scenario 141</A></td>
    <td>Coercion on Fire</td>
    <td>None</td>
    <td>Tree</td>
    <td>Saw</td>
    <td>Neutral on Tree</td>
    <td>Compete on Saw</td>
    <td>Fire</td>
    <td>Tree</td>
</tr>
<tr>
    <td><A href="/scenarios/scenario-142">Scenario 142</A></td>
    <td>Coercion on Fire</td>
    <td>None</td>
    <td>Tree</td>
    <td>Saw</td>
    <td>Neutral on Tree</td>
    <td>Coercion on Saw</td>
    <td>Fire</td>
    <td>Tree</td>
</tr>
<tr>
    <td><A href="/scenarios/scenario-143">Scenario 143</A></td>
    <td>Coercion on Fire</td>
    <td>None</td>
    <td>Tree</td>
    <td>Saw</td>
    <td>Neutral on Tree</td>
    <td>Exchange on Saw</td>
    <td>Fire</td>
    <td>Tree</td>
</tr>
<tr>
    <td><A href="/scenarios/scenario-144">Scenario 144</A></td>
    <td>Coercion on Fire</td>
    <td>None</td>
    <td>Tree</td>
    <td>Saw</td>
    <td>Neutral on Tree</td>
    <td>None on Saw</td>
    <td>Fire</td>
    <td>Tree</td>
</tr>
<tr>
    <td><A href="/scenarios/scenario-145">Scenario 145</A></td>
    <td>Exchange on Tree</td>
    <td>None</td>
    <td>Tree</td>
    <td>Fire</td>
    <td>Cooperate on Tree</td>
    <td>Cooperate on Fire</td>
    <td>Tree</td>
    <td>Fire</td>
</tr>
<tr>
    <td><A href="/scenarios/scenario-146">Scenario 146</A></td>
    <td>Exchange on Fire</td>
    <td>None</td>
    <td>Tree</td>
    <td>Saw</td>
    <td>Cooperate on Tree</td>
    <td>Conflict on Saw</td>
    <td>Fire</td>
    <td>Tree</td>
</tr>
<tr>
    <td><A href="/scenarios/scenario-147">Scenario 147</A></td>
    <td>Exchange on Tree</td>
    <td>None</td>
    <td>Tree</td>
    <td>Saw</td>
    <td>Cooperate on Tree</td>
    <td>Compete on Saw</td>
    <td>Tree</td>
    <td>Fire</td>
</tr>
<tr>
    <td><A href="/scenarios/scenario-148">Scenario 148</A></td>
    <td>Exchange on Fire</td>
    <td>None</td>
    <td>Tree</td>
    <td>Saw</td>
    <td>Cooperate on Tree</td>
    <td>Coercion on Saw</td>
    <td>Fire</td>
    <td>Tree</td>
</tr>
<tr>
    <td><A href="/scenarios/scenario-149">Scenario 149</A></td>
    <td>Exchange on Fire</td>
    <td>None</td>
    <td>Tree</td>
    <td>Saw</td>
    <td>Cooperate on Tree</td>
    <td>Exchange on Saw</td>
    <td>Fire</td>
    <td>Tree</td>
</tr>
<tr>
    <td><A href="/scenarios/scenario-150">Scenario 150</A></td>
    <td>Exchange on Fire</td>
    <td>None</td>
    <td>Tree</td>
    <td>Saw</td>
    <td>Cooperate on Tree</td>
    <td>None on Saw</td>
    <td>Fire</td>
    <td>Tree</td>
</tr>
<tr>
    <td><A href="/scenarios/scenario-151">Scenario 151</A></td>
    <td>Exchange on Fire</td>
    <td>None</td>
    <td>Tree</td>
    <td>Saw</td>
    <td>Conflict on Tree</td>
    <td>Cooperate on Saw</td>
    <td>Fire</td>
    <td>Tree</td>
</tr>
<tr>
    <td><A href="/scenarios/scenario-152">Scenario 152</A></td>
    <td>Exchange on Fire</td>
    <td>None</td>
    <td>Tree</td>
    <td>Saw</td>
    <td>Conflict on Tree</td>
    <td>Conflict on Saw</td>
    <td>Fire</td>
    <td>Tree</td>
</tr>
<tr>
    <td><A href="/scenarios/scenario-153">Scenario 153</A></td>
    <td>Exchange on Fire</td>
    <td>None</td>
    <td>Saw</td>
    <td>Tree</td>
    <td>Conflict on Saw</td>
    <td>Compete on Tree</td>
    <td>Fire</td>
    <td>Tree</td>
</tr>
<tr>
    <td><A href="/scenarios/scenario-154">Scenario 154</A></td>
    <td>Exchange on Fire</td>
    <td>None</td>
    <td>Tree</td>
    <td>Saw</td>
    <td>Conflict on Tree</td>
    <td>Coercion on Saw</td>
    <td>Fire</td>
    <td>Tree</td>
</tr>
<tr>
    <td><A href="/scenarios/scenario-155">Scenario 155</A></td>
    <td>Exchange on Fire</td>
    <td>None</td>
    <td>Tree</td>
    <td>Saw</td>
    <td>Conflict on Tree</td>
    <td>Exchange on Saw</td>
    <td>Fire</td>
    <td>Tree</td>
</tr>
<tr>
    <td><A href="/scenarios/scenario-156">Scenario 156</A></td>
    <td>Exchange on Fire</td>
    <td>None</td>
    <td>Tree</td>
    <td>Saw</td>
    <td>Conflict on Tree</td>
    <td>None on Saw</td>
    <td>Fire</td>
    <td>Tree</td>
</tr>
<tr>
    <td><A href="/scenarios/scenario-157">Scenario 157</A></td>
    <td>Exchange on Fire</td>
    <td>None</td>
    <td>Tree</td>
    <td>Saw</td>
    <td>Compete on Tree</td>
    <td>Cooperate on Saw</td>
    <td>Fire</td>
    <td>Tree</td>
</tr>
<tr>
    <td><A href="/scenarios/scenario-158">Scenario 158</A></td>
    <td>Exchange on Fire</td>
    <td>None</td>
    <td>Tree</td>
    <td>Saw</td>
    <td>Compete on Tree</td>
    <td>Conflict on Saw</td>
    <td>Fire</td>
    <td>Tree</td>
</tr>
<tr>
    <td><A href="/scenarios/scenario-159">Scenario 159</A></td>
    <td>Exchange on Tree</td>
    <td>None</td>
    <td>Tree</td>
    <td>Saw</td>
    <td>Compete on Tree</td>
    <td>Compete on Saw</td>
    <td>Tree</td>
    <td>Fire</td>
</tr>
<tr>
    <td><A href="/scenarios/scenario-160">Scenario 160</A></td>
    <td>Exchange on Fire</td>
    <td>None</td>
    <td>Tree</td>
    <td>Saw</td>
    <td>Compete on Tree</td>
    <td>Coercion on Saw</td>
    <td>Fire</td>
    <td>Tree</td>
</tr>
<tr>
    <td><A href="/scenarios/scenario-161">Scenario 161</A></td>
    <td>Exchange on Fire</td>
    <td>None</td>
    <td>Tree</td>
    <td>Saw</td>
    <td>Compete on Tree</td>
    <td>Exchange on Saw</td>
    <td>Fire</td>
    <td>Tree</td>
</tr>
<tr>
    <td><A href="/scenarios/scenario-162">Scenario 162</A></td>
    <td>Exchange on Fire</td>
    <td>None</td>
    <td>Tree</td>
    <td>Saw</td>
    <td>Compete on Tree</td>
    <td>None on Saw</td>
    <td>Fire</td>
    <td>Tree</td>
</tr>
<tr>
    <td><A href="/scenarios/scenario-163">Scenario 163</A></td>
    <td>Exchange on Fire</td>
    <td>None</td>
    <td>Tree</td>
    <td>Saw</td>
    <td>Coercion on Tree</td>
    <td>Cooperate on Saw</td>
    <td>Fire</td>
    <td>Tree</td>
</tr>
<tr>
    <td><A href="/scenarios/scenario-164">Scenario 164</A></td>
    <td>Exchange on Fire</td>
    <td>None</td>
    <td>Tree</td>
    <td>Saw</td>
    <td>Coercion on Tree</td>
    <td>Conflict on Saw</td>
    <td>Fire</td>
    <td>Tree</td>
</tr>
<tr>
    <td><A href="/scenarios/scenario-165">Scenario 165</A></td>
    <td>Exchange on Fire</td>
    <td>None</td>
    <td>Tree</td>
    <td>Saw</td>
    <td>Coercion on Tree</td>
    <td>Compete on Saw</td>
    <td>Fire</td>
    <td>Tree</td>
</tr>
<tr>
    <td><A href="/scenarios/scenario-166">Scenario 166</A></td>
    <td>Exchange on Fire</td>
    <td>None</td>
    <td>Tree</td>
    <td>Saw</td>
    <td>Coercion on Tree</td>
    <td>Coercion on Saw</td>
    <td>Fire</td>
    <td>Tree</td>
</tr>
<tr>
    <td><A href="/scenarios/scenario-167">Scenario 167</A></td>
    <td>Exchange on Fire</td>
    <td>None</td>
    <td>Tree</td>
    <td>Saw</td>
    <td>Coercion on Tree</td>
    <td>Exchange on Saw</td>
    <td>Fire</td>
    <td>Tree</td>
</tr>
<tr>
    <td><A href="/scenarios/scenario-168">Scenario 168</A></td>
    <td>Exchange on Fire</td>
    <td>None</td>
    <td>Tree</td>
    <td>Saw</td>
    <td>Coercion on Tree</td>
    <td>None on Saw</td>
    <td>Fire</td>
    <td>Tree</td>
</tr>
<tr>
    <td><A href="/scenarios/scenario-169">Scenario 169</A></td>
    <td>Exchange on Fire</td>
    <td>None</td>
    <td>Tree</td>
    <td>Saw</td>
    <td>Exchange on Tree</td>
    <td>Cooperate on Saw</td>
    <td>Fire</td>
    <td>Tree</td>
</tr>
<tr>
    <td><A href="/scenarios/scenario-170">Scenario 170</A></td>
    <td>Exchange on Fire</td>
    <td>None</td>
    <td>Tree</td>
    <td>Saw</td>
    <td>Exchange on Tree</td>
    <td>Conflict on Saw</td>
    <td>Fire</td>
    <td>Tree</td>
</tr>
<tr>
    <td><A href="/scenarios/scenario-171">Scenario 171</A></td>
    <td>Exchange on Fire</td>
    <td>None</td>
    <td>Tree</td>
    <td>Saw</td>
    <td>Exchange on Tree</td>
    <td>Compete on Saw</td>
    <td>Fire</td>
    <td>Tree</td>
</tr>
<tr>
    <td><A href="/scenarios/scenario-172">Scenario 172</A></td>
    <td>Exchange on Fire</td>
    <td>None</td>
    <td>Tree</td>
    <td>Saw</td>
    <td>Exchange on Tree</td>
    <td>Coercion on Saw</td>
    <td>Fire</td>
    <td>Tree</td>
</tr>
<tr>
    <td><A href="/scenarios/scenario-173">Scenario 173</A></td>
    <td>Exchange on Fire</td>
    <td>None</td>
    <td>Tree</td>
    <td>Saw</td>
    <td>Exchange on Tree</td>
    <td>Exchange on Saw</td>
    <td>Fire</td>
    <td>Tree</td>
</tr>
<tr>
    <td><A href="/scenarios/scenario-174">Scenario 174</A></td>
    <td>Exchange on Fire</td>
    <td>None</td>
    <td>Tree</td>
    <td>Saw</td>
    <td>Exchange on Tree</td>
    <td>None on Saw</td>
    <td>Fire</td>
    <td>Tree</td>
</tr>
<tr>
    <td><A href="/scenarios/scenario-175">Scenario 175</A></td>
    <td>Exchange on Tree</td>
    <td>None</td>
    <td>Saw</td>
    <td>Tree</td>
    <td>Neutral on Saw</td>
    <td>Cooperate on Tree</td>
    <td>Tree</td>
    <td>Fire</td>
</tr>
<tr>
    <td><A href="/scenarios/scenario-176">Scenario 176</A></td>
    <td>Exchange on Fire</td>
    <td>None</td>
    <td>Tree</td>
    <td>Saw</td>
    <td>Neutral on Tree</td>
    <td>Conflict on Saw</td>
    <td>Fire</td>
    <td>Tree</td>
</tr>
<tr>
    <td><A href="/scenarios/scenario-177">Scenario 177</A></td>
    <td>Exchange on Fire</td>
    <td>None</td>
    <td>Saw</td>
    <td>Tree</td>
    <td>Neutral on Saw</td>
    <td>Compete on Tree</td>
    <td>Fire</td>
    <td>Tree</td>
</tr>
<tr>
    <td><A href="/scenarios/scenario-178">Scenario 178</A></td>
    <td>Exchange on Fire</td>
    <td>None</td>
    <td>Tree</td>
    <td>Saw</td>
    <td>Neutral on Tree</td>
    <td>Coercion on Saw</td>
    <td>Fire</td>
    <td>Tree</td>
</tr>
<tr>
    <td><A href="/scenarios/scenario-179">Scenario 179</A></td>
    <td>Exchange on Fire</td>
    <td>None</td>
    <td>Tree</td>
    <td>Saw</td>
    <td>Neutral on Tree</td>
    <td>Exchange on Saw</td>
    <td>Fire</td>
    <td>Tree</td>
</tr>
<tr>
    <td><A href="/scenarios/scenario-180">Scenario 180</A></td>
    <td>Exchange on Fire</td>
    <td>None</td>
    <td>Tree</td>
    <td>Saw</td>
    <td>Neutral on Tree</td>
    <td>None on Saw</td>
    <td>Fire</td>
    <td>Tree</td>
</tr>
</tbody></table>