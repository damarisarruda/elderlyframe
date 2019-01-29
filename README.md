<h2>Framework: ElderlyFrame Versão 1.0</h2>

<p>O framework ElderlyFrame foi desenvolvido com o objetivo de facilitar o processo de desenvolvimento de aplicações para dispositivos móveis, considerando usuários idosos. Visando contribuir para que o uso dessas aplicações, por esse público, aconteça de forma efetiva e as restrições de acesso sejam minimizadas.</p>
<p>Os componentes podem ser usados de forma individual ou agrupados. Nesta primeira versão, estes foram desenvolvidos para incorporação ao sistema operacional Android, a partir da versão 5.0 (Lollipop).</p>
<p>Os componentes podem utilizar os atributos de seus respectivos gerenciadores de layout, tais como: layout_width, orientation,gravity, dentre outros.</p>
<p>O posicionamento dos elementos na tela é determinado pelo uso de gerenciadores de tela.</p>

<p>Segue a descrição dos componentes e suas tags, respectivamente:</p>

<h3>SeekbarZoomLinearLayout</h3>
<p>A função deste componente é de ampliar/diminuir as informações na tela através do movimento de arrastar o dedo sobre a barra.<br>
O LinearLayout possibilita organizar seus componentes de duas formas: alinhados horizontalmente ou alinhados verticalmente. Para decidir qual será a orientação deve-se trabalhar com a notação android:orientation.</p>

```
<br.com.elderlyframe.view.zoom.seekbar.SeekBarZoomLinearLayout>
//seu código aqui
</br.com.elderlyframe.view.zoom.seekbar.SeekBarZoomLinearLayout>
```


<h3>SeekbarZoomFrameLayout</h3>
<p>A função deste componente é de ampliar/diminuir as informações na tela através do movimento de arrastar o dedo sobre a barra.<br>
O FrameLayout organiza todos componentes em formato de pilha onde o último componente adicionado fica no topo da pilha, sobrepondo todos deixando só o último visível ao usuário.<br>
O FrameLayout é projetado para exibir um único item por vez, ou para bloquear uma área na tela para exibir um único item. É um dos tipos mais simples de objeto de layout.Todos os elementos filhos do FrameLayout são fixados para o canto superior esquerdo da tela, e ao arrastar o componente para o FrameLayout ele sugestiona a gravidade onde o elemento se posicionará.</p>

```
<br.com.elderlyframe.view.zoom.seekbar.SeekBarZoomFrameLayout>
//seu código aqui
</br.com.elderlyframe.view.zoom.seekbar.SeekBarZoomFrameLayout>
```


<h3>SeekbarZoomRelativeLayout</h3>
<p>A função deste componente é de ampliar/diminuir as informações na tela através do movimento de arrastar o dedo sobre a barra.<br> 
O RelativeLayout permite posicionar um componente relativo a outro, por exemplo, abaixo, acima ou ao lado de um componente já existente. No momento que renomear um componente os outros automaticamente se perdem.</p>

```
<br.com.elderlyframe.view.zoom.seekbar.SeekBarZoomRelativeLayout>
//seu código aqui
</br.com.elderlyframe.view.zoom.seekbar.SeekBarZoomRelativeLayout>
```


<h3>PinchZoomLinearLayout</h3>
<p>A função deste componente é de ampliar/diminuir através do movimento de pinçar os dedos sobre a tela, abrir e fechar.<br>
O LinearLayout possibilita organizar seus componentes de duas formas: alinhados horizontalmente ou alinhados verticalmente. Para decidir qual será a orientação deve-se trabalhar com a notação android:orientation.</p>

```
<br.com.elderlyframe.view.zoom.pinch.PinchZoomLinearLayout>
//seu código aqui
</br.com.elderlyframe.view.zoom.pinch.PinchZoomLinearLayout>
```


<h3>PinchZoomFrameLayout</h3>
<p>A função deste componente é de ampliar/diminuir através do movimento de pinçar os dedos sobre a tela, abrir e fechar.<br>
O FrameLayout organiza todos componentes em formato de pilha onde o último componente adicionado fica no topo da pilha, sobrepondo todos deixando só o último visível ao usuário.<br>
O FrameLayout é projetado para exibir um único item por vez, ou para bloquear uma área na tela para exibir um único item. É um dos tipos mais simples de objeto de layout.Todos os elementos filhos do FrameLayout são fixados para o canto superior esquerdo da tela, e ao arrastar o componente para o FrameLayout ele sugestiona a gravidade onde o elemento se posicionará.</p>

```
<br.com.elderlyframe.view.zoom.pinch.PinchZoomFrameLayout>
//seu código aqui
</br.com.elderlyframe.view.zoom.pinch.PinchZoomFrameLayout>
```


<h3>PinchZoomRelativeLayout</h3>
<p>A função deste componente é de ampliar/diminuir através do movimento de pinçar os dedos sobre a tela, abrir e fechar.<br> 
O RelativeLayout permite posicionar um componente relativo a outro, por exemplo, abaixo, acima ou ao lado de um componente já existente. No momento que renomear um componente os outros automaticamente se perdem.</p>

```
<br.com.elderlyframe.view.zoom.pinch.PinchZoomRelativeLayout>
//seu código aqui
</br.com.elderlyframe.view.zoom.pinch.PinchZoomRelativeLayout>
```


<h3>TouchZoomLinearLayout</h3>
<p>A função deste componente é que ao detectar alguns toques ao redor de um ponto específico, a área ao redor seja ampliada para que o usuário consiga realizar o toque no local desejado.<br>
O LinearLayout possibilita organizar seus componentes de duas formas: alinhados horizontalmente ou alinhados verticalmente. Para decidir qual será a orientação deve-se trabalhar com a notação android:orientation.</p>

```
<br.com.elderlyframe.view.zoom.touch.TouchZoomLinearLayout>
//seu código aqui
</br.com.elderlyframe.view.zoom.touch.TouchZoomLinearLayout>
```


<h3>TouchZoomFrameLayout</h3>
<p>A função deste componente é que ao detectar alguns toques ao redor de um ponto específico, a área ao redor seja ampliada para que o usuário consiga realizar o toque no local desejado.<br>
O FrameLayout organiza todos componentes em formato de pilha onde o último componente adicionado fica no topo da pilha, sobrepondo todos deixando só o último visível ao usuário.<br>
O FrameLayout é projetado para exibir um único item por vez, ou para bloquear uma área na tela para exibir um único item. É um dos tipos mais simples de objeto de layout.Todos os elementos filhos do FrameLayout são fixados para o canto superior esquerdo da tela, e ao arrastar o componente para o FrameLayout ele sugestiona a gravidade onde o elemento se posicionará.</p>

```
<br.com.elderlyframe.view.zoom.touch.TouchZoomFrameLayout>
//seu código aqui
</br.com.elderlyframe.view.zoom.touch.TouchZoomFrameLayout>
```


<h3>TouchZoomRelativeLayout</h3>
<p>A função deste componente é que ao detectar alguns toques ao redor de um ponto específico, a área ao redor seja ampliada para que o usuário consiga realizar o toque no local desejado.<br> 
O RelativeLayout permite posicionar um componente relativo a outro, por exemplo, abaixo, acima ou ao lado de um componente já existente. No momento que renomear um componente os outros automaticamente se perdem.</p>

```
<br.com.elderlyframe.view.zoom.touch.TouchZoomRelativeLayout>
//seu código aqui
</br.com.elderlyframe.view.zoom.touch.TouchZoomRelativeLayout>
```


<h3>SimpleRotationImageView</h3>
<p>A função deste componente é de possibilitar que o usuário consiga rotacionar objetos na tela usando apenas um dedo.</p> 

```
<br.com.elderlyframe.view.image.SimpleRotationImageView>
//seu código aqui
</br.com.elderlyframe.view.image.SimpleRotationImageView>
```


<h3>SpeechText</h3>
<p>A função deste componente é capturar o som emitido e convertê-lo em texto. Ele cria três objetos na tela: label, campo de texto e o botão que dispara a gravação. Esses objetos são organizados linearmente.</p> 

```
<br.com.elderlyframe.view.text.SpeechText>
//seu código aqui
</br.com.elderlyframe.view.text.SpeechText>
```

O atributo app:iconSrc="@drawable/image" deve ser adicionado pois corresponde ao ícone do microfone.


<br><br><br>
Link para dowload do arquivo lib [elderyframelib-release.aar](https://raw.githubusercontent.com/damarisarruda/elderlyframe/master/app/src/main/res/elderlyframelib-release.aar)
