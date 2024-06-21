# Description of the notebooks used in the project VidGame-LLM
The notebooks can be used in the following order:

## 1. Data preprocessing
Event files of each sessions are cleaned and combined into a dataset with the [dataset_preprocessing.ipynb](../notebooks/dataset_preprocessing.ipynb) notebook.

## 2. Video generation
Training videos are generated using the [training_video_generator.ipynb](../notebooks/training_video_generator.ipynb) notebook.

Testing videos are generated using the [testing_video_generator.ipynb](../notebooks/testing_video_generator.ipynb) or [single_testing_video_generator.ipynb](../notebooks/single_testing_video_generator.ipynb) notebooks.

## 3. Data exploration
Specific frames are extracted from the videos based on arbitrary time onset using the [frame_finder.ipynb](../notebooks/frame_finder.ipynb) notebook.

Frames and gifs of gameplay events (e.g., RIGHT, HIT, Kill) are extracted using the [frame_gif_generator.ipynb](../notebooks/frame_gif_generator.ipynb) notebook.

## 4. Fine-tuning file
A custom question-answer json file is generated using the [custom_jason_generator.ipynb](../notebooks/custom_jason_generator.ipynb) notebook.
