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
    <td>Scenario 5</td>
    <td>Cooperate on Fire</td>
    <td>None</td>
    <td> </td>
    <td> </td>
    <td>Cooperate on </td>
    <td>Exchange on </td>
    <td>Fire</td>
    <td>Tree</td>
</tr>
<tr>
    <td>Scenario 6</td>
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
    <td>Scenario 7</td>
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
    <td>Scenario 8</td>
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
    <td>Scenario 9</td>
    <td>Cooperate on Fire</td>
    <td>None</td>
    <td> </td>
    <td> </td>
    <td>Conflict on </td>
    <td>Compete on </td>
    <td>Fire</td>
    <td>Tree</td>
</tr>
<tr>
    <td>Scenario 10</td>
    <td>Cooperate on Fire</td>
    <td>None</td>
    <td> </td>
    <td> </td>
    <td>Conflict on </td>
    <td>Coercion on </td>
    <td>Fire</td>
    <td>Tree</td>
</tr>
<tr>
    <td>Scenario 11</td>
    <td>Cooperate on Fire</td>
    <td>None</td>
    <td> </td>
    <td> </td>
    <td>Conflict on </td>
    <td>Exchange on </td>
    <td>Fire</td>
    <td>Tree</td>
</tr>
<tr>
    <td>Scenario 12</td>
    <td>Cooperate on Fire</td>
    <td>None</td>
    <td> </td>
    <td> </td>
    <td>Conflict on </td>
    <td>None on </td>
    <td>Fire</td>
    <td>Tree</td>
</tr>
<tr>
    <td>Scenario 13</td>
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
    <td>Scenario 14</td>
    <td>Cooperate on Fire</td>
    <td>None</td>
    <td> </td>
    <td> </td>
    <td>Compete on </td>
    <td>Conflict on </td>
    <td>Fire</td>
    <td>Tree</td>
</tr>
<tr>
    <td>Scenario 15</td>
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
    <td>Scenario 16</td>
    <td>Cooperate on Fire</td>
    <td>None</td>
    <td> </td>
    <td> </td>
    <td>Compete on </td>
    <td>Coercion on </td>
    <td>Fire</td>
    <td>Tree</td>
</tr>
<tr>
    <td>Scenario 17</td>
    <td>Cooperate on Fire</td>
    <td>None</td>
    <td> </td>
    <td> </td>
    <td>Compete on </td>
    <td>Exchange on </td>
    <td>Fire</td>
    <td>Tree</td>
</tr>
<tr>
    <td>Scenario 18</td>
    <td>Cooperate on Fire</td>
    <td>None</td>
    <td> </td>
    <td> </td>
    <td>Compete on </td>
    <td>None on </td>
    <td>Fire</td>
    <td>Tree</td>
</tr>
<tr>
    <td>Scenario 19</td>
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
    <td>Scenario 20</td>
    <td>Cooperate on Fire</td>
    <td>None</td>
    <td> </td>
    <td> </td>
    <td>Coercion on </td>
    <td>Conflict on </td>
    <td>Fire</td>
    <td>Tree</td>
</tr>
<tr>
    <td>Scenario 21</td>
    <td>Cooperate on Fire</td>
    <td>None</td>
    <td> </td>
    <td> </td>
    <td>Coercion on </td>
    <td>Compete on </td>
    <td>Fire</td>
    <td>Tree</td>
</tr>
<tr>
    <td>Scenario 22</td>
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
    <td>Scenario 23</td>
    <td>Cooperate on Fire</td>
    <td>None</td>
    <td> </td>
    <td> </td>
    <td>Coercion on </td>
    <td>Exchange on </td>
    <td>Fire</td>
    <td>Tree</td>
</tr>
<tr>
    <td>Scenario 24</td>
    <td>Cooperate on Fire</td>
    <td>None</td>
    <td> </td>
    <td> </td>
    <td>Coercion on </td>
    <td>None on </td>
    <td>Fire</td>
    <td>Tree</td>
</tr>
<tr>
    <td>Scenario 25</td>
    <td>Cooperate on Fire</td>
    <td>None</td>
    <td> </td>
    <td> </td>
    <td>Exchange on </td>
    <td>Cooperate on </td>
    <td>Fire</td>
    <td>Tree</td>
</tr>
<tr>
    <td>Scenario 26</td>
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
    <td>Scenario 27</td>
    <td>Cooperate on Fire</td>
    <td>None</td>
    <td> </td>
    <td> </td>
    <td>Exchange on </td>
    <td>Compete on </td>
    <td>Fire</td>
    <td>Tree</td>
</tr>
<tr>
    <td>Scenario 28</td>
    <td>Cooperate on Fire</td>
    <td>None</td>
    <td> </td>
    <td> </td>
    <td>Exchange on </td>
    <td>Coercion on </td>
    <td>Fire</td>
    <td>Tree</td>
</tr>
<tr>
    <td>Scenario 29</td>
    <td>Cooperate on Fire</td>
    <td>None</td>
    <td> </td>
    <td> </td>
    <td>Exchange on </td>
    <td>Exchange on </td>
    <td>Fire</td>
    <td>Tree</td>
</tr>
<tr>
    <td>Scenario 30</td>
    <td>Cooperate on Fire</td>
    <td>None</td>
    <td> </td>
    <td> </td>
    <td>Exchange on </td>
    <td>None on </td>
    <td>Fire</td>
    <td>Tree</td>
</tr>
<tr>
    <td>Scenario 31</td>
    <td>Cooperate on Fire</td>
    <td>None</td>
    <td> </td>
    <td> </td>
    <td>Neutral on </td>
    <td>Cooperate on </td>
    <td>Fire</td>
    <td>Tree</td>
</tr>
<tr>
    <td>Scenario 32</td>
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
    <td>Scenario 33</td>
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
    <td>Scenario 34</td>
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
    <td>Scenario 35</td>
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
    <td>Scenario 36</td>
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
    <td>Scenario 37</td>
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
    <td>Scenario 38</td>
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
    <td>Scenario 39</td>
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
    <td>Scenario 40</td>
    <td>Conflict on Fire</td>
    <td>None</td>
    <td> </td>
    <td> </td>
    <td>Cooperate on </td>
    <td>Coercion on </td>
    <td>Fire</td>
    <td>Tree</td>
</tr>
<tr>
    <td>Scenario 41</td>
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
    <td>Scenario 42</td>
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
    <td>Scenario 43</td>
    <td>Conflict on Fire</td>
    <td>None</td>
    <td> </td>
    <td> </td>
    <td>Conflict on </td>
    <td>Cooperate on </td>
    <td>Fire</td>
    <td>Tree</td>
</tr>
<tr>
    <td>Scenario 44</td>
    <td>Conflict on Fire</td>
    <td>None</td>
    <td> </td>
    <td> </td>
    <td>Conflict on </td>
    <td>Conflict on </td>
    <td>Fire</td>
    <td>Tree</td>
</tr>
<tr>
    <td>Scenario 45</td>
    <td>Conflict on Fire</td>
    <td>None</td>
    <td> </td>
    <td> </td>
    <td>Conflict on </td>
    <td>Compete on </td>
    <td>Fire</td>
    <td>Tree</td>
</tr>
<tr>
    <td>Scenario 46</td>
    <td>Conflict on Fire</td>
    <td>None</td>
    <td> </td>
    <td> </td>
    <td>Conflict on </td>
    <td>Coercion on </td>
    <td>Fire</td>
    <td>Tree</td>
</tr>
<tr>
    <td>Scenario 47</td>
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
    <td>Scenario 48</td>
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
    <td>Scenario 49</td>
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
    <td>Scenario 50</td>
    <td>Conflict on Fire</td>
    <td>None</td>
    <td> </td>
    <td> </td>
    <td>Compete on </td>
    <td>Conflict on </td>
    <td>Fire</td>
    <td>Tree</td>
</tr>
<tr>
    <td>Scenario 51</td>
    <td>Conflict on Fire</td>
    <td>None</td>
    <td> </td>
    <td> </td>
    <td>Compete on </td>
    <td>Compete on </td>
    <td>Fire</td>
    <td>Tree</td>
</tr>
<tr>
    <td>Scenario 52</td>
    <td>Conflict on Fire</td>
    <td>None</td>
    <td> </td>
    <td> </td>
    <td>Compete on </td>
    <td>Coercion on </td>
    <td>Fire</td>
    <td>Tree</td>
</tr>
<tr>
    <td>Scenario 53</td>
    <td>Conflict on Fire</td>
    <td>None</td>
    <td> </td>
    <td> </td>
    <td>Compete on </td>
    <td>Exchange on </td>
    <td>Fire</td>
    <td>Tree</td>
</tr>
<tr>
    <td>Scenario 54</td>
    <td>Conflict on Fire</td>
    <td>None</td>
    <td> </td>
    <td> </td>
    <td>Compete on </td>
    <td>None on </td>
    <td>Fire</td>
    <td>Tree</td>
</tr>
<tr>
    <td>Scenario 55</td>
    <td>Conflict on Fire</td>
    <td>None</td>
    <td> </td>
    <td> </td>
    <td>Coercion on </td>
    <td>Cooperate on </td>
    <td>Fire</td>
    <td>Tree</td>
</tr>
<tr>
    <td>Scenario 56</td>
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
    <td>Scenario 57</td>
    <td>Conflict on Fire</td>
    <td>None</td>
    <td> </td>
    <td> </td>
    <td>Coercion on </td>
    <td>Compete on </td>
    <td>Fire</td>
    <td>Tree</td>
</tr>
<tr>
    <td>Scenario 58</td>
    <td>Conflict on Fire</td>
    <td>None</td>
    <td> </td>
    <td> </td>
    <td>Coercion on </td>
    <td>Coercion on </td>
    <td>Fire</td>
    <td>Tree</td>
</tr>
<tr>
    <td>Scenario 59</td>
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
    <td>Scenario 60</td>
    <td>Conflict on Fire</td>
    <td>None</td>
    <td> </td>
    <td> </td>
    <td>Coercion on </td>
    <td>None on </td>
    <td>Fire</td>
    <td>Tree</td>
</tr>
<tr>
    <td>Scenario 61</td>
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
    <td>Scenario 62</td>
    <td>Conflict on Fire</td>
    <td>None</td>
    <td> </td>
    <td> </td>
    <td>Exchange on </td>
    <td>Conflict on </td>
    <td>Fire</td>
    <td>Tree</td>
</tr>
<tr>
    <td>Scenario 63</td>
    <td>Conflict on Fire</td>
    <td>None</td>
    <td> </td>
    <td> </td>
    <td>Exchange on </td>
    <td>Compete on </td>
    <td>Fire</td>
    <td>Tree</td>
</tr>
<tr>
    <td>Scenario 64</td>
    <td>Conflict on Fire</td>
    <td>None</td>
    <td> </td>
    <td> </td>
    <td>Exchange on </td>
    <td>Coercion on </td>
    <td>Fire</td>
    <td>Tree</td>
</tr>
<tr>
    <td>Scenario 65</td>
    <td>Conflict on Fire</td>
    <td>None</td>
    <td> </td>
    <td> </td>
    <td>Exchange on </td>
    <td>Exchange on </td>
    <td>Fire</td>
    <td>Tree</td>
</tr>
<tr>
    <td>Scenario 66</td>
    <td>Conflict on Fire</td>
    <td>None</td>
    <td> </td>
    <td> </td>
    <td>Exchange on </td>
    <td>None on </td>
    <td>Fire</td>
    <td>Tree</td>
</tr>
<tr>
    <td>Scenario 67</td>
    <td>Conflict on Fire</td>
    <td>None</td>
    <td> </td>
    <td> </td>
    <td>Neutral on </td>
    <td>Cooperate on </td>
    <td>Fire</td>
    <td>Tree</td>
</tr>
<tr>
    <td>Scenario 68</td>
    <td>Conflict on Fire</td>
    <td>None</td>
    <td> </td>
    <td> </td>
    <td>Neutral on </td>
    <td>Conflict on </td>
    <td>Fire</td>
    <td>Tree</td>
</tr>
<tr>
    <td>Scenario 69</td>
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
    <td>Scenario 70</td>
    <td>Conflict on Fire</td>
    <td>None</td>
    <td> </td>
    <td> </td>
    <td>Neutral on </td>
    <td>Coercion on </td>
    <td>Fire</td>
    <td>Tree</td>
</tr>
<tr>
    <td>Scenario 71</td>
    <td>Conflict on Fire</td>
    <td>None</td>
    <td> </td>
    <td> </td>
    <td>Neutral on </td>
    <td>Exchange on </td>
    <td>Fire</td>
    <td>Tree</td>
</tr>
<tr>
    <td>Scenario 72</td>
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
    <td>Scenario 73</td>
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
    <td>Scenario 74</td>
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
    <td>Scenario 75</td>
    <td>Compete on Fire</td>
    <td>None</td>
    <td> </td>
    <td> </td>
    <td>Cooperate on </td>
    <td>Compete on </td>
    <td>Fire</td>
    <td>Tree</td>
</tr>
<tr>
    <td>Scenario 76</td>
    <td>Compete on Fire</td>
    <td>None</td>
    <td> </td>
    <td> </td>
    <td>Cooperate on </td>
    <td>Coercion on </td>
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
    <td>Scenario 78</td>
    <td>Compete on Fire</td>
    <td>None</td>
    <td> </td>
    <td> </td>
    <td>Cooperate on </td>
    <td>None on </td>
    <td>Fire</td>
    <td>Tree</td>
</tr>
<tr>
    <td>Scenario 79</td>
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
    <td>Scenario 80</td>
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
    <td>Scenario 81</td>
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
    <td>Scenario 82</td>
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
    <td>Scenario 83</td>
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
    <td>Scenario 84</td>
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
    <td>Scenario 85</td>
    <td>Compete on Fire</td>
    <td>None</td>
    <td> </td>
    <td> </td>
    <td>Compete on </td>
    <td>Cooperate on </td>
    <td>Fire</td>
    <td>Tree</td>
</tr>
<tr>
    <td>Scenario 86</td>
    <td>Compete on Fire</td>
    <td>None</td>
    <td> </td>
    <td> </td>
    <td>Compete on </td>
    <td>Conflict on </td>
    <td>Fire</td>
    <td>Tree</td>
</tr>
<tr>
    <td>Scenario 87</td>
    <td>Compete on Fire</td>
    <td>None</td>
    <td> </td>
    <td> </td>
    <td>Compete on </td>
    <td>Compete on </td>
    <td>Fire</td>
    <td>Tree</td>
</tr>
<tr>
    <td>Scenario 88</td>
    <td>Compete on Fire</td>
    <td>None</td>
    <td> </td>
    <td> </td>
    <td>Compete on </td>
    <td>Coercion on </td>
    <td>Fire</td>
    <td>Tree</td>
</tr>
<tr>
    <td>Scenario 89</td>
    <td>Compete on Fire</td>
    <td>None</td>
    <td> </td>
    <td> </td>
    <td>Compete on </td>
    <td>Exchange on </td>
    <td>Fire</td>
    <td>Tree</td>
</tr>
<tr>
    <td>Scenario 90</td>
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
    <td>Scenario 91</td>
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
    <td>Scenario 92</td>
    <td>Compete on Fire</td>
    <td>None</td>
    <td> </td>
    <td> </td>
    <td>Coercion on </td>
    <td>Conflict on </td>
    <td>Fire</td>
    <td>Tree</td>
</tr>
<tr>
    <td>Scenario 93</td>
    <td>Compete on Fire</td>
    <td>None</td>
    <td> </td>
    <td> </td>
    <td>Coercion on </td>
    <td>Compete on </td>
    <td>Fire</td>
    <td>Tree</td>
</tr>
<tr>
    <td>Scenario 94</td>
    <td>Compete on Fire</td>
    <td>None</td>
    <td> </td>
    <td> </td>
    <td>Coercion on </td>
    <td>Coercion on </td>
    <td>Fire</td>
    <td>Tree</td>
</tr>
<tr>
    <td>Scenario 95</td>
    <td>Compete on Fire</td>
    <td>None</td>
    <td> </td>
    <td> </td>
    <td>Coercion on </td>
    <td>Exchange on </td>
    <td>Fire</td>
    <td>Tree</td>
</tr>
<tr>
    <td>Scenario 96</td>
    <td>Compete on Fire</td>
    <td>None</td>
    <td> </td>
    <td> </td>
    <td>Coercion on </td>
    <td>None on </td>
    <td>Fire</td>
    <td>Tree</td>
</tr>
<tr>
    <td>Scenario 97</td>
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
    <td>Scenario 98</td>
    <td>Compete on Fire</td>
    <td>None</td>
    <td> </td>
    <td> </td>
    <td>Exchange on </td>
    <td>Conflict on </td>
    <td>Fire</td>
    <td>Tree</td>
</tr>
<tr>
    <td>Scenario 99</td>
    <td>Compete on Fire</td>
    <td>None</td>
    <td> </td>
    <td> </td>
    <td>Exchange on </td>
    <td>Compete on </td>
    <td>Fire</td>
    <td>Tree</td>
</tr>
<tr>
    <td>Scenario 100</td>
    <td>Compete on Fire</td>
    <td>None</td>
    <td> </td>
    <td> </td>
    <td>Exchange on </td>
    <td>Coercion on </td>
    <td>Fire</td>
    <td>Tree</td>
</tr>
<tr>
    <td>Scenario 101</td>
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
    <td>Scenario 102</td>
    <td>Compete on Fire</td>
    <td>None</td>
    <td> </td>
    <td> </td>
    <td>Exchange on </td>
    <td>None on </td>
    <td>Fire</td>
    <td>Tree</td>
</tr>
<tr>
    <td>Scenario 103</td>
    <td>Compete on Fire</td>
    <td>None</td>
    <td> </td>
    <td> </td>
    <td>Neutral on </td>
    <td>Cooperate on </td>
    <td>Fire</td>
    <td>Tree</td>
</tr>
<tr>
    <td>Scenario 104</td>
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
    <td>Scenario 105</td>
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
    <td>Scenario 106</td>
    <td>Compete on Fire</td>
    <td>None</td>
    <td> </td>
    <td> </td>
    <td>Neutral on </td>
    <td>Coercion on </td>
    <td>Fire</td>
    <td>Tree</td>
</tr>
<tr>
    <td>Scenario 107</td>
    <td>Compete on Fire</td>
    <td>None</td>
    <td> </td>
    <td> </td>
    <td>Neutral on </td>
    <td>Exchange on </td>
    <td>Fire</td>
    <td>Tree</td>
</tr>
<tr>
    <td>Scenario 108</td>
    <td>Compete on Fire</td>
    <td>None</td>
    <td> </td>
    <td> </td>
    <td>Neutral on </td>
    <td>None on </td>
    <td>Fire</td>
    <td>Tree</td>
</tr>
<tr>
    <td>Scenario 109</td>
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
    <td>Scenario 110</td>
    <td>Coercion on Fire</td>
    <td>None</td>
    <td> </td>
    <td> </td>
    <td>Cooperate on </td>
    <td>Conflict on </td>
    <td>Fire</td>
    <td>Tree</td>
</tr>
<tr>
    <td>Scenario 111</td>
    <td>Coercion on Fire</td>
    <td>None</td>
    <td> </td>
    <td> </td>
    <td>Cooperate on </td>
    <td>Compete on </td>
    <td>Fire</td>
    <td>Tree</td>
</tr>
<tr>
    <td>Scenario 112</td>
    <td>Coercion on Fire</td>
    <td>None</td>
    <td> </td>
    <td> </td>
    <td>Cooperate on </td>
    <td>Coercion on </td>
    <td>Fire</td>
    <td>Tree</td>
</tr>
<tr>
    <td>Scenario 113</td>
    <td>Coercion on Fire</td>
    <td>None</td>
    <td> </td>
    <td> </td>
    <td>Cooperate on </td>
    <td>Exchange on </td>
    <td>Fire</td>
    <td>Tree</td>
</tr>
<tr>
    <td>Scenario 114</td>
    <td>Coercion on Fire</td>
    <td>None</td>
    <td> </td>
    <td> </td>
    <td>Cooperate on </td>
    <td>None on </td>
    <td>Fire</td>
    <td>Tree</td>
</tr>
<tr>
    <td>Scenario 115</td>
    <td>Coercion on Fire</td>
    <td>None</td>
    <td> </td>
    <td> </td>
    <td>Conflict on </td>
    <td>Cooperate on </td>
    <td>Fire</td>
    <td>Tree</td>
</tr>
<tr>
    <td>Scenario 116</td>
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
    <td>Scenario 117</td>
    <td>Coercion on Fire</td>
    <td>None</td>
    <td> </td>
    <td> </td>
    <td>Conflict on </td>
    <td>Compete on </td>
    <td>Fire</td>
    <td>Tree</td>
</tr>
<tr>
    <td>Scenario 118</td>
    <td>Coercion on Fire</td>
    <td>None</td>
    <td> </td>
    <td> </td>
    <td>Conflict on </td>
    <td>Coercion on </td>
    <td>Fire</td>
    <td>Tree</td>
</tr>
<tr>
    <td>Scenario 119</td>
    <td>Coercion on Fire</td>
    <td>None</td>
    <td> </td>
    <td> </td>
    <td>Conflict on </td>
    <td>Exchange on </td>
    <td>Fire</td>
    <td>Tree</td>
</tr>
<tr>
    <td>Scenario 120</td>
    <td>Coercion on Fire</td>
    <td>None</td>
    <td> </td>
    <td> </td>
    <td>Conflict on </td>
    <td>None on </td>
    <td>Fire</td>
    <td>Tree</td>
</tr>
<tr>
    <td>Scenario 121</td>
    <td>Coercion on Fire</td>
    <td>None</td>
    <td> </td>
    <td> </td>
    <td>Compete on </td>
    <td>Cooperate on </td>
    <td>Fire</td>
    <td>Tree</td>
</tr>
<tr>
    <td>Scenario 122</td>
    <td>Coercion on Fire</td>
    <td>None</td>
    <td> </td>
    <td> </td>
    <td>Compete on </td>
    <td>Conflict on </td>
    <td>Fire</td>
    <td>Tree</td>
</tr>
<tr>
    <td>Scenario 123</td>
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
    <td>Scenario 124</td>
    <td>Coercion on Fire</td>
    <td>None</td>
    <td> </td>
    <td> </td>
    <td>Compete on </td>
    <td>Coercion on </td>
    <td>Fire</td>
    <td>Tree</td>
</tr>
<tr>
    <td>Scenario 125</td>
    <td>Coercion on Fire</td>
    <td>None</td>
    <td> </td>
    <td> </td>
    <td>Compete on </td>
    <td>Exchange on </td>
    <td>Fire</td>
    <td>Tree</td>
</tr>
<tr>
    <td>Scenario 126</td>
    <td>Coercion on Fire</td>
    <td>None</td>
    <td> </td>
    <td> </td>
    <td>Compete on </td>
    <td>None on </td>
    <td>Fire</td>
    <td>Tree</td>
</tr>
<tr>
    <td>Scenario 127</td>
    <td>Coercion on Fire</td>
    <td>None</td>
    <td> </td>
    <td> </td>
    <td>Coercion on </td>
    <td>Cooperate on </td>
    <td>Fire</td>
    <td>Tree</td>
</tr>
<tr>
    <td>Scenario 128</td>
    <td>Coercion on Tree</td>
    <td>None</td>
    <td>Fire</td>
    <td>Tree</td>
    <td>Coercion on Fire</td>
    <td>Conflict on Tree</td>
    <td>Tree</td>
    <td>Fire</td>
</tr>
<tr>
    <td>Scenario 129</td>
    <td>Coercion on Fire</td>
    <td>None</td>
    <td> </td>
    <td> </td>
    <td>Coercion on </td>
    <td>Compete on </td>
    <td>Fire</td>
    <td>Tree</td>
</tr>
<tr>
    <td>Scenario 130</td>
    <td>Coercion on Fire</td>
    <td>None</td>
    <td> </td>
    <td> </td>
    <td>Coercion on </td>
    <td>Coercion on </td>
    <td>Fire</td>
    <td>Tree</td>
</tr>
<tr>
    <td>Scenario 131</td>
    <td>Coercion on Fire</td>
    <td>None</td>
    <td> </td>
    <td> </td>
    <td>Coercion on </td>
    <td>Exchange on </td>
    <td>Fire</td>
    <td>Tree</td>
</tr>
<tr>
    <td>Scenario 132</td>
    <td>Coercion on Fire</td>
    <td>None</td>
    <td> </td>
    <td> </td>
    <td>Coercion on </td>
    <td>None on </td>
    <td>Fire</td>
    <td>Tree</td>
</tr>
<tr>
    <td>Scenario 133</td>
    <td>Coercion on Fire</td>
    <td>None</td>
    <td> </td>
    <td> </td>
    <td>Exchange on </td>
    <td>Cooperate on </td>
    <td>Fire</td>
    <td>Tree</td>
</tr>
<tr>
    <td>Scenario 134</td>
    <td>Coercion on Fire</td>
    <td>None</td>
    <td> </td>
    <td> </td>
    <td>Exchange on </td>
    <td>Conflict on </td>
    <td>Fire</td>
    <td>Tree</td>
</tr>
<tr>
    <td>Scenario 135</td>
    <td>Coercion on Fire</td>
    <td>None</td>
    <td> </td>
    <td> </td>
    <td>Exchange on </td>
    <td>Compete on </td>
    <td>Fire</td>
    <td>Tree</td>
</tr>
<tr>
    <td>Scenario 136</td>
    <td>Coercion on Fire</td>
    <td>None</td>
    <td> </td>
    <td> </td>
    <td>Exchange on </td>
    <td>Coercion on </td>
    <td>Fire</td>
    <td>Tree</td>
</tr>
<tr>
    <td>Scenario 137</td>
    <td>Coercion on Fire</td>
    <td>None</td>
    <td> </td>
    <td> </td>
    <td>Exchange on </td>
    <td>Exchange on </td>
    <td>Fire</td>
    <td>Tree</td>
</tr>
<tr>
    <td>Scenario 138</td>
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
    <td>Scenario 139</td>
    <td>Coercion on Fire</td>
    <td>None</td>
    <td> </td>
    <td> </td>
    <td>Neutral on </td>
    <td>Cooperate on </td>
    <td>Fire</td>
    <td>Tree</td>
</tr>
<tr>
    <td>Scenario 140</td>
    <td>Coercion on Fire</td>
    <td>None</td>
    <td> </td>
    <td> </td>
    <td>Neutral on </td>
    <td>Conflict on </td>
    <td>Fire</td>
    <td>Tree</td>
</tr>
<tr>
    <td>Scenario 141</td>
    <td>Coercion on Fire</td>
    <td>None</td>
    <td> </td>
    <td> </td>
    <td>Neutral on </td>
    <td>Compete on </td>
    <td>Fire</td>
    <td>Tree</td>
</tr>
<tr>
    <td>Scenario 142</td>
    <td>Coercion on Fire</td>
    <td>None</td>
    <td> </td>
    <td> </td>
    <td>Neutral on </td>
    <td>Coercion on </td>
    <td>Fire</td>
    <td>Tree</td>
</tr>
<tr>
    <td>Scenario 143</td>
    <td>Coercion on Fire</td>
    <td>None</td>
    <td> </td>
    <td> </td>
    <td>Neutral on </td>
    <td>Exchange on </td>
    <td>Fire</td>
    <td>Tree</td>
</tr>
<tr>
    <td>Scenario 144</td>
    <td>Coercion on Fire</td>
    <td>None</td>
    <td> </td>
    <td> </td>
    <td>Neutral on </td>
    <td>None on </td>
    <td>Fire</td>
    <td>Tree</td>
</tr>
<tr>
    <td>Scenario 145</td>
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
    <td>Scenario 146</td>
    <td>Exchange on Fire</td>
    <td>None</td>
    <td> </td>
    <td> </td>
    <td>Cooperate on </td>
    <td>Conflict on </td>
    <td>Fire</td>
    <td>Tree</td>
</tr>
<tr>
    <td>Scenario 147</td>
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
    <td>Scenario 148</td>
    <td>Exchange on Fire</td>
    <td>None</td>
    <td> </td>
    <td> </td>
    <td>Cooperate on </td>
    <td>Coercion on </td>
    <td>Fire</td>
    <td>Tree</td>
</tr>
<tr>
    <td>Scenario 149</td>
    <td>Exchange on Fire</td>
    <td>None</td>
    <td> </td>
    <td> </td>
    <td>Cooperate on </td>
    <td>Exchange on </td>
    <td>Fire</td>
    <td>Tree</td>
</tr>
<tr>
    <td>Scenario 150</td>
    <td>Exchange on Fire</td>
    <td>None</td>
    <td> </td>
    <td> </td>
    <td>Cooperate on </td>
    <td>None on </td>
    <td>Fire</td>
    <td>Tree</td>
</tr>
<tr>
    <td>Scenario 151</td>
    <td>Exchange on Fire</td>
    <td>None</td>
    <td> </td>
    <td> </td>
    <td>Conflict on </td>
    <td>Cooperate on </td>
    <td>Fire</td>
    <td>Tree</td>
</tr>
<tr>
    <td>Scenario 152</td>
    <td>Exchange on Fire</td>
    <td>None</td>
    <td> </td>
    <td> </td>
    <td>Conflict on </td>
    <td>Conflict on </td>
    <td>Fire</td>
    <td>Tree</td>
</tr>
<tr>
    <td>Scenario 153</td>
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
    <td>Scenario 154</td>
    <td>Exchange on Fire</td>
    <td>None</td>
    <td> </td>
    <td> </td>
    <td>Conflict on </td>
    <td>Coercion on </td>
    <td>Fire</td>
    <td>Tree</td>
</tr>
<tr>
    <td>Scenario 155</td>
    <td>Exchange on Fire</td>
    <td>None</td>
    <td> </td>
    <td> </td>
    <td>Conflict on </td>
    <td>Exchange on </td>
    <td>Fire</td>
    <td>Tree</td>
</tr>
<tr>
    <td>Scenario 156</td>
    <td>Exchange on Fire</td>
    <td>None</td>
    <td> </td>
    <td> </td>
    <td>Conflict on </td>
    <td>None on </td>
    <td>Fire</td>
    <td>Tree</td>
</tr>
<tr>
    <td>Scenario 157</td>
    <td>Exchange on Fire</td>
    <td>None</td>
    <td> </td>
    <td> </td>
    <td>Compete on </td>
    <td>Cooperate on </td>
    <td>Fire</td>
    <td>Tree</td>
</tr>
<tr>
    <td>Scenario 158</td>
    <td>Exchange on Fire</td>
    <td>None</td>
    <td> </td>
    <td> </td>
    <td>Compete on </td>
    <td>Conflict on </td>
    <td>Fire</td>
    <td>Tree</td>
</tr>
<tr>
    <td>Scenario 159</td>
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
    <td>Scenario 160</td>
    <td>Exchange on Fire</td>
    <td>None</td>
    <td> </td>
    <td> </td>
    <td>Compete on </td>
    <td>Coercion on </td>
    <td>Fire</td>
    <td>Tree</td>
</tr>
<tr>
    <td>Scenario 161</td>
    <td>Exchange on Fire</td>
    <td>None</td>
    <td> </td>
    <td> </td>
    <td>Compete on </td>
    <td>Exchange on </td>
    <td>Fire</td>
    <td>Tree</td>
</tr>
<tr>
    <td>Scenario 162</td>
    <td>Exchange on Fire</td>
    <td>None</td>
    <td> </td>
    <td> </td>
    <td>Compete on </td>
    <td>None on </td>
    <td>Fire</td>
    <td>Tree</td>
</tr>
<tr>
    <td>Scenario 163</td>
    <td>Exchange on Fire</td>
    <td>None</td>
    <td> </td>
    <td> </td>
    <td>Coercion on </td>
    <td>Cooperate on </td>
    <td>Fire</td>
    <td>Tree</td>
</tr>
<tr>
    <td>Scenario 164</td>
    <td>Exchange on Fire</td>
    <td>None</td>
    <td> </td>
    <td> </td>
    <td>Coercion on </td>
    <td>Conflict on </td>
    <td>Fire</td>
    <td>Tree</td>
</tr>
<tr>
    <td>Scenario 165</td>
    <td>Exchange on Fire</td>
    <td>None</td>
    <td> </td>
    <td> </td>
    <td>Coercion on </td>
    <td>Compete on </td>
    <td>Fire</td>
    <td>Tree</td>
</tr>
<tr>
    <td>Scenario 166</td>
    <td>Exchange on Fire</td>
    <td>None</td>
    <td> </td>
    <td> </td>
    <td>Coercion on </td>
    <td>Coercion on </td>
    <td>Fire</td>
    <td>Tree</td>
</tr>
<tr>
    <td>Scenario 167</td>
    <td>Exchange on Fire</td>
    <td>None</td>
    <td> </td>
    <td> </td>
    <td>Coercion on </td>
    <td>Exchange on </td>
    <td>Fire</td>
    <td>Tree</td>
</tr>
<tr>
    <td>Scenario 168</td>
    <td>Exchange on Fire</td>
    <td>None</td>
    <td> </td>
    <td> </td>
    <td>Coercion on </td>
    <td>None on </td>
    <td>Fire</td>
    <td>Tree</td>
</tr>
<tr>
    <td>Scenario 169</td>
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
    <td>Scenario 170</td>
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
    <td>Scenario 171</td>
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
    <td>Scenario 172</td>
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
    <td>Scenario 173</td>
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
    <td>Scenario 174</td>
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
    <td>Scenario 175</td>
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
    <td>Scenario 176</td>
    <td>Exchange on Fire</td>
    <td>None</td>
    <td> </td>
    <td> </td>
    <td>Neutral on </td>
    <td>Conflict on </td>
    <td>Fire</td>
    <td>Tree</td>
</tr>
<tr>
    <td>Scenario 177</td>
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
    <td>Scenario 178</td>
    <td>Exchange on Fire</td>
    <td>None</td>
    <td> </td>
    <td> </td>
    <td>Neutral on </td>
    <td>Coercion on </td>
    <td>Fire</td>
    <td>Tree</td>
</tr>
<tr>
    <td>Scenario 179</td>
    <td>Exchange on Fire</td>
    <td>None</td>
    <td> </td>
    <td> </td>
    <td>Neutral on </td>
    <td>Exchange on </td>
    <td>Fire</td>
    <td>Tree</td>
</tr>
<tr>
    <td>Scenario 180</td>
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
