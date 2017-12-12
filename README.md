## Progressive Sushi GANs
**Real Images**
![Reals](https://raw.githubusercontent.com/mitchellgordon95/progressive_sushi_gan/master/results/000-sushi-256x256/reals.png)
**Fakes**
![Fakes](https://raw.githubusercontent.com/mitchellgordon95/progressive_sushi_gan/master/results/000-sushi-256x256/fakes010622.png)

Trained Nvidia's progressive growing of GANs architecture on pictures of sushi from Yelp. Had to cut training short, since this was a hackathon project, but you can see the "sushi structure" really come through at the end of training. Training data is located at ./sushi.h5, and the pickled model is located in results/000-sushi-256x256. 

See [the original repo](https://github.com/tkarras/progressive_growing_of_gans) for more info on the architecture.
