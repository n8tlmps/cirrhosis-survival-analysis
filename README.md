<img src="liver.jpg">
<!DOCTYPE html>
<html lang="en">
<body>
   <header>
      <h1>Modeling Survival of Patients with Cirrhosis</h1>
   </header>
</body>

<div class="section">
	<p>
Cirrhosis is severe scarring of the liver. This condition can be caused by many forms of liver diseases and conditions, such as hepatitis or chronic alcohol consumption. Each time your liver is injured, scar tissue forms in the healing process. The accumulation of scar tissue replaces more of the healthy liver tissue as cirrhosis worsens, impairing the liver’s functionality. Advanced cirrhosis can be life-threatening. This project aims to understand the probability of cirrhosis survival and to analyze the underlying factors influencing survival time. A survival analysis was conducted on this dataset using the Kaplan-Meier estimator and curve, logrank tests, and the Cox proportional hazards model.
</div>

<div class="section">
	<h2>Dataset Information</h2>
	<p> The dataset was obtained from the <a href="https://archive.ics.uci.edu/dataset/878/cirrhosis+patient+survival+prediction+dataset-1">UCI Machine Learning Repository</a>, a collection of databases, domain theories, and data generators that are used by the machine learning community for the empirical analysis of machine learning algorithms. It contained 418 observations and 20 variables that featured:
</div>
<ul>
	<li>ID</li>
	<li>Number of days between registration and the earlier of death, transplantation or study analysis time</li>
	<li>Status of the patient</li>
	<li>Type of drug: D-penicillamine or Placebo</li>
	<li>Age</li>
	<li>Sex: Male or Female</li>
	<li>Presence of Ascities</li>
	<li>Presence of Hepatomegaly</li>
	<li>Presence of Spiders</li>
	<li>Presence of Edema</li>
	<li>Bilirubin</li>
	<li>Cholesterol</li>
	<li>Albumin</li>
	<li>Copper</li>
	<li>Alkaline Phosphatase</li>
	<li>SGOT</li>
	<li>Tryglicerides</li>
	<li>Platelets per cubic</li>
	<li>Prothrombin time</li>
	<li>Histologic Stage of Disease</li>
</ul>
	<p>
 After removing missing values, there were 276 observations remaining.
<p>
	During 1974 to 1984, 424 primary biliary cirrhosis (PBC) patients referred to a Mayo Clinic study were qualified for the randomized placebo-controlled trial testing on the drug D-penicillamine. Of these, 312 patients were followed through the trial and have mostly comprehensive data. The remaining 112 patients did not join the clinical trail, but agreed to record basic metrics and undergo survival tracking. By the end of the study, data was collected from 106 of these individuals along with the initial 312 who were participating in the trial. Penicillamine is a chelating agent that binds to excess copper and removes it from the blood stream. It is often prescribed to treat rheumatoid arthiritis, Wilson’s disease, and kidney stones. If the liver is unable to process substances like iron and copper, they can build up to dangerously high levels and cause cirrhosis as they damage your liver tissues over time. Mutation in particular genes is also suggested to contribute to cirrhosis.
</p>


