# SafeHarbor

SafeHarbor is an open source DevOps platform that integrates many of the tasks
associated with coding, testing, governing, and deploying microservice centric
and component centric applications.

In the spirit of microservices, SafeHarbor itself is a componentized system,
consisting of many independently usable microservices, and many independent
Web components. One can literally mix and match these, or one can use the
entire suite.




![SafeHarbor Integrated View](SafeHarbor_Integrated_View.png "SafeHarbor Integrated View")

SafeHarbor supports unmet needs in today’s microservice-centric and component centric
software development/deployment lifecycle, specifically,

<ol>
<li>Support development of microservices.</li>
	<ol>
	<li>Current tools do not help developers to track which services they are
	working on, or which are affected by code changes or API changes.</li>
	<li>Current “Agile” tools do not help developers to plan work in terms of the
	microservices and UI components that comprise the application.</li>
	</ol>
</li>
<li>Support governance needs.
	<ol>
	<li>Current “Agile” tools have major traceability gaps between features, tests,
	data models, and deployments.</li>
	</ol>

<li>Support DevOps needs.
	<ol>
	<li>Current tools do not enable one to define a build/test process in a robust
	and unified way.</li>
	</ol>
</li>

<li>Support reliable DevOps.
	<ol>
	<li>Current tools are based on scripting, schema-free data structures (JSON, YAML),
	or extensions to general purpose languages that have poor software engineering
	characteristics, and thus violate software engineering principles that are
	important for reliability and maintainability. The current tools therefore
	do not adequately support viewing infrastructure “as code”, given that
	reliable and maintainable code are essential for infrastructure.</li>
	</ol>
</li>

<li>Support API management.
	<ol>
	<li>Current “Agile” work planning tools do not integrate API management,
	and thus developers need to separately track APIs. (See 1.i above.)</li>
	</ol>
</li>
</ol>
