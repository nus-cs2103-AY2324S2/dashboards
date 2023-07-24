<head-bottom>
  <link rel="stylesheet" href="{{baseUrl}}/stylesheets/main.css">
</head-bottom>

<header fixed>
{% if archived %}
<div class="w-100 p-1 bg-danger text-center text-warning d-print-none"><md>**This site is from a past semester!**</md></div>
{% endif %}
  <navbar type="dark">
    <a slot="brand" href="{{url_module_website}}" title="Home" class="navbar-brand"> {{ badge_main_site }}</a>
    <li><a href="{{baseUrl}}/index.html" class="nav-link"><md>Dashboards home</md></a></li>
    <li tags="m--cs2103 m--cs2113 m--tic2002 m--tic4001 m--tic4002"><a href="{{baseUrl}}/contents/participation.html" class="nav-link"><md>**Participation dashboard**</md></a></li>
    <li tags="m--cs2103 m--cs2113 m--tic4002"><a href="{{baseUrl}}/contents/forum-activities.html" class="nav-link"><md>**Forum dashboard**</md></a></li>
    <dropdown tags="m--cs2103 m--cs2113 m--tic4001 m--tic4002" header="**iP dashboards**" class="nav-link">
      <li><a href="{{baseUrl}}/contents/ip-progress.html" class="dropdown-item"><md>:fas-tasks: iP progress</md></a></li>
      <li><a href="{{baseUrl}}/contents/ip-comments.html" class="dropdown-item"><md>:octicon-comment: iP comments</md></a></li>
      <li><a href="{{ url_ip_dashboard }}" target="_blank" class="dropdown-item"><md>:fas-chart-area: iP Code</md></a></li>
    </dropdown>
    <dropdown tags="m--cs2103 m--cs2113 m--tic4001 m--tic4002" header="**tP dashboards**" class="nav-link">
      <li><a href="{{baseUrl}}/contents/tp-progress.html" class="dropdown-item"><md>:fas-tasks: tP progress</md></a></li>
      <li><a href="{{baseUrl}}/contents/tp-comments.html" class="dropdown-item"><md>tP comments</md></a></li>
      <li><a href="{{ url_tp_dashboard }}" target="_blank" class="dropdown-item"><md>:fas-chart-area: tP Code</md></a></li>
    </dropdown>
  </navbar>
</header>
<div id="flex-body">
  <div id="content-wrapper" class="fixed-header-padding">
    {{ content }}
  </div>
  <nav id="page-nav" class="fixed-header-padding">
    <div class="nav-component slim-scroll">
      <page-nav />
    </div>
  </nav>
<scroll-top-button/>
</div>
<footer>
  <div class="text-center">
    <small>[<md>**Powered by**</md> <img src="https://markbind.org/favicon.ico" width="30"> {{MarkBind}}, generated on {{timestamp}}]</small>
  </div>
</footer>
