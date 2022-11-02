# Projeto Final - Modelos Preditivos Conexionistas

### Nome do aluno

|**Tipo de Projeto**|**Modelo Selecionado**|**Linguagem**|
|--|--|--|
|<br>Deteção de Objetos|YOLOv5|PyTorch|

## Performance

O modelo treinado possui performance de **70%**.

### Output do bloco de treinamento

<details>
  <summary>Click to expand!</summary>
  
  ```text
       Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
     0/2999      14.1G     0.1173    0.03538    0.04991        146        640: 100% 5/5 [00:07<00:00,  1.59s/it]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 1/1 [00:05<00:00,  5.18s/it]
                   all        101        217   0.000904      0.299   0.000978   0.000222

      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
     1/2999      12.6G     0.1107    0.03537    0.04789        151        640: 100% 5/5 [00:03<00:00,  1.46it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 1/1 [00:02<00:00,  2.40s/it]
                   all        101        217    0.00178      0.359     0.0022   0.000505

      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
     2/2999      12.6G     0.0986    0.03276    0.04598        137        640: 100% 5/5 [00:03<00:00,  1.36it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 1/1 [00:01<00:00,  1.73s/it]
                   all        101        217    0.00308      0.295     0.0029   0.000753

      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
     3/2999      12.6G    0.09014    0.03623    0.04285        142        640: 100% 5/5 [00:03<00:00,  1.43it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 1/1 [00:01<00:00,  1.59s/it]
                   all        101        217    0.00322      0.567    0.00977    0.00344

      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
     4/2999      12.6G    0.08309    0.03621    0.03929         84        640: 100% 5/5 [00:03<00:00,  1.44it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 1/1 [00:01<00:00,  1.52s/it]
                   all        101        217    0.00517      0.781     0.0167    0.00643

      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
     5/2999      12.6G    0.07347    0.03853    0.03575        130        640: 100% 5/5 [00:03<00:00,  1.47it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 1/1 [00:01<00:00,  1.52s/it]
                   all        101        217      0.274     0.0594     0.0496      0.014

      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
     6/2999      12.6G    0.06836     0.0408    0.03289        138        640: 100% 5/5 [00:03<00:00,  1.32it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 1/1 [00:02<00:00,  2.69s/it]
                   all        101        217      0.296       0.13     0.0366       0.01

      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
     7/2999      12.6G    0.06312    0.03665     0.0311        130        640: 100% 5/5 [00:03<00:00,  1.39it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 1/1 [00:01<00:00,  1.36s/it]
                   all        101        217      0.307       0.32     0.0747     0.0225

      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
     8/2999      12.6G    0.06181    0.03553     0.0287        153        640: 100% 5/5 [00:03<00:00,  1.39it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 1/1 [00:01<00:00,  1.50s/it]
                   all        101        217      0.357      0.382      0.124     0.0363

      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
     9/2999      12.6G     0.0592    0.03843    0.02486        131        640: 100% 5/5 [00:03<00:00,  1.42it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 1/1 [00:01<00:00,  1.55s/it]
                   all        101        217      0.387      0.268      0.162     0.0639

      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
    10/2999      12.6G    0.06042    0.03267    0.02352        117        640: 100% 5/5 [00:03<00:00,  1.39it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 1/1 [00:01<00:00,  1.35s/it]
                   all        101        217       0.45      0.309      0.208      0.092

      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
    11/2999      12.6G     0.0571    0.03127    0.02375        139        640: 100% 5/5 [00:03<00:00,  1.40it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 1/1 [00:01<00:00,  1.32s/it]
                   all        101        217      0.431      0.295      0.231     0.0833

      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
    12/2999      12.6G     0.0565    0.03269    0.02207        155        640: 100% 5/5 [00:03<00:00,  1.39it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 1/1 [00:01<00:00,  1.31s/it]
                   all        101        217      0.539      0.273      0.272       0.13

      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
    13/2999      12.6G    0.05693    0.03074    0.02129        136        640: 100% 5/5 [00:03<00:00,  1.39it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 1/1 [00:01<00:00,  1.32s/it]
                   all        101        217      0.463       0.23      0.182     0.0734

      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
    14/2999      12.6G    0.05538    0.02819    0.01743        104        640: 100% 5/5 [00:03<00:00,  1.36it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 1/1 [00:01<00:00,  1.28s/it]
                   all        101        217      0.216      0.468      0.252      0.109

      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
    15/2999      12.6G    0.05464    0.02627    0.01881        107        640: 100% 5/5 [00:03<00:00,  1.36it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 1/1 [00:01<00:00,  1.19s/it]
                   all        101        217      0.307      0.414      0.297      0.134

      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
    16/2999      12.6G    0.05493    0.02728    0.01762        115        640: 100% 5/5 [00:03<00:00,  1.34it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 1/1 [00:01<00:00,  1.15s/it]
                   all        101        217      0.366      0.412      0.332      0.144

      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
    17/2999      12.6G    0.05354    0.02681    0.01563        130        640: 100% 5/5 [00:03<00:00,  1.32it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 1/1 [00:01<00:00,  1.23s/it]
                   all        101        217      0.513      0.415      0.344      0.184

      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
    18/2999      12.6G    0.05356    0.02599    0.01425        115        640: 100% 5/5 [00:03<00:00,  1.30it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 1/1 [00:01<00:00,  1.17s/it]
                   all        101        217      0.462      0.379      0.345      0.163

      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
    19/2999      12.6G    0.05257    0.02764     0.0148         93        640: 100% 5/5 [00:03<00:00,  1.30it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 1/1 [00:01<00:00,  1.10s/it]
                   all        101        217      0.463      0.369      0.373      0.194

      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
    20/2999      12.6G    0.04991    0.02588    0.01544        109        640: 100% 5/5 [00:03<00:00,  1.30it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 1/1 [00:01<00:00,  1.17s/it]
                   all        101        217      0.588       0.37      0.438      0.202

      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
    21/2999      12.6G    0.05033    0.02631    0.01352        130        640: 100% 5/5 [00:03<00:00,  1.34it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 1/1 [00:01<00:00,  1.17s/it]
                   all        101        217      0.405      0.536      0.395      0.207

      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
    22/2999      12.6G    0.04706    0.02711    0.01346        135        640: 100% 5/5 [00:03<00:00,  1.34it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 1/1 [00:01<00:00,  1.20s/it]
                   all        101        217      0.521      0.454      0.393      0.191

      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
    23/2999      12.6G    0.04615    0.02459    0.01431        114        640: 100% 5/5 [00:03<00:00,  1.35it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 1/1 [00:01<00:00,  1.19s/it]
                   all        101        217      0.555      0.448      0.427      0.202

      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
    24/2999      12.6G    0.04781    0.02641     0.0119        122        640: 100% 5/5 [00:03<00:00,  1.35it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 1/1 [00:01<00:00,  1.22s/it]
                   all        101        217      0.608      0.395      0.455      0.216

      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
    25/2999      12.6G    0.04543    0.02333    0.01199        110        640: 100% 5/5 [00:03<00:00,  1.36it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 1/1 [00:01<00:00,  1.21s/it]
                   all        101        217      0.245      0.435      0.236      0.113

      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
    26/2999      12.6G     0.0444    0.02441    0.01193        126        640: 100% 5/5 [00:03<00:00,  1.37it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 1/1 [00:01<00:00,  1.18s/it]
                   all        101        217      0.561      0.317      0.371      0.197

      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
    27/2999      12.6G    0.04542    0.02688    0.01037        134        640: 100% 5/5 [00:03<00:00,  1.37it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 1/1 [00:01<00:00,  1.17s/it]
                   all        101        217      0.458      0.453        0.4      0.202

      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
    28/2999      12.6G    0.04376    0.02281    0.01514        101        640: 100% 5/5 [00:03<00:00,  1.37it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 1/1 [00:01<00:00,  1.23s/it]
                   all        101        217      0.438      0.256      0.266      0.133

      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
    29/2999      12.6G    0.04321    0.02655      0.012         98        640: 100% 5/5 [00:03<00:00,  1.34it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 1/1 [00:01<00:00,  1.07s/it]
                   all        101        217      0.655      0.408      0.473      0.251

      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
    30/2999      12.6G    0.04189    0.02375    0.01124        118        640: 100% 5/5 [00:03<00:00,  1.36it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 1/1 [00:01<00:00,  1.15s/it]
                   all        101        217      0.518      0.406      0.453      0.226

      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
    31/2999      12.6G    0.04182    0.02324    0.01185        130        640: 100% 5/5 [00:03<00:00,  1.36it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 1/1 [00:01<00:00,  1.10s/it]
                   all        101        217      0.498      0.367      0.352      0.182

      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
    32/2999      12.6G    0.04236    0.02531    0.01057        112        640: 100% 5/5 [00:03<00:00,  1.35it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 1/1 [00:01<00:00,  1.08s/it]
                   all        101        217      0.589      0.409      0.383        0.2

      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
    33/2999      12.6G    0.04123    0.02385   0.008931        115        640: 100% 5/5 [00:03<00:00,  1.32it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 1/1 [00:01<00:00,  1.12s/it]
                   all        101        217      0.471      0.509       0.39      0.223

      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
    34/2999      12.6G    0.03871    0.02561    0.01002        149        640: 100% 5/5 [00:03<00:00,  1.33it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 1/1 [00:01<00:00,  1.17s/it]
                   all        101        217       0.37      0.563        0.4      0.192

      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
    35/2999      12.6G    0.04165    0.02517   0.008299        146        640: 100% 5/5 [00:03<00:00,  1.32it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 1/1 [00:01<00:00,  1.18s/it]
                   all        101        217      0.613      0.531      0.489      0.298

      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
    36/2999      12.6G    0.04304    0.02223    0.01039        117        640: 100% 5/5 [00:03<00:00,  1.34it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 1/1 [00:01<00:00,  1.18s/it]
                   all        101        217      0.736      0.532      0.576      0.351

      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
    37/2999      12.6G    0.03984    0.02451    0.01059        138        640: 100% 5/5 [00:03<00:00,  1.32it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 1/1 [00:01<00:00,  1.10s/it]
                   all        101        217      0.653      0.553      0.565      0.279

      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
    38/2999      12.6G    0.03973    0.02258    0.01046        118        640: 100% 5/5 [00:03<00:00,  1.36it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 1/1 [00:01<00:00,  1.20s/it]
                   all        101        217      0.656      0.388      0.497      0.276

      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
    39/2999      12.6G    0.03871    0.02345   0.009865        133        640: 100% 5/5 [00:03<00:00,  1.35it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 1/1 [00:01<00:00,  1.21s/it]
                   all        101        217      0.591      0.487      0.519      0.282

      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
    40/2999      12.6G    0.03778    0.02415    0.01111        148        640: 100% 5/5 [00:03<00:00,  1.35it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 1/1 [00:01<00:00,  1.25s/it]
                   all        101        217      0.564      0.478      0.474      0.267

      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
    41/2999      12.6G    0.03836    0.02202    0.01001         96        640: 100% 5/5 [00:03<00:00,  1.35it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 1/1 [00:01<00:00,  1.16s/it]
                   all        101        217      0.502      0.419      0.384      0.231

      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
    42/2999      12.6G    0.03788    0.02417   0.007875        154        640: 100% 5/5 [00:03<00:00,  1.35it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 1/1 [00:01<00:00,  1.23s/it]
                   all        101        217       0.48      0.515      0.472      0.261

      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
    43/2999      12.6G    0.03756     0.0231    0.01048        121        640: 100% 5/5 [00:03<00:00,  1.33it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 1/1 [00:01<00:00,  1.11s/it]
                   all        101        217      0.578      0.446       0.46      0.225

      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
    44/2999      12.6G     0.0384    0.02428   0.008912        119        640: 100% 5/5 [00:03<00:00,  1.34it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 1/1 [00:01<00:00,  1.09s/it]
                   all        101        217       0.36       0.58      0.414      0.233

      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
    45/2999      12.6G    0.03747     0.0231   0.009518        113        640: 100% 5/5 [00:03<00:00,  1.35it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 1/1 [00:01<00:00,  1.18s/it]
                   all        101        217      0.567      0.583      0.546      0.275

      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
    46/2999      12.6G    0.03752    0.02379   0.008244        138        640: 100% 5/5 [00:03<00:00,  1.33it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 1/1 [00:01<00:00,  1.12s/it]
                   all        101        217      0.493      0.523      0.483      0.281

      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
    47/2999      12.6G    0.03675    0.02191    0.01076        115        640: 100% 5/5 [00:03<00:00,  1.37it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 1/1 [00:01<00:00,  1.19s/it]
                   all        101        217       0.71      0.486      0.512        0.3

      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
    48/2999      12.6G    0.03702    0.02138   0.009663        104        640: 100% 5/5 [00:03<00:00,  1.33it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 1/1 [00:01<00:00,  1.13s/it]
                   all        101        217      0.646      0.436       0.49      0.296

      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
    49/2999      12.6G    0.03542    0.02213   0.009218        119        640: 100% 5/5 [00:03<00:00,  1.36it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 1/1 [00:01<00:00,  1.14s/it]
                   all        101        217      0.577      0.483      0.503      0.284

      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
    50/2999      12.6G    0.03599     0.0225   0.007987        150        640: 100% 5/5 [00:03<00:00,  1.34it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 1/1 [00:01<00:00,  1.10s/it]
                   all        101        217      0.623      0.381       0.48      0.241

      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
    51/2999      12.6G    0.03659    0.02214   0.008107        150        640: 100% 5/5 [00:03<00:00,  1.34it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 1/1 [00:01<00:00,  1.18s/it]
                   all        101        217      0.671      0.469       0.55      0.281

      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
    52/2999      12.6G      0.037     0.0218   0.007579        105        640: 100% 5/5 [00:03<00:00,  1.34it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 1/1 [00:01<00:00,  1.13s/it]
                   all        101        217      0.582      0.458      0.549       0.31

      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
    53/2999      12.6G    0.03572    0.02192   0.008207        116        640: 100% 5/5 [00:03<00:00,  1.27it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 1/1 [00:02<00:00,  2.14s/it]
                   all        101        217       0.69      0.538      0.587      0.321

      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
    54/2999      12.6G    0.03667    0.02177   0.008162         97        640: 100% 5/5 [00:03<00:00,  1.33it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 1/1 [00:01<00:00,  1.11s/it]
                   all        101        217      0.649      0.523      0.512       0.27

      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
    55/2999      12.6G    0.03917    0.02293    0.00866        131        640: 100% 5/5 [00:03<00:00,  1.35it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 1/1 [00:01<00:00,  1.22s/it]
                   all        101        217      0.668      0.473      0.481      0.277

      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
    56/2999      12.6G    0.03601    0.02153   0.008187        139        640: 100% 5/5 [00:03<00:00,  1.35it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 1/1 [00:01<00:00,  1.10s/it]
                   all        101        217      0.405      0.508      0.467      0.258

      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
    57/2999      12.6G    0.03522    0.02328   0.006686        108        640: 100% 5/5 [00:03<00:00,  1.36it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 1/1 [00:01<00:00,  1.18s/it]
                   all        101        217      0.698      0.382      0.505      0.315

      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
    58/2999      12.6G    0.03415    0.02177   0.008117        128        640: 100% 5/5 [00:03<00:00,  1.35it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 1/1 [00:01<00:00,  1.14s/it]
                   all        101        217      0.675      0.554      0.571      0.347

      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
    59/2999      12.6G    0.03442    0.02189   0.008052        139        640: 100% 5/5 [00:03<00:00,  1.36it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 1/1 [00:01<00:00,  1.05s/it]
                   all        101        217      0.708      0.399      0.505      0.285

      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
    60/2999      12.6G    0.03524    0.02083   0.007536        106        640: 100% 5/5 [00:03<00:00,  1.36it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 1/1 [00:01<00:00,  1.17s/it]
                   all        101        217      0.506      0.514      0.515      0.284

      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
    61/2999      12.6G    0.03481    0.02069   0.009796        106        640: 100% 5/5 [00:03<00:00,  1.36it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 1/1 [00:01<00:00,  1.12s/it]
                   all        101        217      0.774      0.448      0.584      0.343

      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
    62/2999      12.6G    0.03395     0.0223     0.0102        126        640: 100% 5/5 [00:03<00:00,  1.33it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 1/1 [00:01<00:00,  1.09s/it]
                   all        101        217      0.721      0.568       0.63       0.37

      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
    63/2999      12.6G    0.03498    0.02071   0.008237        147        640: 100% 5/5 [00:03<00:00,  1.34it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 1/1 [00:01<00:00,  1.10s/it]
                   all        101        217      0.596      0.611       0.63      0.374

      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
    64/2999      12.6G    0.03411    0.02055    0.00705        112        640: 100% 5/5 [00:03<00:00,  1.34it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 1/1 [00:01<00:00,  1.23s/it]
                   all        101        217       0.71      0.554       0.63      0.336

      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
    65/2999      12.6G     0.0331    0.02054    0.00778        115        640: 100% 5/5 [00:03<00:00,  1.35it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 1/1 [00:01<00:00,  1.12s/it]
                   all        101        217      0.652      0.564      0.614      0.353

      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
    66/2999      12.6G    0.03522     0.0219   0.006864        161        640: 100% 5/5 [00:03<00:00,  1.35it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 1/1 [00:01<00:00,  1.13s/it]
                   all        101        217      0.682      0.606      0.605      0.355

      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
    67/2999      12.6G    0.03444    0.02138   0.008082        154        640: 100% 5/5 [00:03<00:00,  1.35it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 1/1 [00:01<00:00,  1.14s/it]
                   all        101        217      0.706      0.422      0.472      0.263

      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
    68/2999      12.6G    0.03399    0.01971   0.006412        101        640: 100% 5/5 [00:03<00:00,  1.36it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 1/1 [00:01<00:00,  1.17s/it]
                   all        101        217      0.652      0.476       0.49      0.291

      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
    69/2999      12.6G    0.03343    0.02186   0.008576        137        640: 100% 5/5 [00:03<00:00,  1.35it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 1/1 [00:01<00:00,  1.12s/it]
                   all        101        217      0.432      0.529      0.453      0.256

      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
    70/2999      12.6G    0.03453    0.02106   0.008258        152        640: 100% 5/5 [00:03<00:00,  1.34it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 1/1 [00:01<00:00,  1.14s/it]
                   all        101        217      0.569      0.471      0.468      0.262

      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
    71/2999      12.6G    0.03361    0.02103   0.009571        109        640: 100% 5/5 [00:03<00:00,  1.35it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 1/1 [00:01<00:00,  1.19s/it]
                   all        101        217      0.488      0.546      0.497      0.293

      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
    72/2999      12.6G    0.03257    0.01983   0.007513        125        640: 100% 5/5 [00:03<00:00,  1.33it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 1/1 [00:01<00:00,  1.16s/it]
                   all        101        217      0.582      0.439      0.473      0.264

      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
    73/2999      12.6G    0.03402    0.02179    0.00849        176        640: 100% 5/5 [00:03<00:00,  1.35it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 1/1 [00:01<00:00,  1.23s/it]
                   all        101        217      0.644      0.506      0.594      0.337

      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
    74/2999      12.6G    0.03332    0.01994   0.007155        136        640: 100% 5/5 [00:03<00:00,  1.32it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 1/1 [00:01<00:00,  1.14s/it]
                   all        101        217      0.549       0.54       0.51      0.309

      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
    75/2999      12.6G    0.03208    0.02047   0.008331        118        640: 100% 5/5 [00:03<00:00,  1.32it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 1/1 [00:01<00:00,  1.08s/it]
                   all        101        217      0.659      0.486      0.552      0.331

      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
    76/2999      12.6G    0.03305    0.02145   0.006415        117        640: 100% 5/5 [00:03<00:00,  1.34it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 1/1 [00:01<00:00,  1.13s/it]
                   all        101        217      0.635      0.542      0.556      0.336

      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
    77/2999      12.6G    0.03135    0.01918   0.006946        134        640: 100% 5/5 [00:03<00:00,  1.34it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 1/1 [00:01<00:00,  1.13s/it]
                   all        101        217      0.705      0.552      0.569      0.325

      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
    78/2999      12.6G    0.03136    0.02132   0.007827        139        640: 100% 5/5 [00:03<00:00,  1.36it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 1/1 [00:01<00:00,  1.18s/it]
                   all        101        217       0.62      0.527       0.52      0.314

      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
    79/2999      12.6G    0.03081    0.02033   0.007186        104        640: 100% 5/5 [00:03<00:00,  1.35it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 1/1 [00:01<00:00,  1.14s/it]
                   all        101        217      0.633      0.521       0.52      0.304

      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
    80/2999      12.6G    0.03099    0.01932   0.008722        132        640: 100% 5/5 [00:03<00:00,  1.33it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 1/1 [00:01<00:00,  1.11s/it]
                   all        101        217      0.667      0.516       0.55      0.319

      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
    81/2999      12.6G    0.03207    0.01799   0.009094        104        640: 100% 5/5 [00:03<00:00,  1.36it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 1/1 [00:01<00:00,  1.17s/it]
                   all        101        217      0.603      0.541       0.55      0.276

      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
    82/2999      12.6G    0.03242    0.02027   0.006197        123        640: 100% 5/5 [00:03<00:00,  1.33it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 1/1 [00:01<00:00,  1.15s/it]
                   all        101        217      0.658      0.595        0.6      0.342

      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
    83/2999      12.6G    0.03093    0.01923   0.008702        101        640: 100% 5/5 [00:03<00:00,  1.32it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 1/1 [00:01<00:00,  1.12s/it]
                   all        101        217      0.621      0.556      0.569      0.348

      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
    84/2999      12.6G      0.032    0.02128   0.006336        115        640: 100% 5/5 [00:03<00:00,  1.35it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 1/1 [00:01<00:00,  1.14s/it]
                   all        101        217      0.669      0.443      0.488      0.308

      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
    85/2999      12.6G    0.03171    0.01906   0.005897         93        640: 100% 5/5 [00:03<00:00,  1.34it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 1/1 [00:01<00:00,  1.07s/it]
                   all        101        217      0.457      0.418      0.382      0.233

      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
    86/2999      12.6G    0.03222    0.02016   0.008253        119        640: 100% 5/5 [00:03<00:00,  1.33it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 1/1 [00:01<00:00,  1.10s/it]
                   all        101        217      0.692      0.519      0.505      0.305

      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
    87/2999      12.6G    0.03168    0.01913   0.007368        138        640: 100% 5/5 [00:03<00:00,  1.35it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 1/1 [00:01<00:00,  1.11s/it]
                   all        101        217      0.648      0.536      0.573      0.346

      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
    88/2999      12.6G     0.0312    0.02057   0.006037        145        640: 100% 5/5 [00:03<00:00,  1.33it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 1/1 [00:01<00:00,  1.17s/it]
                   all        101        217      0.579      0.478       0.46      0.266

      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
    89/2999      12.6G    0.02999    0.02118   0.006405        133        640: 100% 5/5 [00:03<00:00,  1.35it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 1/1 [00:01<00:00,  1.12s/it]
                   all        101        217      0.615      0.408      0.489      0.294

      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
    90/2999      12.6G    0.03152     0.0194   0.005863        149        640: 100% 5/5 [00:03<00:00,  1.34it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 1/1 [00:01<00:00,  1.15s/it]
                   all        101        217      0.759      0.389      0.514      0.294

      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
    91/2999      12.6G    0.03208    0.01994   0.006671        138        640: 100% 5/5 [00:03<00:00,  1.34it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 1/1 [00:01<00:00,  1.16s/it]
                   all        101        217      0.672       0.55      0.554      0.328

      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
    92/2999      12.6G    0.03006    0.01895   0.006584        131        640: 100% 5/5 [00:03<00:00,  1.35it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 1/1 [00:01<00:00,  1.11s/it]
                   all        101        217      0.751      0.446      0.518       0.28

      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
    93/2999      12.6G    0.02952    0.01901   0.006476        110        640: 100% 5/5 [00:03<00:00,  1.33it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 1/1 [00:01<00:00,  1.12s/it]
                   all        101        217      0.671      0.554      0.542      0.306

      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
    94/2999      12.6G    0.02979    0.01976   0.007515        129        640: 100% 5/5 [00:03<00:00,  1.36it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 1/1 [00:01<00:00,  1.20s/it]
                   all        101        217      0.584      0.451      0.448      0.258

      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
    95/2999      12.6G    0.02955    0.01941   0.007143        120        640: 100% 5/5 [00:03<00:00,  1.34it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 1/1 [00:01<00:00,  1.15s/it]
                   all        101        217      0.637      0.504      0.531       0.32

      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
    96/2999      12.6G    0.03057    0.02047   0.007105        120        640: 100% 5/5 [00:03<00:00,  1.36it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 1/1 [00:01<00:00,  1.14s/it]
                   all        101        217      0.681       0.49      0.557      0.325

      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
    97/2999      12.6G    0.03018    0.01928   0.005788        163        640: 100% 5/5 [00:03<00:00,  1.34it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 1/1 [00:01<00:00,  1.11s/it]
                   all        101        217      0.571      0.548      0.528      0.285

      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
    98/2999      12.6G    0.02923    0.02036   0.007478        146        640: 100% 5/5 [00:03<00:00,  1.36it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 1/1 [00:01<00:00,  1.24s/it]
                   all        101        217      0.654       0.56      0.577      0.323

      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
    99/2999      12.6G    0.02952    0.01759   0.008067        113        640: 100% 5/5 [00:03<00:00,  1.35it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 1/1 [00:01<00:00,  1.14s/it]
                   all        101        217      0.703      0.528      0.595      0.358

      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
   100/2999      12.6G    0.02943      0.019   0.007872        130        640: 100% 5/5 [00:03<00:00,  1.33it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 1/1 [00:01<00:00,  1.17s/it]
                   all        101        217      0.713       0.52      0.595      0.344

      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
   101/2999      12.6G    0.02955    0.01913   0.005352        127        640: 100% 5/5 [00:03<00:00,  1.33it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 1/1 [00:01<00:00,  1.77s/it]
                   all        101        217      0.649      0.598      0.652       0.39

      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
   102/2999      12.6G     0.0308    0.01902   0.007234        126        640: 100% 5/5 [00:03<00:00,  1.26it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 1/1 [00:01<00:00,  1.25s/it]
                   all        101        217      0.734      0.492      0.582      0.345

      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
   103/2999      12.6G    0.03036    0.01904   0.005845        135        640: 100% 5/5 [00:03<00:00,  1.33it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 1/1 [00:01<00:00,  1.12s/it]
                   all        101        217      0.684      0.517      0.599      0.374

      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
   104/2999      12.6G    0.02944    0.01841     0.0072        120        640: 100% 5/5 [00:03<00:00,  1.34it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 1/1 [00:01<00:00,  1.13s/it]
                   all        101        217      0.597      0.549      0.534      0.309

      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
   105/2999      12.6G    0.02912    0.01955   0.008463        147        640: 100% 5/5 [00:03<00:00,  1.34it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 1/1 [00:01<00:00,  1.13s/it]
                   all        101        217      0.537      0.536      0.508      0.303

      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
   106/2999      12.6G    0.02903    0.01973   0.007375        130        640: 100% 5/5 [00:03<00:00,  1.36it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 1/1 [00:01<00:00,  1.11s/it]
                   all        101        217      0.684      0.522      0.576      0.328

      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
   107/2999      12.6G     0.0295    0.01761   0.004583        121        640: 100% 5/5 [00:03<00:00,  1.35it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 1/1 [00:01<00:00,  1.15s/it]
                   all        101        217      0.705       0.53      0.558      0.303

      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
   108/2999      12.6G    0.02968    0.01941   0.005742        149        640: 100% 5/5 [00:03<00:00,  1.35it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 1/1 [00:01<00:00,  1.19s/it]
                   all        101        217      0.657      0.563       0.56      0.314

      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
   109/2999      12.6G    0.02832    0.01824      0.007        149        640: 100% 5/5 [00:03<00:00,  1.34it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 1/1 [00:01<00:00,  1.15s/it]
                   all        101        217      0.669      0.547      0.557      0.303

      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
   110/2999      12.6G     0.0293    0.01949   0.005142        137        640: 100% 5/5 [00:03<00:00,  1.34it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 1/1 [00:01<00:00,  1.10s/it]
                   all        101        217      0.751      0.558      0.608      0.364

      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
   111/2999      12.6G    0.02885    0.01768   0.006173        106        640: 100% 5/5 [00:03<00:00,  1.35it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 1/1 [00:01<00:00,  1.13s/it]
                   all        101        217      0.719       0.57      0.641      0.367

      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
   112/2999      12.6G    0.02904    0.01702   0.004868         99        640: 100% 5/5 [00:03<00:00,  1.35it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 1/1 [00:01<00:00,  1.13s/it]
                   all        101        217      0.686      0.624      0.667      0.352

      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
   113/2999      12.6G     0.0315    0.01935    0.00713        126        640: 100% 5/5 [00:03<00:00,  1.35it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 1/1 [00:01<00:00,  1.19s/it]
                   all        101        217      0.703      0.654      0.691      0.411

      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
   114/2999      12.6G    0.02941    0.01801   0.007847        136        640: 100% 5/5 [00:03<00:00,  1.35it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 1/1 [00:01<00:00,  1.22s/it]
                   all        101        217      0.618      0.562      0.586      0.346

      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
   115/2999      12.6G      0.029    0.02006    0.00572        150        640: 100% 5/5 [00:03<00:00,  1.36it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 1/1 [00:01<00:00,  1.13s/it]
                   all        101        217      0.637      0.497      0.534      0.332

      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
   116/2999      12.6G    0.02941    0.01791   0.006359        133        640: 100% 5/5 [00:03<00:00,  1.36it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 1/1 [00:01<00:00,  1.28s/it]
                   all        101        217      0.612      0.471      0.543      0.337

      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
   117/2999      12.6G    0.02805    0.02012   0.006898        133        640: 100% 5/5 [00:03<00:00,  1.34it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 1/1 [00:01<00:00,  1.12s/it]
                   all        101        217      0.523      0.494      0.533      0.322

      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
   118/2999      12.6G    0.02808    0.01769   0.006582        133        640: 100% 5/5 [00:03<00:00,  1.34it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 1/1 [00:01<00:00,  1.14s/it]
                   all        101        217      0.731       0.51      0.549      0.344

      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
   119/2999      12.6G    0.03072    0.01838   0.006894         99        640: 100% 5/5 [00:03<00:00,  1.32it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 1/1 [00:01<00:00,  1.13s/it]
                   all        101        217      0.615      0.548      0.602      0.334

      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
   120/2999      12.6G    0.02917    0.01822   0.005342        120        640: 100% 5/5 [00:03<00:00,  1.33it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 1/1 [00:01<00:00,  1.13s/it]
                   all        101        217      0.808      0.529      0.688      0.405

      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
   121/2999      12.6G    0.02955    0.01967   0.005699        165        640: 100% 5/5 [00:03<00:00,  1.36it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 1/1 [00:01<00:00,  1.13s/it]
                   all        101        217      0.705       0.64      0.707      0.413

      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
   122/2999      12.6G    0.02877    0.01647   0.005442        114        640: 100% 5/5 [00:03<00:00,  1.35it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 1/1 [00:01<00:00,  1.12s/it]
                   all        101        217      0.693      0.619      0.671      0.405

      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
   123/2999      12.6G    0.02817    0.01902   0.006982        109        640: 100% 5/5 [00:03<00:00,  1.33it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 1/1 [00:01<00:00,  1.10s/it]
                   all        101        217       0.67      0.641       0.67      0.389

      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
   124/2999      12.6G    0.02884    0.01767   0.006129        106        640: 100% 5/5 [00:03<00:00,  1.36it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 1/1 [00:01<00:00,  1.13s/it]
                   all        101        217      0.694      0.574      0.661      0.389

      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
   125/2999      12.6G    0.02751    0.01884   0.005193        146        640: 100% 5/5 [00:03<00:00,  1.34it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 1/1 [00:01<00:00,  1.07s/it]
                   all        101        217      0.691      0.588      0.654      0.389

      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
   126/2999      12.6G    0.02718    0.01732   0.007455        118        640: 100% 5/5 [00:03<00:00,  1.33it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 1/1 [00:01<00:00,  1.15s/it]
                   all        101        217      0.643      0.487      0.575       0.34

      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
   127/2999      12.6G    0.02849    0.01794   0.006428        126        640: 100% 5/5 [00:03<00:00,  1.34it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 1/1 [00:01<00:00,  1.12s/it]
                   all        101        217      0.706      0.436      0.501       0.29

      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
   128/2999      12.6G    0.02666      0.017   0.007559        116        640: 100% 5/5 [00:03<00:00,  1.34it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 1/1 [00:01<00:00,  1.14s/it]
                   all        101        217      0.638      0.451      0.499      0.262

      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
   129/2999      12.6G    0.02633    0.01831   0.005878        111        640: 100% 5/5 [00:03<00:00,  1.35it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 1/1 [00:01<00:00,  1.09s/it]
                   all        101        217       0.67      0.439      0.478      0.267

      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
   130/2999      12.6G    0.02806    0.01719   0.006374        128        640: 100% 5/5 [00:03<00:00,  1.34it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 1/1 [00:01<00:00,  1.12s/it]
                   all        101        217      0.701      0.516       0.55      0.322

      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
   131/2999      12.6G    0.02709    0.01817   0.006348        145        640: 100% 5/5 [00:03<00:00,  1.37it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 1/1 [00:01<00:00,  1.18s/it]
                   all        101        217      0.652      0.648      0.658      0.386

      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
   132/2999      12.6G    0.02608    0.01797   0.004802        171        640: 100% 5/5 [00:03<00:00,  1.33it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 1/1 [00:01<00:00,  1.11s/it]
                   all        101        217       0.66      0.586       0.61      0.364

      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
   133/2999      12.6G    0.02621    0.01734   0.007591        112        640: 100% 5/5 [00:03<00:00,  1.34it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 1/1 [00:01<00:00,  1.14s/it]
                   all        101        217      0.777      0.601      0.663      0.404

      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
   134/2999      12.6G    0.02838    0.01758   0.005685        119        640: 100% 5/5 [00:03<00:00,  1.35it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 1/1 [00:01<00:00,  1.08s/it]
                   all        101        217      0.741      0.657      0.693      0.406

      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
   135/2999      12.6G    0.02747    0.01536   0.006742         94        640: 100% 5/5 [00:03<00:00,  1.33it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 1/1 [00:01<00:00,  1.13s/it]
                   all        101        217      0.698       0.63      0.652      0.374

      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
   136/2999      12.6G    0.02812    0.01855   0.005367        161        640: 100% 5/5 [00:03<00:00,  1.35it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 1/1 [00:01<00:00,  1.12s/it]
                   all        101        217      0.775      0.527      0.634      0.363

      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
   137/2999      12.6G    0.02688    0.01761   0.006394        120        640: 100% 5/5 [00:03<00:00,  1.36it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 1/1 [00:01<00:00,  1.08s/it]
                   all        101        217      0.713      0.551      0.568      0.351

      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
   138/2999      12.6G    0.02647    0.01831   0.004582        126        640: 100% 5/5 [00:03<00:00,  1.33it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 1/1 [00:01<00:00,  1.06s/it]
                   all        101        217       0.72      0.525      0.547      0.341

      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
   139/2999      12.6G    0.02838      0.017   0.004589        129        640: 100% 5/5 [00:03<00:00,  1.33it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 1/1 [00:01<00:00,  1.14s/it]
                   all        101        217      0.706      0.559      0.602      0.377

      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
   140/2999      12.6G    0.02636    0.01678   0.005142        115        640: 100% 5/5 [00:03<00:00,  1.36it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 1/1 [00:01<00:00,  1.23s/it]
                   all        101        217      0.688      0.551      0.602      0.357

      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
   141/2999      12.6G    0.02707    0.01875   0.006562        119        640: 100% 5/5 [00:03<00:00,  1.31it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 1/1 [00:01<00:00,  1.23s/it]
                   all        101        217      0.587      0.383       0.49      0.272

      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
   142/2999      12.6G    0.02652    0.01891    0.00586        135        640: 100% 5/5 [00:03<00:00,  1.33it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 1/1 [00:01<00:00,  1.17s/it]
                   all        101        217      0.565       0.61      0.546      0.327

      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
   143/2999      12.6G    0.02696     0.0175   0.004963        137        640: 100% 5/5 [00:03<00:00,  1.33it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 1/1 [00:01<00:00,  1.15s/it]
                   all        101        217      0.624      0.642      0.643      0.371

      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
   144/2999      12.6G    0.02632    0.01703   0.005233        152        640: 100% 5/5 [00:03<00:00,  1.33it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 1/1 [00:01<00:00,  1.19s/it]
                   all        101        217      0.724      0.643      0.637      0.378

      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
   145/2999      12.6G    0.02716    0.01763   0.005126        118        640: 100% 5/5 [00:03<00:00,  1.35it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 1/1 [00:01<00:00,  1.22s/it]
                   all        101        217      0.743      0.531      0.588      0.352

      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
   146/2999      12.6G     0.0279    0.01737   0.005935        128        640: 100% 5/5 [00:03<00:00,  1.35it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 1/1 [00:01<00:00,  1.21s/it]
                   all        101        217       0.79      0.491      0.585      0.343

      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
   147/2999      12.6G    0.02708    0.01756   0.005438        100        640: 100% 5/5 [00:03<00:00,  1.32it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 1/1 [00:01<00:00,  1.13s/it]
                   all        101        217      0.663       0.55      0.565      0.343

      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
   148/2999      12.6G    0.02541    0.01861    0.00459        170        640: 100% 5/5 [00:03<00:00,  1.35it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 1/1 [00:01<00:00,  1.15s/it]
                   all        101        217      0.667      0.567      0.625      0.368

      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
   149/2999      12.6G    0.02702     0.0175   0.005758        121        640: 100% 5/5 [00:03<00:00,  1.32it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 1/1 [00:02<00:00,  2.11s/it]
                   all        101        217      0.761      0.533      0.611      0.367

      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
   150/2999      12.6G    0.02653    0.01796   0.004189        126        640: 100% 5/5 [00:03<00:00,  1.29it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 1/1 [00:01<00:00,  1.34s/it]
                   all        101        217      0.832      0.497        0.6      0.364

      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
   151/2999      12.6G    0.02652    0.01628   0.005387        107        640: 100% 5/5 [00:03<00:00,  1.35it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 1/1 [00:01<00:00,  1.11s/it]
                   all        101        217      0.789      0.524      0.585      0.361

      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
   152/2999      12.6G    0.02563    0.01804     0.0058        105        640: 100% 5/5 [00:03<00:00,  1.36it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 1/1 [00:01<00:00,  1.20s/it]
                   all        101        217      0.787      0.512      0.593      0.365

      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
   153/2999      12.6G    0.02708    0.01716   0.006619        110        640: 100% 5/5 [00:03<00:00,  1.36it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 1/1 [00:01<00:00,  1.21s/it]
                   all        101        217      0.715      0.558      0.647      0.386

      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
   154/2999      12.6G    0.02612    0.01685   0.005833        153        640: 100% 5/5 [00:03<00:00,  1.34it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 1/1 [00:01<00:00,  1.22s/it]
                   all        101        217      0.636      0.532      0.571      0.345

      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
   155/2999      12.6G    0.02648    0.01731   0.004956        125        640: 100% 5/5 [00:03<00:00,  1.35it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 1/1 [00:01<00:00,  1.26s/it]
                   all        101        217      0.722      0.524      0.626      0.359

      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
   156/2999      12.6G    0.02607      0.019   0.004416        137        640: 100% 5/5 [00:03<00:00,  1.35it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 1/1 [00:01<00:00,  1.08s/it]
                   all        101        217      0.646      0.643      0.618      0.365

      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
   157/2999      12.6G    0.02555    0.01679   0.004993        160        640: 100% 5/5 [00:03<00:00,  1.32it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 1/1 [00:01<00:00,  1.12s/it]
                   all        101        217      0.655      0.688      0.682      0.397

      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
   158/2999      12.6G    0.02648    0.01695   0.005976        138        640: 100% 5/5 [00:03<00:00,  1.36it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 1/1 [00:01<00:00,  1.17s/it]
                   all        101        217      0.647       0.53      0.588      0.367

      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
   159/2999      12.6G    0.02533    0.01722   0.005507        136        640: 100% 5/5 [00:03<00:00,  1.37it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 1/1 [00:01<00:00,  1.21s/it]
                   all        101        217      0.702      0.607      0.648        0.4

      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
   160/2999      12.6G     0.0255    0.01784   0.004882        119        640: 100% 5/5 [00:03<00:00,  1.34it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 1/1 [00:01<00:00,  1.12s/it]
                   all        101        217      0.714      0.507      0.563      0.356

      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
   161/2999      12.6G    0.02586    0.01605   0.004613        131        640: 100% 5/5 [00:03<00:00,  1.34it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 1/1 [00:01<00:00,  1.14s/it]
                   all        101        217      0.722      0.467      0.547      0.314

      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
   162/2999      12.6G    0.02449    0.01711   0.005729        170        640: 100% 5/5 [00:03<00:00,  1.33it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 1/1 [00:01<00:00,  1.05s/it]
                   all        101        217      0.606      0.563      0.611      0.344

      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
   163/2999      12.6G    0.02456     0.0161   0.005197        128        640: 100% 5/5 [00:03<00:00,  1.34it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 1/1 [00:01<00:00,  1.14s/it]
                   all        101        217      0.741      0.521      0.621      0.366

      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
   164/2999      12.6G    0.02547    0.01678   0.006509        130        640: 100% 5/5 [00:03<00:00,  1.29it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 1/1 [00:01<00:00,  1.10s/it]
                   all        101        217      0.753      0.526      0.603       0.35

      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
   165/2999      12.6G    0.02648    0.01659   0.005238        115        640: 100% 5/5 [00:03<00:00,  1.36it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 1/1 [00:01<00:00,  1.14s/it]
                   all        101        217      0.725      0.485      0.592      0.344

      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
   166/2999      12.6G    0.02628    0.01789   0.005596        152        640: 100% 5/5 [00:03<00:00,  1.32it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 1/1 [00:01<00:00,  1.15s/it]
                   all        101        217      0.827        0.5      0.649      0.386

      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
   167/2999      12.6G    0.02597    0.01874   0.006031        109        640: 100% 5/5 [00:03<00:00,  1.33it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 1/1 [00:01<00:00,  1.15s/it]
                   all        101        217      0.783      0.528      0.658      0.396

      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
   168/2999      12.6G    0.02517    0.01708   0.006468        120        640: 100% 5/5 [00:03<00:00,  1.36it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 1/1 [00:01<00:00,  1.14s/it]
                   all        101        217      0.623       0.68       0.63      0.367

      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
   169/2999      12.6G    0.02529    0.01675    0.00591        124        640: 100% 5/5 [00:03<00:00,  1.35it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 1/1 [00:01<00:00,  1.17s/it]
                   all        101        217      0.711      0.504        0.6      0.353

      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
   170/2999      12.6G    0.02516    0.01621   0.005552        134        640: 100% 5/5 [00:03<00:00,  1.35it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 1/1 [00:01<00:00,  1.09s/it]
                   all        101        217      0.794      0.514      0.618      0.363

      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
   171/2999      12.6G    0.02552    0.01681   0.006972        133        640: 100% 5/5 [00:03<00:00,  1.35it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 1/1 [00:01<00:00,  1.15s/it]
                   all        101        217      0.737        0.5      0.592      0.341

      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
   172/2999      12.6G    0.02552    0.01655   0.006197        120        640: 100% 5/5 [00:03<00:00,  1.35it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 1/1 [00:01<00:00,  1.13s/it]
                   all        101        217      0.787      0.477      0.611      0.339

      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
   173/2999      12.6G    0.02414    0.01747   0.005449        128        640: 100% 5/5 [00:03<00:00,  1.35it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 1/1 [00:01<00:00,  1.19s/it]
                   all        101        217      0.749      0.558      0.627      0.372

      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
   174/2999      12.6G    0.02453    0.01637   0.005591        118        640: 100% 5/5 [00:03<00:00,  1.35it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 1/1 [00:01<00:00,  1.14s/it]
                   all        101        217      0.671      0.598      0.656      0.382

      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
   175/2999      12.6G    0.02642    0.01786   0.005418        154        640: 100% 5/5 [00:03<00:00,  1.33it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 1/1 [00:01<00:00,  1.24s/it]
                   all        101        217      0.556      0.677       0.64      0.387

      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
   176/2999      12.6G    0.02403    0.01725   0.005673        127        640: 100% 5/5 [00:03<00:00,  1.34it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 1/1 [00:01<00:00,  1.21s/it]
                   all        101        217      0.538      0.634      0.637      0.358

      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
   177/2999      12.6G    0.02475    0.01824   0.004048        178        640: 100% 5/5 [00:03<00:00,  1.34it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 1/1 [00:01<00:00,  1.20s/it]
                   all        101        217      0.686      0.552      0.631      0.371

      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
   178/2999      12.6G    0.02518    0.01629   0.005174        146        640: 100% 5/5 [00:03<00:00,  1.35it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 1/1 [00:01<00:00,  1.09s/it]
                   all        101        217      0.614      0.605      0.609      0.338

      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
   179/2999      12.6G    0.02459    0.01504     0.0052        110        640: 100% 5/5 [00:03<00:00,  1.34it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 1/1 [00:01<00:00,  1.10s/it]
                   all        101        217      0.645      0.541      0.544      0.315

      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
   180/2999      12.6G    0.02357    0.01531   0.004675        116        640: 100% 5/5 [00:03<00:00,  1.35it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 1/1 [00:01<00:00,  1.13s/it]
                   all        101        217      0.698      0.435      0.523      0.298

      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
   181/2999      12.6G    0.02478    0.01809   0.006207        146        640: 100% 5/5 [00:03<00:00,  1.33it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 1/1 [00:01<00:00,  1.09s/it]
                   all        101        217      0.698      0.494      0.525      0.302

      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
   182/2999      12.6G    0.02511    0.01721   0.005772        136        640: 100% 5/5 [00:03<00:00,  1.35it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 1/1 [00:01<00:00,  1.08s/it]
                   all        101        217      0.784      0.526      0.572      0.349

      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
   183/2999      12.6G    0.02516    0.01648   0.004389        138        640: 100% 5/5 [00:03<00:00,  1.36it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 1/1 [00:01<00:00,  1.07s/it]
                   all        101        217      0.784      0.457      0.518      0.321

      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
   184/2999      12.6G    0.02352    0.01595   0.004704        116        640: 100% 5/5 [00:03<00:00,  1.34it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 1/1 [00:01<00:00,  1.15s/it]
                   all        101        217      0.553      0.476      0.461      0.271

      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
   185/2999      12.6G     0.0242    0.01582   0.005127        134        640: 100% 5/5 [00:03<00:00,  1.33it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 1/1 [00:01<00:00,  1.12s/it]
                   all        101        217      0.783      0.495      0.526      0.317

      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
   186/2999      12.6G    0.02603    0.01746    0.00654        114        640: 100% 5/5 [00:03<00:00,  1.32it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 1/1 [00:01<00:00,  1.09s/it]
                   all        101        217      0.726      0.516      0.534      0.341

      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
   187/2999      12.6G    0.02491    0.01526   0.005841        107        640: 100% 5/5 [00:03<00:00,  1.34it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 1/1 [00:01<00:00,  1.12s/it]
                   all        101        217      0.727      0.542      0.575      0.379

      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
   188/2999      12.6G    0.02381    0.01668    0.00573        114        640: 100% 5/5 [00:03<00:00,  1.34it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 1/1 [00:01<00:00,  1.13s/it]
                   all        101        217      0.757      0.506      0.583      0.371

      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
   189/2999      12.6G    0.02374    0.01744   0.003979        138        640: 100% 5/5 [00:03<00:00,  1.33it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 1/1 [00:01<00:00,  1.23s/it]
                   all        101        217      0.579      0.527       0.56      0.333

      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
   190/2999      12.6G    0.02419    0.01787   0.006053        171        640: 100% 5/5 [00:03<00:00,  1.34it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 1/1 [00:01<00:00,  1.13s/it]
                   all        101        217      0.728      0.524      0.605      0.341

      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
   191/2999      12.6G    0.02532    0.01639   0.005275        127        640: 100% 5/5 [00:03<00:00,  1.35it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 1/1 [00:01<00:00,  1.15s/it]
                   all        101        217      0.703      0.482      0.571      0.342

      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
   192/2999      12.6G    0.02426    0.01594    0.00537         90        640: 100% 5/5 [00:03<00:00,  1.36it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 1/1 [00:01<00:00,  1.13s/it]
                   all        101        217      0.615      0.529      0.559      0.303

      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
   193/2999      12.6G     0.0235     0.0155   0.004984        132        640: 100% 5/5 [00:03<00:00,  1.35it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 1/1 [00:01<00:00,  1.17s/it]
                   all        101        217      0.728      0.477      0.572      0.331

      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
   194/2999      12.6G    0.02405    0.01871   0.004977        145        640: 100% 5/5 [00:03<00:00,  1.33it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 1/1 [00:01<00:00,  1.14s/it]
                   all        101        217      0.674      0.511      0.561      0.325

      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
   195/2999      12.6G    0.02389    0.01611    0.00649        129        640: 100% 5/5 [00:03<00:00,  1.33it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 1/1 [00:01<00:00,  1.17s/it]
                   all        101        217       0.74      0.579      0.619      0.343

      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
   196/2999      12.6G    0.02439    0.01726   0.007477        155        640: 100% 5/5 [00:03<00:00,  1.34it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 1/1 [00:01<00:00,  1.14s/it]
                   all        101        217      0.733      0.525      0.586      0.313

      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
   197/2999      12.6G    0.02659    0.01695   0.005528        109        640: 100% 5/5 [00:03<00:00,  1.34it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 1/1 [00:01<00:00,  1.70s/it]
                   all        101        217       0.63       0.49      0.521      0.312

      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
   198/2999      12.6G    0.02439    0.01686   0.005409        131        640: 100% 5/5 [00:03<00:00,  1.26it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 1/1 [00:01<00:00,  1.37s/it]
                   all        101        217      0.757      0.543      0.609      0.346

      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
   199/2999      12.6G    0.02365    0.01591   0.005669         91        640: 100% 5/5 [00:03<00:00,  1.33it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 1/1 [00:01<00:00,  1.15s/it]
                   all        101        217      0.761      0.598       0.64      0.372

      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
   200/2999      12.6G    0.02351    0.01638   0.004883        136        640: 100% 5/5 [00:03<00:00,  1.33it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 1/1 [00:01<00:00,  1.09s/it]
                   all        101        217      0.709      0.524      0.577      0.365

      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
   201/2999      12.6G    0.02324    0.01567   0.004999         99        640: 100% 5/5 [00:03<00:00,  1.35it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 1/1 [00:01<00:00,  1.20s/it]
                   all        101        217      0.792      0.513       0.58      0.368

      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
   202/2999      12.6G    0.02519     0.0172   0.006118        115        640: 100% 5/5 [00:03<00:00,  1.33it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 1/1 [00:01<00:00,  1.10s/it]
                   all        101        217      0.716       0.55      0.593      0.383

      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
   203/2999      12.6G    0.02456    0.01669   0.005136        139        640: 100% 5/5 [00:03<00:00,  1.33it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 1/1 [00:01<00:00,  1.10s/it]
                   all        101        217      0.706      0.541      0.581      0.366

      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
   204/2999      12.6G    0.02429    0.01703   0.005905        159        640: 100% 5/5 [00:03<00:00,  1.36it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 1/1 [00:01<00:00,  1.15s/it]
                   all        101        217      0.742      0.517      0.595      0.353

      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
   205/2999      12.6G    0.02645     0.0162   0.005092         99        640: 100% 5/5 [00:03<00:00,  1.33it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 1/1 [00:01<00:00,  1.12s/it]
                   all        101        217      0.724      0.541      0.595      0.353

      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
   206/2999      12.6G    0.02452    0.01742   0.004537        150        640: 100% 5/5 [00:03<00:00,  1.33it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 1/1 [00:01<00:00,  1.08s/it]
                   all        101        217      0.792      0.611      0.691      0.413

      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
   207/2999      12.6G    0.02442    0.01611   0.005929        113        640: 100% 5/5 [00:03<00:00,  1.34it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 1/1 [00:01<00:00,  1.08s/it]
                   all        101        217      0.787      0.597      0.689      0.385

      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
   208/2999      12.6G    0.02346    0.01676   0.005753        131        640: 100% 5/5 [00:03<00:00,  1.36it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 1/1 [00:01<00:00,  1.18s/it]
                   all        101        217      0.713      0.561      0.609      0.368

      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
   209/2999      12.6G    0.02357    0.01644   0.005965        172        640: 100% 5/5 [00:03<00:00,  1.35it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 1/1 [00:01<00:00,  1.15s/it]
                   all        101        217      0.785      0.589      0.648      0.392

      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
   210/2999      12.6G    0.02189    0.01698   0.004232        156        640: 100% 5/5 [00:03<00:00,  1.34it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 1/1 [00:01<00:00,  1.22s/it]
                   all        101        217      0.705      0.556      0.605      0.367

      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
   211/2999      12.6G    0.02317    0.01652   0.004202        132        640: 100% 5/5 [00:03<00:00,  1.35it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 1/1 [00:01<00:00,  1.17s/it]
                   all        101        217      0.644      0.578      0.603      0.374

      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
   212/2999      12.6G    0.02326    0.01527   0.003914        108        640: 100% 5/5 [00:03<00:00,  1.34it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 1/1 [00:01<00:00,  1.10s/it]
                   all        101        217      0.732      0.499      0.575      0.352

      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
   213/2999      12.6G    0.02385    0.01455   0.004347         96        640: 100% 5/5 [00:03<00:00,  1.33it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 1/1 [00:01<00:00,  1.09s/it]
                   all        101        217      0.561      0.568      0.556      0.348

      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
   214/2999      12.6G     0.0238    0.01612   0.006062        115        640: 100% 5/5 [00:03<00:00,  1.34it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 1/1 [00:01<00:00,  1.17s/it]
                   all        101        217      0.696      0.566      0.586      0.356

      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
   215/2999      12.6G    0.02336    0.01577   0.003583        129        640: 100% 5/5 [00:03<00:00,  1.34it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 1/1 [00:01<00:00,  1.14s/it]
                   all        101        217      0.741      0.505      0.566      0.354

      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
   216/2999      12.6G    0.02414    0.01654   0.005234        118        640: 100% 5/5 [00:03<00:00,  1.36it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 1/1 [00:01<00:00,  1.15s/it]
                   all        101        217       0.75      0.484      0.624      0.387

      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
   217/2999      12.6G     0.0235    0.01588   0.006817        108        640: 100% 5/5 [00:03<00:00,  1.32it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 1/1 [00:01<00:00,  1.16s/it]
                   all        101        217      0.735      0.491      0.617      0.373

      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
   218/2999      12.6G    0.02316    0.01613   0.004268        100        640: 100% 5/5 [00:03<00:00,  1.36it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 1/1 [00:01<00:00,  1.10s/it]
                   all        101        217      0.718      0.507      0.624      0.372

      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
   219/2999      12.6G    0.02357    0.01575   0.003894        115        640: 100% 5/5 [00:03<00:00,  1.34it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 1/1 [00:01<00:00,  1.17s/it]
                   all        101        217      0.582      0.554      0.598      0.382

      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
   220/2999      12.6G    0.02333    0.01653   0.005226        140        640: 100% 5/5 [00:03<00:00,  1.33it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 1/1 [00:01<00:00,  1.19s/it]
                   all        101        217      0.672       0.48      0.546      0.315

      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
   221/2999      12.6G    0.02387    0.01517   0.005005        119        640: 100% 5/5 [00:03<00:00,  1.34it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 1/1 [00:01<00:00,  1.18s/it]
                   all        101        217      0.639      0.498      0.561      0.359
Stopping training early as no improvement observed in last 100 epochs. Best results observed at epoch 121, best model saved as best.pt.
To update EarlyStopping(patience=100) pass a new patience value, i.e. `python train.py --patience 300` or use `--patience 0` to disable EarlyStopping.

222 epochs completed in 0.330 hours.
Optimizer stripped from runs/train/exp/weights/last.pt, 14.5MB
Optimizer stripped from runs/train/exp/weights/best.pt, 14.5MB

Validating runs/train/exp/weights/best.pt...
Fusing layers... 
Model summary: 157 layers, 7020913 parameters, 0 gradients, 15.8 GFLOPs
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 1/1 [00:01<00:00,  1.05s/it]
                   all        101        217      0.703       0.64      0.707      0.412
               cadeira        101        101      0.642      0.426      0.524      0.235
             geladeira        101          6      0.715          1      0.927      0.607
               monitor        101         40      0.693       0.55      0.668      0.344
                quadro        101         70      0.762      0.586       0.71      0.461
  ```
</details>

### Evidências do treinamento


![confusion_matrix](https://user-images.githubusercontent.com/89791550/199508118-393f62b7-d4f2-4024-bdb1-646dbec6c589.png)

## Roboflow

https://app.roboflow.com/wilsoncesarschool/projetofinalmodelosconexionistas/1

## HuggingFace

Nessa seção você deve publicar o link para o HuggingFace
