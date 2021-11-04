# single_file_movement_stumptailed_macaques_toyoda_et_al

This is the python codes for the analysis of the single-file movement of the wild stump-tailed macaques in order to 
- examine the progressive order patterns in the single-file movements
- estimate the social structure by the social network analysis
- estimate the community patterns.
  
The codes with the explanations were prepared as Jupyter notebook.

## Requirements
The code is worked under python3 or anaconda3 with:

```
# platform: osx-64
_anaconda_depends=2020.07=py38_0
_ipyw_jlab_nb_ext_conf=0.1.0=py38_0
alabaster=0.7.12=pyhd3eb1b0_0
anaconda=custom=py38_1
anaconda-client=1.8.0=py38hecd8cb5_0
anaconda-navigator=2.0.3=py38_0
anaconda-project=0.10.1=pyhd3eb1b0_0
anyio=2.2.0=py38hecd8cb5_1
appdirs=1.4.4=pyhd3eb1b0_0
applaunchservices=0.2.1=pyhd3eb1b0_0
appnope=0.1.2=py38hecd8cb5_1001
appscript=1.1.2=py38h9ed2024_0
argh=0.26.2=py38_0
argon2-cffi=20.1.0=py38h9ed2024_1
asn1crypto=1.4.0=py_0
astroid=2.6.6=py38hecd8cb5_0
astropy=4.3.1=py38hf9932de_0
async_generator=1.10=pyhd3eb1b0_0
atomicwrites=1.4.0=py_0
attrs=21.2.0=pyhd3eb1b0_0
autopep8=1.5.6=pyhd3eb1b0_0
babel=2.9.1=pyhd3eb1b0_0
backcall=0.2.0=pyhd3eb1b0_0
backports=1.0=pyhd3eb1b0_2
backports.functools_lru_cache=1.6.4=pyhd3eb1b0_0
backports.shutil_get_terminal_size=1.0.0=pyhd3eb1b0_3
backports.tempfile=1.0=pyhd3eb1b0_1
backports.weakref=1.0.post1=py_1
beautifulsoup4=4.9.3=pyha847dfd_0
bitarray=2.3.0=py38h9ed2024_1
bkcharts=0.2=py38_0
black=19.10b0=py_0
blas=1.0=mkl
bleach=4.0.0=pyhd3eb1b0_0
blosc=1.21.0=h2842e9f_0
bokeh=2.3.3=py38hecd8cb5_0
boto=2.49.0=py38_0
bottleneck=1.3.2=py38hf1fa96c_1
brotli=1.0.9=hb1e8313_2
brotlipy=0.7.0=py38h9ed2024_1003
bzip2=1.0.8=h1de35cc_0
c-ares=1.17.1=h9ed2024_0
ca-certificates=2021.7.5=hecd8cb5_1
certifi=2021.5.30=py38hecd8cb5_0
cffi=1.14.6=py38h2125817_0
chardet=4.0.0=py38hecd8cb5_1003
charset-normalizer=2.0.4=pyhd3eb1b0_0
click=8.0.1=pyhd3eb1b0_0
cloudpickle=1.6.0=pyhd3eb1b0_0
clyent=1.2.2=py38_1
colorama=0.4.4=pyhd3eb1b0_0
conda=4.10.3=py38hecd8cb5_0
conda-build=3.21.4=py38hecd8cb5_0
conda-content-trust=0.1.1=pyhd3eb1b0_0
conda-env=2.6.0=1
conda-pack=0.6.0=pyhd3eb1b0_0
conda-package-handling=1.7.3=py38h9ed2024_1
conda-repo-cli=1.0.4=pyhd3eb1b0_0
conda-token=0.3.0=pyhd3eb1b0_0
conda-verify=3.4.2=py_1
contextlib2=0.6.0.post1=pyhd3eb1b0_0
cryptography=3.4.7=py38h2fd3fbb_0
curl=7.78.0=h7bc2e8c_0
cycler=0.10.0=py38_0
cython=0.29.24=py38h23ab428_0
cytoolz=0.11.0=py38haf1e3a3_0
daal4py=2021.3.0=py38h01d92e1_0
dal=2021.3.0=hecd8cb5_555
dask=2021.8.1=pyhd3eb1b0_0
dask-core=2021.8.1=pyhd3eb1b0_0
dbus=1.13.18=h18a8e69_0
debugpy=1.4.1=py38h23ab428_0
decorator=5.0.9=pyhd3eb1b0_0
defusedxml=0.7.1=pyhd3eb1b0_0
diff-match-patch=20200713=pyhd3eb1b0_0
distributed=2021.8.1=py38hecd8cb5_0
docutils=0.17.1=py38hecd8cb5_1
entrypoints=0.3=py38_0
et_xmlfile=1.1.0=py38hecd8cb5_0
expat=2.4.1=h23ab428_2
fastcache=1.1.0=py38h1de35cc_0
filelock=3.0.12=pyhd3eb1b0_1
flake8=3.9.0=pyhd3eb1b0_0
flask=1.1.2=pyhd3eb1b0_0
fonttools=4.25.0=pyhd3eb1b0_0
freetype=2.10.4=ha233b18_0
fsspec=2021.7.0=pyhd3eb1b0_0
future=0.18.2=py38_1
get_terminal_size=1.0.0=h7520d66_0
gettext=0.21.0=h7535e17_0
gevent=21.8.0=py38h9ed2024_1
glib=2.69.1=hdf23fa2_0
glob2=0.7=pyhd3eb1b0_0
gmp=6.2.1=h23ab428_2
gmpy2=2.0.8=py38h6ef4df4_3
greenlet=1.1.1=py38h23ab428_0
h5py=2.10.0=py38h3134771_0
hdf5=1.10.4=hfa1e0ec_0
heapdict=1.0.1=pyhd3eb1b0_0
html5lib=1.1=pyhd3eb1b0_0
icu=58.2=h0a44026_3
idna=3.2=pyhd3eb1b0_0
imageio=2.9.0=pyhd3eb1b0_0
imagesize=1.2.0=pyhd3eb1b0_0
importlib-metadata=3.10.0=py38hecd8cb5_0
importlib_metadata=3.10.0=hd3eb1b0_0
iniconfig=1.1.1=pyhd3eb1b0_0
intel-openmp=2021.3.0=hecd8cb5_3375
intervaltree=3.1.0=pyhd3eb1b0_0
ipykernel=6.2.0=py38hecd8cb5_1
ipython=7.26.0=py38h01d92e1_0
ipython_genutils=0.2.0=pyhd3eb1b0_1
ipywidgets=7.6.3=pyhd3eb1b0_1
isort=5.9.3=pyhd3eb1b0_0
itsdangerous=2.0.1=pyhd3eb1b0_0
jbig=2.1=h4d881f8_0
jdcal=1.4.1=pyhd3eb1b0_0
jedi=0.17.2=py38hecd8cb5_1
jinja2=2.11.3=pyhd3eb1b0_0
joblib=1.0.1=pyhd3eb1b0_0
jpeg=9b=he5867d9_2
json5=0.9.6=pyhd3eb1b0_0
jsonschema=3.2.0=pyhd3eb1b0_2
jupyter=1.0.0=py38_7
jupyter_client=7.0.1=pyhd3eb1b0_0
jupyter_console=6.4.0=pyhd3eb1b0_0
jupyter_core=4.7.1=py38hecd8cb5_0
jupyter_server=1.4.1=py38hecd8cb5_0
jupyterlab=3.1.7=pyhd3eb1b0_0
jupyterlab_pygments=0.1.2=py_0
jupyterlab_server=2.7.2=pyhd3eb1b0_0
jupyterlab_widgets=1.0.0=pyhd3eb1b0_1
keyring=23.0.1=py38hecd8cb5_0
kiwisolver=1.3.1=py38h23ab428_0
krb5=1.19.2=hcd88c3b_0
lazy-object-proxy=1.6.0=py38h9ed2024_0
lcms2=2.12=hf1fd2bf_0
libarchive=3.4.2=haa3ed63_0
libcurl=7.78.0=hb8e4fae_0
libcxx=12.0.0=h2f01273_0
libedit=3.1.20210714=h9ed2024_0
libev=4.33=haf1e3a3_0
libffi=3.3=hb1e8313_2
libgfortran=3.0.1=h93005f0_2
libiconv=1.16=h1de35cc_0
liblief=0.10.1=h0a44026_0
libllvm10=10.0.1=h76017ad_5
libllvm9=9.0.1=h21ff451_1
libnghttp2=1.41.0=h7580e61_2
libpng=1.6.37=ha441bb4_0
libsodium=1.0.18=h1de35cc_0
libspatialindex=1.9.3=h23ab428_0
libssh2=1.9.0=ha12b0ac_1
libtiff=4.2.0=h87d7836_0
libuv=1.40.0=haf1e3a3_0
libwebp-base=1.2.0=h9ed2024_0
libxml2=2.9.12=hcdb78fc_0
libxslt=1.1.34=h83b36ba_0
llvm-openmp=12.0.0=h0dcd299_1
llvmlite=0.36.0=py38he4411ff_4
locket=0.2.1=py38hecd8cb5_1
lxml=4.6.3=py38h26b266a_0
lz4-c=1.9.3=h23ab428_1
lzo=2.10=haf1e3a3_2
markupsafe=2.0.1=py38h9ed2024_0
matplotlib=3.4.2=py38hecd8cb5_0
matplotlib-base=3.4.2=py38h8b3ea08_0
matplotlib-inline=0.1.2=pyhd3eb1b0_2
mccabe=0.6.1=py38_1
mistune=0.8.4=py38h1de35cc_1001
mkl=2021.3.0=hecd8cb5_517
mkl-service=2.4.0=py38h9ed2024_0
mkl_fft=1.3.0=py38h4a7008c_2
mkl_random=1.2.2=py38hb2f4e1b_0
mock=4.0.3=pyhd3eb1b0_0
more-itertools=8.8.0=pyhd3eb1b0_0
mpc=1.1.0=h6ef4df4_1
mpfr=4.0.2=h9066e36_1
mpi=1.0=mpich
mpich=3.3.2=hc856adb_0
mpmath=1.2.1=py38hecd8cb5_0
msgpack-python=1.0.2=py38hf7b0b51_1
multipledispatch=0.6.0=py38_0
munkres=1.1.4=py_0
mypy_extensions=0.4.3=py38_0
navigator-updater=0.2.1=py38_0
nbclassic=0.2.6=pyhd3eb1b0_0
nbclient=0.5.3=pyhd3eb1b0_0
nbconvert=6.1.0=py38hecd8cb5_0
nbformat=5.1.3=pyhd3eb1b0_0
ncurses=6.2=h0a44026_1
nest-asyncio=1.5.1=pyhd3eb1b0_0
networkx=2.5=py_0
nltk=3.6.2=pyhd3eb1b0_0
nose=1.3.7=pyhd3eb1b0_1006
notebook=6.4.3=py38hecd8cb5_0
numba=0.53.0=py38hb2f4e1b_0
numexpr=2.7.3=py38h5873af2_1
numpy=1.20.3=py38h4b4dc7a_0
numpy-base=1.20.3=py38he0bd621_0
numpydoc=1.1.0=pyhd3eb1b0_1
olefile=0.46=pyhd3eb1b0_0
openjpeg=2.4.0=h66ea3da_0
openpyxl=3.0.7=pyhd3eb1b0_0
openssl=1.1.1l=h9ed2024_0
packaging=21.0=pyhd3eb1b0_0
pandas=1.3.2=py38h5008ddb_0
pandoc=2.12=hecd8cb5_0
pandocfilters=1.4.3=py38hecd8cb5_1
parso=0.7.0=py_0
partd=1.2.0=pyhd3eb1b0_0
path=16.0.0=py38hecd8cb5_0
path.py=12.5.0=hd3eb1b0_0
pathlib2=2.3.6=py38hecd8cb5_2
pathspec=0.7.0=py_0
pathtools=0.1.2=pyhd3eb1b0_1
patsy=0.5.1=py38_0
pcre=8.45=h23ab428_0
pep8=1.7.1=py38_0
pexpect=4.8.0=pyhd3eb1b0_3
pickleshare=0.7.5=pyhd3eb1b0_1003
pillow=8.3.1=py38ha4cf6ea_0
pip=21.2.2=py38hecd8cb5_0
pkginfo=1.7.1=py38hecd8cb5_0
pluggy=0.13.1=py38hecd8cb5_0
ply=3.11=py38_0
prometheus_client=0.11.0=pyhd3eb1b0_0
prompt-toolkit=3.0.17=pyhca03da5_0
prompt_toolkit=3.0.17=hd3eb1b0_0
psutil=5.8.0=py38h9ed2024_1
ptyprocess=0.7.0=pyhd3eb1b0_2
py=1.10.0=pyhd3eb1b0_0
py-lief=0.10.1=py38haf313ee_0
pycodestyle=2.6.0=pyhd3eb1b0_0
pycosat=0.6.3=py38h1de35cc_1
pycparser=2.20=py_2
pycurl=7.44.0=py38hbcfaee0_0
pydocstyle=6.1.1=pyhd3eb1b0_0
pyerfa=2.0.0=py38h9ed2024_0
pyflakes=2.2.0=pyhd3eb1b0_0
pygments=2.10.0=pyhd3eb1b0_0
pygraphviz=1.7=pypi_0
pylint=2.9.6=py38hecd8cb5_1
pyls-black=0.4.6=hd3eb1b0_0
pyls-spyder=0.3.2=pyhd3eb1b0_0
pyodbc=4.0.31=py38h23ab428_0
pyopenssl=20.0.1=pyhd3eb1b0_1
pyparsing=2.4.7=pyhd3eb1b0_0
pyqt=5.9.2=py38h655552a_2
pyrsistent=0.17.3=py38haf1e3a3_0
pysocks=1.7.1=py38_1
pytables=3.6.1=py38h4727e94_0
pytest=6.2.4=py38hecd8cb5_2
python=3.8.8=h88f2d9e_5
python-dateutil=2.8.2=pyhd3eb1b0_0
python-graphviz=0.17=pypi_0
python-jsonrpc-server=0.4.0=py_0
python-language-server=0.36.2=pyhd3eb1b0_0
python-libarchive-c=2.9=pyhd3eb1b0_1
python-louvain=0.15=pyhd3deb0d_0
python.app=3=py38h9ed2024_0
python_abi=3.8=2_cp38
pytz=2021.1=pyhd3eb1b0_0
pywavelets=1.1.1=py38haf1e3a3_2
pyyaml=5.4.1=py38h9ed2024_1
pyzmq=22.2.1=py38h23ab428_1
qdarkstyle=2.8.1=py_0
qt=5.9.7=h468cd18_1
qtawesome=1.0.2=pyhd3eb1b0_0
qtconsole=5.1.0=pyhd3eb1b0_0
qtpy=1.10.0=pyhd3eb1b0_0
readline=8.1=h9ed2024_0
regex=2021.8.3=py38h9ed2024_0
requests=2.26.0=pyhd3eb1b0_0
ripgrep=12.1.1=0
rope=0.19.0=pyhd3eb1b0_0
rtree=0.9.7=py38hecd8cb5_1
ruamel_yaml=0.15.100=py38h9ed2024_0
scikit-image=0.16.2=py38h6c726b0_0
scikit-learn=0.24.2=py38hb2f4e1b_0
scikit-learn-intelex=2021.3.0=py38hecd8cb5_0
scipy=1.7.1=py38h88652d9_2
seaborn=0.11.2=pyhd3eb1b0_0
send2trash=1.5.0=pyhd3eb1b0_1
setuptools=52.0.0=py38hecd8cb5_0
simplegeneric=0.8.1=py38_2
singledispatch=3.7.0=pyhd3eb1b0_1001
sip=4.19.8=py38h0a44026_0
six=1.16.0=pyhd3eb1b0_0
snappy=1.1.8=hb1e8313_0
sniffio=1.2.0=py38hecd8cb5_1
snowballstemmer=2.1.0=pyhd3eb1b0_0
sortedcollections=2.1.0=pyhd3eb1b0_0
sortedcontainers=2.4.0=pyhd3eb1b0_0
soupsieve=2.2.1=pyhd3eb1b0_0
sphinx=4.0.2=pyhd3eb1b0_0
sphinxcontrib=1.0=py38_1
sphinxcontrib-applehelp=1.0.2=pyhd3eb1b0_0
sphinxcontrib-devhelp=1.0.2=pyhd3eb1b0_0
sphinxcontrib-htmlhelp=2.0.0=pyhd3eb1b0_0
sphinxcontrib-jsmath=1.0.1=pyhd3eb1b0_0
sphinxcontrib-qthelp=1.0.3=pyhd3eb1b0_0
sphinxcontrib-serializinghtml=1.1.5=pyhd3eb1b0_0
sphinxcontrib-websupport=1.2.4=py_0
spyder=4.2.5=py38hecd8cb5_0
spyder-kernels=1.10.2=py38hecd8cb5_0
sqlalchemy=1.4.22=py38h9ed2024_0
sqlite=3.36.0=hce871da_0
statsmodels=0.12.2=py38h9ed2024_0
sympy=1.8=py38hecd8cb5_0
tbb=2021.3.0=hf7b0b51_0
tblib=1.7.0=pyhd3eb1b0_0
terminado=0.9.4=py38hecd8cb5_0
testpath=0.5.0=pyhd3eb1b0_0
textdistance=4.2.1=pyhd3eb1b0_0
threadpoolctl=2.2.0=pyh0d69192_0
three-merge=0.1.1=pyhd3eb1b0_0
tk=8.6.10=hb0a8c7a_0
toml=0.10.2=pyhd3eb1b0_0
toolz=0.11.1=pyhd3eb1b0_0
tornado=6.1=py38h9ed2024_0
tqdm=4.62.1=pyhd3eb1b0_1
traitlets=5.0.5=pyhd3eb1b0_0
typed-ast=1.4.3=py38h9ed2024_1
typing_extensions=3.10.0.0=pyhca03da5_0
ujson=4.0.2=py38h23ab428_0
unicodecsv=0.14.1=py38_0
unixodbc=2.3.9=haf1e3a3_0
urllib3=1.26.6=pyhd3eb1b0_1
watchdog=1.0.2=py38h9ed2024_1
wcwidth=0.2.5=pyhd3eb1b0_0
webencodings=0.5.1=py38_1
werkzeug=1.0.1=pyhd3eb1b0_0
wheel=0.37.0=pyhd3eb1b0_1
widgetsnbextension=3.5.1=py38_0
wrapt=1.12.1=py38haf1e3a3_1
wurlitzer=2.1.1=py38hecd8cb5_0
xlrd=2.0.1=pyhd3eb1b0_0
xlsxwriter=3.0.1=pyhd3eb1b0_0
xlwings=0.24.7=py38hecd8cb5_0
xlwt=1.3.0=py38_0
xmltodict=0.12.0=pyhd3eb1b0_0
xz=5.2.5=h1de35cc_0
yaml=0.2.5=haf1e3a3_0
yapf=0.31.0=pyhd3eb1b0_0
zeromq=4.3.4=h23ab428_0
zict=2.0.0=pyhd3eb1b0_0
zipp=3.5.0=pyhd3eb1b0_0
zlib=1.2.11=h1de35cc_3
zope=1.0=py38_1
zope.event=4.5.0=py38_0
zope.interface=5.4.0=py38h9ed2024_0
zstd=1.4.9=h322a384_0
```

