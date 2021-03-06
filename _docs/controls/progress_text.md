---
title: Progress text
category: Controls
type: Subpage
subpageOf: Progress indicators
---

![]({{site.baseurl}}/images/progress_text/desc.png)

## When to use

Follow the rules for [progress indicators]({{site.baseurl}}/controls/progress_indicators).

## How to use

### Process name

Use the progressive form of the verb which describes the process, for example:
![]({{site.baseurl}}/images/progress_text/progressive_form.png)
Add an ellipsis at the end to show that an action is in progress. 

Use sentence case for process names.

A process name remains unchanged while the process runs.

Do not animate the ellipsis, it attracts too much attention. The progressive verb form, the text position and the style are enough to understand that this is an action in progress.

### Details

Use sentence case for details.

Do not provide details that are meaningless for the user, for example, "Please wait":
<p class='label incorrect'>Incorrect</p>
![]({{site.baseurl}}/images/progress_text/meaningless.png)

Add time units if the remaining time can be predicted. 
  
<p class="noanchor">Round up the first time unit to one of the following numeric anchors: 1, 2, 3, 5, 10, 15, 20 and 30. For example, if there are 7 minutes and 50 seconds remaining, the progress text should read "About 10 minutes left". If less than 5 seconds are left, it should say “About 5 seconds left”.</p>
![]({{site.baseurl}}/images/progress_text/time.png)

Use work units if the remaining time cannot be predicted, as they help the user understand why the process takes so long.

<p class="noanchor">Work units: the current step, the currently processed file, the number of processed files/the amount of information, the percentage of work completed, and so on:</p>
![]({{site.baseurl}}/images/progress_text/work.png)
  

The time passed if the user controls the process, for example, needs to stop it after a certain time:
![]({{site.baseurl}}/images/progress_text/passed.png)

<p class="noanchor">Update the timer every second.</p>

### Cancellation action

If the process can be cancelled, add a [link]({{site.baseurl}}/controls/link) for the cancel action for an empty state:
![]({{site.baseurl}}/images/progress_text/cancellation.png)
  

Use title case for the cancel action.

Replace progress text with the loaded data or an [empty state]({{site.baseurl}}/principles/empty_state) when the process has finished. Show another progress indicator, e.g. a loader as in the example below, if loading continues after some data has been displayed. 
![]({{site.baseurl}}/images/progress_indicators/empty_state_text.png)

### Trees

Do not show details or a link to cancel the operation for progress in trees and lists. Only show the process name since space is limited here.

## Sizes and placement

### Empty state

Center-align the first line of the progress text if it is no longer than 200px. If it is longer than 200px, center-align characters from the first 200px and put the rest of the characters to the right.

Left-align subsequent lines with the first line. 

Minimum text width is 40 characters. If an area is too narrow to fit the minimum text width, show text using the whole width, including margins. If no space is left, hide the text under area borders.

Wrap text when the area’s width changes.

Fields and vertical spaces:![]({{site.baseurl}}/images/progress_text/fields.png)

### Tree
![]({{site.baseurl}}/images/progress_text/tree.png)

## Style

Font color is the same as for [Empty state]({{site.baseurl}}/principles/empty_state/#layout-and-colors) text.

