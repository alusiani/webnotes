---
date: 2024-06-04 11:23:01
layout: post
---

## jupytext

```
Welcome to -+- lxplus989.cern.ch -+-
lusiani@lxplus989> pip install --user -U jupytext
Collecting jupytext
  Downloading jupytext-1.16.2-py3-none-any.whl.metadata (13 kB)
Requirement already satisfied: markdown-it-py>=1.0 in /cvmfs/lhcb.cern.ch/lib/var/lib/LbEnv/3149/stable/linux-64/lib/python3.12/site-packages (from jupytext) (3.0.0)
Collecting mdit-py-plugins (from jupytext)
  Downloading mdit_py_plugins-0.4.1-py3-none-any.whl.metadata (2.8 kB)
Collecting nbformat (from jupytext)
  Downloading nbformat-5.10.4-py3-none-any.whl.metadata (3.6 kB)
Requirement already satisfied: packaging in /cvmfs/lhcb.cern.ch/lib/var/lib/LbEnv/3149/stable/linux-64/lib/python3.12/site-packages (from jupytext) (24.0)
Requirement already satisfied: pyyaml in /cvmfs/lhcb.cern.ch/lib/var/lib/LbEnv/3149/stable/linux-64/lib/python3.12/site-packages (from jupytext) (6.0.1)
Requirement already satisfied: mdurl~=0.1 in /cvmfs/lhcb.cern.ch/lib/var/lib/LbEnv/3149/stable/linux-64/lib/python3.12/site-packages (from markdown-it-py>=1.0->jupytext) (0.1.2)
Requirement already satisfied: fastjsonschema>=2.15 in /cvmfs/lhcb.cern.ch/lib/var/lib/LbEnv/3149/stable/linux-64/lib/python3.12/site-packages (from nbformat->jupytext) (2.19.1)
Collecting jsonschema>=2.6 (from nbformat->jupytext)
  Downloading jsonschema-4.22.0-py3-none-any.whl.metadata (8.2 kB)
Collecting jupyter-core!=5.0.*,>=4.12 (from nbformat->jupytext)
  Downloading jupyter_core-5.7.2-py3-none-any.whl.metadata (3.4 kB)
Requirement already satisfied: traitlets>=5.1 in /cvmfs/lhcb.cern.ch/lib/var/lib/LbEnv/3149/stable/linux-64/lib/python3.12/site-packages (from nbformat->jupytext) (5.14.3)
Collecting attrs>=22.2.0 (from jsonschema>=2.6->nbformat->jupytext)
  Downloading attrs-23.2.0-py3-none-any.whl.metadata (9.5 kB)
Collecting jsonschema-specifications>=2023.03.6 (from jsonschema>=2.6->nbformat->jupytext)
  Downloading jsonschema_specifications-2023.12.1-py3-none-any.whl.metadata (3.0 kB)
Collecting referencing>=0.28.4 (from jsonschema>=2.6->nbformat->jupytext)
  Downloading referencing-0.35.1-py3-none-any.whl.metadata (2.8 kB)
Collecting rpds-py>=0.7.1 (from jsonschema>=2.6->nbformat->jupytext)
  Downloading rpds_py-0.18.1-cp312-cp312-manylinux_2_17_x86_64.manylinux2014_x86_64.whl.metadata (4.1 kB)
Requirement already satisfied: platformdirs>=2.5 in /cvmfs/lhcb.cern.ch/lib/var/lib/LbEnv/3149/stable/linux-64/lib/python3.12/site-packages (from jupyter-core!=5.0.*,>=4.12->nbformat->jupytext) (4.2.0)
Downloading jupytext-1.16.2-py3-none-any.whl (153 kB)
   ━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━ 153.2/153.2 kB 3.2 MB/s eta 0:00:00
Downloading mdit_py_plugins-0.4.1-py3-none-any.whl (54 kB)
   ━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━ 54.8/54.8 kB 3.6 MB/s eta 0:00:00
Downloading nbformat-5.10.4-py3-none-any.whl (78 kB)
   ━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━ 78.5/78.5 kB 776.7 kB/s eta 0:00:00
Downloading jsonschema-4.22.0-py3-none-any.whl (88 kB)
   ━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━ 88.3/88.3 kB 2.2 MB/s eta 0:00:00
Downloading jupyter_core-5.7.2-py3-none-any.whl (28 kB)
Downloading attrs-23.2.0-py3-none-any.whl (60 kB)
   ━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━ 60.8/60.8 kB 4.5 MB/s eta 0:00:00
Downloading jsonschema_specifications-2023.12.1-py3-none-any.whl (18 kB)
Downloading referencing-0.35.1-py3-none-any.whl (26 kB)
Downloading rpds_py-0.18.1-cp312-cp312-manylinux_2_17_x86_64.manylinux2014_x86_64.whl (1.1 MB)
   ━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━ 1.1/1.1 MB 14.6 MB/s eta 0:00:00
Installing collected packages: rpds-py, jupyter-core, attrs, referencing, mdit-py-plugins, jsonschema-specifications, jsonschema, nbformat, jupytext
Successfully installed attrs-23.2.0 jsonschema-4.22.0 jsonschema-specifications-2023.12.1 jupyter-core-5.7.2 jupytext-1.16.2 mdit-py-plugins-0.4.1 nbformat-5.10.4 referencing-0.35.1 rpds-py-0.18.1
lusiani@lxplus989> uname -a
Linux lxplus989.cern.ch 5.14.0-427.16.1.el9_4.x86_64 #1 SMP PREEMPT_DYNAMIC Fri Apr 26 18:16:09 EDT 2024 x86_64 x86_64 x86_64 GNU/Linux
lusiani@lxplus989> which jupytext
~/.local/bin/jupytext
```

## jsonlite

```
lusiani@lxplus989> R

R version 4.4.0 (2024-04-24) -- "Puppy Cup"
Copyright (C) 2024 The R Foundation for Statistical Computing
Platform: x86_64-redhat-linux-gnu

R is free software and comes with ABSOLUTELY NO WARRANTY.
You are welcome to redistribute it under certain conditions.
Type 'license()' or 'licence()' for distribution details.

  Natural language support but running in an English locale

R is a collaborative project with many contributors.
Type 'contributors()' for more information and
'citation()' on how to cite R or R packages in publications.

Type 'demo()' for some demos, 'help()' for on-line help, or
'help.start()' for an HTML browser interface to help.
Type 'q()' to quit R.

> install.packages("jsonlite")
Installing package into ‘/usr/lib64/R/library’
(as ‘lib’ is unspecified)
Warning in install.packages("jsonlite") :
  'lib = "/usr/lib64/R/library"' is not writable
Would you like to use a personal library instead? (yes/No/cancel) y
Would you like to create a personal library
‘/afs/cern.ch/user/l/lusiani/R/x86_64-redhat-linux-gnu-library/4.4’
to install packages into? (yes/No/cancel) yes
--- Please select a CRAN mirror for use in this session ---
Secure CRAN mirrors 

 1: 0-Cloud [https]
 2: Australia (Canberra) [https]
 3: Australia (Melbourne 1) [https]
 4: Australia (Melbourne 2) [https]
 5: Austria [https]
 6: Belgium (Brussels) [https]
 7: Brazil (PR) [https]
 8: Brazil (RJ) [https]
 9: Brazil (SP 1) [https]
10: Brazil (SP 2) [https]
11: Bulgaria [https]
12: Canada (MB) [https]
13: Canada (ON 1) [https]
14: Canada (ON 2) [https]
15: Chile (Santiago) [https]
16: China (Beijing 2) [https]
17: China (Beijing 3) [https]
18: China (Hefei) [https]
19: China (Hong Kong) [https]
20: China (Guangzhou) [https]
21: China (Jinan) [https]
22: China (Lanzhou) [https]
23: China (Nanjing) [https]
24: China (Shanghai 2) [https]
25: China (Shenzhen) [https]
26: Colombia (Cali) [https]
27: Costa Rica [https]
28: Cyprus [https]
29: Czech Republic [https]
30: Denmark [https]
31: East Asia [https]
32: Ecuador (Cuenca) [https]
33: France (Lyon 1) [https]
34: France (Lyon 2) [https]
35: France (Marseille) [https]
36: France (Paris 1) [https]
37: Germany (Erlangen) [https]
38: Germany (Göttingen) [https]
39: Germany (Leipzig) [https]
40: Germany (Münster) [https]
41: Greece [https]
42: Iceland [https]
43: India (Bengaluru) [https]
44: India (Bhubaneswar) [https]
45: Indonesia (Banda Aceh) [https]
46: Iran (Mashhad) [https]
47: Italy (Milano) [https]
48: Italy (Padua) [https]
49: Japan (Tokyo) [https]
50: Japan (Yonezawa) [https]
51: Korea (Gyeongsan-si) [https]
52: Mexico (Mexico City) [https]
53: Mexico (Texcoco) [https]
54: Morocco [https]
55: Netherlands (Dronten) [https]
56: New Zealand [https]
57: Norway [https]
58: South Africa (Johannesburg) [https]
59: Spain (A Coruña) [https]
60: Spain (Madrid) [https]
61: Sweden (Umeå) [https]
62: Switzerland (Zurich 1) [https]
63: Taiwan (Taipei) [https]
64: Turkey (Denizli) [https]
65: Turkey (Istanbul) [https]
66: UK (Bristol) [https]
67: UK (London 1) [https]
68: USA (IA) [https]
69: USA (MI) [https]
70: USA (MO) [https]
71: USA (OH) [https]
72: USA (OR) [https]
73: USA (TN) [https]
74: United Arab Emirates [https]
75: Uruguay [https]
76: (other mirrors)

Selection: 62
trying URL 'https://stat.ethz.ch/CRAN/src/contrib/jsonlite_1.8.8.tar.gz'
Content type 'application/x-gzip' length 1053028 bytes (1.0 MB)
==================================================
downloaded 1.0 MB

* installing *source* package ‘jsonlite’ ...
** package ‘jsonlite’ successfully unpacked and MD5 sums checked
** using staged installation
** libs
using C compiler: ‘gcc (GCC) 11.4.1 20231218 (Red Hat 11.4.1-3)’
gcc -I"/usr/include/R" -DNDEBUG -Iyajl/api  -I/usr/local/include   -fvisibility=hidden  -fpic  -O2 -flto=auto -ffat-lto-objects -fexceptions -g -grecord-gcc-switches -pipe -Wall -Werror=format-security -Wp,-D_FORTIFY_SOURCE=2 -Wp,-D_GLIBCXX_ASSERTIONS -specs=/usr/lib/rpm/redhat/redhat-hardened-cc1 -fstack-protector-strong -specs=/usr/lib/rpm/redhat/redhat-annobin-cc1  -m64 -march=x86-64-v2 -mtune=generic -fasynchronous-unwind-tables -fstack-clash-protection -fcf-protection  -c base64.c -o base64.o
gcc -I"/usr/include/R" -DNDEBUG -Iyajl/api  -I/usr/local/include   -fvisibility=hidden  -fpic  -O2 -flto=auto -ffat-lto-objects -fexceptions -g -grecord-gcc-switches -pipe -Wall -Werror=format-security -Wp,-D_FORTIFY_SOURCE=2 -Wp,-D_GLIBCXX_ASSERTIONS -specs=/usr/lib/rpm/redhat/redhat-hardened-cc1 -fstack-protector-strong -specs=/usr/lib/rpm/redhat/redhat-annobin-cc1  -m64 -march=x86-64-v2 -mtune=generic -fasynchronous-unwind-tables -fstack-clash-protection -fcf-protection  -c collapse_array.c -o collapse_array.o
gcc -I"/usr/include/R" -DNDEBUG -Iyajl/api  -I/usr/local/include   -fvisibility=hidden  -fpic  -O2 -flto=auto -ffat-lto-objects -fexceptions -g -grecord-gcc-switches -pipe -Wall -Werror=format-security -Wp,-D_FORTIFY_SOURCE=2 -Wp,-D_GLIBCXX_ASSERTIONS -specs=/usr/lib/rpm/redhat/redhat-hardened-cc1 -fstack-protector-strong -specs=/usr/lib/rpm/redhat/redhat-annobin-cc1  -m64 -march=x86-64-v2 -mtune=generic -fasynchronous-unwind-tables -fstack-clash-protection -fcf-protection  -c collapse_object.c -o collapse_object.o
gcc -I"/usr/include/R" -DNDEBUG -Iyajl/api  -I/usr/local/include   -fvisibility=hidden  -fpic  -O2 -flto=auto -ffat-lto-objects -fexceptions -g -grecord-gcc-switches -pipe -Wall -Werror=format-security -Wp,-D_FORTIFY_SOURCE=2 -Wp,-D_GLIBCXX_ASSERTIONS -specs=/usr/lib/rpm/redhat/redhat-hardened-cc1 -fstack-protector-strong -specs=/usr/lib/rpm/redhat/redhat-annobin-cc1  -m64 -march=x86-64-v2 -mtune=generic -fasynchronous-unwind-tables -fstack-clash-protection -fcf-protection  -c collapse_pretty.c -o collapse_pretty.o
gcc -I"/usr/include/R" -DNDEBUG -Iyajl/api  -I/usr/local/include   -fvisibility=hidden  -fpic  -O2 -flto=auto -ffat-lto-objects -fexceptions -g -grecord-gcc-switches -pipe -Wall -Werror=format-security -Wp,-D_FORTIFY_SOURCE=2 -Wp,-D_GLIBCXX_ASSERTIONS -specs=/usr/lib/rpm/redhat/redhat-hardened-cc1 -fstack-protector-strong -specs=/usr/lib/rpm/redhat/redhat-annobin-cc1  -m64 -march=x86-64-v2 -mtune=generic -fasynchronous-unwind-tables -fstack-clash-protection -fcf-protection  -c escape_chars.c -o escape_chars.o
gcc -I"/usr/include/R" -DNDEBUG -Iyajl/api  -I/usr/local/include   -fvisibility=hidden  -fpic  -O2 -flto=auto -ffat-lto-objects -fexceptions -g -grecord-gcc-switches -pipe -Wall -Werror=format-security -Wp,-D_FORTIFY_SOURCE=2 -Wp,-D_GLIBCXX_ASSERTIONS -specs=/usr/lib/rpm/redhat/redhat-hardened-cc1 -fstack-protector-strong -specs=/usr/lib/rpm/redhat/redhat-annobin-cc1  -m64 -march=x86-64-v2 -mtune=generic -fasynchronous-unwind-tables -fstack-clash-protection -fcf-protection  -c integer64_to_na.c -o integer64_to_na.o
gcc -I"/usr/include/R" -DNDEBUG -Iyajl/api  -I/usr/local/include   -fvisibility=hidden  -fpic  -O2 -flto=auto -ffat-lto-objects -fexceptions -g -grecord-gcc-switches -pipe -Wall -Werror=format-security -Wp,-D_FORTIFY_SOURCE=2 -Wp,-D_GLIBCXX_ASSERTIONS -specs=/usr/lib/rpm/redhat/redhat-hardened-cc1 -fstack-protector-strong -specs=/usr/lib/rpm/redhat/redhat-annobin-cc1  -m64 -march=x86-64-v2 -mtune=generic -fasynchronous-unwind-tables -fstack-clash-protection -fcf-protection  -c is_datelist.c -o is_datelist.o
gcc -I"/usr/include/R" -DNDEBUG -Iyajl/api  -I/usr/local/include   -fvisibility=hidden  -fpic  -O2 -flto=auto -ffat-lto-objects -fexceptions -g -grecord-gcc-switches -pipe -Wall -Werror=format-security -Wp,-D_FORTIFY_SOURCE=2 -Wp,-D_GLIBCXX_ASSERTIONS -specs=/usr/lib/rpm/redhat/redhat-hardened-cc1 -fstack-protector-strong -specs=/usr/lib/rpm/redhat/redhat-annobin-cc1  -m64 -march=x86-64-v2 -mtune=generic -fasynchronous-unwind-tables -fstack-clash-protection -fcf-protection  -c is_recordlist.c -o is_recordlist.o
gcc -I"/usr/include/R" -DNDEBUG -Iyajl/api  -I/usr/local/include   -fvisibility=hidden  -fpic  -O2 -flto=auto -ffat-lto-objects -fexceptions -g -grecord-gcc-switches -pipe -Wall -Werror=format-security -Wp,-D_FORTIFY_SOURCE=2 -Wp,-D_GLIBCXX_ASSERTIONS -specs=/usr/lib/rpm/redhat/redhat-hardened-cc1 -fstack-protector-strong -specs=/usr/lib/rpm/redhat/redhat-annobin-cc1  -m64 -march=x86-64-v2 -mtune=generic -fasynchronous-unwind-tables -fstack-clash-protection -fcf-protection  -c is_scalarlist.c -o is_scalarlist.o
gcc -I"/usr/include/R" -DNDEBUG -Iyajl/api  -I/usr/local/include   -fvisibility=hidden  -fpic  -O2 -flto=auto -ffat-lto-objects -fexceptions -g -grecord-gcc-switches -pipe -Wall -Werror=format-security -Wp,-D_FORTIFY_SOURCE=2 -Wp,-D_GLIBCXX_ASSERTIONS -specs=/usr/lib/rpm/redhat/redhat-hardened-cc1 -fstack-protector-strong -specs=/usr/lib/rpm/redhat/redhat-annobin-cc1  -m64 -march=x86-64-v2 -mtune=generic -fasynchronous-unwind-tables -fstack-clash-protection -fcf-protection  -c modp_numtoa.c -o modp_numtoa.o
gcc -I"/usr/include/R" -DNDEBUG -Iyajl/api  -I/usr/local/include   -fvisibility=hidden  -fpic  -O2 -flto=auto -ffat-lto-objects -fexceptions -g -grecord-gcc-switches -pipe -Wall -Werror=format-security -Wp,-D_FORTIFY_SOURCE=2 -Wp,-D_GLIBCXX_ASSERTIONS -specs=/usr/lib/rpm/redhat/redhat-hardened-cc1 -fstack-protector-strong -specs=/usr/lib/rpm/redhat/redhat-annobin-cc1  -m64 -march=x86-64-v2 -mtune=generic -fasynchronous-unwind-tables -fstack-clash-protection -fcf-protection  -c null_to_na.c -o null_to_na.o
gcc -I"/usr/include/R" -DNDEBUG -Iyajl/api  -I/usr/local/include   -fvisibility=hidden  -fpic  -O2 -flto=auto -ffat-lto-objects -fexceptions -g -grecord-gcc-switches -pipe -Wall -Werror=format-security -Wp,-D_FORTIFY_SOURCE=2 -Wp,-D_GLIBCXX_ASSERTIONS -specs=/usr/lib/rpm/redhat/redhat-hardened-cc1 -fstack-protector-strong -specs=/usr/lib/rpm/redhat/redhat-annobin-cc1  -m64 -march=x86-64-v2 -mtune=generic -fasynchronous-unwind-tables -fstack-clash-protection -fcf-protection  -c num_to_char.c -o num_to_char.o
gcc -I"/usr/include/R" -DNDEBUG -Iyajl/api  -I/usr/local/include   -fvisibility=hidden  -fpic  -O2 -flto=auto -ffat-lto-objects -fexceptions -g -grecord-gcc-switches -pipe -Wall -Werror=format-security -Wp,-D_FORTIFY_SOURCE=2 -Wp,-D_GLIBCXX_ASSERTIONS -specs=/usr/lib/rpm/redhat/redhat-hardened-cc1 -fstack-protector-strong -specs=/usr/lib/rpm/redhat/redhat-annobin-cc1  -m64 -march=x86-64-v2 -mtune=generic -fasynchronous-unwind-tables -fstack-clash-protection -fcf-protection  -c parse.c -o parse.o
gcc -I"/usr/include/R" -DNDEBUG -Iyajl/api  -I/usr/local/include   -fvisibility=hidden  -fpic  -O2 -flto=auto -ffat-lto-objects -fexceptions -g -grecord-gcc-switches -pipe -Wall -Werror=format-security -Wp,-D_FORTIFY_SOURCE=2 -Wp,-D_GLIBCXX_ASSERTIONS -specs=/usr/lib/rpm/redhat/redhat-hardened-cc1 -fstack-protector-strong -specs=/usr/lib/rpm/redhat/redhat-annobin-cc1  -m64 -march=x86-64-v2 -mtune=generic -fasynchronous-unwind-tables -fstack-clash-protection -fcf-protection  -c prettify.c -o prettify.o
gcc -I"/usr/include/R" -DNDEBUG -Iyajl/api  -I/usr/local/include   -fvisibility=hidden  -fpic  -O2 -flto=auto -ffat-lto-objects -fexceptions -g -grecord-gcc-switches -pipe -Wall -Werror=format-security -Wp,-D_FORTIFY_SOURCE=2 -Wp,-D_GLIBCXX_ASSERTIONS -specs=/usr/lib/rpm/redhat/redhat-hardened-cc1 -fstack-protector-strong -specs=/usr/lib/rpm/redhat/redhat-annobin-cc1  -m64 -march=x86-64-v2 -mtune=generic -fasynchronous-unwind-tables -fstack-clash-protection -fcf-protection  -c push_parser.c -o push_parser.o
gcc -I"/usr/include/R" -DNDEBUG -Iyajl/api  -I/usr/local/include   -fvisibility=hidden  -fpic  -O2 -flto=auto -ffat-lto-objects -fexceptions -g -grecord-gcc-switches -pipe -Wall -Werror=format-security -Wp,-D_FORTIFY_SOURCE=2 -Wp,-D_GLIBCXX_ASSERTIONS -specs=/usr/lib/rpm/redhat/redhat-hardened-cc1 -fstack-protector-strong -specs=/usr/lib/rpm/redhat/redhat-annobin-cc1  -m64 -march=x86-64-v2 -mtune=generic -fasynchronous-unwind-tables -fstack-clash-protection -fcf-protection  -c r-base64.c -o r-base64.o
gcc -I"/usr/include/R" -DNDEBUG -Iyajl/api  -I/usr/local/include   -fvisibility=hidden  -fpic  -O2 -flto=auto -ffat-lto-objects -fexceptions -g -grecord-gcc-switches -pipe -Wall -Werror=format-security -Wp,-D_FORTIFY_SOURCE=2 -Wp,-D_GLIBCXX_ASSERTIONS -specs=/usr/lib/rpm/redhat/redhat-hardened-cc1 -fstack-protector-strong -specs=/usr/lib/rpm/redhat/redhat-annobin-cc1  -m64 -march=x86-64-v2 -mtune=generic -fasynchronous-unwind-tables -fstack-clash-protection -fcf-protection  -c register.c -o register.o
gcc -I"/usr/include/R" -DNDEBUG -Iyajl/api  -I/usr/local/include   -fvisibility=hidden  -fpic  -O2 -flto=auto -ffat-lto-objects -fexceptions -g -grecord-gcc-switches -pipe -Wall -Werror=format-security -Wp,-D_FORTIFY_SOURCE=2 -Wp,-D_GLIBCXX_ASSERTIONS -specs=/usr/lib/rpm/redhat/redhat-hardened-cc1 -fstack-protector-strong -specs=/usr/lib/rpm/redhat/redhat-annobin-cc1  -m64 -march=x86-64-v2 -mtune=generic -fasynchronous-unwind-tables -fstack-clash-protection -fcf-protection  -c row_collapse.c -o row_collapse.o
gcc -I"/usr/include/R" -DNDEBUG -Iyajl/api  -I/usr/local/include   -fvisibility=hidden  -fpic  -O2 -flto=auto -ffat-lto-objects -fexceptions -g -grecord-gcc-switches -pipe -Wall -Werror=format-security -Wp,-D_FORTIFY_SOURCE=2 -Wp,-D_GLIBCXX_ASSERTIONS -specs=/usr/lib/rpm/redhat/redhat-hardened-cc1 -fstack-protector-strong -specs=/usr/lib/rpm/redhat/redhat-annobin-cc1  -m64 -march=x86-64-v2 -mtune=generic -fasynchronous-unwind-tables -fstack-clash-protection -fcf-protection  -c transpose_list.c -o transpose_list.o
gcc -I"/usr/include/R" -DNDEBUG -Iyajl/api  -I/usr/local/include   -fvisibility=hidden  -fpic  -O2 -flto=auto -ffat-lto-objects -fexceptions -g -grecord-gcc-switches -pipe -Wall -Werror=format-security -Wp,-D_FORTIFY_SOURCE=2 -Wp,-D_GLIBCXX_ASSERTIONS -specs=/usr/lib/rpm/redhat/redhat-hardened-cc1 -fstack-protector-strong -specs=/usr/lib/rpm/redhat/redhat-annobin-cc1  -m64 -march=x86-64-v2 -mtune=generic -fasynchronous-unwind-tables -fstack-clash-protection -fcf-protection  -c validate.c -o validate.o
gcc -I"/usr/include/R" -DNDEBUG -Iyajl/api  -I/usr/local/include   -fvisibility=hidden  -fpic  -O2 -flto=auto -ffat-lto-objects -fexceptions -g -grecord-gcc-switches -pipe -Wall -Werror=format-security -Wp,-D_FORTIFY_SOURCE=2 -Wp,-D_GLIBCXX_ASSERTIONS -specs=/usr/lib/rpm/redhat/redhat-hardened-cc1 -fstack-protector-strong -specs=/usr/lib/rpm/redhat/redhat-annobin-cc1  -m64 -march=x86-64-v2 -mtune=generic -fasynchronous-unwind-tables -fstack-clash-protection -fcf-protection  -c yajl/yajl.c -o yajl/yajl.o
gcc -I"/usr/include/R" -DNDEBUG -Iyajl/api  -I/usr/local/include   -fvisibility=hidden  -fpic  -O2 -flto=auto -ffat-lto-objects -fexceptions -g -grecord-gcc-switches -pipe -Wall -Werror=format-security -Wp,-D_FORTIFY_SOURCE=2 -Wp,-D_GLIBCXX_ASSERTIONS -specs=/usr/lib/rpm/redhat/redhat-hardened-cc1 -fstack-protector-strong -specs=/usr/lib/rpm/redhat/redhat-annobin-cc1  -m64 -march=x86-64-v2 -mtune=generic -fasynchronous-unwind-tables -fstack-clash-protection -fcf-protection  -c yajl/yajl_alloc.c -o yajl/yajl_alloc.o
gcc -I"/usr/include/R" -DNDEBUG -Iyajl/api  -I/usr/local/include   -fvisibility=hidden  -fpic  -O2 -flto=auto -ffat-lto-objects -fexceptions -g -grecord-gcc-switches -pipe -Wall -Werror=format-security -Wp,-D_FORTIFY_SOURCE=2 -Wp,-D_GLIBCXX_ASSERTIONS -specs=/usr/lib/rpm/redhat/redhat-hardened-cc1 -fstack-protector-strong -specs=/usr/lib/rpm/redhat/redhat-annobin-cc1  -m64 -march=x86-64-v2 -mtune=generic -fasynchronous-unwind-tables -fstack-clash-protection -fcf-protection  -c yajl/yajl_buf.c -o yajl/yajl_buf.o
gcc -I"/usr/include/R" -DNDEBUG -Iyajl/api  -I/usr/local/include   -fvisibility=hidden  -fpic  -O2 -flto=auto -ffat-lto-objects -fexceptions -g -grecord-gcc-switches -pipe -Wall -Werror=format-security -Wp,-D_FORTIFY_SOURCE=2 -Wp,-D_GLIBCXX_ASSERTIONS -specs=/usr/lib/rpm/redhat/redhat-hardened-cc1 -fstack-protector-strong -specs=/usr/lib/rpm/redhat/redhat-annobin-cc1  -m64 -march=x86-64-v2 -mtune=generic -fasynchronous-unwind-tables -fstack-clash-protection -fcf-protection  -c yajl/yajl_encode.c -o yajl/yajl_encode.o
gcc -I"/usr/include/R" -DNDEBUG -Iyajl/api  -I/usr/local/include   -fvisibility=hidden  -fpic  -O2 -flto=auto -ffat-lto-objects -fexceptions -g -grecord-gcc-switches -pipe -Wall -Werror=format-security -Wp,-D_FORTIFY_SOURCE=2 -Wp,-D_GLIBCXX_ASSERTIONS -specs=/usr/lib/rpm/redhat/redhat-hardened-cc1 -fstack-protector-strong -specs=/usr/lib/rpm/redhat/redhat-annobin-cc1  -m64 -march=x86-64-v2 -mtune=generic -fasynchronous-unwind-tables -fstack-clash-protection -fcf-protection  -c yajl/yajl_gen.c -o yajl/yajl_gen.o
gcc -I"/usr/include/R" -DNDEBUG -Iyajl/api  -I/usr/local/include   -fvisibility=hidden  -fpic  -O2 -flto=auto -ffat-lto-objects -fexceptions -g -grecord-gcc-switches -pipe -Wall -Werror=format-security -Wp,-D_FORTIFY_SOURCE=2 -Wp,-D_GLIBCXX_ASSERTIONS -specs=/usr/lib/rpm/redhat/redhat-hardened-cc1 -fstack-protector-strong -specs=/usr/lib/rpm/redhat/redhat-annobin-cc1  -m64 -march=x86-64-v2 -mtune=generic -fasynchronous-unwind-tables -fstack-clash-protection -fcf-protection  -c yajl/yajl_lex.c -o yajl/yajl_lex.o
gcc -I"/usr/include/R" -DNDEBUG -Iyajl/api  -I/usr/local/include   -fvisibility=hidden  -fpic  -O2 -flto=auto -ffat-lto-objects -fexceptions -g -grecord-gcc-switches -pipe -Wall -Werror=format-security -Wp,-D_FORTIFY_SOURCE=2 -Wp,-D_GLIBCXX_ASSERTIONS -specs=/usr/lib/rpm/redhat/redhat-hardened-cc1 -fstack-protector-strong -specs=/usr/lib/rpm/redhat/redhat-annobin-cc1  -m64 -march=x86-64-v2 -mtune=generic -fasynchronous-unwind-tables -fstack-clash-protection -fcf-protection  -c yajl/yajl_parser.c -o yajl/yajl_parser.o
gcc -I"/usr/include/R" -DNDEBUG -Iyajl/api  -I/usr/local/include   -fvisibility=hidden  -fpic  -O2 -flto=auto -ffat-lto-objects -fexceptions -g -grecord-gcc-switches -pipe -Wall -Werror=format-security -Wp,-D_FORTIFY_SOURCE=2 -Wp,-D_GLIBCXX_ASSERTIONS -specs=/usr/lib/rpm/redhat/redhat-hardened-cc1 -fstack-protector-strong -specs=/usr/lib/rpm/redhat/redhat-annobin-cc1  -m64 -march=x86-64-v2 -mtune=generic -fasynchronous-unwind-tables -fstack-clash-protection -fcf-protection  -c yajl/yajl_tree.c -o yajl/yajl_tree.o
ar rcs yajl/libstatyajl.a yajl/yajl.o yajl/yajl_alloc.o yajl/yajl_buf.o yajl/yajl_encode.o yajl/yajl_gen.o yajl/yajl_lex.o yajl/yajl_parser.o yajl/yajl_tree.o
gcc -shared -L/usr/lib64/R/lib -Wl,-z,relro -Wl,--as-needed -Wl,-z,now -specs=/usr/lib/rpm/redhat/redhat-hardened-ld -specs=/usr/lib/rpm/redhat/redhat-annobin-cc1 -o jsonlite.so base64.o collapse_array.o collapse_object.o collapse_pretty.o escape_chars.o integer64_to_na.o is_datelist.o is_recordlist.o is_scalarlist.o modp_numtoa.o null_to_na.o num_to_char.o parse.o prettify.o push_parser.o r-base64.o register.o row_collapse.o transpose_list.o validate.o -Lyajl -lstatyajl -L/usr/lib64/R/lib -lR
installing to /afs/cern.ch/user/l/lusiani/R/x86_64-redhat-linux-gnu-library/4.4/00LOCK-jsonlite/00new/jsonlite/libs
** R
** inst
** byte-compile and prepare package for lazy loading
in method for ‘asJSON’ with signature ‘"AsIs"’: no definition for class “AsIs”
in method for ‘asJSON’ with signature ‘"ITime"’: no definition for class “ITime”
in method for ‘asJSON’ with signature ‘"hms"’: no definition for class “hms”
in method for ‘asJSON’ with signature ‘"json"’: no definition for class “json”
in method for ‘asJSON’ with signature ‘"integer64"’: no definition for class “integer64”
in method for ‘asJSON’ with signature ‘"pairlist"’: no definition for class “pairlist”
in method for ‘asJSON’ with signature ‘"blob"’: no definition for class “blob”
in method for ‘asJSON’ with signature ‘"scalar"’: no definition for class “scalar”
in method for ‘asJSON’ with signature ‘"sf"’: no definition for class “sf”
in method for ‘asJSON’ with signature ‘"sfc"’: no definition for class “sfc”
in method for ‘asJSON’ with signature ‘"vctrs_vctr"’: no definition for class “vctrs_vctr”
** help
*** installing help indices
  converting help for package ‘jsonlite’
    finding HTML links ... done
    base64                                  html  
    flatten                                 html  
    fromJSON                                html  
    gzjson                                  html  
    prettify                                html  
    rbind_pages                             html  
    read_json                               html  
    serializeJSON                           html  
    stream_in                               html  
    unbox                                   html  
    validate                                html  
** building package indices
** installing vignettes
** testing if installed package can be loaded from temporary location
** checking absolute paths in shared objects and dynamic libraries
** testing if installed package can be loaded from final location
** testing if installed package keeps a record of temporary installation path
* DONE (jsonlite)

The downloaded source packages are in
        ‘/tmp/lusiani/Rtmp8BWQUc/downloaded_packages’
> 
```
