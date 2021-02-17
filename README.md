# alpha-brainwaves_eyes_open-closed
Time series of alpha brain waves: eyes open/eyes shut classification

{
   "cell_type": "markdown",
   "metadata": {},
   "source": [
    "Hello, my name is Kamila. I am getting my master's degree in Data Science now and after 3 months of studies I decided to try my new-aquired skills on a Kaggle dataset. \n",
    "\n",
    "I admire Data Science for ability of learning new every day and opportunity of constantly challenging oneself.\n",
    "Last 3,5 years I worked in cyber security, but apart from this I have a broad range of interests. For example, I am a huge fan of human brain. It's a masterpiece which we still didn't study as much as other parts of human body. I have high hopes that in the nearest future we will make fantastic discoveries in neuroscience.\n",
    "\n",
    "\n",
    "// Disclaimer: I believe data scientists spend most of the time on aquiring and clening data (so do I on another project), but for the sake of practice here I am with \"picard\" dataset.\n",
    "\n",
    "\n",
    "Today I bring your attention on Classification problem: \"Eyes open/Eyes shut\" based on time series of brain waves aquired during experiment conducted by Ben Latimer. Thank you Ben! https://www.kaggle.com/latimerb/eeg-leftright I have seen your work and it's truly impressive! I'm not here to copy-paste your work but rather try different approach in cleaning and building / training model. \n",
    "\n",
    "----- \n",
    "\n",
    "What we know: Brain is a highly-complex in its processes (group of) organ(s), driven by chemical reactions that create electromagnetic radiation. As electrical impulses differ of its origins and intensity so do the waves we can register. \n",
    "\n",
    "The experiment obtained alpha waves as they are known to have highest amplitude when we close eyes (in a dark room) and weaken when eyes are open. Exciting! Let's see what we can do with it."
   ]
  },
