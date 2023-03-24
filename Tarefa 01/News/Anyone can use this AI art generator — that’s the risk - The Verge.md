Original: [Link](https://www.theverge.com/2022/9/15/23340673/ai-image-generation-stable-diffusion-explained-ethics-copyright-data)

#ai #ethics #machine-learning



Type and ye shall receive. That’s the basic premise of AI text-to-image programs.

Users type out descriptions of whatever they like — a cyborg Joe Biden wielding a samurai sword; a medieval tapestry of frogs jousting — and these systems, trained on huge databases of existing art, generate never-before-seen pictures that match these prompts (more or less). And while the output of current state-of-the-art models certainly isn’t perfect, for those excited about the technology, such flaws are insignificant when measured against the potential of software that generates _any image you can imagine_.

Up until now, though, these “type and ye shall receive” tools have been controlled by a small number of well-funded companies like OpenAI (which built [DALL-E](https://www.theverge.com/23162454/openai-dall-e-image-generation-tool-creative-revolution)) and Google (which made [Imagen](https://www.theverge.com/2022/5/24/23139297/google-imagen-text-to-image-ai-system-examples-paper)). These are big outfits with a lot to lose, and as a result, they’ve balanced the possibilities of what this technology can do with what their corporate reputations will allow.

So, for a model like DALL-E, public access is drip-fed via a lengthy waiting list, while Google’s Imagen is completely off-limits to the public. DALL-E’s output is also [filtered](https://labs.openai.com/policies/content-policy), making it difficult to generate images that contain violence, nudity, or realistic faces. And, of course, you have to pay. DALL-E’s users get 15 image prompts a month for free, with additional generations costing roughly $0.08 a pop. It’s not expensive, but it’s still a barrier.

![Stable Diffusion is notable for the quality of its output and its ability to reproduce and combine a range of styles, copyrighted imagery, and public figures. Top-left is “Mickey Mouse WW2 Propaganda poster,” and top-right is “Boris Johnson as 12th century peasant, oil painting.”](https://duet-cdn.vox-cdn.com/thumbor/0x0:2000x2000/2400x2400/filters:focal(1000x1000:1001x1001):format(webp)/cdn.vox-cdn.com/uploads/chorus_asset/file/24021973/stable_diffusion_4_up_collage.jpg)

_Stable Diffusion is notable for the quality of its output and its ability to reproduce and combine a range of styles, copyrighted imagery, and public figures. Top-left is “Mickey Mouse WW2 Propaganda poster,” and top-right is “Boris Johnson as 12th century peasant, oil painting.”_

Images: [1](https://lexica.art/prompt/524839df-af50-4421-8421-fedde318e983), [2](https://lexica.art/prompt/40909f65-9f2a-4f9a-8ef4-6ac1954be34e), [3](https://lexica.art/prompt/17cb002e-735d-450c-8bd7-084bcba20ec1), [4](https://lexica.art/prompt/10023e09-97d2-4ba3-8e01-4ee149a42c6f) via _Lexica_

Stable Diffusion is making access to unfiltered image generation easier than ever

In the last few weeks, though, this status quo has been upended by a new player on the scene: a text-to-image program named Stable Diffusion that offers open-source, unfiltered image generation, that’s free to use for anyone with a decent computer and a little technical knowhow. The model was only [released publicly on August 22nd](https://stability.ai/blog/stable-diffusion-public-release), but already, its influence has spread, quietly and rapidly. It’s been embraced by the AI art community and decried by many traditional artists; it’s been picked apart, exalted, and worried over.

“The reality is, this is an alien technology that allows for superpowers,” Emad Mostaque, CEO of Stability AI, the company that has funded the development of Stable Diffusion, tells _The Verge_. “We’ve seen three-year-olds to 90-year–olds able to _create_ for the first time. But we’ve also seen people create amazingly hateful things.”

Although momentum behind AI-generated art has been building for a while, the release of Stable Diffusion might be the moment the technology really takes off. It’s free to use, easy to build on, and puts fewer barriers in the way of what users can generate. That makes what happens next difficult to predict.

### **What makes Stable Diffusion different**

The key difference between Stable Diffusion and other AI art generators is the focus on open source. Even [Midjourney](https://www.theverge.com/2022/8/2/23287173/ai-image-generation-art-midjourney-multiverse-interview-david-holz) — another text-to-image model that’s being built outside of the Big Tech compound — doesn’t offer such comprehensive access to its software.

The company behind Stable Diffusion, [Stability AI](https://stability.ai/), has packaged up this tech in various ways. There’s a [public demo](https://huggingface.co/spaces/stabilityai/stable-diffusion) anyone can try (though it’s extremely slow and often breaks). There’s a software beta that’s fast and easy to use named [DreamStudio](https://stabilityai.us.auth0.com/u/login?state=hKFo2SA5NWxmSEJuVzBHeVRGOHBVc2oweXhVSC15Vk93S2JnWKFur3VuaXZlcnNhbC1sb2dpbqN0aWTZIHJRanUzTFY1YUlnZXMxMTBqYjdXVXJZbzJRRXNXU0doo2NpZNkgS3ZZWkpLU2htVW9PalhwY2xRbEtZVXh1Y0FWZXNsSE4) (though it charges you after a certain number of image generations). And, most significantly, there’s a [full-fat version of the model](https://huggingface.co/CompVis/stable-diffusion) that anyone can download and tinker with. Already, third-party developers have been making this software easier to download and use. There’s already a version for macOS that comes with a [simple one-click installer](https://twitter.com/divamgupta/status/1569014206912929796), for example. (Though be warned — it takes a long time to generate images on any Mac without serious processing grunt.)

![An image created by Stable Diffusion from the software’s subreddit. The exact text description used to create the image was “Photo of Bernie Sanders in Mad Max Fury Road (2015), explosions, white hair, goggles, ragged clothes, detailed symmetrical facial features, dramatic lighting.” ](https://duet-cdn.vox-cdn.com/thumbor/0x0:512x512/2400x2400/filters:focal(256x256:257x257):format(webp)/cdn.vox-cdn.com/uploads/chorus_asset/file/24021619/ub3pufm3u6m91.png)

_An image created by Stable Diffusion from the software’s subreddit. The exact text description used to create the image was “Photo of Bernie Sanders in Mad Max Fury Road (2015), explosions, white hair, goggles, ragged clothes, detailed symmetrical facial features, dramatic lighting.”_

Image: [Reddit / Licovoda](https://www.reddit.com/r/StableDiffusion/comments/x77d2l/bernie_sanders_in_a_mad_max_movie_that_doesnt/)

It’s this openness that Mostaque says will allow Stable Diffusion to improve faster than its rivals. If you check out the [Stable Diffusion subreddit](https://www.reddit.com/r/StableDiffusion/), for example, you can see users not only sharing their favorite image prompts (e.g., “[McDonalds in Edo-Period Japan](https://www.reddit.com/r/StableDiffusion/comments/xbyxxz/mcdonalds_in_edoperiod_japan/)” and “[Bernie Sanders in a Mad Max movie that doesn’t e](https://www.reddit.com/r/StableDiffusion/comments/x77d2l/bernie_sanders_in_a_mad_max_movie_that_doesnt/)[xist](https://www.reddit.com/r/StableDiffusion/comments/x3q0cv/jaba_the_trump/)”) but coming up with new use cases for the program and integrating it into established creative tools.

In the example below, a user built a Photoshop plug-in that uses Stable Diffusion to paint over their rough doodles. They start with images of a wooded Japanese hilltop, then sketch out where the grass, trees, and sky should go. Stable Diffusion then fills in these gaps, and the user clears up the joins manually. As one Redditor [commented](https://old.reddit.com/r/StableDiffusion/comments/wyduk1/show_rstablediffusion_integrating_sd_in_photoshop/ilwfijb/) underneath the post: “I’m stunned by all the amazing projects coming out and it hasn’t even been a week since release. The world in 6 months is going to be a totally different place.”

In Mostaque’s explanation, open source is about “putting this in the hands of people that will build on and extend this technology.” However, that means putting _all_ these capabilities in the hands of the public — and dealing with the consequences, both good and bad.

### **No way, no filter?**

The most dramatic difference for Stability AI’s open-source approach is its hands-off approach to moderation. Unlike DALL-E, it’s easy to use the model to generate imagery that is violent or sexual; that depicts public figures and celebrities; or that mimics copyrighted imagery, from the work of small artists to the mascots of huge corporations. (Comprehending exactly how broad the scope of imagery Stable Diffusion can generate is difficult, but if you want some idea, trying [typing some terms into Lexica](http://lexica.art/), a search engine that scrapes images generated using Stable Diffusion.)

To be clear: consumer-friendly versions of Stable Diffusion have some built-in keyword filters that stop users from generating NSFW content, and overtly political or violent imagery (words like “Nazi” and “gore” are banned, for example). But while these restrictions also exist in the downloadable model, they can be bypassed pretty easily. (See, for example, a post in the Stable Diffusion subreddit titled “[How to remove the safety filter in 5 seconds](https://www.reddit.com/r/StableDiffusion/comments/wv2nw0/tutorial_how_to_remove_the_safety_filter_in_5/).”)

Stable Diffusion makes it much easier to generate violent and sexual imagery, including pictures featuring real people

Similarly, while the model’s [open-source license](https://huggingface.co/spaces/CompVis/stable-diffusion-license) forbids people from using the software for a whole range of sins (including “exploiting, harming or attempting to exploit or harm minors in any way” and to “generate or disseminate verifiably false information”), once someone has downloaded Stable Diffusion to their computer, there are no technical constraints to what they can use the software for.

Mostaque’s view on this is straightforward. “Ultimately, it’s peoples’ responsibility as to whether they are ethical, moral, and legal in how they operate this technology,” he says. “The bad stuff that people create with it \[...\] I think it will be a very, very small percentage of the total use.”

This is essentially uncharted territory, and it’s not clear what the consequences of releasing a model like this into the wild will be. It’s easy to imagine the many malicious uses this technology could be put to, but that doesn’t meant these predictions will all come to pass.

For example, when OpenAI debuted its AI text generator GPT-3, the company initially limited access for fears the software would be used to create a [deluge of spam, fake news, and propaganda](https://www.oreilly.com/radar/ai-powered-misinformation-and-manipulation-at-scale-gpt-3). So far, though, those threats have proved overblown. As access has widened, the deluge hasn’t appeared. That’s not to say there haven’t been serious problems with the technology (see, for example, the case of AI Dungeon, a GPT-3-based text fantasy game that had to introduce filters to [stop its software from generating sex scenes involving minors](https://www.theregister.com/2021/10/08/ai_game_abuse/)), but a cataclysm of infinite AI spam, hate speech, etc. has so far been avoided. (Not coincidentally, Stability AI _also_ helped make an [open-source version of GPT-3](https://blog.eleuther.ai/announcing-20b/).)

![A stylistic, safe-for-work example of Stable Diffusion’s capacity to generate nude imagery. The text prompts to generate this image included “muscular soldier wading through water,” “tom of finland,” and “claude monet.” ](https://duet-cdn.vox-cdn.com/thumbor/0x0:509x636/2400x2999/filters:focal(255x318:256x319):format(webp)/cdn.vox-cdn.com/uploads/chorus_asset/file/24022062/Screenshot_2022_09_14_at_15.03.43.png)

_A stylistic, safe-for-work example of Stable Diffusion’s capacity to generate nude imagery. The text prompts to generate this image included “muscular soldier wading through water,” “tom of finland,” and “claude monet.”_

Image: [_via Lexica_](https://lexica.art/prompt/40f680e1-e153-40e5-a870-9af5e5e9c26a)

With Stable Diffusion, the most visible NSFW use case to date has been users generating pornography. After the model’s public release, a number of subreddits dedicated to curating the software’s NSFW output [sprung up](https://www.vice.com/en/article/xgygy4/stable-diffusion-stability-ai-nsfw-ai-generated-porn). (Though most have since been banned due to Reddit’s policy forbidding [pornographic deepfakes](https://www.theverge.com/2018/2/7/16982046/reddit-deepfakes-ai-celebrity-face-swap-porn-community-ban). Many users were generating images of nude celebrities and public figures). This NSFW content often veers between the grotesque and the absurd, with naked models sporting extra limbs and placed in physically impossible poses. But the quality of this output will certainly improve in the near future, bringing with it new questions about the ethics of AI-generated porn.

It’s also almost certain, for example, that Stable Diffusion can be used to generate sexual imagery featuring children, though if such activity is happening, it’s taking place in the less-observed corners of the web. Mostaque notes that this is one domain of image generation that the company actively tried to hinder by removing child sexual abuse material (CSAM) from Stable Diffusion’s training data: “We removed illegal content from our scrape of the internet, and that’s it.”

Overall, though, Mostaque’s position is that Stability AI has been neither thoughtless nor reckless in its release of Stable Diffusion. In contrast, he says, the roughly 75-strong company considered baking in more filters but concluded that its open-source approach was best. “Once you start filtering something, where do you stop?” he says.

Ultimately, the company is hewing to one of the industry’s most well-rehearsed (and frequently criticized) mantras: that technology is neutral, and that building things is better than not. “This is the approach that we take because we see these tools as a potential infrastructure to advance humanity,” says Mostaque. “We think the positive elements far outweigh the negatives.”

### **Copying artists and scraping copyrights**

One visual domain that Stability AI certainly didn’t filter from its training data is copyrighted work. As a result, many see the ability of Stable Diffusion to mimic the style and aesthetics of living artists as untenable: not only a potential breach of copyright, but of ethics, too. An early viral tweet [criticizing the software](https://twitter.com/arvalis/status/1558632898336501761) cataloged some of the many living artists that the model can imitate (though it falsely claimed Stability AI was “advertising” this function).

Like most modern AI systems, Stable Diffusion is trained on a vast dataset that it mines for patterns and learns to replicate. In this case, that core of the training data is a huge package of 5 billion-plus pairs of images and text tags known as LAION-5B, all of which have been scraped from the public web. (It’s worth noting that LAION-5B is not maintained by Stability AI itself, but by a non-profit based in Germany, [LAION](https://laion.ai/).)

![The presence of copyrighted imagery in Stable Diffusion’s training data is obvious from the program’s tendency to reproduce the “Getty Images” watermark in certain pictures. ](https://duet-cdn.vox-cdn.com/thumbor/0x0:510x502/2400x2362/filters:focal(255x251:256x252):format(webp)/cdn.vox-cdn.com/uploads/chorus_asset/file/24022144/Screenshot_2022_09_14_at_15.23.25.png)

_The presence of copyrighted imagery in Stable Diffusion’s training data is obvious from the program’s tendency to reproduce the “Getty Images” watermark in certain pictures._

Image: [_via Lexica_](https://lexica.art/?q=getty+images&prompt=d38438c4-8275-4492-9ef3-5b3bcff32bcd)

We know for certain that LAION-5B contains a lot of copyrighted content. An [independent analysis of a 12 million-strong sample of the dataset](https://waxy.org/2022/08/exploring-12-million-of-the-images-used-to-train-stable-diffusions-image-generator/) found that nearly half the pictures contained were taken from just 100 domains. The most popular was Pinterest, constituting around 8.5 percent of the pictures sampled, while the next-biggest sources were sites known for hosting user-generated content (like Flickr, DeviantArt, and Tumblr) and stock photo sites like Getty Images and Shutterstock. In other words: sources that contain copyrighted content, whether from independent artists or professional photographers.

This copyright aspect adds a new dimension to complaints that tools like Stable Diffusion are taking work away from human artists. Not only is AI stealing artists’ jobs, say critics, but it’s doing so by [bootlegging the skills](https://www.wired.com/story/artists-rage-against-machines-that-mimic-their-work/) it took these individuals hours and hours to hone.

“Some of my earliest freelance gigs were card game illustrations, book covers and album art. It’s heartbreaking to watch that space (especially the latter) fill up with AI-generated imagery and realize how much harder it just became for aspiring artists,” commented art director Logan Preshaw in a recent [viral Twitter thread](https://twitter.com/wickedinsignia/status/1569185240593367040) on AI art software. “Everyone has a right to create art, but they don’t have the right to do it at others’ expense.”

Stability AI’s response is again one of claimed neutrality. Mostaque says that scraping public material from the web — even copyrighted content — is legal in both the US and UK (though this doesn’t mean legal objections won’t be raised in the future). He also argues that the open-source nature of Stable Diffusion means that he and his colleagues are not hoarding these new powers, but sharing them widely for anyone to use.

“How is this being released?” asks Mostaque. “Is this creating a service around it that we’re keeping private, like OpenAI? Is this an art model? No, this is being released by a research institute as a generalized model, and it’s up to the end user how they use it. If they use it in a way that infringes on copyright, then they’re breaking the law.” (By saying the model is being released by a “research institute,” Mostaque is referring to the fact that the technical license for Stable Diffusion has been [released by the Ludwig Maximilian University of Munich’s CompVis lab](https://github.com/CompVis), though Stability AI funded and shaped its development.)

Mostaque says future iterations of Stable Diffusion will give artists the option to upload their portfolios and names to filter out their influence from the model’s output. But, as with the generation of NSFW content, these filters will be optional for users who download the open-source version of the software. In other words: if artists have problems with AI art generators mimicking their work, solutions are unlikely to come from companies like Stability AI.

_(The gallery below shows searches Stable Diffusion’s take on some named artists.)_

### **It’s time for some game theory**

All of this, though, leads to another interesting question: what _is_ Stability AI, and what is the company trying to achieve?

Mostaque himself is a former hedge fund manager who’s contributed an unknown (but seemingly significant sum) to bankroll the creation of Stable Diffusion. He’s given slightly varying estimates as to the initial cost of the project, but they tend to hover at around $600,000 to $750,000. It’s a lot of money — well outside the reach of most academic institutions — but a tiny sum compared with the imagined value of the end product. And Mostaque is clear that he wants Stability AI to make a lot of money while sticking to its open source ethos, pointing to open source unicorns in the database market as a comparison.

He also insists, though, that money is not his biggest concern. Instead, he says, he wants to achieve something more like a revolution in the AI world: to dethrone the deep-pocketed corporate behemoths that are building ever bigger and more expensive systems, and replaces them with communities that are smarter, faster, and independent.

“OpenAI and everyone will have to join our communities and our ecosystems.”

“I view companies and organizations as slow, dumb AI,” he says. “And when we talk about being killed by AI if it gets too smart, we’re already being killed every day by the bureaucracies that really grind us down.” Releasing Stable Diffusion as an open-source project is, in his view, a way to out-maneuver these lumbering institutions. “Everyone is making \[these AI models\] private until the first person makes them public. From a game theory standpoint, what happens when someone makes them public? Everyone goes public. OpenAI and everyone will have to join our communities and our ecosystems.”

Forcing this change isn’t just about developing the technology faster, says Mostaque, but about spreading these systems globally. In his view, the AI world is currently on a path to be dominated by the culture and ethics of Silicon Valley, but open source software can help decentralize this future. In the case of image generation tools, for example, he hopes that different nations will develop their own models and datasets in order to “reflect the diversity of humanity” rather than the “monoculture of the internet, which is overwhelmingly Western.”

It’s a grand aim but no less so than his description of Stable Diffusion as “bringing fire from the gods of creativity to the world.”

Now, the world needs to figure out how not to get burned.

![Stealing fire from the gods, illustrated by Stable Diffusion. (Exact prompt: “fantasy portrait of a hero stealing fire from the gods, digital painting, illustration, high quality, fantasy, style by jordan grimmer and greg rutkowski”)](https://duet-cdn.vox-cdn.com/thumbor/0x0:508x510/2400x2409/filters:focal(254x255:255x256):format(webp)/cdn.vox-cdn.com/uploads/chorus_asset/file/24024836/Screenshot_2022_09_15_at_12.50.10.png)

_Stealing fire from the gods, illustrated by Stable Diffusion. (Exact prompt: “fantasy portrait of a hero stealing fire from the gods, digital painting, illustration, high quality, fantasy, style by jordan grimmer and greg rutkowski”)_

Image: James Vincent

_**Correction, Thursday September 15th, 12:33PM ET:** The story previously stated that Stability AI maintains the LAION-5B database and solely released the Stable Diffusion model. This is incorrect. The LAION-5B database is maintained by a charity in Germany, LAION, while the Stable Diffusion model — though funded and developed with input from Stability AI — is released under a license from the_ [_CompVis lab at Germany’s LMU Munich university_](https://github.com/CompVis)_._