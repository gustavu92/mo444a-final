# mo444a-final
MO444A - Project


**28/10/2018** - Atualização

  [01. Detectar emoções - CNN](01.%20Projeto%20-%20Detectar%20emoções%20-%20CNN.ipynb): CNN com as seguintes camadas 

         Conv2d(32, 5x5)  | Ativação (Relu) | MaxPooling2D (2x2)

         Conv2D(64, 3x3)  | Ativação (Relu) | Dropout(0.1) | MaxPooling2D (2x2)

         Conv2D(128, 3x3) | Ativação (Relu) | Dropout(0.1) | MaxPooling2D (2x2)

         Dense(1024)      | Ativação (Relu) | Dropout(0.5)

         Dense(512)       | Ativação (Relu) | Dropout(0.5)

         Dense(10)        | Softmax
