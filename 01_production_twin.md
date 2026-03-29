---
layout: landing
title: Digital Production Twin
description: Shopfloor planning and simulation
image: assets/images/Projects/DigitalProductionTwin/DigitalProductionTwin_06.jpg
nav-menu: true
---

<hr/>
<!-- Main -->
<div id="main">
<section id="two" class="spotlights">
	<section>
		<a href="assets/images/Projects/DigitalProductionTwin/DigitalProductionTwin_06.jpg" class="image">
		<img src="{% link assets/images/Projects/DigitalProductionTwin/DigitalProductionTwin_06.jpg %}" alt="" data-position="center center" />
		</a>
		<div class="content">
			<div class="inner">
				<header class="major">
					<h3>Project Goal</h3>
				</header>
				<p>3D Digital Twin to simulate a virtual space providing functionality to iterate over layout variants of a production facility. The toolset includes the management of 3D models of unique objects (from drawers/shelves to lithography systems and CNC Machines) and analysis of configuration such as distance measuring, dimensions, boundaries etc. <br/>The core application facilitates extensibility and adaptation to different types of shopfloor plans (manufacturing, montage, recycling, semiconductor etc.).</p>
			</div>
		</div>
	</section>
	<section>
		<a href="assets/images/Projects/DigitalProductionTwin/Blueprints_vs_Cpp_Alex_Forsythe.jpg" class="image">
			<img src="{% link assets/images/Projects/DigitalProductionTwin/Blueprints_vs_Cpp_Alex_Forsythe.jpg %}" alt="" data-position="center center" />
		</a>
		<div class="content">
			<div class="inner">
				<header class="major">
					<h3>Development</h3>
				</header>
				<p><b>Unreal Engine 5.3</b> features as the base development framework balancing the usage of C++ and Blueprints to enable all contributors including Designers and 3D Artists to make changes and integrate assets into the project through UI elements without special programming knowledge.
        The core functionality contains multiple solutions of the Epic Games` project <b>Lyra</b> and its best practices (Procedural Level generation, Gameplay Ability System, GameplayTags, UI layouts etc.), which combines with its another tool Modular Game Features for further customizations.
        </p>
			</div>
		</div>
	</section>
</section>

<!-- One -->
<section id="one">
	<div class="inner">
	<div class="row">
        		<ul>
       			<li><a href="#performance">C++ Programming & Performance</a></li>
       			<li><a href="#scene">Scene assembly, shading and lighting</a></li>
       			<li><a href="#blueprints">Blueprints</a></li>
            <li><a href="#vr">VR Trainings</a></li>
        		</ul>
       	</div>
<h2 id="performance">C++ Programming & Performance</h2>
<span class="image fit"><img src="{% link assets/images/Projects/DigitalProductionTwin/DigitalProductionTwin_02.jpg %}" alt="" /></span>
<p>A custom module as the entry-point for all customer CAD-data using also DataPrep and (Runtime-)DataSmith allows to load provided 3D data in editor libraries as well as in runtime.</p>
<!--<h3>Scene assembly</h3>-->
<div class="row">
<div class="6u 12u$(medium)">
	<p><span class="image left">
	<a href="assets/images/Projects/DigitalProductionTwin/DigitalProductionTwin_01_scene_assembly.jpg" class="image">
	<img src="{% link assets/images/Projects/DigitalProductionTwin/DigitalProductionTwin_01_scene_assembly.jpg %}" alt="" />
	</a>
	</span>
	<b>Object management</b><br/>
	Combination with C++ makes it possible to process large object datasets maintaining the required FPS (Frames Per Second).
	</p>
</div>
<div class="6u$ 12u$(medium)">
	<p><span class="image right">
	<a href="assets/images/Projects/DigitalProductionTwin/DigitalProductionTwin_02_scene_assembly.jpg" class="image">
	<img src="{% link assets/images/Projects/DigitalProductionTwin/DigitalProductionTwin_02_scene_assembly.jpg %}" alt="" />
	</a>
	</span>
	<b>Modular design</b><br/>
	The main content modules subsystem represents storage of isolated datasets. The modular nature of the asset management makes visual adjustments easier allowing changing / delivering of new 3D data without reworking application's core functionality.</p>
</div>
</div>
<h2 id="scene">Scene assembly, shading and lighting</h2>
<span class="image fit"><img src="{% link assets/images/Projects/DigitalProductionTwin/DigitalProductionTwin_04.jpg %}" alt="" /></span>
<p><span class="image left"><img src="{% link assets/images/Projects/DigitalProductionTwin/DigitalProductionTwin_03.jpg %}" alt="" /></span>
A more thorough visual analysis and first-person view control is possible thanks to multiple view modes in the camera subsystem. Many spatial geometrical issues are easier to spot from different view angles at the same time displaying the 3D layout for various purposes - from developing new layouts to refining an object placement.</p>
<div class="row">
<div class="6u 12u$(medium)">
	<p><span class="image left">
	<a href="assets/images/Projects/DigitalProductionTwin/DigitalProductionTwin_06_shading.jpg" class="image">
	<img src="{% link assets/images/Projects/DigitalProductionTwin/DigitalProductionTwin_06_shading.jpg %}" alt="" />
	</a>
	</span>
	<b>3D Library Automation</b><br/>
	Each 3D model has an appropriate autogenerated thumbnail for UI to identify it in the scene for a pick-and-place interaction system.</p>
</div>
<div class="6u$ 12u$(medium)">
	<p><span class="image right">
	<a href="assets/images/Projects/DigitalProductionTwin/DigitalProductionTwin_04_lighting.jpg" class="image">
	<img src="{% link assets/images/Projects/DigitalProductionTwin/DigitalProductionTwin_04_lighting.jpg %}" alt="" />
	</a>
	</span>
	<b>Lighting</b><br/>
	Switching between indoor and outdoor lighting conditions is implemented through the level streaming. Uniquely created for each project to meet client`s requirements.</p>
</div>
</div>
<h2 id="blueprints">Blueprints</h2>
<span class="image fit"><img src="{% link assets/images/Projects/DigitalProductionTwin/DigitalProductionTwin_06.jpg %}" alt="" /></span>
<span class="image left"><img src="{% link assets/images/Projects/DigitalProductionTwin/DigitalProductionTwin_07.jpg %}" alt="" /></span>
Special requirements in layout are integrated by modular game features. Decoupling feature developement from the core makes collaboration more flexible by parallel task assignment between contributors. Standardization of plugin developement also increase feature reusability between projects and speed up onboarding of the new team members.
<div class="row">
<div class="6u 12u$(medium)">
	<p><span class="image left">
	<a href="assets/images/Projects/DigitalProductionTwin/DigitalProductionTwin_05_gizmo_bp.jpg" class="image">
	<img src="{% link assets/images/Projects/DigitalProductionTwin/DigitalProductionTwin_05_gizmo_bp.jpg %}" alt="" />
	</a>
	</span>
	<b>3D Interaction</b><br/>
	The desktop version comprises also from the third party systems/plugins. One of the crucial parts is an object manipulation (gizmo) event-driven subsystem with a proper visual feedback using mouse-keyboard bindings syncing with other functionalities.</p>
</div>
<div class="6u$ 12u$(medium)">
	<p><span class="image right">
	<a href="assets/images/Projects/DigitalProductionTwin/DigitalProductionTwin_08_bp.jpg" class="image">
	<img src="{% link assets/images/Projects/DigitalProductionTwin/DigitalProductionTwin_08_bp.jpg %}" alt="" />
	</a>
	</span>
	<b>Scenario Scripting</b><br/>
	Many basic scripting scenarios are data-driven and interfacing key points to project maintainers for a quick VR trainings and tutorials creation process.</p>
</div>
</div>
<h2 id="vr">VR Trainings</h2>
<span class="image fit"><img src="{% link assets/images/Projects/DigitalProductionTwin/DigitalProductionTwin_08.jpg %}" alt="" /></span>

<div class="row">
<p><span class="image right"><img src="{% link assets/images/Projects/DigitalProductionTwin/DigitalProductionTwin_10.jpg %}" alt="" /></span>Unreal Engine`s Enhanced Input System is used for a programming for different devices and interaction modes with reusability in mind.</p>
</div>

</div> <!-- END id="one"-->
</section> <!-- END id="inner"-->

</div>
