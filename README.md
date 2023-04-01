

**Opensource prompts for arible.co/prompts, precursor to the arible format**

Simdi: 

> Hey, have you seen this idea about a Universal Prompt Format for
> AI-generated images? It aims to make reproducing the same image easier
> by including all the necessary information in a single file.

P1: 

> Oh, that sounds interesting! How would it work?

Simdi: 

> The idea is to include the model details, training parameters,
> control-net based parameters, depth and pose information, and
> in-painting masks in a single file. So, instead of asking the OP about
> the steps they took, you'd just ask for the file and import it into
> your web UI to get the same image.

P1: 

> That's a neat concept. It could be helpful for professionals or even
> for teaching and learning purposes. But I have some concerns about
> including the model and training images, as they might be too big to
> share in a single file.

Simdi: 

> You're right, including the entire model and training images might not
> be feasible. We could just include the model name and hash instead,
> and expect users to have the model as a dependency.

P1: 

> How do you envision tracking and incorporating inpainting operations
> within the Universal Prompt Format, given that they can be run
> multiple times on a single image with different masks, prompts, and
> parameters?

Simdi: 

> It might be difficult but not impossible. We'd need adoption by or
> cooperation with various UIs to keep a history of inpainting
> operations, adding to the file's history every time there's img2img or
> inpainting.

P1: 

> How could the Universal Prompt Format incorporate version control to
> track and manage changes made to the AI-generated images, especially
> when working with different models and user inputs?

Simdi: 

> The Universal Prompt Format could incorporate version control by using
> a system similar to Git. Each change made to the AI-generated image
> would create a new version, tracking changes and allowing users to
> revert to previous versions if needed. The system would store metadata
> about the changes, supporting branching and merging for collaboration.
> This approach would simplify managing and reviewing changes when
> working with different models and user inputs.
