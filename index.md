---
layout: home
category: home
attibution:
  author: "xxxx"
  link_to_image: "https://www.iwcinnovations.com/hubfs/Waterborn%20Pathogen%201.jpg"




{% include header.html %}

# The Schloss Lab

> "...it would appear to be a pointless and doubtful exercise to examine and disentangle the apparently random appearing bacteria in normal feces and the intestinal tract, a situation that seems controlled by a thousand coincidences... Yet I have nevertheless devoted myself now for a year virtually exclusively to this special study, it was with the conviction that the accurate knowledge of these conditions is essential, for the understanding of not only the physiology of digestion..., but also the pathology and therapy of microbial intestinal diseases."
>
> [Theodor Escherich (1888)](http://cid.oxfordjournals.org/content/10/6/1220.full.pdf)

## Our Mission

Nearly 130 years later, our research group shares the dedication of Theodor Escherich as we try to understand the role of the gut microbiota in *Clostridium difficile* infections and the progression of colorectal cancer. Since Escherich found the causative agent for diarrhea, what we now call *E. coli*, a lot has happened in science. We now have a far better understanding of microbiology, molecular biology, ecology, evolutionary theory, and statistics. Our research group is dedicated to integrating across disciplines to advance our knowledge of the role of the microbiome in human health. Human microbiome research is experiencing an amazing period of growth and we are helping to lead that effort. If you are interested in learning more about our work please explore this site and feel free to [contact Pat](mailto:{{ site.email }}) with any questions.

## Hail to the Victors Valiant

We are fortunate to reside within the [Department of Microbiology & Immunology](https://medicine.umich.edu/dept/microbiology-immunology/) at the [University of Michigan](http://www.umich.edu) [School of Medicine](https://medicine.umich.edu/medschool/). Our department has a [rich history](https://medicine.umich.edu/dept/microbiology-immunology/about-us/history) spanning the last 100 years. Our laboratory is in the [Medical Science Research Building I](https://campusinfo.umich.edu/campumdap/100) within the University of Michigan's [Host-Microbiome Initiative](https://medicine.umich.edu/medschool/research/research-strengths/host-microbiome-initiative). We have direct access to DNA sequencers, robotics, animal facilities, and anaerobic chambers. Over the years we have benefited from rich collaborations with diverse colleagues within and beyond the School of Medicine. These have included Drs. [Vincent Young](https://medicine.umich.edu/dept/microbiology-immunology/bio/young.htm), [Mack Ruffin](https://cancer.psu.edu/researchers/individual/-/researcher/5B6500F63D6B38DBE0540010E056499A/mack-ruffin-md-mph), [Jenna Wiens](http://www-personal.umich.edu/~wiensj/), [Elena Stoffel](https://www.uofmhealth.org/profile/2702/elena-martinez-stoffel-md), [Marcy Balunas](https://balunaslab.uconn.edu), and [Grace Chen](https://sites.google.com/a/umich.edu/chenlab/). With great clinical collaborators and generous patients, we are able to insure that our results have the greatest possible relevance. It's hard to imagine a better environment to carry out microbiome research today.

## Learn more about our research group

[Science](science)

[Labbies](labbies)

[Papers](papers)

[Lab Business](lab_business)

<div class="blurb">
	<div class="container-fluid">
		<div class="row vcenter">
			<div class="col-md-4">
				<img class="img-responsive" src="assets/img/pat_professional.jpg" alt="Pat Schloss"/>
			</div>
			<div class="col-md-8">
				<h3>Join Us!</h3>
				<p>I am always looking for exceptional and dedicated scientists and try to maintain a balance between training graduate students and postdoctoral researchers. It is important to me that we maintain a diverse team so that we do the best job of synergizing our experiences and interests. If you are interested in working towards a PhD at Michigan, I participate in the [Program in Biomedical Sciences (PIBS)](https://medicine.umich.edu/medschool/education/phd-programs/phd-admissions
















<!-- # The Huiyun Wu Lab -->

Our lab conduct microbial water research 
---
{%
  include figure.html
  image="images/JoinUs.jpg"
  caption="Join us."
  link="team"
  width="1000px"
%}

{% include section.html %}

{% capture text %}

We conduct research at three levels. Firstly we apply **molecular microbiology methods** to detect microbial waterborne pathogens to characterize temporal and spatial variations of pathogens in water systems. We use advanced sequencing techniques to study microbiome in natural water and built water as a framework for the health of human, animals, and the environment. Such big data derived analysis, enable us to identify pathogens, novel microbial water indicators, or bacterial phages that can potentially combat antimicrobial resistant crisis.  

These studies empower our second level research. We use environmental metagenomic data to **characterize microbiome in environmental waters, identify waterborne disease associated, reduce the health risks to the environment and human**. We use machine learning for microbiome discovery, espcially viruse communities in environmental water samples.

Last, we perform our research based on **Open Science and reproducible research principle**. We profile temporally as well as spatially separated samples (diagnosis, pre-treatment, post treatment) to quantify changing clonal phylogenies, during disease progression, or in response to therapeutic intervention.

{%
  include button.html
  link="research"
  text="See our publications"
  icon="fa-solid fa-arrow-right"
  flip=true
  style="bare"
%}

{% endcapture %}

{%
  include feature.html
  image="images/icon.png"
  link="research"
  title="Our Research"
  text=text
  width="500px"
  className="feature-image large"
%}

{% capture text %}

Our aim is to enhance resilience to water quality stresses due to climate change, promote water reuse, engage communities, and explore interdisciplinary fields like machine learning and environmental bioinformatics to mitigate the impacts of merging waterborne microbial pollutants.

We benefit from a fully resourced computational and research environment at Washington State University. We have access to state-of-the-art computing and laboratory facilities to support truly ambitious and innovative research.

{%
  include button.html
  link="tools"
  text="Browse our tools"
  icon="fa-solid fa-arrow-right"
  flip=true
  style="bare"
%}

{% endcapture %}

{%
  include feature.html
  image="images/MisRiver.jpg"
  link="tools"
  title="Our Projects"
  flip=true
  style="bare"
  text=text
%}

{% capture text %}

We like to perform ambitious research, but operate in a fun, collaborative, and team-oriented environment, and we are strongly committed to mentoring young scientists and engineers through internal and international internship schemes.

**Join us:** We are looking for inspiring, motivated individuals to join our team, challenge our current understanding of cancer biology and help make new discoveries that will inform cancer care and improve patient outcomes.


{%
  include button.html
  link="team"
  text="Meet our team"
  icon="fa-solid fa-arrow-right"
  flip=true
  style="bare"
%}

{% endcapture %}

{%
  include feature.html
  image="images/lab-edge.jpg"
  link="team"
  title="Our Team"
  text=text
%}
