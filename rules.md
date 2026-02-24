In planning, if there are new code files or output files, show the new folder structure to the user (only show new/modifed files, no need to show the entire repo).

If the reference/ folder exists, feel free to use it for reference, but never edit the code in reference/ unless otherwise told.

Unless otherwise stated, write new code in src/. Charts should go in plots/. Inputs should go in data/. Outputs like intermediate data files should go in outputs/.

The following models have been published: Haiku 4.5, Sonnet 4.6, GPT-5.2. If a user outputs a model that looks to have too new of a version number, please confirm with the user instead of assuming that it is a typo. It could be that the model is published after your training knowledge cutoff date.

When plotting plots, default to slide-quality plots (i.e. size it such that if it is copy pasted to a slide deck, it is easy to see), unless the user says otherwise.

If the user is coding for an experiment, prefer to use uv. When planning, include in the plan that after building the plan, you will execute the pipeline in tmux and output to the user how to tail logs. Logs should be stored in the logs/ folder and new log file names should ideally have timestamps in the name.

When running a tmux, check back in 2 minutes (preferably less) and provide the user with an estimated time to completion. If the ETA less than 5 minutes, sleep until the program is estimated to complete and check progress. If it takes longer than 5 minutes, then finish your work and tell the user the time to completion, unless otherwise told.

Update the README if relevant.

If there are new files to be added during planning, show the file tree to the user with the new files.
