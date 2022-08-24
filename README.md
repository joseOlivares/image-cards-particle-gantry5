# image-cards-particle-gantry5
Image card particle for Gantry 5.3.2+ (Joomla 4 or 3 compatible), using UIkit 3.x and FontAwesome 5.x

# Developer info :ninja:
Hi my name is Jose Luis Olivares, this is my particle to show cards with image, text and link.
If you appreciate my effort, please endorse my skills on Linkedin (https://www.linkedin.com/in/jolivaress/) or making a voluntary donation through Paypal https://paypal.me/joolivares 

You can see an example implemented in this website I made (https://iconnsv.com) or down below checking the screenshots

# Installation on Joomla 3.x / 4.x:

1-Copy cards-img-olivares.html.twig and cards-img-olivares.yaml files to root/templates/TEMPLATE_DIR/custom/particles (if the particles folder does not exist, you have to create it manually)

2-Copy the file _cards-img-olivares.scss inside the path root/templates/TEMPLATE_DIR/custom/scss (if the scss folder does not exists, you will need to create it manually)

3- Add the following code in your custom.scss file.

	@import "dependencies";
	@import "cards-img-olivares"; /* Your custom css*/

  If the custom.scss file does not exists, you will need to create it manually. Also, make sure your custom.scss file has the @import "dependencies"; code at the very top.

# Some Screenshots

## Particle on Gantry 5.3.2+
![gantry5-particle]( ./no-copy-imgs/agregar-particle.jpg?raw=true "Add particle")

## Configiration
![particle-configuration](./no-copy-imgs/configuracion-particle.jpg?raw=true "Particle configuration")

## Real example
![particle-screenshot]( ./no-copy-imgs/presentacion-particle.jpg?raw=true "Particle implemented")
