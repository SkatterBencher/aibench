## aibenchmark miniconda env ##

install miniconda https://docs.anaconda.com/miniconda/install/

git clone in /users/{name}/miniconda/envs/ (folder aibench contains files)

open miniconda terminal

conda activate aibench (activates env)

set TF_ENABLE_ONEDNN_OPTS=1 (enables onednn acceleration)

python

from ai_benchmark import AIBenchmark

benchmark = AIBenchmark(use_CPU=True, verbose_level=3)

benchmark.run()
