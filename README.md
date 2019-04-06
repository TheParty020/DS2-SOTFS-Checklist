# DS2-SOTFS-Checklist
.in_progress,
.done {
  color: #C60;
  border: 1px solid;
  border-radius: 3px;
  padding: .1em 0.4em;
  font-weight: normal;
  margin-left: .2em;
  vertical-align: middle;
  font-size: 0.9em;
}
.done { color: #009933; }

@media print {
    body { color: #000; }
    .navbar, #intro, input[type="checkbox"], .done, .in_progress { display: none; }
    a { color: #000; text-decoration: underline; }
    a[href]:after { content: none !important; }
    .tab-content > .tab-pane, .pill-content > .pill-pane { display: block; }
    .tab-pane { page-break-after: always; }
}

ul {
  list-style-type: none;
	padding-left: 22px;
}
ul li ul {
  padding-top: 0;
}
h3 {
  margin-bottom: 0;
}
.checkbox label,
.radio label {
  padding-left: 24px;
}
.checkbox input[type=checkbox],
.checkbox-inline input[type=checkbox],
.radio input[type=radio],
.radio-inline input[type=radio] {
  margin-left: -24px;
}

.table_of_contents {
  margin-left: 0;
  padding: 0;
  line-height: 1.8;
}

.highlight {
    background-color: rgb(255, 246, 18);
}

.hiddenfile {
 width: 0px;
 height: 0px;
 overflow: hidden;
}

.back-to-top {
	position: fixed;
	bottom: 2em;
	right: 0px;
	text-decoration: none;
	color: #000000;
	background-color: rgba(235, 235, 235, 0.80);
	font-size: 12px;
	padding: 1em;
	display: none;
}

.back-to-top:hover{
	background-color: rgba(135, 135, 135, 0.50);
}

.btn-collapse {
  padding: 4px 10px 1px;
  margin-right: 10px;
  vertical-align: top;
}

.btn:focus, .btn.active:focus {
    outline: none;
    outline: 0;
}

.btn.filter-inactive .glyphicon-eye-close {
display: inline-block;
}
.btn.filter-inactive .glyphicon-eye-close {
display: none;
}
.btn.filter-active .glyphicon-eye-open {
display: inline-block;
}
.btn.filter-active .glyphicon-eye-open {
display: none;
}

/* Icon when the collapsible content is shown */
.btn-collapse:after {
  font-family: 'Glyphicons Halflings';
  content:"\e082";
}
/* Icon when the collapsible content is hidden */
.btn-collapse.collapsed:after {
  content:"\e081";
}

h1 {
  margin-top: 0;
  margin-bottom: 20px;
}

body.hide_completed .completed {
  display: none !important;
}

input[type="checkbox"]:checked + .item_content {
  text-decoration: line-through;
}

input[type="checkbox"] ~ .glyphicon-eye-close { display:none; }

input[type="checkbox"]:checked ~ .glyphicon-eye-close { display: inline-block; }

input[type="checkbox"] ~ .glyphicon-eye-open { display: inline-block; }

input[type="checkbox"]:checked ~ .glyphicon-eye-open { display: none; }
