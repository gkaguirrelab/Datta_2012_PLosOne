# Datta_2012_PLosOne
A digital atlas of the canine brain

  * R Datta, J Lee, J Duda, BB Avants, CH Vite, B Tseng, JC Gee, GD Aguirre, GK Aguirre. (2012) [[http://dx.plos.org/10.1371/journal.pone.0052140|A digital atlas of the dog brain]]. PLoS ONE 7(12): e52140

The atlas is comprised of both low resolution (1 mm isotropic) and high resolution (0.33 mm isotropic) [[http://en.wikipedia.org/wiki/Diffeomorphism|diffeomorphic]] templates of the canine brain, as well as cortical surface representations suitable for use in FreeSurfer.

The atlas is free to use (with appropriate attribution) for academic or commercial purposes. The atlas may not be distributed for commercial gain. Please report any errors or difficulties with the atlas to via e-mail (<aguirreg@mail.med.upenn.edu>).
=====Access to the templates=====

<WRAP download round box 50%>**Download**\\ \\ [[https://cfn.upenn.edu/aguirre/public/caninebrain/InvivoTemplate.zip|InvivoTemplate]]\\ \\ A diffeomorphic average of 7, in-vivo canine brains, at 1mm resolution, including entire head and skull-striped versions.</WRAP>

<WRAP download round box 50%>**Download**\\ \\ [[https://cfn.upenn.edu/aguirre/public/caninebrain/ExvivoTemplate.zip|ExvivoTemplate.zip]]\\ \\ A diffeomorphic average of 8, ex-vivo canine brains, at 0.33 mm resolution, warped to the in-vivo space.</WRAP>


<WRAP download round box 50%>**Download**\\ \\ [[https://cfn.upenn.edu/aguirre/public/caninebrain/SurfaceTemplate.zip|SurfaceTemplate.zip]]\\ \\ Cortical surface representations derived from the high-resolution, ex-vivo atlas, for use in FreeSurfer.</WRAP>

=====A limitation: gray matter layer=====

While a white matter segmentation is included in the atlas and is the basis of a surface reconstruction, we have been unable to produce a gray-matter surface. Our images have a image intensity boundary at the outer surface of the gray matter that is unlike in-vivo specimens. Consequently, the FreeSurfer algorithms for growing a gray-matter layer atop the white matter volume do not perform properly. 

We would welcome any assistance in modifying the FreeSurfer routines to accommodate the properties of our images. Please contact us if you know how to help!


