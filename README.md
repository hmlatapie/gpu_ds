# gpu_ds
X11-based data science container with support for gpu anaconda-based pytorch. Eliminates need to map container ports by using container-internal web browser (epiphany-browser).

## start container
\`gpu_ds run\`

## inside container
### list environments
conda info --env
### select environment
source activate <desired environment>
### start notebook
jupyter notebook --allow-root
