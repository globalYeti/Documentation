---
title:  Episode
summary: "Track information at the highest level, stored in the context of the episode, covering the whole span of time of the trading session. On this page: Serial Number, Identifier, Begin, End, Begin Rate, End Rate, Status, and Exit Type."
sidebar: suite_sidebar
permalink: suite-trading-engine-episode.html
toc: false
---


{% include /trading_engine/episode.md more="no" heading="" icon="150" definition="bold" table="yes" content="yes" adding="" configuring="" starting="" %}

{% include note.html content="Find below the data structure under the episode node, including concepts covered in detail elsewhere. Hover your mouse over a node for a tooltip definition." %}

<table class='hierarchyTable'><thead><tr><th><a href='#episode' data-toggle='tooltip' data-original-title='{{site.data.trading_engine.episode}}'><img src='images/icons/nodes/png50/episode.png' /><br />Episode</a></th><th></th><th></th><th></th><th></th><th></th><th></th><th></th><th></th><th></th></tr></thead><tbody>
<tr><td><img src='images/icons/various/png/tree-connector-fork.png' /></td><td><a href='#serial-number' data-toggle='tooltip' data-original-title='{{site.data.trading_engine.serial_number}}'><img src='images/icons/nodes/png50/serial-number.png' /><br />Serial Number</a></td><td></td><td></td><td></td><td></td><td></td><td></td><td></td><td></td></tr>
<tr><td><img src='images/icons/various/png/tree-connector-fork.png' /></td><td><a href='#identifier' data-toggle='tooltip' data-original-title='{{site.data.trading_engine.identifier}}'><img src='images/icons/nodes/png50/identifier.png' /><br />Identifier</a></td><td></td><td></td><td></td><td></td><td></td><td></td><td></td><td></td></tr>
<tr><td><img src='images/icons/various/png/tree-connector-fork.png' /></td><td><a href='#begin' data-toggle='tooltip' data-original-title='{{site.data.trading_engine.begin}}'><img src='images/icons/nodes/png50/begin.png' /><br />Begin</a></td><td></td><td></td><td></td><td></td><td></td><td></td><td></td><td></td></tr>
<tr><td><img src='images/icons/various/png/tree-connector-fork.png' /></td><td><a href='#end' data-toggle='tooltip' data-original-title='{{site.data.trading_engine.end}}'><img src='images/icons/nodes/png50/end.png' /><br />End</a></td><td></td><td></td><td></td><td></td><td></td><td></td><td></td><td></td></tr>
<tr><td><img src='images/icons/various/png/tree-connector-fork.png' /></td><td><a href='#begin-rate' data-toggle='tooltip' data-original-title='{{site.data.trading_engine.begin_rate}}'><img src='images/icons/nodes/png50/begin-rate.png' /><br />Begin Rate</a></td><td></td><td></td><td></td><td></td><td></td><td></td><td></td><td></td></tr>
<tr><td><img src='images/icons/various/png/tree-connector-fork.png' /></td><td><a href='#end-rate' data-toggle='tooltip' data-original-title='{{site.data.trading_engine.end_rate}}'><img src='images/icons/nodes/png50/end-rate.png' /><br />End Rate</a></td><td></td><td></td><td></td><td></td><td></td><td></td><td></td><td></td></tr>
<tr><td><img src='images/icons/various/png/tree-connector-fork.png' /></td><td><a href='#status' data-toggle='tooltip' data-original-title='{{site.data.trading_engine.status}}'><img src='images/icons/nodes/png50/status.png' /><br />Status</a></td><td></td><td></td><td></td><td></td><td></td><td></td><td></td><td></td></tr>
<tr><td><img src='images/icons/various/png/tree-connector-fork.png' /></td><td><a href='#exit-type' data-toggle='tooltip' data-original-title='{{site.data.trading_engine.exit_type}}'><img src='images/icons/nodes/png50/exit-type.png' /><br />Exit Type</a></td><td></td><td></td><td></td><td></td><td></td><td></td><td></td><td></td></tr>
<tr><td><img src='images/icons/various/png/tree-connector-fork.png' /></td><td><a href='#episode-base-asset' data-toggle='tooltip' data-original-title='{{site.data.trading_engine.episode_base_asset}}'><img src='images/icons/nodes/png50/episode-base-asset.png' /><br />Episode Base Asset</a></td><td></td><td></td><td></td><td></td><td></td><td></td><td></td><td></td></tr>
<tr><td><img src='images/icons/various/png/tree-connector-fork.png' /></td><td><a href='#episode-quoted-asset' data-toggle='tooltip' data-original-title='{{site.data.trading_engine.episode_quoted_asset}}'><img src='images/icons/nodes/png50/episode-quoted-asset.png' /><br />Episode Quoted Asset</a></td><td></td><td></td><td></td><td></td><td></td><td></td><td></td><td></td></tr>
<tr><td><img src='images/icons/various/png/tree-connector-fork.png' /></td><td><a href='#episode-counters' data-toggle='tooltip' data-original-title='{{site.data.trading_engine.episode_counters}}'><img src='images/icons/nodes/png50/episode-counters.png' /><br />Episode Counters</a></td><td></td><td></td><td></td><td></td><td></td><td></td><td></td><td></td></tr>
<tr><td><img src='images/icons/various/png/tree-connector-fork.png' /></td><td><a href='#episode-statistics' data-toggle='tooltip' data-original-title='{{site.data.trading_engine.episode_statistics}}'><img src='images/icons/nodes/png50/episode-statistics.png' /><br />Episode Statistics</a></td><td></td><td></td><td></td><td></td><td></td><td></td><td></td><td></td></tr>
<tr><td><img src='images/icons/various/png/tree-connector-fork.png' /></td><td><a href='#distance-to-event' data-toggle='tooltip' data-original-title='{{site.data.trading_engine.distance_to_event}}'><img src='images/icons/nodes/png50/distance-to-event.png' /><br />Distance to Event</a></td><td></td><td></td><td></td><td></td><td></td><td></td><td></td><td></td></tr>
<tr><td><img src='images/icons/various/png/tree-connector-fork.png' /></td><td><a href='#candle' data-toggle='tooltip' data-original-title='{{site.data.trading_engine.candle}}'><img src='images/icons/nodes/png50/candle.png' /><br />Candle</a></td><td></td><td></td><td></td><td></td><td></td><td></td><td></td><td></td></tr>
<tr><td><img src='images/icons/various/png/tree-connector-elbow.png' /></td><td><a href='#cycle' data-toggle='tooltip' data-original-title='{{site.data.trading_engine.cycle}}'><img src='images/icons/nodes/png50/cycle.png' /><br />Cycle</a></td><td></td><td></td><td></td><td></td><td></td><td></td><td></td><td></td></tr></tbody></table>

