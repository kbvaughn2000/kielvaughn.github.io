---
layout: page
title: About Me
tags: [about, skills]
date: 2020-05-17
comments: false
---

<div class="container">
	<h1>Pure CSS (SCSS) Bootstrap compatible circular progress bars</h1>
	<p>This uses a data-attribute to create the progress bar. Forked from <a href="https://bootsnipp.com/snippets/featured/circle-progress-bar">circle-progress-bar</a>. This functions based on increments defined in the the scss. Change the $howManySteps var and the for loops below will generate the CSS. The data attributes will need to be changed to reflect the newly generated CSS. This doesn't require Bootstrap. Let me know if you use it your project, I'd love to see it in the wild.</p>
</div>
<div class="container">
	<div class="row">
		<div class="col-sm-3 col-md-2">
			<div class="progress" data-percentage="20">
				<span class="progress-left">
					<span class="progress-bar"></span>
				</span>
				<span class="progress-right">
					<span class="progress-bar"></span>
				</span>
				<div class="progress-value">
					<div>
						20%<br>
						<span>completed</span>
					</div>
				</div>
			</div>
		</div>
		<div class="col-sm-3 col-md-2">
			<div class="progress" data-percentage="40">
				<span class="progress-left">
					<span class="progress-bar"></span>
				</span>
				<span class="progress-right">
					<span class="progress-bar"></span>
				</span>
				<div class="progress-value">
					<div>
						40%<br>
						<span>completed</span>
					</div>
				</div>
			</div>
		</div>
		
		<div class="col-sm-3 col-md-2">
			<div class="progress" data-percentage="80">
				<span class="progress-left">
					<span class="progress-bar"></span>
				</span>
				<span class="progress-right">
					<span class="progress-bar"></span>
				</span>
				<div class="progress-value">
					<div>
						80%<br>
						<span>completed</span>
					</div>
				</div>
			</div>
		</div>
		
		
		<div class="col-sm-3 col-md-2">
			<div class="progress" data-percentage="100">
				<span class="progress-left">
					<span class="progress-bar"></span>
				</span>
				<span class="progress-right">
					<span class="progress-bar"></span>
				</span>
				<div class="progress-value">
					<div>
						100%<br>
						<span>completed</span>
					</div>
				</div>
			</div>
		</div>
		
		
			<div class="col-sm-3 col-md-2">
			<div class="progress" data-percentage="0">
				<span class="progress-left">
					<span class="progress-bar"></span>
				</span>
				<span class="progress-right">
					<span class="progress-bar"></span>
				</span>
				<div class="progress-value">
					<div>
						0%<br>
						<span>completed</span>
					</div>
				</div>
			</div>
		</div>
		
	</div>
</div>
