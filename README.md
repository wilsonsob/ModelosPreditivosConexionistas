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
     0/2999      14.1G     0.1176    0.03496    0.04929        227        640: 100% 5/5 [00:08<00:00,  1.65s/it]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 1/1 [00:04<00:00,  4.23s/it]
                   all         79        172    0.00117       0.29    0.00144   0.000293

      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
     1/2999      13.3G       0.11    0.03478    0.04837        216        640: 100% 5/5 [00:03<00:00,  1.34it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 1/1 [00:01<00:00,  1.98s/it]
                   all         79        172    0.00148       0.36    0.00143   0.000484

      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
     2/2999      13.3G    0.09838    0.03372    0.04588        189        640: 100% 5/5 [00:03<00:00,  1.29it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 1/1 [00:01<00:00,  1.42s/it]
                   all         79        172    0.00276       0.37    0.00585    0.00135

      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
     3/2999      13.3G    0.08941    0.03499    0.04303        171        640: 100% 5/5 [00:03<00:00,  1.39it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 1/1 [00:01<00:00,  1.42s/it]
                   all         79        172    0.00324       0.61    0.00878    0.00303

      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
     4/2999      13.3G    0.08229    0.03798    0.03902        230        640: 100% 5/5 [00:03<00:00,  1.39it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 1/1 [00:01<00:00,  1.24s/it]
                   all         79        172    0.00479      0.803     0.0192     0.0057

      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
     5/2999      13.3G    0.07235    0.03762    0.03592        187        640: 100% 5/5 [00:03<00:00,  1.39it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 1/1 [00:01<00:00,  1.32s/it]
                   all         79        172      0.772     0.0641     0.0685     0.0199

      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
     6/2999      13.3G    0.06836    0.03883    0.03304        227        640: 100% 5/5 [00:03<00:00,  1.38it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 1/1 [00:01<00:00,  1.07s/it]
                   all         79        172      0.332      0.221     0.0677     0.0184

      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
     7/2999      13.3G    0.06247    0.03535     0.0311        201        640: 100% 5/5 [00:03<00:00,  1.38it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 1/1 [00:01<00:00,  1.57s/it]
                   all         79        172      0.326      0.266      0.082     0.0217

      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
     8/2999      13.3G    0.05948     0.0349    0.02835        161        640: 100% 5/5 [00:03<00:00,  1.36it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 1/1 [00:01<00:00,  1.30s/it]
                   all         79        172      0.393      0.295      0.175     0.0498

      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
     9/2999      13.3G    0.05892    0.03628    0.02495        221        640: 100% 5/5 [00:03<00:00,  1.38it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 1/1 [00:01<00:00,  1.40s/it]
                   all         79        172      0.386      0.303      0.138     0.0436

      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
    10/2999      13.3G    0.05797    0.03046    0.02325        158        640: 100% 5/5 [00:03<00:00,  1.39it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 1/1 [00:01<00:00,  1.24s/it]
                   all         79        172      0.449      0.376      0.226     0.0926

      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
    11/2999      13.3G    0.05604    0.03243    0.02248        226        640: 100% 5/5 [00:03<00:00,  1.37it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 1/1 [00:01<00:00,  1.23s/it]
                   all         79        172      0.519      0.326        0.3      0.129

      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
    12/2999      13.3G    0.05705    0.03044    0.02158        181        640: 100% 5/5 [00:03<00:00,  1.32it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 1/1 [00:01<00:00,  1.08s/it]
                   all         79        172      0.508      0.342      0.361      0.191

      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
    13/2999      13.3G    0.05534    0.02701    0.01887        167        640: 100% 5/5 [00:03<00:00,  1.37it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 1/1 [00:01<00:00,  1.29s/it]
                   all         79        172      0.429      0.367      0.242     0.0978

      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
    14/2999      13.3G    0.05445    0.03095    0.01875        188        640: 100% 5/5 [00:03<00:00,  1.35it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 1/1 [00:01<00:00,  1.15s/it]
                   all         79        172      0.517      0.495      0.393      0.178

      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
    15/2999      13.3G    0.05658    0.02785    0.01648        175        640: 100% 5/5 [00:03<00:00,  1.33it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 1/1 [00:01<00:00,  1.12s/it]
                   all         79        172      0.512      0.479      0.358      0.177

      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
    16/2999      13.3G    0.05553    0.02625    0.01534        186        640: 100% 5/5 [00:03<00:00,  1.37it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 1/1 [00:01<00:00,  1.13s/it]
                   all         79        172      0.533      0.464      0.412      0.178

      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
    17/2999      13.3G     0.0524    0.02705    0.01531        187        640: 100% 5/5 [00:04<00:00,  1.18it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 1/1 [00:02<00:00,  2.25s/it]
                   all         79        172      0.304      0.483      0.299       0.12

      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
    18/2999      13.3G    0.05295    0.02631    0.01442        162        640: 100% 5/5 [00:04<00:00,  1.01it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 1/1 [00:01<00:00,  1.99s/it]
                   all         79        172      0.649      0.416      0.435      0.203

      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
    19/2999      13.3G    0.05205      0.027    0.01497        227        640: 100% 5/5 [00:03<00:00,  1.28it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 1/1 [00:01<00:00,  1.01s/it]
                   all         79        172      0.305      0.518      0.336      0.151

      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
    20/2999      13.3G    0.05057    0.02601    0.01201        190        640: 100% 5/5 [00:03<00:00,  1.32it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 1/1 [00:01<00:00,  1.02s/it]
                   all         79        172      0.456      0.594      0.442      0.192

      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
    21/2999      13.3G     0.0488    0.02679    0.01386        138        640: 100% 5/5 [00:03<00:00,  1.32it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 1/1 [00:00<00:00,  1.07it/s]
                   all         79        172      0.418      0.586      0.428      0.221

      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
    22/2999      13.3G    0.04713    0.02576    0.01446        215        640: 100% 5/5 [00:03<00:00,  1.33it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 1/1 [00:00<00:00,  1.01it/s]
                   all         79        172      0.642      0.477      0.467       0.23

      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
    23/2999      13.3G    0.04759    0.02555     0.0115        179        640: 100% 5/5 [00:03<00:00,  1.32it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 1/1 [00:01<00:00,  1.06s/it]
                   all         79        172      0.611      0.474      0.436       0.21

      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
    24/2999      13.3G     0.0453    0.02547    0.01341        218        640: 100% 5/5 [00:03<00:00,  1.31it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 1/1 [00:00<00:00,  1.05it/s]
                   all         79        172      0.661      0.485      0.517      0.273

      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
    25/2999      13.3G    0.04469    0.02657    0.01159        229        640: 100% 5/5 [00:03<00:00,  1.34it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 1/1 [00:00<00:00,  1.04it/s]
                   all         79        172       0.62       0.42      0.481      0.236

      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
    26/2999      13.3G    0.04451    0.02416     0.0126        202        640: 100% 5/5 [00:03<00:00,  1.31it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 1/1 [00:01<00:00,  1.15s/it]
                   all         79        172      0.719      0.431      0.502       0.28

      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
    27/2999      13.3G    0.04454    0.02421     0.0113        165        640: 100% 5/5 [00:03<00:00,  1.29it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 1/1 [00:00<00:00,  1.06it/s]
                   all         79        172      0.484      0.424      0.438      0.217

      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
    28/2999      13.3G    0.04353    0.02453    0.01121        222        640: 100% 5/5 [00:03<00:00,  1.28it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 1/1 [00:00<00:00,  1.05it/s]
                   all         79        172      0.328      0.335      0.307      0.165

      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
    29/2999      13.3G    0.04318      0.024    0.01177        168        640: 100% 5/5 [00:03<00:00,  1.26it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 1/1 [00:00<00:00,  1.01it/s]
                   all         79        172      0.399      0.317      0.292      0.141

      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
    30/2999      13.3G    0.04106     0.0244    0.01042        202        640: 100% 5/5 [00:03<00:00,  1.31it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 1/1 [00:00<00:00,  1.08it/s]
                   all         79        172      0.654      0.512       0.52       0.29

      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
    31/2999      13.3G    0.04151    0.02421    0.01037        193        640: 100% 5/5 [00:03<00:00,  1.29it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 1/1 [00:01<00:00,  1.06s/it]
                   all         79        172       0.73      0.389       0.46      0.254

      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
    32/2999      13.3G    0.04187    0.02569   0.009244        193        640: 100% 5/5 [00:03<00:00,  1.31it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 1/1 [00:01<00:00,  1.08s/it]
                   all         79        172      0.372      0.432      0.397      0.184

      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
    33/2999      13.3G    0.04139    0.02411   0.007808        191        640: 100% 5/5 [00:03<00:00,  1.30it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 1/1 [00:01<00:00,  1.03s/it]
                   all         79        172      0.657      0.571      0.583      0.354

      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
    34/2999      13.3G    0.03919    0.02373   0.008649        186        640: 100% 5/5 [00:03<00:00,  1.29it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 1/1 [00:01<00:00,  1.04s/it]
                   all         79        172      0.719      0.515      0.556      0.273

      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
    35/2999      13.3G    0.03933    0.02373    0.01062        194        640: 100% 5/5 [00:03<00:00,  1.27it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 1/1 [00:00<00:00,  1.12it/s]
                   all         79        172      0.646      0.496      0.499      0.297

      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
    36/2999      13.3G    0.03985    0.02292    0.01068        171        640: 100% 5/5 [00:03<00:00,  1.28it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 1/1 [00:00<00:00,  1.05it/s]
                   all         79        172      0.597      0.514      0.424      0.212

      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
    37/2999      13.3G    0.04022    0.02436    0.01181        206        640: 100% 5/5 [00:03<00:00,  1.27it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 1/1 [00:00<00:00,  1.06it/s]
                   all         79        172      0.468      0.473      0.381      0.199

      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
    38/2999      13.3G     0.0392    0.02418    0.01042        207        640: 100% 5/5 [00:03<00:00,  1.30it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 1/1 [00:00<00:00,  1.06it/s]
                   all         79        172      0.589      0.442      0.495       0.25

      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
    39/2999      13.3G    0.03949     0.0232   0.008525        175        640: 100% 5/5 [00:03<00:00,  1.29it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 1/1 [00:01<00:00,  1.07s/it]
                   all         79        172      0.578      0.413      0.467      0.233

      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
    40/2999      13.3G    0.03951    0.02309    0.00936        189        640: 100% 5/5 [00:03<00:00,  1.30it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 1/1 [00:01<00:00,  1.03s/it]
                   all         79        172      0.473      0.597      0.552      0.319

      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
    41/2999      13.3G    0.03824    0.02332    0.01016        183        640: 100% 5/5 [00:03<00:00,  1.29it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 1/1 [00:01<00:00,  1.03s/it]
                   all         79        172       0.46      0.647      0.494      0.284

      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
    42/2999      13.3G    0.03829    0.02417   0.009787        197        640: 100% 5/5 [00:03<00:00,  1.30it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 1/1 [00:00<00:00,  1.01it/s]
                   all         79        172      0.289      0.588      0.436      0.211

      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
    43/2999      13.3G    0.03897    0.02372   0.009366        182        640: 100% 5/5 [00:03<00:00,  1.27it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 1/1 [00:00<00:00,  1.01it/s]
                   all         79        172      0.272      0.612      0.385      0.217

      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
    44/2999      13.3G     0.0391    0.02348   0.008347        223        640: 100% 5/5 [00:03<00:00,  1.29it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 1/1 [00:00<00:00,  1.01it/s]
                   all         79        172      0.621      0.392      0.457      0.238

      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
    45/2999      13.3G    0.03792    0.02103    0.01101        159        640: 100% 5/5 [00:03<00:00,  1.31it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 1/1 [00:01<00:00,  1.17s/it]
                   all         79        172      0.543      0.488      0.527      0.293

      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
    46/2999      13.3G    0.03747    0.02327   0.009737        211        640: 100% 5/5 [00:03<00:00,  1.30it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 1/1 [00:01<00:00,  1.04s/it]
                   all         79        172      0.423      0.621      0.509      0.278

      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
    47/2999      13.3G    0.03701    0.02207   0.008706        189        640: 100% 5/5 [00:03<00:00,  1.30it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 1/1 [00:01<00:00,  1.17s/it]
                   all         79        172      0.459      0.505      0.448      0.231

      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
    48/2999      13.3G    0.03722    0.02309   0.008686        179        640: 100% 5/5 [00:03<00:00,  1.31it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 1/1 [00:00<00:00,  1.14it/s]
                   all         79        172      0.488      0.637      0.532      0.289

      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
    49/2999      13.3G    0.03637    0.02043   0.007798        179        640: 100% 5/5 [00:03<00:00,  1.27it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 1/1 [00:00<00:00,  1.10it/s]
                   all         79        172      0.732      0.443      0.491      0.267

      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
    50/2999      13.3G    0.03709    0.02212   0.007632        194        640: 100% 5/5 [00:03<00:00,  1.32it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 1/1 [00:01<00:00,  1.29s/it]
                   all         79        172      0.468      0.676      0.564      0.324

      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
    51/2999      13.3G    0.03752    0.02221   0.009035        168        640: 100% 5/5 [00:03<00:00,  1.28it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 1/1 [00:00<00:00,  1.03it/s]
                   all         79        172      0.417      0.667      0.451      0.248

      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
    52/2999      13.3G    0.03637    0.02205   0.007745        216        640: 100% 5/5 [00:03<00:00,  1.30it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 1/1 [00:01<00:00,  1.08s/it]
                   all         79        172      0.602      0.533      0.563      0.305

      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
    53/2999      13.3G    0.03561    0.02235   0.006919        213        640: 100% 5/5 [00:03<00:00,  1.30it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 1/1 [00:01<00:00,  1.10s/it]
                   all         79        172       0.71      0.514      0.575      0.317

      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
    54/2999      13.3G     0.0375    0.02151   0.007491        189        640: 100% 5/5 [00:03<00:00,  1.30it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 1/1 [00:00<00:00,  1.05it/s]
                   all         79        172      0.724       0.39      0.472      0.246

      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
    55/2999      13.3G    0.03676    0.02192   0.007115        211        640: 100% 5/5 [00:03<00:00,  1.31it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 1/1 [00:01<00:00,  1.06s/it]
                   all         79        172      0.617      0.509      0.502      0.308

      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
    56/2999      13.3G    0.03543    0.02149   0.008343        174        640: 100% 5/5 [00:03<00:00,  1.30it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 1/1 [00:00<00:00,  1.05it/s]
                   all         79        172      0.599      0.519      0.537      0.302

      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
    57/2999      13.3G    0.03516    0.02129    0.00804        185        640: 100% 5/5 [00:03<00:00,  1.26it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 1/1 [00:01<00:00,  1.09s/it]
                   all         79        172       0.48      0.465      0.442      0.253

      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
    58/2999      13.3G    0.03451    0.02335   0.009221        200        640: 100% 5/5 [00:03<00:00,  1.29it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 1/1 [00:01<00:00,  1.09s/it]
                   all         79        172      0.503      0.407      0.386      0.196

      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
    59/2999      13.3G     0.0356    0.02126   0.006811        248        640: 100% 5/5 [00:03<00:00,  1.29it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 1/1 [00:00<00:00,  1.05it/s]
                   all         79        172      0.697      0.329      0.407      0.219

      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
    60/2999      13.3G    0.03437    0.02229   0.007112        226        640: 100% 5/5 [00:03<00:00,  1.29it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 1/1 [00:01<00:00,  1.03s/it]
                   all         79        172      0.422       0.53      0.456      0.252

      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
    61/2999      13.3G    0.03398    0.02009   0.007508        209        640: 100% 5/5 [00:03<00:00,  1.29it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 1/1 [00:01<00:00,  1.12s/it]
                   all         79        172      0.716      0.369      0.501      0.286

      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
    62/2999      13.3G    0.03399    0.02136   0.007171        189        640: 100% 5/5 [00:03<00:00,  1.29it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 1/1 [00:01<00:00,  1.07s/it]
                   all         79        172      0.492      0.623       0.51      0.289

      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
    63/2999      13.3G     0.0354    0.02072   0.008472        176        640: 100% 5/5 [00:03<00:00,  1.32it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 1/1 [00:01<00:00,  1.49s/it]
                   all         79        172      0.623      0.603      0.616      0.373

      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
    64/2999      13.3G    0.03459    0.02183   0.008503        187        640: 100% 5/5 [00:04<00:00,  1.21it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 1/1 [00:01<00:00,  1.17s/it]
                   all         79        172        0.6      0.618      0.642      0.324

      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
    65/2999      13.3G    0.03388    0.02139   0.008551        205        640: 100% 5/5 [00:03<00:00,  1.27it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 1/1 [00:01<00:00,  1.02s/it]
                   all         79        172      0.614      0.314       0.34       0.18

      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
    66/2999      13.3G    0.03483    0.02107   0.009369        173        640: 100% 5/5 [00:03<00:00,  1.28it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 1/1 [00:00<00:00,  1.10it/s]
                   all         79        172      0.494      0.505      0.489      0.257

      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
    67/2999      13.3G     0.0334     0.0195   0.006718        162        640: 100% 5/5 [00:03<00:00,  1.31it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 1/1 [00:01<00:00,  1.05s/it]
                   all         79        172      0.608      0.412      0.454      0.246

      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
    68/2999      13.3G    0.03517    0.02186   0.008161        200        640: 100% 5/5 [00:03<00:00,  1.28it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 1/1 [00:00<00:00,  1.02it/s]
                   all         79        172      0.691      0.441      0.521      0.324

      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
    69/2999      13.3G    0.03397     0.0213   0.007542        192        640: 100% 5/5 [00:03<00:00,  1.28it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 1/1 [00:00<00:00,  1.07it/s]
                   all         79        172      0.598      0.403      0.453      0.233

      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
    70/2999      13.3G    0.03464    0.02079    0.00808        220        640: 100% 5/5 [00:03<00:00,  1.29it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 1/1 [00:01<00:00,  1.11s/it]
                   all         79        172      0.657      0.415      0.505      0.287

      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
    71/2999      13.3G    0.03414    0.02142   0.006937        149        640: 100% 5/5 [00:03<00:00,  1.29it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 1/1 [00:00<00:00,  1.05it/s]
                   all         79        172      0.529      0.476      0.479       0.28

      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
    72/2999      13.3G    0.03195    0.02103   0.007308        189        640: 100% 5/5 [00:03<00:00,  1.31it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 1/1 [00:01<00:00,  1.01s/it]
                   all         79        172      0.611      0.424      0.426      0.258

      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
    73/2999      13.3G    0.03293     0.0218    0.00651        222        640: 100% 5/5 [00:03<00:00,  1.27it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 1/1 [00:00<00:00,  1.15it/s]
                   all         79        172      0.728      0.479      0.542      0.337

      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
    74/2999      13.3G    0.03236    0.01866   0.009649        127        640: 100% 5/5 [00:03<00:00,  1.29it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 1/1 [00:01<00:00,  1.01s/it]
                   all         79        172      0.588      0.594      0.595       0.36

      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
    75/2999      13.3G    0.03235    0.01942   0.007454        176        640: 100% 5/5 [00:03<00:00,  1.30it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 1/1 [00:01<00:00,  1.04s/it]
                   all         79        172      0.713      0.562      0.592      0.334

      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
    76/2999      13.3G    0.03392    0.02069   0.006954        187        640: 100% 5/5 [00:03<00:00,  1.27it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 1/1 [00:00<00:00,  1.00it/s]
                   all         79        172      0.753      0.474      0.537       0.31

      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
    77/2999      13.3G    0.03292    0.02024    0.00708        179        640: 100% 5/5 [00:03<00:00,  1.29it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 1/1 [00:00<00:00,  1.03it/s]
                   all         79        172      0.724      0.502      0.523      0.285

      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
    78/2999      13.3G    0.03178      0.021   0.006592        208        640: 100% 5/5 [00:03<00:00,  1.30it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 1/1 [00:00<00:00,  1.03it/s]
                   all         79        172      0.724      0.503      0.527      0.304

      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
    79/2999      13.3G    0.03131    0.01963     0.0057        187        640: 100% 5/5 [00:03<00:00,  1.29it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 1/1 [00:01<00:00,  1.12s/it]
                   all         79        172      0.703      0.471      0.539      0.329

      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
    80/2999      13.3G    0.03203    0.02018   0.008287        198        640: 100% 5/5 [00:03<00:00,  1.30it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 1/1 [00:01<00:00,  1.04s/it]
                   all         79        172       0.77      0.499      0.564      0.324

      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
    81/2999      13.3G    0.03084    0.01961   0.007307        206        640: 100% 5/5 [00:04<00:00,  1.16it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 1/1 [00:01<00:00,  1.81s/it]
                   all         79        172      0.687      0.463      0.535      0.318

      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
    82/2999      13.3G    0.03089    0.02012   0.006733        202        640: 100% 5/5 [00:04<00:00,  1.20it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 1/1 [00:01<00:00,  1.27s/it]
                   all         79        172      0.597      0.511      0.501      0.287

      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
    83/2999      13.3G    0.03064    0.01998   0.005996        211        640: 100% 5/5 [00:03<00:00,  1.28it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 1/1 [00:01<00:00,  1.18s/it]
                   all         79        172      0.601      0.418       0.48       0.25

      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
    84/2999      13.3G    0.03132    0.01948   0.004924        206        640: 100% 5/5 [00:03<00:00,  1.30it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 1/1 [00:01<00:00,  1.08s/it]
                   all         79        172      0.651      0.478      0.534      0.317

      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
    85/2999      13.3G    0.03003    0.01933   0.006001        216        640: 100% 5/5 [00:03<00:00,  1.28it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 1/1 [00:01<00:00,  1.02s/it]
                   all         79        172      0.718      0.447      0.572       0.33

      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
    86/2999      13.3G     0.0322    0.01857   0.006746        204        640: 100% 5/5 [00:03<00:00,  1.29it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 1/1 [00:00<00:00,  1.06it/s]
                   all         79        172      0.712      0.534       0.57      0.315

      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
    87/2999      13.3G    0.02937     0.0195   0.007804        208        640: 100% 5/5 [00:03<00:00,  1.26it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 1/1 [00:00<00:00,  1.06it/s]
                   all         79        172      0.667      0.539       0.59      0.377

      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
    88/2999      13.3G    0.03086    0.02039   0.007138        200        640: 100% 5/5 [00:03<00:00,  1.27it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 1/1 [00:00<00:00,  1.08it/s]
                   all         79        172      0.628      0.543      0.558      0.323

      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
    89/2999      13.3G    0.03102    0.01957   0.006189        216        640: 100% 5/5 [00:03<00:00,  1.30it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 1/1 [00:00<00:00,  1.09it/s]
                   all         79        172      0.558       0.57      0.476      0.272

      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
    90/2999      13.3G    0.03026    0.02042   0.008099        211        640: 100% 5/5 [00:03<00:00,  1.30it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 1/1 [00:00<00:00,  1.03it/s]
                   all         79        172      0.668       0.57      0.512      0.306

      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
    91/2999      13.3G    0.02908    0.01987   0.007552        200        640: 100% 5/5 [00:03<00:00,  1.29it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 1/1 [00:00<00:00,  1.01it/s]
                   all         79        172      0.616      0.483      0.481      0.278

      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
    92/2999      13.3G    0.03033    0.01963   0.007505        171        640: 100% 5/5 [00:03<00:00,  1.28it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 1/1 [00:00<00:00,  1.11it/s]
                   all         79        172      0.808      0.519      0.616      0.369

      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
    93/2999      13.3G       0.03    0.01985   0.007565        192        640: 100% 5/5 [00:03<00:00,  1.31it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 1/1 [00:01<00:00,  1.03s/it]
                   all         79        172      0.741      0.466      0.533      0.313

      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
    94/2999      13.3G    0.03061    0.01982   0.006072        164        640: 100% 5/5 [00:03<00:00,  1.31it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 1/1 [00:00<00:00,  1.04it/s]
                   all         79        172      0.839      0.448      0.552      0.332

      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
    95/2999      13.3G    0.02993    0.01983    0.00618        197        640: 100% 5/5 [00:03<00:00,  1.29it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 1/1 [00:01<00:00,  1.11s/it]
                   all         79        172      0.783      0.435      0.549       0.35

      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
    96/2999      13.3G     0.0297    0.01942   0.004898        193        640: 100% 5/5 [00:03<00:00,  1.30it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 1/1 [00:00<00:00,  1.05it/s]
                   all         79        172      0.808      0.534      0.602      0.383

      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
    97/2999      13.3G    0.03024     0.0192   0.007548        199        640: 100% 5/5 [00:03<00:00,  1.27it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 1/1 [00:00<00:00,  1.12it/s]
                   all         79        172      0.677      0.545      0.644      0.388

      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
    98/2999      13.3G    0.02892    0.01992   0.006328        202        640: 100% 5/5 [00:03<00:00,  1.29it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 1/1 [00:00<00:00,  1.04it/s]
                   all         79        172      0.659      0.531      0.599      0.365

      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
    99/2999      13.3G    0.02903    0.01783   0.008322        179        640: 100% 5/5 [00:03<00:00,  1.29it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 1/1 [00:00<00:00,  1.12it/s]
                   all         79        172      0.598      0.545      0.559      0.325

      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
   100/2999      13.3G    0.03175    0.01939   0.005829        211        640: 100% 5/5 [00:03<00:00,  1.30it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 1/1 [00:00<00:00,  1.09it/s]
                   all         79        172      0.602      0.477      0.479      0.279

      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
   101/2999      13.3G    0.02981    0.01811   0.006895        187        640: 100% 5/5 [00:03<00:00,  1.30it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 1/1 [00:01<00:00,  1.12s/it]
                   all         79        172      0.532      0.483      0.449      0.254

      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
   102/2999      13.3G    0.02894    0.01893   0.007293        178        640: 100% 5/5 [00:03<00:00,  1.30it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 1/1 [00:00<00:00,  1.03it/s]
                   all         79        172       0.76      0.362      0.532      0.311

      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
   103/2999      13.3G    0.02853    0.01932   0.005571        233        640: 100% 5/5 [00:03<00:00,  1.30it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 1/1 [00:00<00:00,  1.00it/s]
                   all         79        172      0.603      0.514      0.581      0.337

      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
   104/2999      13.3G    0.02875    0.01752   0.006674        162        640: 100% 5/5 [00:03<00:00,  1.29it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 1/1 [00:00<00:00,  1.03it/s]
                   all         79        172       0.76      0.454       0.57      0.332

      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
   105/2999      13.3G    0.02874    0.01946   0.006926        211        640: 100% 5/5 [00:03<00:00,  1.27it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 1/1 [00:00<00:00,  1.08it/s]
                   all         79        172      0.694       0.45      0.506      0.289

      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
   106/2999      13.3G    0.02967    0.01745   0.005547        205        640: 100% 5/5 [00:04<00:00,  1.22it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 1/1 [00:01<00:00,  1.75s/it]
                   all         79        172      0.748      0.507      0.519      0.296

      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
   107/2999      13.3G    0.03031    0.01972   0.006291        210        640: 100% 5/5 [00:04<00:00,  1.25it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 1/1 [00:01<00:00,  1.18s/it]
                   all         79        172      0.745      0.489      0.565      0.335

      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
   108/2999      13.3G    0.02897    0.01927   0.006829        186        640: 100% 5/5 [00:03<00:00,  1.28it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 1/1 [00:00<00:00,  1.06it/s]
                   all         79        172      0.743      0.543      0.545      0.312

      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
   109/2999      13.3G    0.03018    0.01939   0.006308        237        640: 100% 5/5 [00:03<00:00,  1.31it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 1/1 [00:01<00:00,  1.12s/it]
                   all         79        172      0.715      0.591      0.575      0.308

      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
   110/2999      13.3G    0.02912    0.01956   0.006358        192        640: 100% 5/5 [00:03<00:00,  1.30it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 1/1 [00:00<00:00,  1.01it/s]
                   all         79        172      0.717      0.545      0.581      0.347

      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
   111/2999      13.3G    0.02963    0.01883   0.007443        157        640: 100% 5/5 [00:03<00:00,  1.28it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 1/1 [00:00<00:00,  1.03it/s]
                   all         79        172      0.732      0.498      0.617      0.348

      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
   112/2999      13.3G    0.02796    0.01824   0.006296        226        640: 100% 5/5 [00:03<00:00,  1.29it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 1/1 [00:00<00:00,  1.00it/s]
                   all         79        172       0.67      0.632      0.623      0.384

      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
   113/2999      13.3G    0.02855    0.01817   0.005978        190        640: 100% 5/5 [00:03<00:00,  1.31it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 1/1 [00:01<00:00,  1.02s/it]
                   all         79        172      0.675      0.574      0.594      0.321

      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
   114/2999      13.3G    0.02922    0.01838   0.006151        185        640: 100% 5/5 [00:03<00:00,  1.28it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 1/1 [00:00<00:00,  1.07it/s]
                   all         79        172      0.782      0.457      0.584      0.336

      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
   115/2999      13.3G    0.02933     0.0188   0.008184        161        640: 100% 5/5 [00:03<00:00,  1.31it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 1/1 [00:01<00:00,  1.10s/it]
                   all         79        172      0.588      0.567      0.559      0.324

      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
   116/2999      13.3G    0.02704     0.0186   0.005759        217        640: 100% 5/5 [00:03<00:00,  1.31it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 1/1 [00:01<00:00,  1.01s/it]
                   all         79        172      0.712      0.594       0.61      0.387

      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
   117/2999      13.3G    0.02805    0.01756   0.007583        183        640: 100% 5/5 [00:03<00:00,  1.30it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 1/1 [00:00<00:00,  1.06it/s]
                   all         79        172       0.72      0.483      0.574       0.36

      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
   118/2999      13.3G    0.02756     0.0179   0.006019        190        640: 100% 5/5 [00:03<00:00,  1.28it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 1/1 [00:00<00:00,  1.11it/s]
                   all         79        172      0.726      0.576      0.603      0.351

      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
   119/2999      13.3G    0.02793    0.01717   0.007643        168        640: 100% 5/5 [00:03<00:00,  1.30it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 1/1 [00:00<00:00,  1.00it/s]
                   all         79        172      0.735      0.538      0.595      0.338

      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
   120/2999      13.3G     0.0286    0.01874   0.005134        223        640: 100% 5/5 [00:03<00:00,  1.26it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 1/1 [00:01<00:00,  1.11s/it]
                   all         79        172      0.653      0.528      0.551      0.323

      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
   121/2999      13.3G     0.0283    0.01745   0.005626        189        640: 100% 5/5 [00:03<00:00,  1.26it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 1/1 [00:00<00:00,  1.05it/s]
                   all         79        172      0.763      0.444      0.544       0.34

      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
   122/2999      13.3G    0.02849    0.01963    0.00636        189        640: 100% 5/5 [00:03<00:00,  1.30it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 1/1 [00:01<00:00,  1.06s/it]
                   all         79        172      0.728      0.518      0.622      0.356

      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
   123/2999      13.3G    0.02766    0.01739   0.005559        157        640: 100% 5/5 [00:03<00:00,  1.29it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 1/1 [00:00<00:00,  1.14it/s]
                   all         79        172      0.705      0.387      0.452      0.269

      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
   124/2999      13.3G    0.02744    0.01842   0.007753        207        640: 100% 5/5 [00:03<00:00,  1.30it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 1/1 [00:00<00:00,  1.05it/s]
                   all         79        172      0.756      0.553      0.605      0.347

      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
   125/2999      13.3G    0.02833    0.01658   0.005275        144        640: 100% 5/5 [00:03<00:00,  1.28it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 1/1 [00:00<00:00,  1.02it/s]
                   all         79        172      0.771      0.441      0.507      0.327

      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
   126/2999      13.3G    0.02873    0.01809   0.006018        230        640: 100% 5/5 [00:03<00:00,  1.30it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 1/1 [00:01<00:00,  1.12s/it]
                   all         79        172      0.777      0.509      0.608       0.33

      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
   127/2999      13.3G    0.02782    0.01771   0.005374        184        640: 100% 5/5 [00:03<00:00,  1.28it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 1/1 [00:00<00:00,  1.06it/s]
                   all         79        172      0.736      0.517      0.548      0.345

      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
   128/2999      13.3G    0.02666    0.01821   0.004101        210        640: 100% 5/5 [00:03<00:00,  1.29it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 1/1 [00:00<00:00,  1.09it/s]
                   all         79        172      0.638      0.596      0.615      0.336

      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
   129/2999      13.3G    0.02662    0.01685   0.005201        182        640: 100% 5/5 [00:03<00:00,  1.30it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 1/1 [00:00<00:00,  1.07it/s]
                   all         79        172      0.722      0.597      0.629      0.366

      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
   130/2999      13.3G    0.02622    0.01672   0.006191        144        640: 100% 5/5 [00:03<00:00,  1.28it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 1/1 [00:00<00:00,  1.10it/s]
                   all         79        172      0.802      0.468      0.542      0.325

      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
   131/2999      13.3G    0.02667    0.01867    0.00618        197        640: 100% 5/5 [00:03<00:00,  1.27it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 1/1 [00:01<00:00,  1.02s/it]
                   all         79        172      0.609      0.454       0.49      0.301

      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
   132/2999      13.3G    0.02787    0.01969   0.005775        229        640: 100% 5/5 [00:03<00:00,  1.26it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 1/1 [00:00<00:00,  1.04it/s]
                   all         79        172      0.525      0.437      0.459      0.266

      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
   133/2999      13.3G    0.02774    0.01836   0.006047        212        640: 100% 5/5 [00:03<00:00,  1.31it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 1/1 [00:00<00:00,  1.13it/s]
                   all         79        172      0.632       0.52      0.575      0.317

      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
   134/2999      13.3G    0.02741    0.01768    0.00579        219        640: 100% 5/5 [00:03<00:00,  1.31it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 1/1 [00:01<00:00,  1.03s/it]
                   all         79        172      0.625      0.632      0.585       0.37

      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
   135/2999      13.3G    0.02713    0.01778   0.005949        217        640: 100% 5/5 [00:03<00:00,  1.27it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 1/1 [00:00<00:00,  1.02it/s]
                   all         79        172      0.514      0.585      0.452      0.257

      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
   136/2999      13.3G     0.0277    0.01698   0.007301        162        640: 100% 5/5 [00:03<00:00,  1.30it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 1/1 [00:00<00:00,  1.07it/s]
                   all         79        172      0.578      0.407      0.444      0.255

      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
   137/2999      13.3G     0.0272    0.01767   0.004752        179        640: 100% 5/5 [00:03<00:00,  1.29it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 1/1 [00:00<00:00,  1.05it/s]
                   all         79        172      0.479      0.457      0.483      0.284

      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
   138/2999      13.3G    0.02749      0.018   0.004356        216        640: 100% 5/5 [00:03<00:00,  1.30it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 1/1 [00:01<00:00,  1.05s/it]
                   all         79        172      0.729      0.473      0.532      0.288

      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
   139/2999      13.3G    0.02768    0.01737   0.006317        188        640: 100% 5/5 [00:03<00:00,  1.28it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 1/1 [00:00<00:00,  1.09it/s]
                   all         79        172      0.657      0.548      0.533      0.298

      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
   140/2999      13.3G    0.02608    0.01767    0.00451        184        640: 100% 5/5 [00:03<00:00,  1.30it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 1/1 [00:01<00:00,  1.10s/it]
                   all         79        172      0.737      0.553      0.586      0.347

      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
   141/2999      13.3G    0.02657    0.01743   0.004523        201        640: 100% 5/5 [00:03<00:00,  1.30it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 1/1 [00:01<00:00,  1.51s/it]
                   all         79        172      0.781      0.515      0.606      0.363

      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
   142/2999      13.3G    0.02724    0.01774   0.006709        184        640: 100% 5/5 [00:04<00:00,  1.16it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 1/1 [00:01<00:00,  1.88s/it]
                   all         79        172      0.742      0.576      0.637      0.346

      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
   143/2999      13.3G    0.02575    0.01799   0.005323        212        640: 100% 5/5 [00:04<00:00,  1.25it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 1/1 [00:01<00:00,  1.30s/it]
                   all         79        172      0.776      0.492      0.563       0.35

      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
   144/2999      13.3G    0.02654    0.01726   0.005264        166        640: 100% 5/5 [00:04<00:00,  1.19it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 1/1 [00:01<00:00,  1.60s/it]
                   all         79        172      0.679      0.535      0.565      0.314

      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
   145/2999      13.3G    0.02687    0.01829   0.005005        250        640: 100% 5/5 [00:03<00:00,  1.29it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 1/1 [00:01<00:00,  1.03s/it]
                   all         79        172       0.81      0.523      0.563      0.342

      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
   146/2999      13.3G    0.02672    0.01687   0.005595        208        640: 100% 5/5 [00:03<00:00,  1.30it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 1/1 [00:01<00:00,  1.07s/it]
                   all         79        172       0.76      0.503      0.556      0.328

      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
   147/2999      13.3G    0.02691    0.01723   0.005911        180        640: 100% 5/5 [00:03<00:00,  1.29it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 1/1 [00:01<00:00,  1.08s/it]
                   all         79        172      0.748      0.537      0.579      0.338

      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
   148/2999      13.3G    0.02626    0.01806   0.004589        227        640: 100% 5/5 [00:04<00:00,  1.20it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 1/1 [00:01<00:00,  1.39s/it]
                   all         79        172      0.795      0.512      0.556       0.34

      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
   149/2999      13.3G    0.02653    0.01662   0.005405        177        640: 100% 5/5 [00:04<00:00,  1.24it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 1/1 [00:00<00:00,  1.12it/s]
                   all         79        172      0.791      0.464      0.531      0.328

      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
   150/2999      13.3G     0.0274    0.01625   0.006181        147        640: 100% 5/5 [00:03<00:00,  1.30it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 1/1 [00:00<00:00,  1.06it/s]
                   all         79        172      0.749      0.544      0.602      0.352

      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
   151/2999      13.3G    0.02522    0.01715   0.004715        184        640: 100% 5/5 [00:03<00:00,  1.29it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 1/1 [00:00<00:00,  1.08it/s]
                   all         79        172      0.801      0.549      0.596      0.363

      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
   152/2999      13.3G    0.02576    0.01662   0.004771        139        640: 100% 5/5 [00:03<00:00,  1.28it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 1/1 [00:00<00:00,  1.04it/s]
                   all         79        172      0.825      0.503      0.559      0.349

      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
   153/2999      13.3G    0.02895    0.01797   0.005624        185        640: 100% 5/5 [00:03<00:00,  1.31it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 1/1 [00:01<00:00,  1.05s/it]
                   all         79        172      0.837      0.465       0.54      0.341

      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
   154/2999      13.3G    0.02476    0.01641   0.005789        184        640: 100% 5/5 [00:03<00:00,  1.30it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 1/1 [00:00<00:00,  1.07it/s]
                   all         79        172       0.79      0.498      0.564      0.341

      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
   155/2999      13.3G    0.02548    0.01872   0.005374        212        640: 100% 5/5 [00:03<00:00,  1.28it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 1/1 [00:00<00:00,  1.11it/s]
                   all         79        172      0.824      0.498      0.573      0.347

      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
   156/2999      13.3G    0.02632    0.01815   0.006032        229        640: 100% 5/5 [00:04<00:00,  1.21it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 1/1 [00:00<00:00,  1.05it/s]
                   all         79        172      0.715      0.549      0.597      0.343

      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
   157/2999      13.3G    0.02511    0.01649   0.005817        195        640: 100% 5/5 [00:03<00:00,  1.27it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 1/1 [00:00<00:00,  1.17it/s]
                   all         79        172      0.821      0.566      0.663      0.385

      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
   158/2999      13.3G    0.02516    0.01653   0.005879        159        640: 100% 5/5 [00:03<00:00,  1.30it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 1/1 [00:00<00:00,  1.02it/s]
                   all         79        172      0.686      0.641      0.643      0.372

      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
   159/2999      13.3G    0.02657    0.01595   0.005654        185        640: 100% 5/5 [00:03<00:00,  1.29it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 1/1 [00:01<00:00,  1.00s/it]
                   all         79        172      0.676      0.625      0.652      0.378

      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
   160/2999      13.3G    0.02582     0.0173   0.005202        215        640: 100% 5/5 [00:03<00:00,  1.31it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 1/1 [00:00<00:00,  1.05it/s]
                   all         79        172      0.729      0.547      0.621      0.351

      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
   161/2999      13.3G    0.02607    0.01732   0.006912        218        640: 100% 5/5 [00:03<00:00,  1.30it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 1/1 [00:00<00:00,  1.04it/s]
                   all         79        172      0.679      0.483      0.547      0.322

      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
   162/2999      13.3G    0.02534    0.01606   0.005221        169        640: 100% 5/5 [00:03<00:00,  1.29it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 1/1 [00:01<00:00,  1.06s/it]
                   all         79        172      0.799       0.44      0.601      0.379

      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
   163/2999      13.3G    0.02638    0.01726   0.006002        216        640: 100% 5/5 [00:03<00:00,  1.30it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 1/1 [00:01<00:00,  1.00s/it]
                   all         79        172      0.689      0.635      0.631      0.381

      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
   164/2999      13.3G    0.02443    0.01882   0.005191        279        640: 100% 5/5 [00:03<00:00,  1.30it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 1/1 [00:00<00:00,  1.01it/s]
                   all         79        172      0.721       0.67      0.685      0.404

      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
   165/2999      13.3G    0.02414    0.01719   0.003583        182        640: 100% 5/5 [00:03<00:00,  1.28it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 1/1 [00:00<00:00,  1.03it/s]
                   all         79        172       0.67      0.646      0.681      0.409

      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
   166/2999      13.3G    0.02653    0.01778   0.005552        195        640: 100% 5/5 [00:03<00:00,  1.28it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 1/1 [00:00<00:00,  1.06it/s]
                   all         79        172      0.796      0.659      0.663      0.362

      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
   167/2999      13.3G    0.02577    0.01602   0.005825        178        640: 100% 5/5 [00:03<00:00,  1.31it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 1/1 [00:01<00:00,  1.14s/it]
                   all         79        172      0.721       0.69      0.704      0.404

      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
   168/2999      13.3G    0.02503    0.01867   0.004954        244        640: 100% 5/5 [00:03<00:00,  1.29it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 1/1 [00:00<00:00,  1.05it/s]
                   all         79        172      0.692      0.658      0.701      0.417

      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
   169/2999      13.3G    0.02524    0.01849   0.006853        222        640: 100% 5/5 [00:03<00:00,  1.29it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 1/1 [00:01<00:00,  1.07s/it]
                   all         79        172      0.716      0.598      0.644      0.371

      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
   170/2999      13.3G    0.02458      0.017   0.004295        193        640: 100% 5/5 [00:03<00:00,  1.28it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 1/1 [00:01<00:00,  1.03s/it]
                   all         79        172      0.589      0.633      0.537      0.318

      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
   171/2999      13.3G    0.02478    0.01661   0.003602        186        640: 100% 5/5 [00:03<00:00,  1.30it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 1/1 [00:00<00:00,  1.02it/s]
                   all         79        172      0.685      0.599      0.582      0.355

      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
   172/2999      13.3G    0.02531    0.01569   0.005721        175        640: 100% 5/5 [00:03<00:00,  1.29it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 1/1 [00:01<00:00,  1.06s/it]
                   all         79        172      0.687      0.607       0.62      0.367

      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
   173/2999      13.3G    0.02561     0.0182   0.005804        214        640: 100% 5/5 [00:03<00:00,  1.28it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 1/1 [00:00<00:00,  1.01it/s]
                   all         79        172      0.769      0.533      0.642      0.393

      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
   174/2999      13.3G    0.02489    0.01687   0.006483        180        640: 100% 5/5 [00:03<00:00,  1.28it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 1/1 [00:00<00:00,  1.04it/s]
                   all         79        172      0.647       0.56      0.638       0.39

      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
   175/2999      13.3G    0.02413    0.01744   0.006103        222        640: 100% 5/5 [00:03<00:00,  1.28it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 1/1 [00:00<00:00,  1.11it/s]
                   all         79        172      0.722      0.537      0.659      0.392

      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
   176/2999      13.3G    0.02617     0.0165   0.004711        183        640: 100% 5/5 [00:03<00:00,  1.29it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 1/1 [00:01<00:00,  1.06s/it]
                   all         79        172      0.658      0.547      0.588       0.34

      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
   177/2999      13.3G    0.02391     0.0172   0.006477        160        640: 100% 5/5 [00:04<00:00,  1.19it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 1/1 [00:00<00:00,  1.21it/s]
                   all         79        172      0.722      0.485       0.57      0.329

      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
   178/2999      13.3G    0.02595     0.0167   0.004114        203        640: 100% 5/5 [00:03<00:00,  1.28it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 1/1 [00:01<00:00,  1.03s/it]
                   all         79        172       0.75      0.421      0.499      0.285

      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
   179/2999      13.3G    0.02545    0.01615   0.005344        185        640: 100% 5/5 [00:03<00:00,  1.28it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 1/1 [00:00<00:00,  1.10it/s]
                   all         79        172      0.862      0.506      0.609      0.366

      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
   180/2999      13.3G     0.0244    0.01572   0.005259        219        640: 100% 5/5 [00:03<00:00,  1.29it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 1/1 [00:00<00:00,  1.02it/s]
                   all         79        172      0.848      0.563      0.642      0.371

      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
   181/2999      13.3G    0.02403    0.01656   0.004655        198        640: 100% 5/5 [00:03<00:00,  1.31it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 1/1 [00:01<00:00,  1.04s/it]
                   all         79        172      0.708      0.582      0.607      0.349

      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
   182/2999      13.3G      0.025    0.01808   0.005477        238        640: 100% 5/5 [00:03<00:00,  1.28it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 1/1 [00:00<00:00,  1.10it/s]
                   all         79        172      0.756      0.603      0.637      0.389

      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
   183/2999      13.3G    0.02387    0.01685   0.007013        194        640: 100% 5/5 [00:03<00:00,  1.30it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 1/1 [00:00<00:00,  1.00it/s]
                   all         79        172       0.75      0.625      0.693      0.435

      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
   184/2999      13.3G    0.02442    0.01655   0.005348        242        640: 100% 5/5 [00:03<00:00,  1.28it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 1/1 [00:00<00:00,  1.19it/s]
                   all         79        172      0.754      0.529      0.602      0.362

      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
   185/2999      13.3G    0.02413    0.01696     0.0051        175        640: 100% 5/5 [00:03<00:00,  1.29it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 1/1 [00:00<00:00,  1.14it/s]
                   all         79        172      0.843      0.546      0.663      0.395

      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
   186/2999      13.3G    0.02388    0.01608   0.003896        203        640: 100% 5/5 [00:03<00:00,  1.29it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 1/1 [00:00<00:00,  1.04it/s]
                   all         79        172       0.82      0.542      0.656      0.401

      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
   187/2999      13.3G    0.02426    0.01638   0.005311        166        640: 100% 5/5 [00:03<00:00,  1.26it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 1/1 [00:01<00:00,  1.72s/it]
                   all         79        172      0.802      0.555      0.616      0.374

      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
   188/2999      13.3G    0.02368    0.01607   0.005871        181        640: 100% 5/5 [00:03<00:00,  1.26it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 1/1 [00:00<00:00,  1.03it/s]
                   all         79        172      0.736      0.628      0.667      0.394

      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
   189/2999      13.3G     0.0257    0.01712   0.006646        205        640: 100% 5/5 [00:03<00:00,  1.28it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 1/1 [00:01<00:00,  1.01s/it]
                   all         79        172      0.781      0.441      0.596      0.332

      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
   190/2999      13.3G    0.02485    0.01648   0.005049        222        640: 100% 5/5 [00:03<00:00,  1.32it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 1/1 [00:00<00:00,  1.17it/s]
                   all         79        172       0.76      0.466      0.549      0.304

      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
   191/2999      13.3G    0.02291    0.01608   0.005364        217        640: 100% 5/5 [00:03<00:00,  1.29it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 1/1 [00:00<00:00,  1.08it/s]
                   all         79        172      0.696      0.473       0.51      0.315

      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
   192/2999      13.3G    0.02464    0.01737   0.006162        205        640: 100% 5/5 [00:03<00:00,  1.32it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 1/1 [00:01<00:00,  1.17s/it]
                   all         79        172      0.696      0.493      0.535      0.325

      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
   193/2999      13.3G    0.02452    0.01706   0.005202        197        640: 100% 5/5 [00:03<00:00,  1.29it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 1/1 [00:00<00:00,  1.14it/s]
                   all         79        172      0.801      0.429      0.562      0.332

      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
   194/2999      13.3G    0.02326    0.01667   0.004886        190        640: 100% 5/5 [00:03<00:00,  1.29it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 1/1 [00:01<00:00,  1.05s/it]
                   all         79        172      0.768      0.432      0.531      0.294

      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
   195/2999      13.3G    0.02424    0.01685   0.005938        231        640: 100% 5/5 [00:03<00:00,  1.30it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 1/1 [00:00<00:00,  1.02it/s]
                   all         79        172       0.87      0.384      0.528      0.319

      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
   196/2999      13.3G    0.02383    0.01643   0.005414        160        640: 100% 5/5 [00:03<00:00,  1.30it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 1/1 [00:00<00:00,  1.00it/s]
                   all         79        172      0.752      0.584      0.617      0.351

      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
   197/2999      13.3G    0.02474    0.01629   0.004213        195        640: 100% 5/5 [00:03<00:00,  1.28it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 1/1 [00:00<00:00,  1.14it/s]
                   all         79        172      0.819      0.516      0.617      0.336

      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
   198/2999      13.3G    0.02378    0.01605   0.004158        202        640: 100% 5/5 [00:03<00:00,  1.30it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 1/1 [00:00<00:00,  1.01it/s]
                   all         79        172      0.691      0.492      0.623      0.353

      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
   199/2999      13.3G    0.02474    0.01601   0.005006        196        640: 100% 5/5 [00:03<00:00,  1.29it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 1/1 [00:00<00:00,  1.11it/s]
                   all         79        172      0.845      0.481       0.57      0.349

      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
   200/2999      13.3G    0.02325    0.01525   0.004579        200        640: 100% 5/5 [00:03<00:00,  1.31it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 1/1 [00:01<00:00,  1.04s/it]
                   all         79        172      0.679      0.425      0.496      0.301

      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
   201/2999      13.3G    0.02245    0.01579    0.00427        226        640: 100% 5/5 [00:04<00:00,  1.23it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 1/1 [00:01<00:00,  1.72s/it]
                   all         79        172      0.743      0.428      0.494      0.303

      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
   202/2999      13.3G    0.02279    0.01541   0.007018        163        640: 100% 5/5 [00:03<00:00,  1.27it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 1/1 [00:01<00:00,  1.24s/it]
                   all         79        172      0.795      0.485      0.547      0.328

      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
   203/2999      13.3G    0.02381    0.01648   0.004034        192        640: 100% 5/5 [00:03<00:00,  1.30it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 1/1 [00:00<00:00,  1.10it/s]
                   all         79        172      0.695      0.529      0.619       0.37

      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
   204/2999      13.3G    0.02344    0.01555   0.003905        196        640: 100% 5/5 [00:03<00:00,  1.29it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 1/1 [00:01<00:00,  1.34s/it]
                   all         79        172       0.81       0.49      0.566      0.348

      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
   205/2999      13.3G    0.02414    0.01678   0.005969        225        640: 100% 5/5 [00:04<00:00,  1.21it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 1/1 [00:01<00:00,  1.77s/it]
                   all         79        172      0.793      0.499      0.551      0.343

      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
   206/2999      13.3G    0.02397    0.01629   0.005902        211        640: 100% 5/5 [00:04<00:00,  1.20it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 1/1 [00:01<00:00,  1.13s/it]
                   all         79        172      0.848      0.569      0.645      0.394

      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
   207/2999      13.3G    0.02395    0.01554   0.005462        170        640: 100% 5/5 [00:04<00:00,  1.24it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 1/1 [00:00<00:00,  1.10it/s]
                   all         79        172      0.826      0.536      0.643      0.394

      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
   208/2999      13.3G    0.02359     0.0166   0.005498        224        640: 100% 5/5 [00:03<00:00,  1.31it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 1/1 [00:00<00:00,  1.06it/s]
                   all         79        172      0.747      0.591      0.647      0.398

      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
   209/2999      13.3G    0.02367    0.01604    0.00558        225        640: 100% 5/5 [00:03<00:00,  1.27it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 1/1 [00:01<00:00,  1.02s/it]
                   all         79        172      0.747       0.53      0.614      0.378

      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
   210/2999      13.3G    0.02559    0.01545   0.005393        171        640: 100% 5/5 [00:03<00:00,  1.29it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 1/1 [00:00<00:00,  1.15it/s]
                   all         79        172      0.787      0.519      0.618      0.384

      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
   211/2999      13.3G    0.02273     0.0167   0.005695        202        640: 100% 5/5 [00:03<00:00,  1.30it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 1/1 [00:00<00:00,  1.10it/s]
                   all         79        172       0.79      0.512      0.612      0.386

      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
   212/2999      13.3G    0.02254    0.01724   0.005585        208        640: 100% 5/5 [00:03<00:00,  1.32it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 1/1 [00:01<00:00,  1.13s/it]
                   all         79        172      0.788      0.571      0.639      0.375

      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
   213/2999      13.3G    0.02419    0.01494   0.005212        207        640: 100% 5/5 [00:03<00:00,  1.29it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 1/1 [00:00<00:00,  1.10it/s]
                   all         79        172      0.842       0.53      0.648      0.364

      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
   214/2999      13.3G    0.02568    0.01664   0.004367        183        640: 100% 5/5 [00:03<00:00,  1.30it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 1/1 [00:00<00:00,  1.04it/s]
                   all         79        172       0.68      0.579       0.58      0.347

      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
   215/2999      13.3G    0.02463    0.01619   0.005758        209        640: 100% 5/5 [00:03<00:00,  1.31it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 1/1 [00:00<00:00,  1.05it/s]
                   all         79        172       0.69      0.573      0.583      0.335

      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
   216/2999      13.3G    0.02261    0.01598   0.005402        208        640: 100% 5/5 [00:03<00:00,  1.29it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 1/1 [00:00<00:00,  1.07it/s]
                   all         79        172      0.798      0.543       0.61      0.374

      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
   217/2999      13.3G    0.02275    0.01476   0.004736        160        640: 100% 5/5 [00:03<00:00,  1.28it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 1/1 [00:00<00:00,  1.07it/s]
                   all         79        172      0.714      0.539       0.56      0.341

      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
   218/2999      13.3G    0.02411    0.01569   0.004459        187        640: 100% 5/5 [00:03<00:00,  1.27it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 1/1 [00:00<00:00,  1.07it/s]
                   all         79        172       0.78      0.521      0.564       0.35

      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
   219/2999      13.3G    0.02208    0.01444    0.00422        173        640: 100% 5/5 [00:03<00:00,  1.30it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 1/1 [00:00<00:00,  1.04it/s]
                   all         79        172      0.627      0.504      0.557      0.353

      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
   220/2999      13.3G      0.023     0.0164   0.004591        218        640: 100% 5/5 [00:03<00:00,  1.29it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 1/1 [00:01<00:00,  1.01s/it]
                   all         79        172      0.838      0.465      0.597       0.36

      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
   221/2999      13.3G    0.02155    0.01479   0.003508        192        640: 100% 5/5 [00:03<00:00,  1.31it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 1/1 [00:01<00:00,  1.00s/it]
                   all         79        172      0.807      0.548      0.654      0.384

      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
   222/2999      13.3G    0.02316    0.01552   0.004726        217        640: 100% 5/5 [00:03<00:00,  1.32it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 1/1 [00:00<00:00,  1.06it/s]
                   all         79        172      0.747      0.677      0.707       0.39

      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
   223/2999      13.3G     0.0233    0.01691   0.007177        180        640: 100% 5/5 [00:03<00:00,  1.29it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 1/1 [00:01<00:00,  1.03s/it]
                   all         79        172      0.742      0.567      0.639      0.372

      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
   224/2999      13.3G    0.02206    0.01515    0.00455        173        640: 100% 5/5 [00:03<00:00,  1.28it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 1/1 [00:00<00:00,  1.06it/s]
                   all         79        172       0.76      0.499      0.619      0.368

      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
   225/2999      13.3G     0.0244    0.01643   0.004599        181        640: 100% 5/5 [00:03<00:00,  1.27it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 1/1 [00:00<00:00,  1.04it/s]
                   all         79        172       0.84      0.505      0.606      0.352

      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
   226/2999      13.3G    0.02239    0.01505   0.005543        201        640: 100% 5/5 [00:03<00:00,  1.29it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 1/1 [00:00<00:00,  1.02it/s]
                   all         79        172      0.676      0.555      0.635      0.378

      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
   227/2999      13.3G    0.02369    0.01622   0.005755        177        640: 100% 5/5 [00:03<00:00,  1.30it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 1/1 [00:00<00:00,  1.10it/s]
                   all         79        172      0.729      0.595      0.608      0.356

      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
   228/2999      13.3G    0.02266    0.01487   0.004909        204        640: 100% 5/5 [00:03<00:00,  1.30it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 1/1 [00:01<00:00,  1.13s/it]
                   all         79        172      0.665       0.54      0.549      0.345

      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
   229/2999      13.3G     0.0233    0.01656    0.00652        172        640: 100% 5/5 [00:04<00:00,  1.17it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 1/1 [00:01<00:00,  1.10s/it]
                   all         79        172      0.769      0.492      0.603      0.384

      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
   230/2999      13.3G    0.02232    0.01574   0.004084        183        640: 100% 5/5 [00:03<00:00,  1.29it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 1/1 [00:01<00:00,  1.13s/it]
                   all         79        172      0.678      0.568      0.599      0.381

      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
   231/2999      13.3G     0.0231    0.01623   0.004324        230        640: 100% 5/5 [00:03<00:00,  1.31it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 1/1 [00:00<00:00,  1.08it/s]
                   all         79        172      0.756      0.594      0.632      0.394

      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
   232/2999      13.3G    0.02286    0.01546    0.00569        185        640: 100% 5/5 [00:03<00:00,  1.28it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 1/1 [00:00<00:00,  1.06it/s]
                   all         79        172      0.789       0.53      0.608      0.378

      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
   233/2999      13.3G     0.0229    0.01477   0.004437        149        640: 100% 5/5 [00:03<00:00,  1.28it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 1/1 [00:01<00:00,  1.04s/it]
                   all         79        172      0.683      0.499      0.573      0.338

      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
   234/2999      13.3G     0.0234    0.01698   0.005284        215        640: 100% 5/5 [00:03<00:00,  1.31it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 1/1 [00:00<00:00,  1.08it/s]
                   all         79        172      0.771      0.472      0.544      0.317

      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
   235/2999      13.3G    0.02219     0.0148   0.004658        186        640: 100% 5/5 [00:03<00:00,  1.30it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 1/1 [00:01<00:00,  1.17s/it]
                   all         79        172      0.717       0.49      0.543      0.333

      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
   236/2999      13.3G    0.02321     0.0145   0.005254        161        640: 100% 5/5 [00:03<00:00,  1.29it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 1/1 [00:00<00:00,  1.09it/s]
                   all         79        172       0.73      0.506       0.55      0.328

      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
   237/2999      13.3G    0.02371    0.01623   0.004812        204        640: 100% 5/5 [00:03<00:00,  1.31it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 1/1 [00:00<00:00,  1.04it/s]
                   all         79        172      0.693      0.511      0.554      0.343

      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
   238/2999      13.3G    0.02394    0.01551   0.004886        161        640: 100% 5/5 [00:03<00:00,  1.28it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 1/1 [00:00<00:00,  1.14it/s]
                   all         79        172      0.791      0.444      0.594      0.376

      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
   239/2999      13.3G    0.02325     0.0154   0.004177        195        640: 100% 5/5 [00:03<00:00,  1.29it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 1/1 [00:00<00:00,  1.00it/s]
                   all         79        172      0.758      0.629      0.657      0.421

      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
   240/2999      13.3G    0.02192     0.0154   0.003914        202        640: 100% 5/5 [00:03<00:00,  1.30it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 1/1 [00:00<00:00,  1.10it/s]
                   all         79        172      0.683      0.556      0.631      0.388

      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
   241/2999      13.3G    0.02239    0.01488   0.007844        184        640: 100% 5/5 [00:03<00:00,  1.29it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 1/1 [00:00<00:00,  1.13it/s]
                   all         79        172      0.694      0.441      0.561      0.346

      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
   242/2999      13.3G    0.02268     0.0156   0.005672        179        640: 100% 5/5 [00:03<00:00,  1.25it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 1/1 [00:01<00:00,  1.61s/it]
                   all         79        172      0.841       0.46      0.552      0.341

      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
   243/2999      13.3G    0.02341     0.0154   0.005667        185        640: 100% 5/5 [00:04<00:00,  1.23it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 1/1 [00:01<00:00,  1.14s/it]
                   all         79        172      0.662      0.475      0.542      0.315

      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
   244/2999      13.3G    0.02246    0.01587   0.005929        182        640: 100% 5/5 [00:03<00:00,  1.29it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 1/1 [00:00<00:00,  1.04it/s]
                   all         79        172      0.674      0.509       0.56      0.354

      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
   245/2999      13.3G    0.02381    0.01481   0.005467        151        640: 100% 5/5 [00:03<00:00,  1.27it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 1/1 [00:00<00:00,  1.14it/s]
                   all         79        172       0.78      0.568      0.636      0.378

      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
   246/2999      13.3G    0.02173    0.01692   0.005114        238        640: 100% 5/5 [00:03<00:00,  1.27it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 1/1 [00:00<00:00,  1.02it/s]
                   all         79        172      0.639      0.566      0.578      0.352

      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
   247/2999      13.3G    0.02268    0.01652   0.004531        200        640: 100% 5/5 [00:03<00:00,  1.28it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 1/1 [00:01<00:00,  1.04s/it]
                   all         79        172      0.623      0.536      0.525      0.321

      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
   248/2999      13.3G    0.02235    0.01425   0.005001        192        640: 100% 5/5 [00:04<00:00,  1.25it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 1/1 [00:00<00:00,  1.08it/s]
                   all         79        172      0.697      0.525      0.599      0.386

      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
   249/2999      13.3G    0.02352    0.01621   0.003642        222        640: 100% 5/5 [00:03<00:00,  1.29it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 1/1 [00:00<00:00,  1.08it/s]
                   all         79        172      0.625       0.49      0.574      0.378

      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
   250/2999      13.3G    0.02184    0.01575    0.00716        221        640: 100% 5/5 [00:03<00:00,  1.29it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 1/1 [00:00<00:00,  1.09it/s]
                   all         79        172      0.657      0.513      0.563      0.364

      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
   251/2999      13.3G    0.02174    0.01629   0.004422        242        640: 100% 5/5 [00:03<00:00,  1.30it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 1/1 [00:00<00:00,  1.04it/s]
                   all         79        172      0.668      0.522      0.576      0.378

      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
   252/2999      13.3G    0.02075    0.01556   0.004782        225        640: 100% 5/5 [00:03<00:00,  1.28it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 1/1 [00:01<00:00,  1.04s/it]
                   all         79        172      0.705      0.523      0.559      0.341

      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
   253/2999      13.3G    0.02199    0.01595   0.003561        159        640: 100% 5/5 [00:03<00:00,  1.31it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 1/1 [00:00<00:00,  1.01it/s]
                   all         79        172      0.818      0.495      0.577      0.366

      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
   254/2999      13.3G    0.02302    0.01519   0.005618        225        640: 100% 5/5 [00:03<00:00,  1.28it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 1/1 [00:00<00:00,  1.17it/s]
                   all         79        172      0.818      0.511      0.561       0.34

      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
   255/2999      13.3G    0.02252    0.01508   0.004516        209        640: 100% 5/5 [00:03<00:00,  1.27it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 1/1 [00:00<00:00,  1.03it/s]
                   all         79        172       0.77      0.508      0.567      0.356

      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
   256/2999      13.3G    0.02207    0.01442   0.005011        174        640: 100% 5/5 [00:03<00:00,  1.30it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 1/1 [00:00<00:00,  1.02it/s]
                   all         79        172      0.763      0.515      0.566      0.366

      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
   257/2999      13.3G    0.02165    0.01472   0.005958        205        640: 100% 5/5 [00:03<00:00,  1.31it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 1/1 [00:00<00:00,  1.16it/s]
                   all         79        172      0.737      0.488      0.564       0.35

      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
   258/2999      13.3G    0.02085    0.01448    0.00546        197        640: 100% 5/5 [00:03<00:00,  1.27it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 1/1 [00:00<00:00,  1.11it/s]
                   all         79        172      0.666      0.512      0.608      0.374

      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
   259/2999      13.3G    0.02247    0.01579   0.004364        179        640: 100% 5/5 [00:03<00:00,  1.31it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 1/1 [00:00<00:00,  1.12it/s]
                   all         79        172      0.845      0.575      0.625      0.382

      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
   260/2999      13.3G    0.02216    0.01446   0.004768        206        640: 100% 5/5 [00:03<00:00,  1.31it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 1/1 [00:00<00:00,  1.07it/s]
                   all         79        172      0.717      0.526      0.613      0.373

      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
   261/2999      13.3G    0.02163    0.01531   0.004534        214        640: 100% 5/5 [00:03<00:00,  1.30it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 1/1 [00:01<00:00,  1.15s/it]
                   all         79        172      0.667      0.577      0.606      0.385

      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
   262/2999      13.3G    0.02124     0.0156   0.004753        214        640: 100% 5/5 [00:03<00:00,  1.28it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 1/1 [00:00<00:00,  1.03it/s]
                   all         79        172      0.691      0.504      0.557      0.333

      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
   263/2999      13.3G    0.02157    0.01402   0.003773        168        640: 100% 5/5 [00:04<00:00,  1.22it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 1/1 [00:01<00:00,  1.78s/it]
                   all         79        172      0.692      0.618      0.621      0.369

      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
   264/2999      13.3G    0.02115    0.01505   0.004787        219        640: 100% 5/5 [00:04<00:00,  1.14it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 1/1 [00:01<00:00,  1.54s/it]
                   all         79        172      0.703      0.587      0.617      0.358

      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
   265/2999      13.3G    0.02119    0.01501   0.003825        230        640: 100% 5/5 [00:04<00:00,  1.24it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 1/1 [00:01<00:00,  1.22s/it]
                   all         79        172      0.633      0.557      0.562       0.34

      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
   266/2999      13.3G    0.02232    0.01488   0.005141        193        640: 100% 5/5 [00:03<00:00,  1.29it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 1/1 [00:00<00:00,  1.20it/s]
                   all         79        172      0.679      0.553       0.55      0.348

      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
   267/2999      13.3G    0.02236    0.01423   0.003963        213        640: 100% 5/5 [00:03<00:00,  1.28it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 1/1 [00:01<00:00,  1.02s/it]
                   all         79        172      0.658      0.539      0.565      0.347

      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
   268/2999      13.3G    0.02109    0.01543   0.005812        185        640: 100% 5/5 [00:03<00:00,  1.29it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 1/1 [00:00<00:00,  1.17it/s]
                   all         79        172      0.631      0.529      0.567       0.36

      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
   269/2999      13.3G    0.02206    0.01438   0.004758        192        640: 100% 5/5 [00:03<00:00,  1.29it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 1/1 [00:00<00:00,  1.03it/s]
                   all         79        172      0.662      0.507      0.577      0.362

      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
   270/2999      13.3G    0.02145    0.01416   0.006062        183        640: 100% 5/5 [00:04<00:00,  1.23it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 1/1 [00:01<00:00,  1.62s/it]
                   all         79        172      0.808      0.489      0.598      0.377

      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
   271/2999      13.3G    0.02128    0.01363   0.004508        210        640: 100% 5/5 [00:04<00:00,  1.23it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 1/1 [00:01<00:00,  1.14s/it]
                   all         79        172      0.788      0.498      0.592      0.373

      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
   272/2999      13.3G    0.02323    0.01416   0.004713        181        640: 100% 5/5 [00:03<00:00,  1.28it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 1/1 [00:00<00:00,  1.02it/s]
                   all         79        172       0.68      0.556      0.591      0.383

      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
   273/2999      13.3G    0.02241    0.01433   0.005521        175        640: 100% 5/5 [00:03<00:00,  1.32it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 1/1 [00:00<00:00,  1.10it/s]
                   all         79        172       0.72      0.539      0.587      0.375

      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
   274/2999      13.3G    0.02156    0.01502   0.005296        187        640: 100% 5/5 [00:03<00:00,  1.31it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 1/1 [00:00<00:00,  1.07it/s]
                   all         79        172        0.7      0.516      0.578      0.371

      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
   275/2999      13.3G    0.02187    0.01516   0.004791        177        640: 100% 5/5 [00:03<00:00,  1.31it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 1/1 [00:01<00:00,  1.15s/it]
                   all         79        172      0.676      0.566      0.574      0.361

      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
   276/2999      13.3G    0.02218    0.01589   0.004767        229        640: 100% 5/5 [00:03<00:00,  1.27it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 1/1 [00:00<00:00,  1.03it/s]
                   all         79        172      0.699      0.514       0.59      0.365

      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
   277/2999      13.3G    0.02195    0.01649   0.004888        205        640: 100% 5/5 [00:03<00:00,  1.30it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 1/1 [00:00<00:00,  1.05it/s]
                   all         79        172      0.737      0.607      0.652      0.416

      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
   278/2999      13.3G    0.02141    0.01452   0.003921        173        640: 100% 5/5 [00:03<00:00,  1.27it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 1/1 [00:00<00:00,  1.01it/s]
                   all         79        172      0.657      0.603      0.639      0.408

      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
   279/2999      13.3G    0.02054    0.01555   0.004726        229        640: 100% 5/5 [00:03<00:00,  1.29it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 1/1 [00:01<00:00,  1.05s/it]
                   all         79        172      0.778      0.508      0.665       0.41

      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
   280/2999      13.3G    0.02179    0.01484   0.004448        188        640: 100% 5/5 [00:03<00:00,  1.29it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 1/1 [00:00<00:00,  1.04it/s]
                   all         79        172      0.793      0.552      0.646      0.392

      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
   281/2999      13.3G     0.0219    0.01377   0.006125        195        640: 100% 5/5 [00:03<00:00,  1.31it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 1/1 [00:01<00:00,  1.13s/it]
                   all         79        172      0.744      0.546        0.6      0.392

      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
   282/2999      13.3G    0.02197    0.01625   0.004896        215        640: 100% 5/5 [00:03<00:00,  1.31it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 1/1 [00:00<00:00,  1.04it/s]
                   all         79        172      0.678      0.521       0.56      0.347

      Epoch    GPU_mem   box_loss   obj_loss   cls_loss  Instances       Size
   283/2999      13.3G    0.02083    0.01468   0.005276        143        640: 100% 5/5 [00:03<00:00,  1.29it/s]
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 1/1 [00:01<00:00,  1.52s/it]
                   all         79        172      0.634      0.553      0.573      0.343
Stopping training early as no improvement observed in last 100 epochs. Best results observed at epoch 183, best model saved as best.pt.
To update EarlyStopping(patience=100) pass a new patience value, i.e. `python train.py --patience 300` or use `--patience 0` to disable EarlyStopping.

284 epochs completed in 0.433 hours.
Optimizer stripped from runs/train/exp/weights/last.pt, 14.5MB
Optimizer stripped from runs/train/exp/weights/best.pt, 14.5MB

Validating runs/train/exp/weights/best.pt...
Fusing layers... 
Model summary: 157 layers, 7020913 parameters, 0 gradients, 15.8 GFLOPs
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100% 1/1 [00:01<00:00,  1.20s/it]
                   all         79        172       0.75      0.624      0.693      0.434
               cadeira         79         78      0.714      0.462      0.527      0.255
             geladeira         79          4      0.763      0.816      0.895       0.64
               monitor         79         36      0.735      0.463      0.572      0.338
                quadro         79         54      0.788      0.756       0.78      0.505
  ```
</details>

### Evidências do treinamento


![confusion_matrix](![results](https://user-images.githubusercontent.com/89791550/200121581-22cd817d-babb-436d-83bf-2b607d526df2.png)
)

## Roboflow

https://app.roboflow.com/wilsoncesarschool/projetofinalmodelosconexionistas/1

## HuggingFace

https://huggingface.co/wilsonsob/projetoFinal
