<frontmatter>
title: "Participation dashboard"
</frontmatter>

<h1 class="display-4">Participation dashboard</h1>

<box>

* Details about participation marks calculations are [here]({{ url_module_website }}{{ '/admin/index.html#assessment' if tic2002 else '/admin/participation.html' }}).
* The important column of the table below is the <span class="text-monospace">==Weeks participated==</span> column. It tells you how many weeks in which you have met _participation bar_ %%(i.e., scored more than half of the participation points)%%.
* Meaning of colors/icons:
  * %%{{ icon_info }}%% : you can click on this icon to find more info
  * <span class="badge bg-success">N</span> : you reached the participation bar for week `N`
  * <span class="badge bg-warning text-dark">~~N~~</span> : you earned _some_ participation points in the week `N` but fell short of the participation bar for that week (these _tried-but-fell-short_ weeks are not normally counted for participation, but they could be given _some_ consideration if you failed to earn full participation marks at the end)
  * <span class="badge bg-danger">~~N~~</span> : you did not earn _any_ participation points for week `N`{% if cs2103 %}
* Note: The weekly Canvas quiz percentage can exceed `100%` if the quiz contains bonus questions %%(they are not penalized for incorrect answers, but given credit for correct answers)%%.{% endif %}
* If you have queries about the participation marks, please email `{{ module | lower }}@comp.nus.edu.sg`.
* This dashboard is **updated weekly**.
</box>

<include src="{{ module | lower }}/participation-table-fragment.md" />
