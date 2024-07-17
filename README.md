What are LoRA models and how to use them in AUTOMATIC1111

LoRA models are small Stable Diffusion models that apply tiny changes to standard checkpoint models. They are usually 10 to 100 times smaller than checkpoint models. That makes them very attractive to people who have an extensive collection of models.
This is a tutorial for beginners who haven’t used LoRA models before. You will learn what LoRA models are, where to find them, and how to use them in AUTOMATIC1111 GUI. Then you will find a few demos of LoRA models at the end.

What are LoRA models?
LoRA (Low-Rank Adaptation) is a training technique for fine-tuning Stable Diffusion models.

But we already have training techniques such as Dreambooth and textual inversion. What’s the big deal about LoRA? LoRA offers a good trade-off between file size and training power. Dreambooth is powerful but results in large model files (2-7 GBs). Textual inversions are tiny (about 100 KBs), but you can’t do as much.

LoRA sits in between. Its file size is much more manageable (2 – 200 MBs), and the training power is decent.

Stable Diffusion users who like to try different models can tell you how quickly their local storage fills up. Because of the large size, It is hard to maintain a collection with a personal computer. LoRA is an excellent solution to the storage problem.

Like textual inversion, you cannot use a LoRA model alone. It must be used with a model checkpoint file. LoRA modifies styles by applying small changes to the accompanying model file.

LoRA is a great way to customize AI art models without filling up local storage.

