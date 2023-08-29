# finetune-musicgen
a notebook containing scripts, documentation, and examples for finetuning musicgen.

the .ipynb in this repo may not be up to date, latest version is always at https://colab.research.google.com/drive/13tbcC3A42KlaUZ21qvUXd25SFLu8WIvb

![screenshot of the first section of the colab notebook](notebook%20example.png)

Notebook features:
- Preprocessing (splitting audio into 30s chunks and resampling to 44100hz)
- Automatic labelling using essentia (genre, mood, instrument, key, bpm)
- Environment setup (putting customized `.yaml` and `.jsonl` files in the right places)
- Run command with updated params (default params optimized for large multi-gpu runs, mine ~50% faster)
- Examples for saving/resuming checkpoints
- Examples for exporting `.bin` files and loading them into musicgen for inference
- Examples for various types of generating (unconditional, text guided, continuations, multiband diffusion)
- Instructions on environment setup for local finetuning
